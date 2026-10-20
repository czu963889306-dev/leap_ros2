# LEAP ROS2 开源机器人

![LEAP ROS2 开源机器人](leap_ros.png)

> 交流 QQ 群：`1055265929`

## 项目简介

LEAP ROS2 是面向学生和机器人爱好者的低成本开源机器人平台，适合入门学习、教学、课程设计和二次开发。希望通过常见、易采购的器件，让更多人能够亲手组装机器人，学习固件烧录、ROS2 通信、传感器接入和运动控制。

## 配置对比

| 配置 | 说明 | 制作参考成本 | 单片机源码 | 购买链接 |
| --- | --- | --- | --- | --- |
| LEAP_ROS | 基础配置，适合低成本入门 | 约 200 元 | [leap_ros_mcu_driver](https://github.com/czu963889306-dev/leap_ros_mcu_driver) | [淘宝购买](https://item.taobao.com/item.htm?ft=t&id=1064850611171&spm=a21dvs.23580594.0.0.3f062c1b3ZDGGt) |
| LEAP_ROS_MAX | 麦克纳姆轮配置 | 约 400 元 | [leap_ros_max_mcu_driver](https://github.com/czu963889306-dev/leap_ros_max_mcu_driver) | [淘宝购买](https://item.taobao.com/item.htm?abbucket=20&id=1089241377336&mi_id=0000ET3fb_KiIW4VhASN5uTCuZD_0xEe1QxNPIAL9M1xc7E&ns=1&skuId=6313650887438&spm=a21n57.1.hoverItem.1&utparam=%7B%22aplus_abtest%22%3A%22e66b19880a8cfa4a4d7b5d141d7cffac%22%7D&xxc=qcpx) |

制作成本随配件选型和采购渠道变化，售价以商品页面为准。贴片 PCB 板、散件、配件或成品机器人也可联系博主购买。

## 开源内容

本仓库的 `硬件` 目录包含原理图、BOM 物料清单、嘉立创工程和 3D 打印外壳文件。单片机源码见上表，其余软件在独立仓库维护：

- WiFi 图传：[esp32_s3_wifi_camera](https://github.com/czu963889306-dev/esp32_s3_wifi_camera)，ESP32-S3 WiFi 摄像头图传源码。
- ROS 功能包：[leap_ros_ws](https://github.com/czu963889306-dev/leap_ros_ws)，ROS2 工作空间与功能包源码。

## 快速开始

1. 选择配置，阅读对应的原理图和 BOM，准备硬件并完成组装。
2. 获取对应的单片机源码，按需要获取 WiFi 图传和 ROS 功能包代码。
3. 按各源码仓库的说明完成编译、烧录和运行。

## 学习资料

- 学习文档：[飞书文档](https://my.feishu.cn/wiki/Qzl8wFIfKiksMskyEqMc02sYnXf)
- 入门视频：[Bilibili](https://www.bilibili.com/video/BV1nNNb6cER7/?spm_id_from=333.1387.homepage.video_card.click&vd_source=339f0240733dcda285627ff53cbd145f)
- 进阶版（含主控）视频：[Bilibili含主控](https://www.bilibili.com/video/BV1uxp46SEoU/?vd_source=339f0240733dcda285627ff53cbd145f)
- 虚拟机镜像：[百度网盘](https://pan.baidu.com/s/1cjOiwqZdjTcRxwIW4gEIOg?pwd=vst7)，提取码：`vst7`

## 使用声明

**未经允许禁止商用，本项目仅供学习、交流和研究使用。**

实际效果可能受硬件批次、焊接质量和使用环境影响，制作前请阅读相关资料。欢迎反馈问题、分享经验和改进方案。
