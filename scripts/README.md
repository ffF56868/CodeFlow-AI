# 开发辅助脚本

提供本地环境启动、数据库初始化、演示数据与 GitHub 访问检查等工具。

| 脚本 | 用途 |
| --- | --- |
| `start_rag.ps1` | 启动使用 SQLite、deterministic embedding 且关闭 Milvus 的本地 RAG 演示环境 |
| `init_pgvector.sql` | 为 PostgreSQL 启用 pgvector 扩展，由 Docker Compose 初始化数据库时加载 |
| `seed_demo_data.py` | 写入演示仓库、Issue、PR 与 CI 数据并建立文档索引 |
| `sync_github_repo.py` | 检查 GitHub 仓库访问，输出仓库名称与默认分支 |
| `build_resume_templates.py` | 生成简历模板 |
| `organize_course_images.py` | 整理课程图片资源 |

启动演示环境前需要安装后端与前端依赖。环境准备和完整 RAG 服务的启动方式见
[项目 README](../README.md#快速开始)及其 RAG 知识问答系统说明。
