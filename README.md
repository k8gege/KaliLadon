### Ladon For Linux
Author K8gege<br>
Build 20191210<br>
https://github.com/k8gege/Ladon<br>

### Teston 
Kali 2019.4 x64<br>
Ubuntu 18.04 x64<br>

### install
apt install mono-runtime<br>

### run
mono Ladon OnlinePC<br>

### Kali 2019.4 可用功能
由于mono的兼容性问题，不保证Linux下所有功能均可用<br>
就对于Ladon功能的测试来看Kali的兼容性要比Ubuntu好<br>
测试发现有些功能的稳定性以及速度没有Windows系统快<br>
未列功能系未测试或暂不可用功能，使用前请先看说明<br>
在Kali 2019.4下测试，Ladon支持以下所列的27种功能<br>
=============================================<br>
WebDir<br>
UrlScan<br>
PhpStudyPoc<br>
WebScan<br>
MysqlScan<br>
OracleScan<br>
VncScan<br>
HttpDownLoad<br>
FtpDownLoad<br>
WhatCMS<br>
FtpScan<br>
PortScan<br>
SmbScan<br>
SameWeb<br>
MS17010<br>
OnlinePC<br>
OnlineIP<br>
HostIP<br>
DomainIP<br>
EnBase64<br>
DeBase64<br>
EnHex<br>
DeHex<br>
OsScan<br>
SubDomain<br>
SshScan<br>

支持加载*.ps1(无需目标安装powershell,kali & ubuntu测试通过)<br>
=============================================<br>


### 暂不支持功能
=============================================<br>
Struts2Poc  X不支持<br>
TomcatScan X不支持<br>
HttpBasicScan X不支持，只能检测是否401认证URL，无法爆破<br>
WeblogicPoc X不支持(Win下mono也不支持，显然mono问题)<br>
MssqlScan X不支持只能扫到开放端口<br>
IpcScan X不支持(因为调用cmd命令)<br>


