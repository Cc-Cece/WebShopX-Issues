# WebShopX

[简体中文](README.md) | [English](README_EN.md)

> 官方商城（B2C） · 玩家市场（C2C） · 拍卖 · 动态定价 · 订单履约 · Web 管理后台

[![Minecraft](https://img.shields.io/badge/Minecraft-1.18.2%2B-2e7d32?style=flat&logo=minecraft&logoColor=white)](https://modrinth.com/plugin/webshopx)  [![Languages](https://img.shields.io/badge/Language-%E4%B8%AD%E6%96%87%20%7C%20English-1565c0?style=flat)](https://docs.akihito.dpdns.org/webshopx/overview)  [![License](https://img.shields.io/badge/License-Custom-blue?style=flat)](LICENSE)

[![Modrinth](https://img.shields.io/badge/Modrinth-Download-00AF5C?style=flat&logo=modrinth&logoColor=white)](https://modrinth.com/plugin/webshopx)  [![Wiki](https://img.shields.io/badge/Wiki-Documentation-34d058?style=flat&logo=docusaurus&logoColor=white)](https://docs.akihito.dpdns.org/webshopx/overview)  [![Bilibili](https://img.shields.io/badge/%E8%A7%86%E9%A2%91%E4%BB%8B%E7%BB%8D-Bilibili-fb7299?style=flat&logo=bilibili&logoColor=white)](https://www.bilibili.com/video/BV16zdZBTEbV/)  [![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/4mSg4VyxBN)

**WebShopX** 是面向 Paper / Purpur / Spigot / Folia Minecraft 服务器的 Web 商城与玩家交易系统。

Minecraft 插件负责游戏侧业务逻辑与 API，Web 前端为玩家和服务器运营者提供现代化的商城、市场与管理界面。

> 此处介绍项目基本信息及进行自动构建。完整功能介绍、截图和版本更新请查看 [Modrinth 项目页](https://modrinth.com/plugin/webshopx)。

## 功能特性

- **官方商城** — 商品购买、回收、库存、限购与动态定价
- **玩家市场** — 出售、收购、玩家商店、供货箱与交易管理
- **拍卖系统** — English / Dutch / Vickrey / Candle Auction
- **经济与支付** — ShopCoin / GameCoin、Vault、兑换、充值与退款
- **订单履约** — 自动发货、`/ws claim`、游戏信箱与异常兜底
- **Web 管理后台** — 商品、订单、市场、用户、经济与权限管理
- **多服支持** — MySQL / MariaDB + Redis
- **Web 部署** — Embedded / External / Relay

更完整的能力列表请查看 **[Modrinth](https://modrinth.com/plugin/webshopx)**。

## 运行环境

| Minecraft | Java | 服务端                          |
| --------- | ---- | ------------------------------- |
| `1.18.2+` | 17   | Paper / Purpur / Spigot         |
| `1.20.6+` | 21   | Paper / Purpur / Spigot / Folia |
| `26.1+`   | 25   | Paper / Purpur / Spigot / Folia |
| `26.2+`   | 25   | Paper / Purpur / Spigot / Folia |

数据库支持 **SQLite、MySQL、MariaDB**。

## 快速开始

1. 从 [Modrinth](https://modrinth.com/plugin/webshopx) 下载与你的 Minecraft / Java 环境匹配的构建。
2. 将 JAR 放入服务器的 `plugins/` 目录并启动服务器。
3. 按照 [安装与部署文档](https://docs.akihito.dpdns.org/webshopx/admin/install-deploy) 完成初始化。

首次使用推荐直接阅读：

**[WebShopX 快速开始](https://docs.akihito.dpdns.org/webshopx/player/quick-start)**

## 文档

README 仅提供项目概览。配置、命令、部署、API 和详细使用方法统一维护在正式文档中。

- 📖 [文档首页](https://docs.akihito.dpdns.org/)
- 🛒 [WebShopX 概览](https://docs.akihito.dpdns.org/webshopx/overview)
- 🚀 [安装与部署](https://docs.akihito.dpdns.org/webshopx/admin/install-deploy)
- ⚙️ [管理员配置](https://docs.akihito.dpdns.org/webshopx/admin/configuration)
- 📘 [使用指南](https://docs.akihito.dpdns.org/webshopx/guides/overview)
- 💻 [开发者快速开始](https://docs.akihito.dpdns.org/webshopx/developer/quickstart)
- 📑 [参考文档](https://docs.akihito.dpdns.org/webshopx/reference/overview)
- 📝 [文档仓库](https://github.com/Prism-Committee/docs)

## 相关项目

| 仓库                                                         | 说明                    |
| ------------------------------------------------------------ | ----------------------- |
| [WebShopX-Issues](https://github.com/Cc-Cece/WebShopX-Issues) | Bug、功能建议与社区反馈 |
| [Wiki](https://github.com/Prism-Committee/docs)                      | WebShopX 官方文档       |

## 参与贡献

欢迎参与测试、功能改进、文档完善和问题排查。

Bug 和功能建议请优先提交至：**[WebShopX Issues](https://github.com/Cc-Cece/WebShopX-Issues/issues)**

## 支持与社区

- 🐛 [问题反馈 / 功能建议](https://github.com/Cc-Cece/WebShopX-Issues/issues)
- 📖 [官方文档](https://docs.akihito.dpdns.org/)
- 💬 [Discord](https://discord.gg/4mSg4VyxBN)
- 🐧 QQ 群：`636803372`

## 许可证

截至目前 WebShopX **不是开源软件**。

使用、研究、修改和分发 WebShopX 前，请阅读完整的 **[LICENSE](LICENSE)**。未经许可，请勿重新分发软件或修改版本。
