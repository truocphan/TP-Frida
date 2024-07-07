# TP-Frida

<p align="center">
    <a href="https://github.com/truocphan/TP-Frida/releases/"><img src="https://img.shields.io/github/release/truocphan/TP-Frida" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/downloads/truocphan/TP-Frida/total" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/stars/truocphan/TP-Frida" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/forks/truocphan/TP-Frida" height=30></a>
	<a href="https://github.com/truocphan/TP-Frida/issues?q=is%3Aopen+is%3Aissue"><img src="https://img.shields.io/github/issues/truocphan/TP-Frida" height=30></a>
	<a href="https://github.com/truocphan/TP-Frida/issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed/truocphan/TP-Frida" height=30></a>
	<a href="https://pypi.org/project/TP-Frida/" target="_blank"><img src="https://img.shields.io/badge/pypi-3775A9?style=for-the-badge&logo=pypi&logoColor=white" height=30></a>
	<a href="https://www.facebook.com/61550595106970" target="_blank"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" height=30></a>
	<a href="https://twitter.com/TPCyberSec" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" height=30></a>
	<a href="https://github.com/truocphan" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" height=30></a>
	<a href="mailto:tpcybersec2023@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" height=30></a>
	<a href="https://www.buymeacoffee.com/truocphan" target="_blank"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" height=30></a>
</p>

## Installation
#### From PyPI:
```console
pip install TP-Frida
```
#### From Source:
```console
git clone https://github.com/truocphan/TP-Frida.git --branch <Branch/Tag>
cd TP-Frida
python setup.py build
python setup.py install
```

## Basic Usage
```
> TP-Frida --help

 ___________      ______    _     _
|_   _| ___ \     |  ___|  (_)   | |
  | | | |_/ /_____| |_ _ __ _  __| | __ _
  | | |  __/______|  _| '__| |/ _` |/ _` |
  | | | |         | | | |  | | (_| | (_| |
  \_/ \_|         \_| |_|  |_|\__,_|\__,_|

usage: TP-Frida [-h] [--remote-ip FRIDA-IP] [--remote-port FRIDA-PORT] [--run-app-cmd [CMD-Argument ...]]
                [--script-files [SCRIPT-FILE ...]] [--proxy-ip PROXY-IP] [--proxy-port PROXY-PORT]
                [--capture-targets [CAPTURE-TARGET ...]]
                {start,hook}

positional arguments:
  {start,hook}

options:
  -h, --help            show this help message and exit
  --remote-ip FRIDA-IP, -ri FRIDA-IP
                        Remote Frida-Server IP
  --remote-port FRIDA-PORT, -rp FRIDA-PORT
                        Remote Frida-Server PORT
  --run-app-cmd [CMD-Argument ...], -rac [CMD-Argument ...]
  --script-files [SCRIPT-FILE ...], -sf [SCRIPT-FILE ...]
  --proxy-ip PROXY-IP, -pi PROXY-IP
                        Proxy-Server IP
  --proxy-port PROXY-PORT, -pp PROXY-PORT
                        Proxy-Server PORT
  --capture-targets [CAPTURE-TARGET ...], -ct [CAPTURE-TARGET ...]

```
