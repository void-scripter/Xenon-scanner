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
```

```bash
wget https://github.com/void-scripter/Xenon-scanner/raw/main/xenon_1.5_all.deb
```

```bash
sudo apt install ./xenon_1.5_all.deb
```

```bash
sudo chmod +x /usr/bin/xenon
```

```bash
xenon --help
```


## how to use it:
```bash
xenon -Url http://127.0.0.1:1234/login.php -User /usr/share/seclists/Usernames/best15.txt -Pass /usr/share/seclists/Usernames/top-usernames-shortlist.txt -Fail "LOGIN GAGAL: Password atau Username salah"
```


REMEMBER THIS IS FOR EDUCATIONAL ONLY, NEVER DO THIS ON THE REAL WEBSITE WITHOUT PERMISSION!