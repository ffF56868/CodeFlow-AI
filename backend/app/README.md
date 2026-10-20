# 后端应用

包含 API 路由、基础配置、数据访问与业务服务，由 [main.py](main.py) 组装为 FastAPI 应用。

| 路径 | 用途 |
| --- | --- |
| [api/routes/](api/routes/) | API 路由：仓库、研发分析、Agent 对话与知识检索 |
| [core/](core/) | 核心配置：环境设置、日志与凭据加解密 |
| [db/](db/) | 数据访问：SQLAlchemy 模型、连接与会话管理 |
| [mcp/](mcp/) | MCP 服务：知识证据检索与会话记忆读取 |
| [schemas/](schemas/) | 数据结构：API 请求、响应与参数校验 |
| [services/](services/) | 业务服务：Agent、GitHub、RAG 与工作区管理 |
| [skills/](skills/) | Agent 技能：Issue 分析、PR 审查、CI 排障与周报 |
| [tests/](tests/) | 自动化测试：Agent、RAG、仓库同步与上下文管理 |
| [main.py](main.py) | 应用入口：FastAPI 初始化、路由注册与启动任务 |

环境准备与启动方法见[后端说明](../README.md)和[项目快速开始](../../README.md#快速开始)。
