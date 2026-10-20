# 数据访问

使用 SQLAlchemy 定义业务数据模型，并管理数据库连接与会话生命周期。

| 模块 | 用途 |
| --- | --- |
| [models.py](models.py) | 定义仓库、Issue、PR、CI、知识库、会话、记忆、Agent 运行、评测与操作草稿等实体 |
| [session.py](session.py) | 定义声明式模型基类、数据库引擎、会话工厂和 FastAPI 数据库依赖 |

数据库地址由 [core/config.py](../core/config.py) 中的 `database_url` 配置。
