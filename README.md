# v2ray-agent

> [Thanks for non-commercial open source development authorization by JetBrains](https://www.jetbrains.com/?from=v2ray-agent)

> [Thanks for non-commercial open source development authorization by JetBrains](https://www.jetbrains.com/?from=v2ray-agent)

> [English Version](https://github.com/mack-a/v2ray-agent/blob/master/documents/en/README_EN.md)

- [Cloudflare optimization solution](https://github.com/mack-a/v2ray-agent/blob/master/documents/optimize_V2Ray.md)
- [Traffic Transit](https://github.com/mack-a/v2ray-agent/blob/master/documents/traffic_relay.md)
- [Manual self-build tutorial](https://github.com/mack-a/v2ray-agent/blob/master/documents/Cloudflare_install_manual.md)
- [ssh starter tutorial](https://www.v2ray-agent.com/2020-12-16-ssh%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B)

- [TG Group](https://t.me/technologyshare), [TG Channel - Update Notice](https://t.me/v2rayAgentChannel), [Blog Address](https://www.v2ray-agent.com/)
- **Please give a ⭐ support **

* * * *

# Contents

- [1. script installation](#1vlesstcptlsvlesswstlsvmesstcptlsvmesswstlstrojan-disguise site-five-in-one coexistence script)
    - [features](#features)
    - [Notes](#Notes)
    - [install script](#install script)

* * *

# 1. 8-in-1 coexistence script + disguise site

- [Cloudflare Getting Started Tutorial](https://github.com/mack-a/v2ray-agent/blob/master/documents/cloudflare_init.md)

## Features
- Support [Xray-core[XTLS]](https://github.com/XTLS/Xray-core), [v2ray-core](https://github.com/v2fly/v2ray-core), [hysteria](https://) github.com/apernet/hysteria)
- Support for reading configuration files from different cores to each other
- Support for VLESS/VMess/Trojan/hysteria protocols
- Support Debian, Ubuntu, Centos system, support the mainstream cpu architecture.
- Support any combination of installation, support multi-user management, support DNS streaming unlock, support adding multiple ports, [support any door forwarding traffic, can be used to unlock Netflix, Google human authentication, etc.](https://github.com/mack-a/v2ray-agent/blob/master/ documents/netflix/dokodemo-unblock_netflix.md)
- Support retaining tls certificate after uninstallation
- Support IPv6, [IPv6 notes](https://github.com/mack-a/v2ray-agent/blob/master/documents/ipv6_help.md)
- Support WARP shunting, IPv6 shunting, arbitrary gate shunting
- Support BT download management, log management, domain name blacklist management, core management, pseudo site management, routing rules file management
- [Support for custom certificate installation](https://github.com/mack-a/v2ray-agent/blob/master/documents/install_tls.md)

## Supported installation types

- VLESS+TCP+TLS
- VLESS+TCP+xtls-rprx-vision [recommended
- VLESS+gRPC+TLS [CDN support, IPv6, low latency
- VLESS+WS+TLS [support CDN, IPv6
- Trojan+TCP+TLS
- Trojan+gRPC+TLS【support CDN, IPv6, low latency
- VMess+WS+TLS【support CDN, IPv6
- Hysteria [Recommended

## Line recommendation

- [CN2 GIA](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md#1cn2-gia)
- [AS9929](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md#2%E8%81%94%E9%80%9A-as9929a%E7%BD%91)
- [AS4837](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md#3%E8%81%94%E9%80%9A-as4837%E6%99%AE%E9%80%) 9A%E6%B0%91%E7%94%A8%E7%BD%91)
- [Softbank Japan](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md#4%E8%81%94%E9%80%9A-%E6%97%A5%E6%9C%AC%E8%BD% AF%E9%93%B6)
- [CMI](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md#5cmi)
- transit + cloudflare + landing machine [can pull global]

## Caution

- **Modify Cloudflare->SSL/TLS->Overview->Full**
- **Cloudflare ---> A record resolution of the cloud must be gray [if not gray, it will affect the automatic renewal of the certificate of the timed task]**
- **If you use CDN and use direct connection at the same time, close the cloud + self-selected IP, self-selected IP reference above [Cloudflare optimization program](https://github.com/mack-a/v2ray-agent/blob/master/documents/optimize_V2Ray.md) **
- **Install using pure system, if you have installed using other scripts and can't change the error yourself, please try again after reinstalling the system**
- wget: command not found [** here you need to manually install wget yourself**]
  If you have not used Linux before, [click to view](https://github.com/mack-a/v2ray-agent/tree/master/documents/install_tools.md) installation tutorial
- Non-root accounts are not supported
- **If you find Nginx-related problems, please uninstall the self-compiled nginx or reinstall the system**
- **To save time, please bring a detailed screenshot or follow the template specification for feedback, issues without screenshots or not following the specification will be closed directly**
- **Not recommended for GCP users**
- **Centos and lower versions are not recommended, if Centos installation fails, please switch to Debian10 and try again, the script no longer supports Centos6, Ubuntu 16.x**
- **[Please check the script usage guide first if you don't understand anything](https://github.com/mack-a/v2ray-agent/blob/master/documents/how_to_use.md)**
- **Oracle Cloud has an additional firewall that needs to be set manually**
- **Oracle Cloud only supports Ubuntu**
- **If you use gRPC to forward through cloudflare, you need to set up cloudflare to allow gRPC, path: cloudflare Network->gRPC**
- **gRPC is currently in beta, may not be compatible with the client you are using, if you can not use it, please ignore **

## [Script Usage Guide](https://github.com/mack-a/v2ray-agent/blob/master/documents/how_to_use.md), [Script Directory](https://github.com/mack-a/v2ray-agent) /blob/master/documents/how_to_use.md#5 scripts directory)

## Donate

[You can use my AFF to buy VPS donations - blog](https://www.v2ray-agent.com/%E6%82%A8%E5%8F%AF%E4%BB%A5%E9%80%9A%E8%BF%87%E6%88%91%E7%9A%84AFF%E8%B4%AD% E4%B9%B0vps%E6%8D%90%E8%B5%A0)

[You can use my AFF to buy VPS donations-Github](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation_aff.md)

[Support donating to me via virtual coins](https://github.com/mack-a/v2ray-agent/blob/master/documents/donation.md)

## Installation Script

- Support shortcut start, after installation, shell input [**vasma**] to open the script, script execution path [**/etc/v2ray-agent/install.sh**]

- Latest Version【Recommended

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/rynsm4rt/v2ray-agent-en/master/install.sh" && chmod 700 /root/install .sh && /root/install.sh
```

# Example image

<img src="https://raw.githubusercontent.com/mack-a/v2ray-agent/master/fodder/install/install.jpg" width=700>

# License

[AGPL-3.0](https://github.com/mack-a/v2ray-agent/blob/master/LICENSE)

## Stargazers over time

[! [Stargazers over time](https://starchart.cc/mack-a/v2ray-agent.svg)](https://starchart.cc/mack-a/v2ray-agent)
