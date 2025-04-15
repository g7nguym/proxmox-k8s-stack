### Introduction
**In this repo, I want to build a fully functional HCI (Hyper Converged Infrastructure) based on:**  
- Proxmox (Compute)
- Linstor (Software Defined Storage)
- Talos Linux (Kubernetes Cluster will be running on Talos Linux)

### Test LAB Hardware List
**03 HPE DL380 Servers with**
- OS boot disk in RAID 1 `dev/sda`
- Data disk in RAID 10 `/dev/sdb`
- Dual port 1Gbps `eno1 and eno2`  
*Note: for production, it's better to separate traffic for workloads, VM live migration and storage synchronization into their own network interfaces. At least 10Gbps network cards are recommended.*
### Software Versions
**At the time of this writing, the following softwares are used for this demo**
- Proxmox 8.4.1
- Linstor 1.31.0
- Talos Linux 1.9.5
- Kubernetes 1.32.3
### Proxmox Installation
You can follow Proxmox installation documentation at https://www.proxmox.com/en/products/proxmox-virtual-environment/get-started  
In this demo, Proxmox is installed on `/dev/sda`  
Following network configuration is done on all nodes  
![image](https://github.com/user-attachments/assets/41048945-ea45-4269-aa6b-728773f18af3)



