# Box Rush（BOXラッシュ）

TGC 开箱平台 **Box Rush / BOXラッシュ** 的设计文档库。主打 **Breaking（众筹开卡）**，目标市场**日本**，差异化对手 **DOPA（オリパ）**，**只做 Web**，支付首选 **Stripe**。

设计内容分两份文档，**章号在两份之间全局统一**：

- **产品文档**：[docs/breaking-platform.md](docs/breaking-platform.md)（前言 + 第 1、5–10 章 + 附录 A、B）
- **市场研究**：[docs/market-research.md](docs/market-research.md)（第 2–4 章）

**团队预览站**：<https://box-rush.github.io/preview/>（模块示意图 + 全部原型 + 截图与 prompt 汇总；仓库 `box-rush/preview`，公开、noindex）

界面原型源文件：[`prototype/`](prototype/)（静态 HTML，浏览器直接打开；**只作布局与交互参考，其中参数是示例**）

**实现仓库**：`box-rush/project`（第一版代码；实现中发现的文档问题见 §10.14）

**开发从第 10 章读起**：规格权威顺序、按角色的阅读路径、状态枚举、验证算法规格与测试向量、未定参数与技术决策。

| 章 | 内容 |
|---|---|
| 前言 | 阅读指引、编号约定、**核心结论速查**（产品文档） |
| 1 | 体系总纲（推导主干，从这里读起） |
| 2 | 产品形态分类体系（市场研究） |
| 3 | 市场格局（市场研究） |
| 4 | 中国 Hobby 板块：上市公司证据（市场研究） |
| 5 | Breaking 玩法与日本落地 |
| 6 | 机制设计：多商家平台（不变量 I1–I9） |
| 7 | 单位经济模型 |
| 8 | 产品功能拆解 |
| 9 | 界面设计 Prompt（v0 / Lovable / Claude）；prompt 模板与生成过程（§9.8 / §9.9） |
| 10 | 开发交接（权威顺序、状态枚举、算法规格、技术选型、MVP 排期估算、待定事项总表） |
| 附录 A | 待决策与 Blocker |
| 附录 B | 产品名初步商标检索 |
