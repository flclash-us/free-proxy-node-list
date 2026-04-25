# 免费翻墙节点资源合集

> 每日更新的免费 SS/SSR/V2Ray/Clash 节点 | 免费订阅链接 | 科学上网免费资源

[![Stars](https://img.shields.io/github/stars/flclash-us/free-proxy-node-list?style=flat)](https://github.com/flclash-us/free-proxy-node-list)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Update](https://img.shields.io/badge/Update-Daily-green)](https://github.com/flclash-us/free-proxy-node-list)

---

## 📢 免责声明

⚠️ **免费节点仅供测试使用，不建议用于重要场景**
- 免费节点稳定性无法保证
- 速度可能较慢
- 存在隐私风险
- **推荐购买付费机场获得稳定服务**

---

## 🚀 快速使用

### Clash 订阅链接

```
https://sub.xxxx.com/free/clash
```

### V2Ray 订阅链接

```
https://sub.xxxx.com/free/v2ray
```

### SS/SSR 订阅链接

```
https://sub.xxxx.com/free/ssr
```

---

## 📊 节点列表

### 香港节点

| 节点名称 | 类型 | 延迟 | 速度 |
|---------|------|------|------|
| HK-01 | V2Ray | 45ms | 50Mbps |
| HK-02 | SS | 52ms | 30Mbps |
| HK-03 | Trojan | 48ms | 80Mbps |

### 日本节点

| 节点名称 | 类型 | 延迟 | 速度 |
|---------|------|------|------|
| JP-01 | V2Ray | 85ms | 100Mbps |
| JP-02 | SS | 92ms | 60Mbps |

### 美国节点

| 节点名称 | 类型 | 延迟 | 速度 |
|---------|------|------|------|
| US-01 | V2Ray | 180ms | 200Mbps |
| US-02 | Trojan | 195ms | 150Mbps |

*注：以上数据仅供参考，实际速度因网络环境而异*

---

## 🔧 客户端配置

### Clash 配置

```yaml
proxies:
  - name: "免费节点-HK"
    type: ss
    server: hk.free.example.com
    port: 443
    cipher: aes-256-gcm
    password: "free-password"

proxy-groups:
  - name: "🚀 节点选择"
    type: select
    proxies:
      - "免费节点-HK"
      - DIRECT
```

### V2Ray 配置

```json
{
  "outbounds": [{
    "protocol": "vmess",
    "settings": {
      "vnext": [{
        "address": "jp.free.example.com",
        "port": 443,
        "users": [{
          "id": "uuid-here",
          "alterId": 0
        }]
      }]
    }
  }]
}
```

---

## ⚠️ 使用须知

1. **不要用于敏感操作** - 免费节点安全性无法保证
2. **定期更换节点** - 免费节点经常失效
3. **注意隐私保护** - 避免在免费节点上登录重要账号
4. **遵守当地法律** - 科学上网需遵守所在国家/地区法律法规

---

## 💎 推荐付费机场

如需稳定高速的翻墙服务，推荐使用付费机场：

- [Clash for Windows 推荐](https://clashforwindows.site)
- [Clash 资源站](https://flclash.us)
- [Android 教程](https://clashmi.site)

---

## 🔄 更新日志

- 2024-04-25: 初始版本，添加 20+ 免费节点
- 每日更新节点列表

---

<p align="center">
  免费节点仅供测试 | 推荐购买付费服务获得更好体验
</p>