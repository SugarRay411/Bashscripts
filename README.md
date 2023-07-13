# Bashscripts
bashscripts for my DevOps Class
# Vagrant Configuration for Multiple Virtual Machines

This repository contains a Vagrantfile that defines a multi-machine configuration for creating virtual machines using Vagrant and VirtualBox. The configuration sets up the following machines:

- `controlbox`: A CentOS 7 virtual machine with the hostname "controlbox" and a private network IP address of 192.168.5.2.
- `web11`: A CentOS 7 virtual machine with the hostname "web11" and a private network IP address of 192.168.5.3.
- `web12`: A CentOS 7 virtual machine with the hostname "web12" and a private network IP address of 192.168.5.4.
- `web13`: An Ubuntu Xenial 64-bit virtual machine with the hostname "web13" and a private network IP address of 192.168.5.5.

## Prerequisites

To use this configuration, make sure you have the following software installed on your machine:

- Vagrant: [Download and Install Vagrant](https://www.vagrantup.com/downloads)
- VirtualBox: [Download and Install VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## Usage

1. Clone this repository to your local machine:


