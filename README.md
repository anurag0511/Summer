# Summer 2017
### Embedded reservoirs for Learning on the Edge

This repository consists of scripts implementing [reservoir networks](https://en.wikipedia.org/wiki/Reservoir_computing#:~:text=Reservoir%20computing%20is%20a%20framework,linear%20system%20called%20a%20reservoir.)
on an embedded linux SoC. This involves running ensembles of [Echo State Networks](http://www.scholarpedia.org/article/Echo_state_network) with a 9-DOF IMU reading as the input 
to learn and predict different movements in real-time. The user can train multiple actions to the device and use those actions for performing different tasks in just less than 15 seconds. the preliminary example involves dynamically programming the servo based on the actions trained.
Ths technology can be highly useful in medical assistive technology. 
