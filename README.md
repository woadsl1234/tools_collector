# tools_collector
=。=经常看到想用的工具过一会就忘了写个记一下
## 信息收集
### 子域名收集
#### 自动监控目标子域，助你快速挖洞——Sublert
https://paper.tuisec.win/detail/514c976ca3510cc

#### get-domain
https://github.com/guimaizi/get_domain

### nmap插件
#### Freevulnsearch - Free And Open NMAP NSE Script To Query Vulnerabilities Via The cve-search.org API
https://github.com/OCSAF/freevulnsearch  
`nmap -sVC --script freevulnsearch www.ckj123.com`

## 漏洞挖掘
### poc开源框架
#### pocsuite3 
https://paper.seebug.org/857/

### burp插件
#### 将unicode转中文
https://github.com/stayliv3/burpsuite-changeU.git

#### domain hunter
https://github.com/bit4woo/domain_hunter

### 扫描工具
#### Gourdscan v2.1 被动式漏洞扫描系统
https://github.com/ysrc/GourdScanV2

#### dzscan dz扫描工具
https://github.com/code-scan/dzscan

### 渗透框架
#### Pymetasploit3
https://nosec.org/home/detail/2663.html

#### 溯光
https://github.com/iSafeBlue/TrackRay

#### pupy
可以生成
https://github.com/n1nj4sec/pupy  
使用手册: https://www.hackingarticles.in/command-control-tool-pupy/  
使用手册: https://github.com/n1nj4sec/pupy/wiki/Installation#docker-compose

#### kage
https://github.com/WayzDev/Kage
msf的gui版本

#### Weevely
https://github.com/epinna/weevely3
小马生成器
```
weevely generate <password> <path>
weevely <URL> <password> [cmd]
```

## 内网渗透

### 密码破解
### JohnTheRipper
https://github.com/magnumripper/JohnTheRipper
`john shadow.txt`



### 代理转发
#### reGeorg
https://github.com/zsxsoft/reGeorg.git
