# 前端应用

基于 Next.js、React、TypeScript 与 Tailwind CSS 构建，使用 React Query 管理服务端数据。

主要界面包括仓库管理、Issue 与 PR 分析、CI 排障、Agent 对话、知识库与 RAG 问答、
评测、工程周报和操作草稿。

## 目录说明

| 路径 | 用途 |
| --- | --- |
| `app/` | 页面路由、布局与全局样式 |
| `components/` | 共享界面组件 |
| `lib/` | API 客户端与通用工具 |

## 开发启动

先按照[项目快速开始](../README.md#快速开始)配置并启动后端，再在本目录运行：

```bash
npm install
npm run dev
```

默认前端地址为 `http://localhost:3000`，后端地址默认为 `http://localhost:8000`。
如需修改后端地址，请在启动或构建前设置 `NEXT_PUBLIC_API_BASE_URL` 环境变量。
