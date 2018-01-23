# 温馨提示
强烈建议您参照[https://toutyrater.github.io/](https://toutyrater.github.io/)上的模板自行搭建，能不使用一键脚本那就尽量不要使用！

<!-- vim-markdown-toc GFM -->
#目录
* [V2ray.fun](#v2rayfun)
    * [功能](#功能)
    * [安装命令](#安装命令)
    * [升级命令](#升级命令)
    * [卸载命令](#卸载命令)
    * [截图](#截图)
    * [系统要求](#系统要求)
    * [软件要求](#软件要求)
    * [更新日志](#更新日志)
    * [特别说明](#特别说明)
    * [感谢](#感谢)

<!-- vim-markdown-toc -->

# V2ray.fun
V2ray控制脚本，向导式更改端口，加密方式，传输协议，享受V2ray的乐趣~

## 功能

- 一键 启动 / 停止 / 重启 V2ray 服务端
- 自动随机生成 UUID
- 自助修改端口
- 快速查看服务器连接信息
- 自由更改**传输配置**：
  - 常规TCP
  - HTTP头部伪装
  - WebSocket流量
  - 常规mKCP流量
  - mKCP 伪装 FaceTime通话流量
  - mKCP 伪装 BT下载流量
  - mKCP 伪装 微信视频通话流量

**WebSocket不包括Nginx分流，请自行安装Nginx来分流。**

## 安装命令

```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/1715173329/v2ray.fun/master/install.sh)"
```

## 升级命令
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/1715173329/v2ray.fun/master/upgrade.sh)"
```

## 卸载命令
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/1715173329/v2ray.fun/master/uninstall.sh)"
```


## 截图

![1](1.png)

![2](2.png)

![3](3.png)

![4](4.png)

## 系统要求

- Debian 7 
- **Debian 8（推荐）**
- Ubuntu 14 
- Ubuntu 16 
- CentOS 7

**不支持Centos 6**

## 软件要求

请使用**Xshell**连接服务器，以获得完美的中文支持以及配置文件下载功能。

## 更新日志

**2017.9.4**
第一版通过测试发布。

**2017.10.16**
新增TLS功能，自动获取证书。


## 感谢

V2ray : [https://v2ray.com](https://v2ray.com)

v2ray.fun的原作者: [雨落无声Dalao](https://github.com/YLWS-4617)

