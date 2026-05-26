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
wget [https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb](https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb)
sudo apt install ./xenon_1.0_all.deb
sudo chmod +x /usr/bin/xenon
xenon --help

## Advanced Manual Installation
If you prefer a low-level manual installation or encounter dependency issues:
wget [https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb](https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb)
sudo dpkg -i xenon_1.0_all.deb
sudo apt-get install -f
sudo chmod +x /usr/bin/xenon

## Non-Debian Linux (Arch Linux, Fedora, CentOS, etc.)
If your target machine does not support .deb packages, you can still run Xenon universally as a raw Python script:
wget [https://raw.githubusercontent.com/void-scripter/Xenon-scanner/main/xenon_1.0_all/usr/bin/xenon](https://raw.githubusercontent.com/void-scripter/Xenon-scanner/main/xenon_1.0_all/usr/bin/xenon)
chmod +x xenon
python3 xenon --help