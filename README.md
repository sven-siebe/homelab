# My Homelab

## Hardware

### Hetzner Server
	- CPU: Intel Core i7-6700
	- RAM: 64 GB 
	- Drives: 2x 512GB NVME SSD Raid 1 
	- Internet: 1 Gbit
	- OS: Proxmox

### Minisforum HM90
	- CPU: AMD Ryzen 9 4900H
	- RAM: 32 GB 
	- Drives: 512GB SSD & 1 TB SSD
	- OS: Proxmox


## Services

### 1. Firewall
	1. PfSense on Hetzner Server 
		- Cores: 2
		- RAM: 4 GB
	2. Mikrotik CHR on Minisforum HM90
		- Cores: 2
		- RAM: 2 GB

### 2. Backup
#### Proxmox Backup Server on both Systems
The Backupservers are connected to the Servers via VPN running on PfSense
