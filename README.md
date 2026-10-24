# 考研日历（只读镜像）

2026 考研备考日程，供手机日历（小米日历 / 其他支持 ICS 的客户端）通过 URL 订阅。

## 订阅地址

```
https://cdn.jsdelivr.net/gh/sadhfuahflsid/kaoyan-calendar@main/kaoyan.ics
```

备用（无 CDN 缓存，但国内可能需要代理）：

```
https://raw.githubusercontent.com/sadhfuahflsid/kaoyan-calendar/main/kaoyan.ics
```

## 说明

- 文件内容：1370+ 条日程，覆盖 2026-10-03 至 2026-12-20（初试结束）
- 更新方式：本地改完后 push 到本仓库，订阅端按自己的周期拉取
- jsDelivr 对 `@main` 有约 12 小时边缘缓存，改完不会立刻生效

## 结构

`kaoyan.ics` —— 唯一文件，RFC 5545 规范化（CRLF、75 字节折行、单 VCALENDAR 块）
