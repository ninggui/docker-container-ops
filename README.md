# docker-container-ops

Docker 容器运维：exec/cp/restart、只读挂载修改、config热更新、常见避坑。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀。

## 使用方式

将本仓库内容放入你的 Agent 技能目录：

- **Hermes**: `skills/` 目录
- **Claude**: `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式

Agent 会在匹配触发条件时自动加载并使用。

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
