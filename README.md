# radicore-vagrant

Provides a virtual environment for [Radicore](http://radicore.org/).

Installs Apache 2.4, MySQL 5.5 and PHP 5.5 in an Ubuntu 12.04 virtual machine to then configure Radicore and import the
demo files. This is just for trying out the system and play a little with its internals, is not supposed to be a development
environment.

## Requirements

- [Vagrant](https://www.vagrantup.com/)
- [Ansible](https://docs.ansible.com/)

## Setup

1. Clone this project with ```git clone https://github.com/joksnet/radicore-vagrant.git``` or download and unzip,
1. [Download Radicore](http://www.radicore.org/downloads.php) lastest version (tested with 1.93.0),
1. Unzip into root of `radicore-vagrant` folder,
1. Run `vagrant up` and cross your fingers,
1. Open http://192.168.17.25/ on your browser.
