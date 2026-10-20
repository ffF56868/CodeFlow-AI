# API 路由

提供仓库管理、研发分析、Agent 对话与知识检索等 HTTP 接口。
各模块的路由前缀由[应用入口](../../main.py)统一注册，请求与响应结构位于
[schemas](../../schemas/)，业务实现位于 [services](../../services/)。

| 模块 | 用途 |
| --- | --- |
| [action_drafts.py](action_drafts.py) | 操作草稿：创建、确认执行与审计记录 |
| [chat.py](chat.py) | Agent 对话：任务规划、流式响应与工具协作 |
| [ci.py](ci.py) | CI 分析：运行记录、失败任务与排障建议 |
| [code_graph.py](code_graph.py) | 代码图谱：索引重建、符号查询与关联检索 |
| [conversations.py](conversations.py) | 会话管理：创建、查询与删除仓库对话 |
| [evaluations.py](evaluations.py) | 质量评测：RAGAS 评分、结果对比与重新评分 |
| [feedback.py](feedback.py) | 对话反馈：评价记录、审核与执行轨迹查询 |
| [issues.py](issues.py) | Issue 分析：问题详情、智能诊断与相似检索 |
| [knowledge.py](knowledge.py) | 知识管理：资料上传、长期记忆与团队信息 |
| [project_index.py](project_index.py) | 项目索引：后台扫描、状态查询与提醒控制 |
| [pull_requests.py](pull_requests.py) | PR 审查：变更分析、代码快照与检查清单 |
| [rag.py](rag.py) | RAG 服务：文档处理、混合检索与引用问答 |
| [reports.py](reports.py) | 工程报告：周报生成与仓库健康分析 |
| [repos.py](repos.py) | 仓库管理：接入、同步、切换与删除 |
| [search.py](search.py) | 知识检索：语义搜索与元数据条件过滤 |
| [skills.py](skills.py) | 技能接口：Skill 列表、指令与 MCP 状态 |
| [webhooks.py](webhooks.py) | GitHub 事件：签名校验与后台同步 |
| [workspaces.py](workspaces.py) | 工作区管理：工作区创建与跨仓库报告 |

启动后端后，可通过 `http://localhost:8000/docs` 查看完整接口与参数。
