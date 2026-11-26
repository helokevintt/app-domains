# app-domains

各应用官方域名清单。

## 收录规则

- 只收录官网、官方 FAQ、官方文档或 DNS 记录可以核实的域名。
- 每个应用一个文件，放在 `apps/` 目录下，文件名用应用名小写。
- 每个应用另有一份同名的 `.list` 规则文件（如 `apps/monzo.list`），格式参照 yfamilys 规则列表：每行一条 `DOMAIN-SUFFIX,域名`，一个根域名覆盖其全部子域名，不再重复列子域名；钓鱼、仿冒域名不进 `.list`；已停用的官方域名单独分组标注。
- 钓鱼、仿冒域名不算官方域名，单独列在各应用文件末尾的“不是官方”一节，只作提醒。
- 每条清单注明核实日期和来源。

## 应用清单

| 应用 | 文件 | 规则文件 | 核实日期 |
| --- | --- | --- | --- |
| Monzo | [apps/monzo.md](apps/monzo.md) | [apps/monzo.list](apps/monzo.list) | 2026-11-26 |
| Zopa Bank | [apps/zopa.md](apps/zopa.md) | [apps/zopa.list](apps/zopa.list) | 2026-11-26 |
| Altery | [apps/altery.md](apps/altery.md) | [apps/altery.list](apps/altery.list) | 2026-11-26 |
| Meta AI | [apps/meta-ai.md](apps/meta-ai.md) | [apps/meta-ai.list](apps/meta-ai.list) | 2026-11-26 |
| Facebook | [apps/facebook.md](apps/facebook.md) | [apps/facebook.list](apps/facebook.list) | 2026-11-26 |
| WeChat | [apps/wechat.md](apps/wechat.md) | [apps/wechat.list](apps/wechat.list) | 2026-11-26 |
| Claude | [apps/claude.md](apps/claude.md) | [apps/claude.list](apps/claude.list) | 2026-11-26 |
| ChatGPT | [apps/chatgpt.md](apps/chatgpt.md) | [apps/chatgpt.list](apps/chatgpt.list) | 2026-11-26 |
| X | [apps/x.md](apps/x.md) | [apps/x.list](apps/x.list) | 2026-11-26 |
| PayPal | [apps/paypal.md](apps/paypal.md) | [apps/paypal.list](apps/paypal.list) | 2026-11-26 |
