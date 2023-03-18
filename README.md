# Netbeans_Termux

# System Requirements
CPU: Octa-core with 1.30GHz or up <br />

Architecture: 32bit/64bit <br />

Android 7.0 Nougat or up <br />

RAM: 3GB <br />

Internal storage: 6GB free space <br />

Termux: Latest version! <br />

# How to install?
 - Tutorial: [Not available]
1. Download Termux APK (click on Picture): 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://f-droid.org/repo/com.termux_118.apk)
 or 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/releases/download/NinjaServerTermuxv01/termux_0.118.apk)

2. Install Termux APK

3. Open Termux, copy this line and paste it on Termux

```bash
echo "deb https://packages-cf.termux.org/apt/termux-main stable main" > ~/../usr/etc/apt/sources.list; clear; echo "Updating Termux...."; apt update -y >/dev/null 2>&1; apt -o DPkg::Options::="--force-confnew" -y upgrade >/dev/null 2>&1; apt update -y >/dev/null 2>&1; echo "Install wget...."; apt install -o DPkg::Options::="--force-confnew" -y wget >/dev/null 2>&1; wget -O install.sh https://raw.githubusercontent.com/KhanhNguyen9872/Netbeans_Termux/main/install.sh; bash install.sh https://fb.me/khanh10a1
```

4. Wait for download and install!

# How to start?
- You can use this command to start!

```bash
kalilite
```
- Use this command to start VNC after run [kalilite]!
```bash
khanh --start
```

# PASSWORD VNC:
```
khanhnguyen9872
```

# User/Password PHPMyAdmin:
```
root
```
```
khanhnguyen
```
