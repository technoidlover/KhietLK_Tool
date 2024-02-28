
## Methods

```sh
  [Layer 7]
 - spoof | STRONG ATTACK with spoof Header X-ForWard
 - http2 | HTTP/2 attack with proxy [httpx]
 - cfb   | Bypass CF attack
 - pxcfb | Bypass CF attack tsl1.3 with proxy [fixed work]
 - cfpro | Bypass CF UAM(Under Attack Mode), CAPTCHA, BFM(Bot Fight Mode) etc.. (request)
 - cfsoc | Bypass CF UAM(Under Attack Mode), CAPTCHA, BFM(Bot Fight Mode) etc.. (socket)
 - bypass| Bypass Google Project Shield, Vshield etc.. (socket)
 - raw   | Request Attack
 - post  | Post Request Attack
 - head  | Head Request Attack
 - soc   | Socket Attack
 - hulk  | HTTP Unbearable Load King
 - hulk  | proxy hulk HTTP Unbearable Load King
 - sky   | HTTPS Flood and bypass for CF NoSec, DDoS Guard Free and vShield (SOCKS5)
 -stellar| HTTPS Sky method without proxies
 - pxraw | Proxy Request Attack
 - pxsoc | Proxy Socket Attack
 - pxslow| slowloris Attack (SOCKS5)
 
  [Layer 4]
  -udp | simple udp flood
  -tcp | simple tcp syn flood <work fine ! >
  -vse | Send Valve Source Engine Protocol
  -mine| minecraft dos attack
  
  [Tools]
 - Dns        | Classic DNS Lookup
 - Geoip      | Geo IP Address Lookup
 - Subnet     | Subnet IP Address Lookup
 
 - Next Update SLOWREAD method (SOON...)
```

## Usage
```sh
You must use Python 3.9 or higher
DOWNLOAD:  git clone https://github.com/cutipu/HASOKI.git
INSTALL: - python setup.py install or python3 setup.py install
         - with pip:
           pip3 install -r requirements.txt  or  pip install -r requirements.txt
NOTICE: For bypass work need install lastest verion Chrome
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb
       WINDOWS: python -m pip install undetected_chromedriver --upgrade
 Thread set 10-50 > work
```