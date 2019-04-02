# tools_collector
=。=经常看到想用的工具过一会就忘了写个记一下
## 信息收集
### 子域名收集
#### 自动监控目标子域，助你快速挖洞——Sublert
https://paper.tuisec.win/detail/514c976ca3510cc

### nmap插件
#### Freevulnsearch - Free And Open NMAP NSE Script To Query Vulnerabilities Via The cve-search.org API
https://github.com/OCSAF/freevulnsearch  
`nmap -sV --script freevulnsearch www.ckj123.com`

## 漏洞挖掘
### poc开源框架
#### pocsuite3 
https://paper.seebug.org/857/

### 渗透框架
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
### 代理转发
#### reGeorg
https://github.com/zsxsoft/reGeorg.git
