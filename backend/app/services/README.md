# 业务服务

实现 Agent 编排、GitHub 集成、RAG 检索与工作区管理等后端业务能力，供 API 路由及工具调用。

| 路径 | 用途 |
| --- | --- |
| [agents/](agents/) | 对话、Issue、PR、CI、周报等 Agent 与工作流编排 |
| [github/](github/) | GitHub API 客户端与数据访问 |
| [llm/](llm/) | 模型调用与消息处理 |
| [rag/](rag/) | 文档解析、切片、Embedding、检索、重排与问答 |
| [skills/](skills/) | Skill 注册、选择、加载与执行校验 |
| [evals/](evals/) | 评测集、评测执行与结果分析 |
| [repos_sync.py](repos_sync.py)、[scheduler.py](scheduler.py) | 仓库数据同步与定时任务 |
| [chat_memory.py](chat_memory.py)、[memory_hub.py](memory_hub.py) | 会话记忆、证据召回与长期记忆管理 |
| [context_compression.py](context_compression.py) | 对话上下文压缩 |
| [code_analysis.py](code_analysis.py)、[code_search.py](code_search.py) | 代码分析、索引与检索 |
| [worktree_manager.py](worktree_manager.py) | PR 代码快照与工作区管理 |
| [permissions.py](permissions.py) | 角色权限检查与审计日志 |
