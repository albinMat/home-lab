# Proxmox VE Setup

## Purpose

I repurposed an HP ProDesk 600 G1 into a virtualization server using Proxmox VE.

The goal of the project is to gain hands-on experience with virtualization,
Linux servers, networking, and self-hosted applications.

## Current Virtual Machines

| VM | Purpose |
|---|---|
| ubuntu01 | General Linux lab |
| minecraft01 | Minecraft server hosting |
| jellyfin01 | Media server |

## Networking

The virtual machines use a bridged network through Proxmox's `vmbr0` interface.

This allows each virtual machine to obtain its own IP address on the local network.

## What I Learned

- Difference between a physical host and a virtual machine
- How CPU and RAM are allocated to VMs
- How bridged networking connects VMs to the LAN
- How to access Linux machines remotely using SSH
- How IP addresses and ports identify services
