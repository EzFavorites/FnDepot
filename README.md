# FnDepot

飞牛 fnOS 应用合集，统一管理、统一构建。

| 应用 | 最新版本 | 编译时间 |
|:-----|:-------:|:-------:|
| [ClawBot Gateway](clawbot-gateway/) — 微信 iLink 消息网关，支持多后端适配、智能路由和虚拟 Bot 代理 | [![clawbot-gateway](https://img.shields.io/github/v/release/EzFavorites/FnDepot?filter=clawbot-gateway-v*&label=&color=blue)](https://github.com/EzFavorites/FnDepot/releases) | 2026-08-16 19:28 |

## 应用列表

- [ClawBot Gateway](clawbot-gateway/) — 微信 iLink 消息网关，支持多后端适配、智能路由和虚拟 Bot 代理

## 构建方式

每个应用通过 GitHub Actions 自动构建，打 tag 触发：

```bash
# 构建 ClawBot Gateway
git tag clawbot-gateway-v0.1.0 && git push origin clawbot-gateway-v0.1.0
```

也可通过 Workflow Dispatch 手动触发构建。