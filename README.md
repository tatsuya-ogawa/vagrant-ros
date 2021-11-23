# Vagrant ROS
Vagrant Virtual Machines of ROS and Ubuntu:
* Provision Ubuntu virtual machines with GUI (to run Gazebo and other visualization tools)
* Use base image from bento(to use VirtualBox,Parallels,VMWare)

# Instructions
1. Get on the folder with versions you want to run e.g. cd melodic-bionic
2. Provision the virtual machine by running
    ```
    vagrant up
    ```  
    For Parallels
    ```
    vagrant plugin install vagrant-parallels
    vagrant up --provider=parallels
    ```