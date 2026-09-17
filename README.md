# Cybersecurity-learning-portfolio

## About This Repository

This repository documents my practical cybersecurity learning journey,
including my virtual machine setup, laboratory environment,
experiments, and learning notes.

## Lab Environment

- Host OS: Windows
- Virtualization Software: VirtualBox
- Guest OS: Ubuntu Linux
- Purpose: Cybersecurity learning and authorized testing

## Lab Objectives

- Learn Linux fundamentals
- Understand virtual machines
- Practice cybersecurity concepts safely
- Learn basic networking and security tools
- Perform security experiments in an isolated environment

## Authorization Statement

I, Wale Fidel, will test only systems that I own or have explicit permission to test.

## Questions

### What is a virtual machine?

A virtual machine is a software-based computer that runs inside
another computer. It has its own operating system, storage,
memory, and virtual hardware.

### Why must security experiments be isolated?

Security experiments should be isolated to prevent accidental damage
to personal devices, networks, data, or other systems.

### What is authorization in cybersecurity?

Authorization is having explicit permission to access, test, or
perform security activities on a system.

# Device Specification And Diagram

## Device Specification

- Model: HP EliteBook 840
- Processor: Intel Core i5
- RAM: 8GB
- storage: 256GB
- Operating System: window 11 pro
- Display: 14-inch
- Graphics: Integrated Intel graphics
- Keyboard: Backlit
- Condition: Refurbished

## Practical Steps for Setting Up My Ubuntu Virtual Machine

### 1. Prepare the Host Computer

Before creating the virtual machine, I:
1.	Connected the laptop to a reliable power source.
2.	Connected to the internet.
3.	Closed unnecessary applications.
4.	Ensured that VirtualBox was installed.
5.	Confirmed that hardware virtualization was enabled on the laptop.
Task Manager → Performance → CPU → Virtualization. It show Enabled.

### 2. Download the Ubuntu ISO

I downloaded the 64-bit Ubuntu Desktop ISO image
The ISO file is used as the installation media for the virtual machine.
For a cybersecurity learning environment, an Ubuntu LTS release is preferable when stability and long-term support are priorities.

### 3. Open VirtualBox

I launched Oracle VirtualBox on Windows. From the VirtualBox Manager, I selected:
'New' This opened the virtual machine creation wizard.

### 4. Create the Virtual Machine

I entered the following settings:
- Name: Ubuntu-Cybersecurity-Lab
- VM Folder: I choose a folder where i will get all my files (desktop/cybersecurity-lab)
- ISO: I selected the downloaded Ubuntu ISO as the installation image.
after i choose the Ubuntu ISO image, the following settings appears automatically
- OS Edition: 
- OS: Linux
- OS Distribution: Oracle Linux
- OS Version: Ubuntu (64-bit)
For learning purposes, I chose a manual installation rather than relying on an unattended installation so that I could understand each installation step.

### 5. Configure the Virtual Machine Hardware

Because the laptop has 8 GB of RAM, I used moderate resources for Ubuntu.
Recommended configuration

#### Setting         Configuration
- RAM                  4096 MB (4 GB)
- CPU                  4 cores
- Video Memory         128 MB
- Storage              50 GB virtual disk
- Firmware             EFI enabled
- Network              NAT initially
- Display              Automatic/appropriate scaling

I avoided allocating all of the laptop's RAM or CPU cores to the virtual machine because Window needs resources to continue operating.
