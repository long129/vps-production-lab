# Phase 01 — Linux VM Baseline

## Objective

Build and validate a clean Linux VM baseline before deploying application services or automation.

## Environment

- Hypervisor: VMware
- VM: `vps-lab-01`
- OS: Ubuntu Server 26.04 LTS
- Architecture: x86_64
- CPU: 2 vCPU
- RAM: 6 GB configured
- Disk: 100 GB
- Network mode: NAT
- Linux interface: `ens33`

## Administrative Access

Daily remote administration uses a non-root account:

```text
MobaXterm
    |
    | SSH
    v
long
    |
    | sudo
    v
root privileges
