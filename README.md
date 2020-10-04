# Autoware_class20
Self-Driving Cars with ROS 2 and Autoware 

# Lectures
Find lectures [here](https://gitlab.com/ApexAI/autowareclass2020/-/tree/master/)

# Building ADE
## Requirments
- Ubuntu 18.04
- Docker.ce, [installion](https://docs.docker.com/engine/install/ubuntu/).
- [Nvidia-container-runtime](https://github.com/NVIDIA/nvidia-container-runtime).

## Installation
Follow installtion [here](https://ade-cli.readthedocs.io/en/latest/install.html)

**Notes**

- After docker installtion, docker and `ade start` command should be started with root privilages 
so you should do:
```
sudo groupadd docker 
sudo usermod -aG docker $USER
reboot
```
  for more info, Check this [link](https://docs.docker.com/engine/install/linux-postinstall/)

- Disable secure boot from BIOS -> to avoid problems to Nvidia dirivers installtion
- Do `unset ADE_DISABLE_NVIDIA_DOCKER` and delete ADE_DISABLE_NVIDIA_DOCKER line from `~/AutowareAuto/.aderc` -> to avoid Rviz problems


## Demo 
First implemention of ADE by checking 3D perception stack
- [lecture 1](https://gitlab.com/ApexAI/autowareclass2020/-/blob/master/lectures/01_DevelopmentEnvironment/devenv.md)

[![Demo](http://img.youtube.com/vi/vzfrloH_Gs4/0.jpg)](http://www.youtube.com/watch?v=vzfrloH_Gs4 "Demo - Autoware.Auto 3D perception stack")
