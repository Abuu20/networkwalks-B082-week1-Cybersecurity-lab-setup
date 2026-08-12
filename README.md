# NetworkWALKS Week 1 — Cybersecurity Lab Setup

## Overview

This project documents my Week 1 cybersecurity lab environment setup
for the NetworkWALKS internship.

The lab uses VirtualBox and a custom NAT Network with the
10.0.0.0/24 network range.

## Objectives

- Install and configure VirtualBox
- Create a custom NAT Network
- Configure Kali Linux as a virtual machine
- Configure the Kali Linux IP address
- Verify network connectivity
- Take a snapshot of the configured Kali VM
- Document the complete lab setup

## Lab Network

| Component | Configuration |
|---|---|
| Virtualization | VirtualBox |
| Network Type | Custom NAT Network |
| Network | 10.0.0.0/24 |
| Kali Linux | Virtual Machine |
| IP Address | 10.0.0.2/24 |
| Gateway | 10.0.0.1 |

## 1. Custom NAT Network

I created a custom VirtualBox NAT Network using:

`10.0.0.0/24`



## 2. Kali Linux VM Network Configuration

The Kali Linux VM was connected to the custom NAT Network.



## 3. Kali IP Configuration

I configured Kali Linux with the assigned IP address:

`10.0.0.2/24`

I verified the configuration using:

ip addr




## 4. Connectivity Testing
I tested connectivity between Kali Linux and the lab network.

Commands used:
ip route
ping -c 4 10.0.0.1
ping -c 4 google.com

## 5. Kali Linux Snapshot

After completing the configuration, I created a VirtualBox snapshot so
the configured state could be restored later.

What I Learned

Through this lab I practiced:

Virtual machine deployment
VirtualBox network configuration
NAT networking
IPv4 addressing
Network troubleshooting
Connectivity verification
Virtual machine snapshots
Technical documentation
Demonstration

A short video demonstration of the lab setup is available here:


## Conclusion

This lab provided practical experience setting up an isolated
cybersecurity practice environment using VirtualBox and Kali Linux.

```bash
