# Xray-V2ray
- 科学上网搭建脚本代码，VPS服务器搭建系统最好选择 Debian9或以上  
- 自备VPS和域名

# 环境搭建
### Debian:(Curl安装):
```
apt update -y && apt install -y curl && apt install -y socat
```
### CentOS:(Curl安装):
```
yum update -y && yum update -y && yum install -y socat
```

# 开启自带 BBR 加速
### DebianBBR2加速：
```
wget --no-check-certificate -q -O bbr2.sh "https://github.com/yeyingorg/bbr2.sh/raw/master/bbr2.sh" && chmod +x bbr2.sh && bash bbr2.sh auto
```

# 脚本搭建
### V2ray:
```
bash <(curl -s -L https://git.io/v2ray.sh)
```
### Xray:
```
bash <(curl -Ss https://raw.githubusercontent.com/paniy/Xray_bash_onekey/main/install.sh)
```

# VPS测试脚本 
```
wget -N --no-check-certificate https://raw.githubusercontent.com/91yun/91yuntest/master/test_91yun.sh && bash test_91yun.sh
```
# 特别感谢 Special Thanks

1. 脚本感谢 https://github.com/sprov065/v2-ui 
2. 脚本感谢 https://github.com/Jrohy/trojan 
3. 脚本感谢 https://github.com/v2fly/v2ray-core
4. 脚本感谢 https://github.com/XTLS/Xray-core
5. 脚本感谢 https://github.com/trojan-gfw/trojan
6. 脚本感谢 https://github.com/p4gefau1t/trojan-go
7. 脚本感谢 https://github.com/ylx2016/Linux-NetSpeed
8. 脚本感谢 秋水逸冰、Atrandys、V2ray官方 和 波仔分享 等 
9. 脚本感谢 JCNF的博客 https://ybfl.xyz/111.html

# Stargazers over time

[![Stargazers over time](https://starchart.cc/jinwyp/one_click_script.svg)](https://starchart.cc/jinwyp/one_click_script)
[better-cloudflare-ip]: https://github.com/badafans/better-cloudflare-ip/releases
[CFIP]: https://github.com/BlueSkyXN/CFIP/releases
[CloudflareScanner]: https://github.com/Spedoske/CloudflareScanner/releases/tag/1.1.2
[CloudflareSpeedTest]: https://github.com/XIU2/CloudflareSpeedTest/releases/tag/v1.4.9

