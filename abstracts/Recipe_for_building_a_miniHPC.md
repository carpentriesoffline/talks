# Recipe For Building a MiniHPC

## Terminology
1. Login node
1. Computer node

## Ingredients
1. Two or more Raspberry Pi computers
1. PoE Hat for each RPi
1. One SD card or preferably and SSD
1. External USB fan
1. PoE switch and power cord
1. Cat 6 Network cables
1. DIN Rail Stand
1. DIN rail cases for RPis
1. Raspberry Pi's Imager software
1. A computer connected to the Internet

## Directions
### Prepare OS on On computer:
1. Attach SSD via USB or insert SD
1. Start Imager software
1. Select device: Raspberry Pi 4
1. Choose OS:
	- Raspberry Pi OS (other)
	- Raspberry Pi OS Lite (64-bit)
1. Click `Next`
1. Edit Settings:
	- Set hostname: minihpc001
	- Set username and password
	- Select SSID
	- Enter SSID password
	- Select Wireless LAN country: GB
	- Set locale settings:
		- Time Zone: Europe/London
		- Keyboard Layout: gb
1. Click `Yes`

### Assembly
1. Place hats on RPis
1. Place RPis in cases
1. Hook cases on DIN Rail
1. Attach/Insert SD/SSD to login node
1. Connect RPis to switch with network cables
1. Connect USB fan to one of the RPis
1. Switch the switch on

### Software installation
- Update
```bash
sudo apt-get update -y
```
- Upgrade
```bash
sudo apt-get upgrade -y
```
- Install
```bash
sudo apt-get install -y nfs-kernel-server lmod ansible slurm slurmd slurm-client munge nmap nfs-common net-tools build-essential htop net-tools screen vim python3-pip slurm-wlm dnsmasq ntp ntpdate iptables-persistent
```
When asked about saving ip rules, just select yes.
### Configure
- pxe
- slurm
- munge
- dns masquerading
- dhcp
- tftp
- nfs

#### Installing eessi
```bash
wget https://raw.githubusercontent.com/EESSI/eessi-demo/main/scripts/install_cvmfs_eessi.sh
sudo bash install_cvmfs_eessi.sh
source /cvmfs/software.eessi.io/versions/2023.06/init/bash
```
Add the last line to /etc/profile to make it persistent for all users
