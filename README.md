<div align="center">

# BiLi

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/qhlai/BiliBili-NET)](https://github.com/qhlai/BiliBili-NET/releases) 
![GitHub Release Date](https://img.shields.io/github/release-date/qhlai/BiliBili-NET) 
![GitHub All Releases](https://img.shields.io/github/downloads/qhlai/BiliBili-NET/total) 
![GitHub stars](https://img.shields.io/github/stars/qhlai/BiliBili-NET?style=flat) 
![GitHub forks](https://img.shields.io/github/forks/qhlai/BiliBili-NET)

`BiLi`是一款设计精美的第三方UWP应用

### 主体基于[BiliBili-UWP](https://github.com/Richasy/BiliBili-UWP)原作者停更后，继续维护


</div>

## 新开发者项目声明

> 本意开发一种自己用的舒服的桌面端，感觉这几种现有的[biliuwp-lite](https://github.com/xiaoyaocz/biliuwp-lite)和[BiliBili-UWP](https://github.com/Richasy/BiliBili-UWP)有点毛病，学着改改，搞个杂交版。
## 开发日志
2021.04.18 clone 原项目，更新库，调整错误api

## 原作者项目声明（一定要看）
[原作者声明](https://github.com/qhlai/BiliBili-NET/oldREADME.md)

## 简介

应用提供了两种显示模式：`桌面模式`及`平板模式`，截图如下：

**桌面模式**

![桌面](https://i.loli.net/2020/08/30/Y4vV6LjIxwidhBk.png)

**平板模式**

![平板](https://i.loli.net/2020/08/30/ywEBWn3Vr94k16x.png)

桌面模式适用于1080P以上的显示器，信息密度较高，由于同屏渲染资源较多，对配置要求也相对较高。

平板模式适用于小平板或者XBOX，在操作上比较适合触摸，信息密度较低，所以对配置要求也更低一些。

## 开发环境

|||
|-|-|
|开发工具|Visual Studio 2019|
|最低版本|Windows10 1809|
|目标版本|Windows10 2004|

## 常见问题



## 如何使用及安装

1. 克隆项目到本地
2. 使用 Visual Studio 2019 打开项目
3. 在 `package.appxmanifest` 中的 `Package` 选项卡下，重新生成一个测试证书
4. 重新生成项目并部署

---

如果你要安装，请在旁边[Release](https://github.com/qhlai/BiliBili-NET/releases)中下载对应你系统的压缩包，解压后右键`install.ps1`，根据提示进行安装。

*如果出现需要手动安装证书的情况，请双击包内的证书，将其导入到本地计算机->受信任的根证书目录中，然后再走一遍应用安装流程即可。*



## API 定义

[Api.cs](https://github.com/Richasy/BiliBili-UWP/blob/master/BiliBili-Lib/Models/Others/Api.cs)

## 鸣谢

*(排名不分先后)*
 
- [Richasy](https://github.com/Richasy)
- [蓝火火](https://github.com/cnbluefire)
- [Dino Chen](https://github.com/DinoChan)
- [逍遥橙子](https://github.com/xiaoyaocz)
- [NSDanmaku](https://github.com/xiaoyaocz/NSDanmaku)
- [SYEngine](https://github.com/xqq/SYEngine)
- [JustinXinLiu/Continuity](https://github.com/JustinXinLiu/Continuity)