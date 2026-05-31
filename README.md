# Secure Business Network

## Overview

This project is a small secure business network created in Cisco Packet Tracer.

## Devices

* 1 Router
* 2 Cisco 2960 Switches
* 8 PCs

## VLAN Structure

* VLAN 10 – Administration
* VLAN 20 – IT
* VLAN 99 – Management
* VLAN 999 – Unused Ports

## Features

* VLAN Segmentation
* Inter-VLAN Routing (Router-on-a-Stick)
* DHCP
* SSH
* Port Security
* Trunk Restrictions
* Native VLAN Configuration
* Management VLAN
* Disabled Unused Ports

## Topology

1 Router, 2 Switches And 8 Pc's

## Troubleshooting

A major issue occurred where VLAN 10 could only communicate within its own VLAN. After extensive troubleshooting, the root cause was identified as an incorrect DHCP pool configuration using `192.160.x.x` instead of `192.168.x.x`. The issue was confirmed by assigning static IPv4 addresses and later correcting the DHCP configuration.
