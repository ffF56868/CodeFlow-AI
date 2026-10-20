# Agent 技能

各子目录通过 `SKILL.md` 定义专用任务指令、触发条件与允许使用的工具；
由 [Skill 注册中心](../services/skills/registry.py)加载并供 Agent 选择。

| 技能 | 用途 |
| --- | --- |
| [issue-triage](issue-triage/SKILL.md) | Issue 分类与问题分析 |
| [pr-review](pr-review/SKILL.md) | PR 变更审查与风险检查 |
| [ci-debug](ci-debug/SKILL.md) | CI 失败分析与排障 |
| [project-investigation](project-investigation/SKILL.md) | 项目调查与上下文检索 |
| [safety-draft](safety-draft/SKILL.md) | 生成需要确认的操作草稿 |
| [weekly-report](weekly-report/SKILL.md) | 工程周报生成 |

查询技能列表、完整指令与 MCP 状态的接口见 [api/routes/skills.py](../api/routes/skills.py)。
