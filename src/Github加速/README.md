# Github加速
获取最优IP写入hosts

1.运行前请先修改config.ini

[config]
#1.hosts文件位置
HostsPath = C:\Windows\System32\drivers\etc\hosts
#2.修改hosts文件里的网址
DealWebUrl = github.com
#3.爬取网址
IpUrl = http://tool.chinaz.com/dns/?type=1&host=github.com&ip=
#4.TTL阈值
MaxTTL = 300
#5.本机谷歌浏览器版本号
VersionNumber = 94.0.4606.61

2.以管理员身份运行程序