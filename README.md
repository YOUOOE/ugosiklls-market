# Ugosikllo · AI 技能与数字资产市场

> **让 AI 能力自由流通** —— 一个开箱即用、打开就能用的 AI 技能 / 源码 / 模板交易展示平台。

🔗 **在线访问：https://aiugooe.com/sikllo/** （无需注册即可浏览，发布作品后审核上架）

---

## 🎯 这是什么

Ugosikllo 是一个 **AI 生态数字资产展示与对接平台**：
- 开发者发布 **技能包、源码、模板、提示词、工作流、教程、MCP 服务、智能体、插件、数据集**
- 平台审核后展示，买家通过详情页 **直接联系开发者** 私下对接
- 内置 **炫技社区**（开发者朋友圈实时秀技）、**今日炫技榜**、**精选开发者**

## ✨ 核心功能

| 功能 | 说明 |
|---|---|
| 🗂️ 多分类市场 | 技能包 / 源码 / 模板 / 提示词 / 工作流 / 教程 / MCP / 智能体 / 插件 / 数据集 |
| 🚀 开发者发布 | 一键发布作品，审核通过后上架 |
| 🔍 智能筛选 | 按分类 + 按智能体（DeepSeek / Claude / 豆包 / Kimi / 通义 / n8n / Dify）筛选 |
| 📱 炫技社区 | 开发者朋友圈实时秀技、点赞评论 |
| 🏆 今日炫技榜 | 实时热度榜单 |
| 👤 精选开发者 | 认证开发者展示 |
| 🎨 动效背景 | 粒子网络 / 魔法方块 / 代码雨 / 波纹（鼠标交互） |

## 🖼️ 界面预览

**首页**

![首页](screenshots/home-top.png)

**商品市场**

![商品市场](screenshots/home-market.png)

**商品详情**

![商品详情](screenshots/product.png)

**炫技社区**

![炫技社区](screenshots/feed.png)

**发布作品**

![发布作品](screenshots/publish.png)

**我的作品**

![我的作品](screenshots/mine.png)


## 🚀 快速使用

1. **打开** https://aiugooe.com/sikllo/
2. **浏览**：按分类 / 智能体筛选，搜索你想找的 AI 技能
3. **联系开发者**：点开商品详情，通过微信 / 邮箱直接联系开发者对接
4. **发布作品**：注册开发者账号 → 填写商品信息 → 提交审核 → 上架展示
5. **参与炫技**：发布你的 AI 作品动态，让更多人看到

## 🛠️ 技术栈

- **前端**：Next.js 16（App Router + TypeScript）+ 原生 CSS（DeepSeek 极简大气风）
- **后端**：Next.js Route Handler + Prisma ORM
- **数据库**：SQLite（开发期，可切换 PostgreSQL）
- **部署**：Docker / PM2 + Nginx

## 📦 本地运行

```bash
npm install
npx prisma migrate dev
npm run dev
# 打开 http://localhost:3000
```

## ⚠️ 说明

- 平台仅提供信息展示服务，交易由买卖双方私下完成
- 本项目为展示用途，欢迎体验交流

---

**Ugosikllo · 让 AI 能力自由流通**
