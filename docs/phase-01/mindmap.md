# Phase 01 — Mindmap

```mermaid
mindmap
  root((Phase 01 Linux VM Baseline))
    VMware
      Ubuntu Server VM
      2 vCPU
      6 GB RAM
      100 GB Disk
      NAT
      Snapshot
    Linux
      Ubuntu 26.04 LTS
      x86_64
      User long
      sudo
    Networking
      ens33
      192.168.236.129/24
      Network 192.168.236.0/24
      Gateway 192.168.236.2
      DHCP
      Internet verified
    DNS
      systemd-resolved
      127.0.0.53 stub
      192.168.236.2 upstream
    Storage
      sda
      Partitions
      LVM
        PV
        ubuntu-vg
        ubuntu-lv
        49 GB free
      ext4
    SSH
      TCP 22
      Host keys
      sshd validation
      Admin user
      sudo
      Root SSH policy
    systemd
      ssh.socket
        enabled
        active
      ssh.service
        triggered by socket
        active
      Socket activation
    Troubleshooting
      Verify network
      Verify port
      Inspect service
      sshd validation
      Missing host keys
      Missing run sshd
      Authentication policy
      Reboot verification
