# 🚀 免费节点自动测活订阅池 (含真实家宽/住宅IP甄选)

> 👤 **定制规范命名**: 所有订阅节点均重命名为 `国旗 地区 序号 (家宽) - xiaohe`
> ⚡ **真实可用保障**: 所有节点由 `sing-box v1.14.0` 内核建立实际代理隧道, 完成真实 HTTPS 双向传输握手 + 出口 IP 穿透验证 + Cloudflare 限速下载断流检测 + TLS 证书校验 (MITM 劫持识别), 拒绝虚假通畅、断流节点与高危劫持节点。
> 🛡️ **本轮出库协议** (共 821 个): VLESS 462 · Shadowsocks 218 · Hysteria2 73 · VMESS 54 · Trojan 14
> 解析层支持 VLESS (Reality/Vision) · VMESS · Trojan · Shadowsocks · Hysteria2 · TUIC · AnyTLS; 上面只列本轮真正测活通过的协议 —— 没出现即本轮为 0, 不代表不支持。

---

## 📌 全部节点总订阅链接

| 客户端 / 格式类型 | 节点总数 | 订阅直链 (CDN 免翻 / 官方 Raw) |
| :--- | :---: | :--- |
| 🚀 **Clash (YAML 格式)** | `821` | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/clash.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/clash.yaml) |
| ⚡ **V2RayN (Base64 格式)** | `821` | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/v2ray.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/v2ray.txt) |
| 📦 **sing-box (JSON 格式)** | `821` | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/singbox.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/singbox.json) |

---

## 🏠 按照家宽分类节点订阅 (住宅 IP 专区)

> 家宽判定六重信号: ① ip-api.com `hosting` 字段 ② `mobile` 移动网络字段 ③ Cloudflare/主流 CDN Anycast 网段比对 ④ MaxMind GeoLite2 ASN 白/黑名单 (覆盖 60+ 国家主流民用运营商) ⑤ rDNS/ISP 名称特征 ⑥ Scamalytics 风控评分复核 (fraud ≥75 降级、≥90 剔除)。排除所有云主机/数据中心/CDN 任播, 保留真实民用宽带与移动网络。
> ℹ️ 本轮家宽池仅 5 个 —— 判定标准严格 (六重信号 + 欺诈分复核), 免费源里合格样本稀少, 数量少属正常, 不代表筛选失效。

| 家宽地区 | 节点数 | V2RayN 专属订阅 | Clash 专属订阅 | sing-box 专属订阅 |
| :--- | :---: | :---: | :---: | :---: |
| 🇹🇼 中国台湾 (Taiwan) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/TW.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/TW.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/clash-TW.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/clash-TW.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/singbox-TW.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/singbox-TW.json) |
| 🇺🇸 美国 (United States) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/US.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/US.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/clash-US.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/clash-US.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/singbox-US.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/singbox-US.json) |
| 🇹🇷 土耳其 (Turkey) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/TR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/TR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/clash-TR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/clash-TR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/residential-by-country/singbox-TR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/residential-by-country/singbox-TR.json) |

---

## 🗺️ 按照国家分类节点订阅 (非家宽/数据中心节点)

| 地区/国家 | 节点数 | V2RayN 专属订阅 | Clash 专属订阅 | sing-box 专属订阅 |
| :--- | :---: | :---: | :---: | :---: |
| 🇺🇸 美国 (United States) | 281 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/US.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/US.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-US.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-US.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-US.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-US.json) |
| 🇳🇱 荷兰 (Netherlands) | 96 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/NL.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/NL.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-NL.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-NL.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-NL.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-NL.json) |
| 🇩🇪 德国 (Germany) | 51 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/DE.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/DE.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-DE.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-DE.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-DE.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-DE.json) |
| 🇯🇵 日本 (Japan) | 41 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/JP.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/JP.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-JP.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-JP.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-JP.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-JP.json) |
| 🇬🇧 英国 (United Kingdom) | 35 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/GB.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/GB.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-GB.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-GB.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-GB.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-GB.json) |
| 🇫🇷 法国 (France) | 31 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/FR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/FR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-FR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-FR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-FR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-FR.json) |
| 🇸🇪 瑞典 (Sweden) | 23 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/SE.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/SE.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-SE.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-SE.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-SE.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-SE.json) |
| 🇨🇦 加拿大 (Canada) | 21 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/CA.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/CA.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-CA.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-CA.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-CA.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-CA.json) |
| 🇸🇬 新加坡 (Singapore) | 20 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/SG.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/SG.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-SG.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-SG.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-SG.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-SG.json) |
| 🇵🇱 波兰 (Poland) | 19 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/PL.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/PL.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-PL.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-PL.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-PL.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-PL.json) |
| 🇰🇷 韩国 (South Korea) | 19 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/KR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/KR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-KR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-KR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-KR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-KR.json) |
| 🇮🇹 意大利 (Italy) | 16 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/IT.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/IT.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-IT.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-IT.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-IT.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-IT.json) |
| 🇧🇬 保加利亚 (Bulgaria) | 14 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/BG.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/BG.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-BG.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-BG.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-BG.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-BG.json) |
| 🇫🇮 芬兰 (Finland) | 12 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/FI.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/FI.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-FI.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-FI.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-FI.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-FI.json) |
| 🇱🇻 拉脱维亚 (Latvia) | 11 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/LV.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/LV.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-LV.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-LV.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-LV.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-LV.json) |
| 🇭🇰 中国香港 (Hong Kong) | 11 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/HK.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/HK.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-HK.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-HK.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-HK.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-HK.json) |
| 🇨🇱 智利 (Chile) | 10 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/CL.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/CL.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-CL.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-CL.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-CL.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-CL.json) |
| 🇱🇹 立陶宛 (Lithuania) | 9 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/LT.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/LT.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-LT.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-LT.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-LT.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-LT.json) |
| 🇪🇸 西班牙 (Spain) | 8 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/ES.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/ES.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-ES.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-ES.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-ES.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-ES.json) |
| 🇷🇴 罗马尼亚 (Romania) | 8 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/RO.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/RO.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-RO.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-RO.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-RO.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-RO.json) |
| 🇦🇪 阿联酋 (UAE) | 8 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/AE.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/AE.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-AE.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-AE.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-AE.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-AE.json) |
| 🇷🇺 俄罗斯 (Russia) | 8 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/RU.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/RU.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-RU.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-RU.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-RU.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-RU.json) |
| 🇨🇭 瑞士 (Switzerland) | 7 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/CH.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/CH.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-CH.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-CH.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-CH.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-CH.json) |
| 🇹🇼 中国台湾 (Taiwan) | 6 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/TW.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/TW.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-TW.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-TW.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-TW.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-TW.json) |
| 🇪🇪 爱沙尼亚 (Estonia) | 6 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/EE.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/EE.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-EE.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-EE.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-EE.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-EE.json) |
| 🇰🇿 哈萨克斯坦 (Kazakhstan) | 5 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/KZ.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/KZ.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-KZ.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-KZ.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-KZ.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-KZ.json) |
| 🇲🇽 墨西哥 (Mexico) | 4 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/MX.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/MX.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-MX.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-MX.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-MX.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-MX.json) |
| 🇨🇾 塞浦路斯 (Cyprus) | 4 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/CY.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/CY.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-CY.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-CY.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-CY.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-CY.json) |
| 🇿🇦 南非 (South Africa) | 3 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/ZA.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/ZA.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-ZA.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-ZA.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-ZA.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-ZA.json) |
| 🇮🇱 以色列 (Israel) | 3 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/IL.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/IL.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-IL.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-IL.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-IL.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-IL.json) |
| 🇦🇹 奥地利 (Austria) | 3 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/AT.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/AT.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-AT.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-AT.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-AT.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-AT.json) |
| 🇮🇪 爱尔兰 (Ireland) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/IE.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/IE.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-IE.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-IE.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-IE.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-IE.json) |
| 🇦🇺 澳大利亚 (Australia) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/AU.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/AU.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-AU.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-AU.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-AU.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-AU.json) |
| 🌐 其他地区 (Other) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/OTHER.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/OTHER.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-OTHER.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-OTHER.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-OTHER.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-OTHER.json) |
| 🇹🇭 泰国 (Thailand) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/TH.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/TH.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-TH.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-TH.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-TH.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-TH.json) |
| 🇲🇩 摩尔多瓦 (Moldova) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/MD.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/MD.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-MD.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-MD.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-MD.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-MD.json) |
| 🇮🇷 IR | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/IR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/IR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-IR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-IR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-IR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-IR.json) |
| 🇮🇳 印度 (India) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/IN.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/IN.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-IN.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-IN.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-IN.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-IN.json) |
| 🇹🇷 土耳其 (Turkey) | 2 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/TR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/TR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-TR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-TR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-TR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-TR.json) |
| 🇱🇰 斯里兰卡 (Sri Lanka) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/LK.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/LK.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-LK.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-LK.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-LK.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-LK.json) |
| 🇸🇨 塞舌尔 (Seychelles) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/SC.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/SC.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-SC.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-SC.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-SC.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-SC.json) |
| 🇷🇸 塞尔维亚 (Serbia) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/RS.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/RS.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-RS.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-RS.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-RS.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-RS.json) |
| 🇳🇴 挪威 (Norway) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/NO.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/NO.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-NO.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-NO.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-NO.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-NO.json) |
| 🇬🇹 GT | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/GT.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/GT.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-GT.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-GT.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-GT.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-GT.json) |
| 🇸🇦 沙特 (Saudi Arabia) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/SA.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/SA.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-SA.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-SA.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-SA.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-SA.json) |
| 🇬🇷 希腊 (Greece) | 1 | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/GR.txt) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/GR.txt) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/clash-GR.yaml) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/clash-GR.yaml) | [CDN 直链](https://cdn.jsdelivr.net/gh/mrjxyz/freesub@output/by-country/singbox-GR.json) · [Raw 直链](https://raw.githubusercontent.com/mrjxyz/freesub/output/by-country/singbox-GR.json) |

---

## 🔒 私有仓库 (Private) 无感订阅方案 (基于 Cloudflare Workers)

> 如果你希望将本 GitHub 仓库设置为 **Private (私有仓库)** 保护节点资产，外部客户端无法直接拉取原生 Raw 或公共 CDN 链接，可以通过以下 Cloudflare Worker 搭建轻量级私密网关反代：

### 1. 生成最小权限的 GitHub 令牌
1. 进入 GitHub → **Settings** → **Developer settings** → **Personal access tokens** → **Fine-grained tokens**。
2. **Repository access** 只勾选这一个仓库。
3. **Permissions** 只给 `Contents: Read-only` —— 只读就够反代用，不要给写权限。
4. **Expiration** 设一个明确期限（如 90 天）到期换新，不要选 `No expiration`。
   > 经典令牌 (classic) 必须整份 `repo` 权限且常被设成永不过期，一旦泄露等于交出整个账号的仓库读写权，不建议再用于此处。

### 2. 把令牌存成 Worker 的加密变量
在 Worker 的 **Settings → Variables and Secrets** 里新增一个 **Secret**，名字填 `GH_TOKEN`，值填令牌。
**不要把令牌写进 Worker 代码** —— 代码里明文粘贴，任何能看到这个 Worker 的人就拿到了它。

### 3. 部署 Worker
新建 Worker，粘贴以下脚本并部署（只需把 `OWNER`/`REPO` 改成你自己的）：

```javascript
export default {
  async fetch(request, env) {
    const OWNER = "mrjxyz";
    const REPO = "freesub";
    const BRANCH = "output";
    const GITHUB_TOKEN = env.GH_TOKEN;
    if (!GITHUB_TOKEN) {
      return new Response("missing GH_TOKEN secret", { status: 500 });
    }

    const url = new URL(request.url);
    const filePath = url.pathname.slice(1);
    if (!filePath || filePath.includes("..")) {
      return new Response("Bad Request", { status: 400 });
    }
    const ghUrl = "https://raw.githubusercontent.com/" + OWNER + "/" + REPO + "/" + BRANCH + "/" + filePath;

    const res = await fetch(ghUrl, {
      headers: {
        "Authorization": "token " + GITHUB_TOKEN,
        "User-Agent": "Cloudflare-Worker"
      }
    });

    if (!res.ok) {
      return new Response("Not Found", { status: 404 });
    }

    return new Response(await res.text(), {
      headers: {
        "Content-Type": "text/plain; charset=utf-8",
        "Cache-Control": "no-store"
      }
    });
  }
}
```

### 4. 私有订阅链接映射方式
部署后 Worker 会分配一个专属域名（例如 `my-sub.yourname.workers.dev`），客户端可直接无感订阅。
路径与产物分支的目录结构一致，**不要加 `output/` 前缀**：

* **总 V2RayN 订阅**: `https://你的域名.workers.dev/v2ray.txt`
* **总 Clash 订阅**: `https://你的域名.workers.dev/clash.yaml`
* **总 sing-box 订阅**: `https://你的域名.workers.dev/singbox.json`
* **按国家（例：日本 V2RayN）**: `https://你的域名.workers.dev/by-country/JP.txt`
* **按国家（例：美国 Clash）**: `https://你的域名.workers.dev/by-country/clash-US.yaml`
* **家宽专区（例：中国台湾 sing-box）**: `https://你的域名.workers.dev/residential-by-country/singbox-TW.json`

> 家宽专区只收录通过六重信号判定的样本，目录里有什么国家就只能订阅什么国家（见上方家宽表格）。

---

## ⭐ 项目热度

[![Star History Chart](https://api.star-history.com/svg?repos=mrjxyz/freesub&type=Date)](https://star-history.com/#mrjxyz/freesub&Date)

---

## 🛠️ 项目使用说明
1. **自动更新机制**：GitHub Actions 每 8 小时全自动运行并刷新上述全部订阅与数据。
2. **测活标准**：节点必须通过 ① 端口预检 ② sing-box 实际隧道 3 个 generate_204 探测 ③ 真实出口 IP 穿透获取 ④ Cloudflare 5MB 限时下载 (吞吐 ≥ 70KB/s) ⑤ TLS 证书校验非 MITM, 方可入库。
3. **多客户端兼容**：Clash / v2rayN / sing-box 全格式订阅。
4. **节点时效说明**：免费节点寿命为小时级（实测相邻两轮出库数波动约 ±30%），两轮刷新之间节点失效是常态。Clash 订阅已内置 `AUTO` 自动测速组（每 2 分钟自测、死节点自动剔除）、sing-box 内置 `auto` urltest（每 3 分钟）——客户端请**选 AUTO / auto 组使用**，不要手动锁定单个节点；v2rayN 请开启「自动选择最快服务器 / 多服务器延迟测试」。
5. **产物与代码分离**：本 README 与 `scripts/` 在 `main` 分支；全部订阅产物在 `output` 分支（每轮以单个提交整体覆盖），上述链接均指向该分支。
6. **本地调试**（不必烧 CI）：`MAX_NODES=50 DRY_RUN=1 python scripts/main_v2.py` 只跑 50 个候选且不写产物；另有 `SKIP_CHAIN=1`、`PROBE_WORKERS=<n>`；解析层单测为 `python scripts/test_parsers.py`。
