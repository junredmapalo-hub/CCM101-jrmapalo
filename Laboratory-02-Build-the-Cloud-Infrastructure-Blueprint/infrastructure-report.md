# Cloud Infrastructure Assessment Report

## System Overview
* **Hostname:** ubuntu
* **Operating System:** Ubuntu 24.04.4 LTS (Noble Numbat)
* **Kernel Version:** 6.8.0-138-generic

## Hardware & Compute Resources
* **CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
* **Number of CPU Cores:** 1 Core
* **Total RAM:** 1.9 GiB

## Storage Resources
* **Disk Capacity:** 19 GiB (`/dev/vda1`)
* **Mounted File Systems:**
  * `/dev/vda1` mounted on `/` (ext4 - 19G capacity, 5.4G used, 13G available)
  * `/dev/vda16` mounted on `/boot` (881M capacity)
  * `/dev/vda15` mounted on `/boot/efi` (105M capacity)
  * `tmpfs` mounted on `/run`, `/dev/shm`, `/run/lock`, and `/run/user/1001`

## Network Resources
* **IP Address:** 172.30.1.2/24 (`enp1s0`)
* **Docker Network IP:** 172.17.0.1/16 (`docker0`)
* **Loopback IP:** 127.0.0.1/8 (`lo`)
