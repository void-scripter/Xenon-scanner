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
wget https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.0_all.deb
sudo apt install ./xenon_1.0_all.deb
sudo chmod +x /usr/bin/xenon
xenon --help


## how to use it:
xenon -Url http://127.0.0.1:1234/login.php -User /usr/share/seclists/Usernames/best15.txt -Pass /usr/share/seclists/Usernames/top-usernames-shortlist.txt -Fail "LOGIN GAGAL: Password atau Username salah"