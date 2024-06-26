---
sidebar_position: 6
---

# 开机

在上一节系统镜像烧录完成后MicroSD卡里面就带有核桃派Linux系统了，将它插入核桃派背面的SD卡槽，连接好HDMI显示器，上电后可以看到操作系统正常启动即可。

- `普通用户（默认）` 账号：pi ; 密码：pi
- `管理员账户` 账号：root ; 密码：root

:::tip 提示

核桃派桌面版（Desktop版）系统首次启动由于需要初始化软件等，耗时比较长，大约几分钟，需要耐心等待系统桌面显示出来。以后再次启动速度会快很多，大约几十秒。

::: 

## HDMI显示器方式登录

系统正常启动蓝灯会常亮。启动成功后带桌面系统显示核桃派桌面，无桌面系统显示终端。

- `桌面系统` : 默认pi用户自动登录。
![start_up1](./img/start_up/start_up1.png)

- `无桌面系统` : 需要输入账号密码登录。
![start_up2](./img/start_up/start_up2.png)

:::tip 提示

当蓝灯常亮而HDMI无显示时请更换一个HDMI显示器测试，依然无效可以使用下面串口终端方式查看系统启动信息。

::: 

## 串口终端方式登录

如果你没有显示器，可以使用USB转TTL工具连接到核桃派的调试串口使用串口终端方式登录。具体参考：[调试串口打开终端](../os_software/terminal#调试串口打开终端) 章节内容。
