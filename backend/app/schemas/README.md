# API 数据结构

定义接口使用的 Pydantic 请求与响应模型，供 FastAPI 执行数据校验、序列化并生成 OpenAPI 文档。

| 模块 | 数据范围 |
| --- | --- |
| [repos.py](repos.py)、[workspaces.py](workspaces.py) | 仓库接入、同步、工作区与跨仓库报告 |
| [issues.py](issues.py)、[pull_requests.py](pull_requests.py)、[ci.py](ci.py) | Issue、PR、CI 记录与分析结果 |
| [chat.py](chat.py)、[conversations.py](conversations.py)、[feedback.py](feedback.py) | 对话、会话与用户反馈 |
| [knowledge.py](knowledge.py)、[rag.py](rag.py)、[search.py](search.py) | 知识管理、RAG 问答与检索 |
| [code_graph.py](code_graph.py)、[project_index.py](project_index.py) | 代码图谱与项目索引 |
| [skills.py](skills.py)、[workflow.py](workflow.py) | Skill、MCP 状态与 Agent 工作流 |
| [evals.py](evals.py)、[reports.py](reports.py) | 评测与工程报告 |
| [action_drafts.py](action_drafts.py)、[analysis.py](analysis.py) | 操作草稿与通用分析结构 |

对应的 HTTP 接口见 [api/routes](../api/routes/)。
