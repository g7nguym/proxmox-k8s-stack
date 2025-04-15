### Introduction
**In this repo, I want to build a fully functional HCI (Hyper Converged Infrastructure) based on:**

- Proxmox (Compute)
- Linstor (Software Defined Storage)
- Talos Linux (Kubernetes Cluster will be running on Talos Linux)

### Test Hardware List
**03 HPE DL380 Servers with**
- OS boot disk in RAID 1 `dev/sda`
- Data disk in RAID 10 `/dev/sdb`
- Dual port 1Gbps (10Gbps is recommended for production)
### Software Versions
**At the time of this writing, the following softwares are used for this demo**
- Proxmox 8.4.1
- Linstor 1.31.0
- Talos Linux 1.9.5
- Kubernetes 1.32.3
