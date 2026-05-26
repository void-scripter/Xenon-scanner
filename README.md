## Supported Operating Systems
This package (`.deb`) natively supports all Debian and Ubuntu-based Linux distributions, including:
* Kali Linux / NetHunter
* Ubuntu
* Debian GNU/Linux
* Linux Mint
* Parrot Security OS
* Pop!_OS

## Standard Installation (Debian/Ubuntu Families)
```bash
apt install wget -y
wget [https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb](https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb)
sudo apt install ./xenon_1.0_all.deb
sudo chmod +x /usr/bin/xenon
xenon --help