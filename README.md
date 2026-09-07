# Docker 容器运维

![GitHub stars](https://img.shields.io/github/stars/ninggui/docker-container-ops)
![License](https://img.shields.io/github/license/ninggui/docker-container-ops)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/docker-container-ops)

容器操作 / 只读挂载修改 / config 热更新。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| docker exec/cp/restart |
| 只读挂载配置热补丁 |
| 容器内代码替换 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/docker-container-ops

## 优势

- NAS 只读挂载场景实测
- 免重建容器的热更新方案
- 操作步骤可复制执行

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
