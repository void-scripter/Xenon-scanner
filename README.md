## Xenon-scanner
Xenon scanner is a tools like hydra for brute force login page, but, because hydra to hard to use it (like me to), i make this tools for brute force login page

![Xenon Terminal Screenshot](Xenonv.jpg)

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
wget https://github.com/void-scripter/Xenon-scanner/raw/main/xenon-3.5.deb
```

```bash
sudo apt install ./xenon-3.5.deb
```

```bash
sudo chmod +x /usr/bin/xenon
```

```bash
xenon
```


## how to use it:
```bash
xenon -Url http://127.0.0.1:1234/login.php -User /usr/share/seclists/Usernames/best15.txt -Pass /usr/share/seclists/Usernames/top-usernames-shortlist.txt -Fail "LOGIN GAGAL: Password atau Username salah"
```


REMEMBER THIS IS FOR EDUCATIONAL ONLY, NEVER DO THIS ON THE REAL WEBSITE WITHOUT PERMISSION!
