# 每日免费节点 · 每日实测更新

![更新](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0-2026-11-19-00e676)
![可用节点](https://img.shields.io/badge/%E5%8F%AF%E7%94%A8%E8%8A%82%E7%82%B9-160-00b0ff)
![实测候选](https://img.shields.io/badge/%E5%AE%9E%E6%B5%8B%E5%80%99%E9%80%89-581-fbbf24)
[![主站](https://img.shields.io/badge/%E4%B8%BB%E7%AB%99-haiwanai.com-00e676)](https://haiwanai.com/free-node/)

> 🕛 **2026-11-19 17:30 更新** · 本轮从 581 个候选里实测筛出 **160 个可用节点**，覆盖 31 个地区
> 每天 **0 点与 17:30** 各实测一次，连不通的节点直接删掉，不留在订阅里凑数。

---

## 订阅地址

导入客户端一次，之后每天自动拉最新节点。

**Clash / mihomo（小火箭选 Clash 格式也行）**
```
https://raw.githubusercontent.com/haiwanai/free-nodes/main/sub.yaml
```

**通用订阅（v2rayN / v2rayNG / 小火箭）**
```
https://raw.githubusercontent.com/haiwanai/free-nodes/main/sub.txt
```

大陆直连 GitHub 打不开时，把上面的地址换镜像前缀：

| 镜像 | 用法 |
|:---|:---|
| ghfast.top | `https://ghfast.top/https://raw.githubusercontent.com/haiwanai/free-nodes/main/sub.yaml` · `https://ghfast.top/https://raw.githubusercontent.com/haiwanai/free-nodes/main/sub.txt` |
| jsDelivr | `https://cdn.jsdelivr.net/gh/haiwanai/free-nodes@main/sub.yaml` · `https://cdn.jsdelivr.net/gh/haiwanai/free-nodes@main/sub.txt`（缓存落后几分钟，急用走上面两个） |

---

## ⚠️ 用之前必读

- **免费节点随时失效**：这批是实测当时能连通的，几小时后可能就死一片。要长期用请自己准备付费方案。
- **安全风险**：节点由陌生人搭建，运营者能看到你走它线路的流量。不要用它登录网银、支付、主邮箱或公司账号。
- **速度别期待**：免费节点普遍超售，晚高峰能掉到几十 KB/s。这里的延迟是测速时的连通耗时，不等于下载速度。
- 需要稳定线路、能看流媒体、能稳用 AI 工具：主站有一份付费机场的横向对比 → <https://haiwanai.com/tuijian/>
- 只想先试一家：夜煞云月付 10 元给 138GB，五个套餐我们逐档拆过 → <https://haiwanai.com/review/夜煞云/> · <https://haiwanlink.com/65?site=13hao>

---

## 数据说明

| 项目 | 数值 |
|:---|:---|
| 本轮候选 | 581 个 |
| 实测可用 | 160 个 |
| 覆盖地区 | 31 个 |
| 更新时间 | 2026-11-19 17:30（UTC+8） |

节点来自公开发布的开源清单，本仓库只做聚合、去重和逐个实测，不运营任何节点服务器，也不修改节点内容。

### 地区分布（前 10）

| 地区 | 可用节点 |
|:---|:---|
| 🇺🇸 美国 | 47 |
| 🇩🇪 德国 | 15 |
| 🇮🇹 意大利 | 9 |
| 🇸🇬 新加坡 | 8 |
| 🇳🇱 荷兰 | 8 |
| 🇯🇵 日本 | 7 |
| 🇬🇧 英国 | 7 |
| 🇫🇷 法国 | 5 |
| 🇨🇦 加拿大 | 5 |
| 🇪🇸 西班牙 | 5 |

---

## 自动更新

每天 **00:05** 与 **17:30**（UTC+8）各跑一次：拉取候选 → 本地逐个测速 → 只保留连通节点 → 提交到本仓库。失败了就沿用上一版，不会把空订阅推上来。

页面版说明：<https://haiwanai.com/free-node/>
