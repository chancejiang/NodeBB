## Overview
This project aims to provide Startup Grind Guangzhou (over http://sg.startupgrind.cn) a forum like online resource sharing,
publishing and comments app, embbeded-able into WeChat, for easier social sharing and content consumption.

## Customization Requirements
1. Add UI language switches, support English and Simplified Chinese
2. First time user can resiger using WeChat (WeChat OAuth-enabled)login, while requiring their emails 
(email ownership validation required)
3. Registered user only use WeChat to login the forum

## 测试期间的 Hosting
Digital Ocean node: 162.243.138.169

user: your Github email prefix
passwd: (will email you), pls use SSH key to do password-less login and app deployment

## 生产部署的 Hosting
Digital Ocean 节点仅仅用于测试，最终托管在 qcloud的以下节点（待开通）：

## 官方代码库的协同、官方版本升级：
https://help.github.com/articles/duplicating-a-repository/

这个方式方便定期拉取官方新版本，融合到我们的定制版本，持续测试、发布。
