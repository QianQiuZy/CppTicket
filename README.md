<div align="left">
  <a href="https://github.com/qianqiuzy/cppticket" target="_blank">
    <img width="160" src="sakuna.ico" alt="logo">
  </a>
  <h1 id="sakuna">CppTicket</h1>

</div>

适用于CPP无差别平台抢票，极简页面，无需繁琐操作，快速上手

![GitHub all releases](https://img.shields.io/github/downloads/QianQiuZy/CppTicket/total)
![GitHub release (with filter)](https://img.shields.io/github/v/release/QianQiuZy/CppTicket)
![GitHub Repo stars](https://img.shields.io/github/stars/QianQiuZy/CppTicket)

## 快速入门

在[release](https://github.com/QianQiuZy/CppTicket/releases/tag/CP31)中点击cppticket.exe进行下载

（如有浏览器警告请点击右侧的三个点，点击保留，点击显示详细信息，点击仍然保留）

双击cppticket.exe打开并按照命令行内操作即可

## 介绍

为防止大规模倒卖，本脚本暂时采用闭源模式

没有任何后台，所有请求均为CPP官方API请求

目前实现进阶功能：

- [x] 纯命令行界面不需要调用webdriver（登录、选票、抢票、付款）
- [x] 轮询API查询余票，有票再发起请求抢票（https://www.allcpp.cn/allcpp/ticket/getTicketTypeList.do）
- [x] 抢票期间查询是否有未支付订单（https://www.allcpp.cn/api/tk/getList.do?type=0&sort=0&index=1&size=10）
- [x] 验证cookie有效性并获取用户名（https://www.allcpp.cn/mng/action.do）
- [x] 根据开票时间准时开始抢票（使用ntplib校准时间）
- [x] 开票内一小时不查询余票数量，不断尝试发起订单（狂暴抢票模式）
- [x] 命令行内显示付款二维码（目前仅支持微信）

## 问题报告

提交issue或者B站私信[千秋紫莹](https://space.bilibili.com/351708822)

如发现倒卖行为和要求B站三连获取脚本等获利行为也请B站联系作者[千秋紫莹](https://space.bilibili.com/351708822)

## 友情链接

更多高级功能，更好的用户交互界面，支持多用户多票种配置

[https://github.com/Hanzzkj652/CPPRush](https://github.com/Hanzzkj652/CPPRush)

## 免责声明

详见[License](./LICENSE)，切勿进行盈利，所造成的后果与本人无关

本脚本仅供学习交流使用, 不得用于商业用途, 如有侵权请联系删除

## 感谢名单

投喂地点：[爱发电](https://afdian.com/a/qianqiuzy)

如果你投喂了作者就会出现在下面的感谢名单，可以匿名投喂
