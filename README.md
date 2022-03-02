# tcping
# Install
Debian/Ubuntu
```
apt install -y tcptraceroute bc
cd /usr/bin && wget -O tcping https://raw.githubusercontent.com/aheig/tcping/main/TCP-PING
chmod +x tcping
```
CentOS/RadHat 
```
yum install epel-release
yum install tcping
```
Windows
```
cd %WINDIR%
winget tcping https://raw.githubusercontent.com/aheig/tcping/main/tcping.exe
```
# Use
```
tcping qq.com 3389
```

