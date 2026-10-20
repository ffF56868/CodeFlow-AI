# 核心配置

集中管理应用环境设置、日志配置与仓库凭据加解密。

| 模块 | 用途 |
| --- | --- |
| [config.py](config.py) | 使用 Pydantic Settings 读取环境变量与 `.env`，定义数据库、GitHub、模型、RAG 和同步配置 |
| [logging.py](logging.py) | 定义日志级别与输出格式 |
| [security.py](security.py) | 提供 Token 加密与解密函数 |

可用配置项的示例见[环境变量模板](../../../.env.example)。
