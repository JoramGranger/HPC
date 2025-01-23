# HPC
This documents how to setup an HPC cluster from scracth using Rocky Linux, OpenHPC, SLURM, Warewulf

## Requirements
- Rocky Linux ISO image
- Bare metal server (We used a Dell Power Edge C6320p, A chassis of 4 units).
- Ethernet cables (1 for IDRAC, 1 Interconnectivity)
- Monitor, Mouse, Keyboard

## Assumptions
- Networking already setup (routing & switching)
- your PC and server should be on the same network
## Pre-Setup
- choose a master node from the chasis
- configure IDRAC details for remote management on the selected master node
## Setup
- On your PC browser's connect to the IDRAC IP address
- from the IDRAC window launch the virtual console
- 
