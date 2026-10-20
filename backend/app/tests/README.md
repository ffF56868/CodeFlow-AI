# 后端自动化测试

覆盖 Agent 分析与工作流、RAG 文档处理与检索、仓库接入与同步、代码索引、会话记忆、
上下文压缩和评测等能力。

| 代表性测试 | 验证范围 |
| --- | --- |
| [test_chat_agent.py](test_chat_agent.py)、[test_workflow_orchestrator.py](test_workflow_orchestrator.py) | 对话 Agent 与多 Agent 工作流 |
| [test_rag_retrieval_pipeline.py](test_rag_retrieval_pipeline.py)、[test_rag_qa.py](test_rag_qa.py) | RAG 检索链路与知识问答 |
| [test_repo_sync_integration.py](test_repo_sync_integration.py) | 仓库分页同步、故障处理与数据库升级 |
| [test_code_indexing.py](test_code_indexing.py)、[test_code_search.py](test_code_search.py) | 代码索引与检索 |
| [test_context_compression.py](test_context_compression.py)、[test_context_memory_projection.py](test_context_memory_projection.py) | 上下文压缩与记忆投影 |
| [test_eval_runner.py](test_eval_runner.py) | 评测执行 |

安装后端依赖后，可在 `backend` 目录运行：

```bash
python -m pytest app/tests
```
