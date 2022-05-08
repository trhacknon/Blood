<div align=center>
 
# Blood DDoS

 DDoS Attack Panel includes CloudFlare Bypass (UAM, CAPTCHA, BFM, etc..)<br/><br/>
 Don't attack any websites you don't own it<br/>
 This was created for educational purposes<br/>
 All responsibilities and disadvantages of using this program is for the user.
 

## Language</br>

 <img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/></br>
</div>

## Menu
![image](https://user-images.githubusercontent.com/96767456/167305588-8049db11-64d1-43e2-908e-ac05724a0e3b.png)



## Methods

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfpro   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - http2   | HTTP 2.0 Request Attack 
 = pxhttp2 | HTTP 2.0 Request Attack With Proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 -bypass   | Bypass Google Project Shield, Vshield
 -stellar  | HTTPS Sky method without proxies
- hulk     | Hulk DoS tool
- pxraw    | Proxy Request Attack
- pxslow   | Proxy Slowloris attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  -mine    | Minecraft Dos attack 
  -vse     | Send Valve Source Engine Protocol
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
 - .proxy  | Getting proxies into proxy.txt
 - .proxies| Counts the number of proxies in the proxy.txt file
```


## Usage on Linux
```sh
You must use Python 3.9 or higher

git clone https://github.com/firstapostle/Blood.git

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 setup.py

```
## Usage on Windows
```sh
Install python - https://www.python.org
Install Git - https://gitforwindows.org (instruction in telegram-channel. contact @AuraNetz or @CyberEducational or @MiraiLove )

git clone https://github.com/firstapostle/Blood
cd Blood
python3 setup.py / py setup.py
python3 blood.py / py blood.py


```
## Usage on Termux
```sh
pkg install x11-repo
pkg install unstable-repo
pkg update
pkg upgrade
если спросит нажимаем y
pkg install python3
pkg install git
pkg install wget
pkg install rust
pip install supertools wheel
pip install shutup
git clone https://github.com/firstapostle/Blood
cd Blood
export CARGO_BUILD_TARGET=aarch64-linux-android && python3 -m pip install cryptography
export CARGO_BUILD_TARGET==aarch64-linux-android && python3 -m pip install -r requirements.txt
python3 -m pip install httpx[http2]
python3 setup.py
Нажимаем 1
python3 main.py


```
## Example
```sh
Use DDoS Panel   : python3 main.py
Use command line : python3 main.py <method> <target> <thread> <time>
      └──────────> python3 main.py cfb https://example.com 100 30
```

## Contact Developer
```sh
 Telegram: @AuraNetz
```

