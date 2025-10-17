<div align="left">
  <a href="https://github.com/qianqiuzy/cppticket" target="_blank">
    <img width="160" src="sakuna.ico" alt="logo">
  </a>
  <h1 id="sakuna">CppTicket</h1>

</div>

适用于CPP无差别平台抢票，极简页面，无需繁琐操作，快速上手

![GitHub all releases](https://img.shields.io/github/downloads/QianQiuZy/CppTicket/total)
![使用次数](https://img.shields.io/badge/dynamic/json?label=%E4%BD%BF%E7%94%A8%E6%AC%A1%E6%95%B0&query=%24.count&url=https%3A%2F%2Fapi.qianqiuzy.cn%2Fvisit%2Fcpp_version&color=brightgreen)
![GitHub release (with filter)](https://img.shields.io/github/v/release/QianQiuZy/CppTicket)
![GitHub Repo stars](https://img.shields.io/github/stars/QianQiuZy/CppTicket)

## 快速入门

在[release](https://github.com/QianQiuZy/CppTicket/releases)中点击cppticket.exe进行下载

（下载速度慢可以使用[gitee](https://gitee.com/qianqiuzy/CppTicket/releases)进行下载）

（如有浏览器警告请点击右侧的三个点，点击保留，点击显示详细信息，点击仍然保留）

双击cppticket.exe打开并按照命令行内操作即可

## 问题解决

[杀毒软件误报解决](https://blog.csdn.net/xitongzhijia_abc/article/details/125373425)

[github下载慢解决方法1](https://blog.csdn.net/qq_42009262/article/details/106992684)

[github下载慢解决方法2](https://github-hosts.tinsfox.com/)

## 介绍

已使用httpx完全重构

目前实现进阶功能：

- [x] 纯命令行界面不需要调用webdriver（登录、选票、抢票、付款）
- [x] 轮询API查询余票，有票再发起请求抢票
- [x] 抢票期间查询是否有未支付订单
- [x] 验证cookie有效性并获取用户名
- [x] 根据开票时间准时开始抢票（使用ntplib校准时间）
- [x] 开票内一小时不查询余票数量，不断尝试发起订单（狂暴抢票模式）
- [x] 命令行内显示付款二维码（目前仅支持微信）

## 问题报告

提交issue、[QQ](https://qm.qq.com/cgi-bin/qm/qr?k=SoG6ZDKLfwPs7_YFbhU9vAD1ORCTq4h1)、邮箱qianqiuzy@gmail.com或者B站私信[千秋紫莹](https://space.bilibili.com/351708822)

如发现倒卖行为和要求B站三连获取脚本等获利行为也请联系作者

## 友情链接

[cppTickerBuy](https://github.com/mikumifa/cppTickerBuy)

[CPPTicketManager](https://github.com/shotoguazi/CPPTicketManager)

[CPPRush](https://github.com/Hanzzkj652/CPPRush)

## 免责声明

详见[License](./LICENSE)，切勿进行盈利，所造成的后果与本人无关

本脚本仅供学习交流使用, 不得用于商业用途, 如有侵权请联系删除

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=QianQiuZy/CppTicket&type=Date)](https://star-history.com/#QianQiuZy/CppTicket&Date)

## 投喂作者

投喂地点：[爱发电](https://afdian.com/a/qianqiuzy)
