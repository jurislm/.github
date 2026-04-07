<div align="center">

<img src="https://github.com/jurislm.png" width="120" alt="JurisLM Logo" />

# JurisLM

**AI 驅動的法律智慧平台 · AI-Powered Legal Intelligence for Taiwan**

[![Website](https://img.shields.io/badge/🌐_Website-jurislm.com-blue?style=for-the-badge)](https://entire.jurislm.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/orgs/jurislm/repositories?language=typescript)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/orgs/jurislm/repositories?language=python)
[![Anthropic](https://img.shields.io/badge/Powered_by-Claude_AI-orange?style=for-the-badge)](https://www.anthropic.com)

</div>

---

## 🏛️ 關於 JurisLM

JurisLM 是一個專為台灣法律環境設計的 AI 智慧法律平台，整合判決書、法規資料庫與 AI 語言模型，提供律師、法務人員與法學研究者精準的法律資訊檢索與分析服務。

> *Juris* (Law) + *LM* (Language Model) — 讓 AI 讀懂法律，讓法律觸手可及。

---

## 🚀 核心產品

| 產品 | 說明 | 狀態 |
|------|------|------|
| **[Entire](https://entire.jurislm.com)** | 全量司法判決書 AI 搜尋與分析平台 | 🟢 上線中 |
| **[Lawyer](https://lawyer.jurislm.com)** | 律師事務所智慧工作流程助理 | 🟢 上線中 |
| **[LexVision](https://lexvision.jurislm.com)** | 法規視覺化與語意搜尋工具 | 🟢 上線中 |

---

## 🛠️ 技術棧

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-Vector_Search-green?style=flat-square)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-Self_Hosted-purple?style=flat-square)

</div>

- **前端**：Next.js 15 + TypeScript + Tailwind CSS
- **後端**：Bun Runtime + PostgreSQL 16 + pgvector
- **AI**：Claude (Anthropic) · OpenAI Embeddings
- **基礎設施**：Hetzner Cloud + Coolify + Cloudflare
- **MCP**：自建 Coolify MCP Server ([coolify-mcp](https://github.com/jurislm/coolify-mcp)) · Hetzner MCP Server ([hetzner-mcp](https://github.com/jurislm/hetzner-mcp))

---

## 📦 開源專案

### 🔧 [coolify-mcp](https://github.com/jurislm/coolify-mcp)

Coolify MCP Server — 讓 Claude AI 直接管理 Coolify 部署平台的 Model Context Protocol 整合工具。

```bash
npx jurislm-coolify-mcp
```

### ☁️ [hetzner-mcp](https://github.com/jurislm/hetzner-mcp)

Hetzner MCP Server — 讓 Claude Code 透過自然語言管理 Hetzner Cloud 基礎設施，支援建立/刪除伺服器、SSH 金鑰管理等 14 種操作。

```bash
npm install -g hetzner-mcp-server
```

---

## 🌏 我們的使命

台灣擁有數百萬份公開判決書與法規文件，卻缺乏有效的智慧化工具。JurisLM 致力於：

- 📚 **全量索引**：建立完整的司法判決書向量資料庫
- 🔍 **語意搜尋**：超越關鍵字，理解法律語境
- 🤖 **AI 分析**：自動摘要、風險評估、案例比對
- ⚖️ **民主化法律知識**：讓每個人都能平等取得法律資訊

---

<div align="center">

**📍 Taiwan** · **🔒 Privacy First** · **⚡ Powered by Claude AI**

</div>
