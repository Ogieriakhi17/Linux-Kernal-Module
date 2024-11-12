# Linux-Kernal-Module
Linux Kernal Programming
This repository contains a custom Linux Kernel Module. This module demonstrates core concepts in kernel programming, including module initialization, cleanup, and interaction with the kernel.

**Overview**
This Linux Kernel Module (LKM) project was developed to gain hands-on experience with kernel module programming. It covers essential tasks such as creating, loading, and unloading a module, as well as interacting with kernel logs. The module performs simple string manipulation, monitoring kernel activity, device driver behavior.

Requirements
To build and test this module, the following are required:

Linux kernel headers 
GCC compiler for building the kernel module
Root privileges for loading and unloading the module
Tested on:
Kernel Version: Ubuntu 6.8
Operating System:  Ubuntu 22.04

**Code Structure**
kmlab.c: Main source code file for the kernel module.
Makefile: Compilation instructions to build the kernel module.
Userapp.c: User space logic
README.md: Documentation for the project.
