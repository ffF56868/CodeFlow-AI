# 后端服务

基于 FastAPI 构建，提供 GitHub 数据同步、AI Agent 编排、
RAG 知识检索以及 Issue、PR 和 CI 分析能力。

## 目录说明

| 路径 | 用途 |
| --- | --- |
| `app/api/` | HTTP API 路由 |
| `app/services/` | Agent 编排、GitHub 集成、RAG 与业务服务 |
| `app/db/` | 数据模型与数据库会话 |
| `app/schemas/` | 请求与响应数据结构 |
| `app/skills/` | Agent 使用的 Skill 指令与参考资源 |
| `app/tests/` | 后端自动化测试 |

依赖安装与启动步骤见[项目快速开始](../README.md#快速开始)。默认 API 地址为
`http://localhost:8000`，交互式接口文档位于 `http://localhost:8000/docs`。
