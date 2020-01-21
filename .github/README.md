# Vagrant Hadoop

A simple vagrant setup for projects.

# ITS NOT MEANT FOR USE IN PRODUCTION

## How to use

1. Install VirtualBox and Vagrant
2. Download or clone this repo
3. Do `vagrant up`
4. `vagrant ssh` to connect to the machine
5. Depending upon requirements or in case any failure happens, make changes in the Vagrantfile 
6. Once done with the work `vagrant halt` to stop the vagrant machine

The system uses about 1gb ram and requires storage upto 10Gb.

## Included

1. Installs Java 11
2. Installs Hadoop 3.2.1
3. On machine boot, runs hadoop automatically
## Todo:

* [ ] Check if hadoop folders exist and remove if not empty
* [ ] Write FAQ.
* [ ] Documentations for possible errors and their fixes.
## FAQ
* pending
