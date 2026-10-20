# 后端服务

基于 FastAPI 构建，提供 GitHub 数据同步、AI Agent 编排、
RAG 知识检索以及 Issue、PR 和 CI 分析能力。

## 目录说明

| 路径 | 用途 |
| --- | --- |
| [app/api/routes/](app/api/routes/) | 仓库、研发分析、Agent 对话与知识检索接口 |
| [app/core/](app/core/) | 环境配置、日志与凭据加解密 |
| [app/db/](app/db/) | SQLAlchemy 数据模型、连接与会话管理 |
| [app/mcp/](app/mcp/) | MCP 知识证据检索与会话记忆服务 |
| [app/schemas/](app/schemas/) | API 请求、响应与参数校验 |
| [app/services/](app/services/) | Agent 编排、GitHub 集成、RAG 与业务服务 |
| [app/skills/](app/skills/) | Agent 使用的 Skill 指令与参考资源 |
| [app/tests/](app/tests/) | 后端自动化测试 |
| [app/main.py](app/main.py) | FastAPI 应用初始化、路由注册与启动任务 |

完整模块导航见 [app/README.md](app/README.md)，API 文件用途见[路由目录说明](app/api/routes/README.md)。

依赖安装与启动步骤见[项目快速开始](../README.md#快速开始)。默认 API 地址为
`http://localhost:8000`，交互式接口文档位于 `http://localhost:8000/docs`。
