# CVE-2022-24934


## 漏洞概述

WPS Office的更新程序wpsupdate.exe从注册表HKEY_CURRENT_USER中读取自定义的更新服务器地址，下载自定义的更新程序并执行，导致任意代码执行。

## 影响范围

WPS Office版本小于或等于11.2.0.10382均存在该漏洞。

（WPS版本号看最后一组，最后一组数字大即为新版本，11.1表示个人版，11.2表示企业版，11.6和11.8表示政企定制版）

## 复现环境

操作系统：Win7 sp1。

WPS Office版本：WPS 2019 v11.8.2.10229。

分析工具：Detect It Easy，OD，IDA，Openssl，数字签名复制工具sigthief.py。

## 技术咨询
![图片](http://r9jxr6lcn.hn-bkt.clouddn.com/qrcode_for_gh_9e53931bba71_344.jpg)
