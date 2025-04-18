# Vasma Chaining

该分支仅为上游 [v2ray-agent](https://github.com/mack-a/v2ray-agent) 项目添加了一点儿自用的功能。

- VLESS 链式代理
- GitHub Token 防止限流

### 安装

运行下列指令安装，脚本安装在 `/etc/v2ray-agent/install.sh`，输入 `vasma` 运行脚本。

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/zetaloop/v2ray-agent-chaining/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

[AGPL-3.0](https://github.com/mack-a/v2ray-agent/blob/master/LICENSE)
