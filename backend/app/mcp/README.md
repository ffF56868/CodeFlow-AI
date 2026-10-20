# MCP 记忆服务

[memory_server.py](memory_server.py) 通过 stdio 提供 MCP 工具，连接仓库知识证据与会话记忆。

| 工具 | 用途 |
| --- | --- |
| `devflow_search_evidence` | 搜索仓库知识与持久记忆 |
| `devflow_get_thread_context` | 按关键词、消息标识或分页范围读取原始聊天转录 |
| `devflow_read_session_events` | 读取已封存的会话摘要、原始消息和工具事件 |

工具使用 `repo_id` 定位仓库，可通过 `conversation_id` 指定会话。
后端的 stdio MCP 客户端实现见 [services/mcp_client.py](../services/mcp_client.py)。
