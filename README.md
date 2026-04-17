# OpenClaw Cookbook

OpenClaw 实操手册 -- 养虾过程中的知识沉淀、制品模板与最佳实践。

## 项目结构

```
openclaw-cookbook/
├── workspace-templates/   # OpenClaw 工作区核心制品模板
│   ├── SOUL.md            # Agent 人格与行为定义
│   ├── AGENTS.md          # 多 Agent 协作与流程编排
│   ├── HEARTBEAT.md       # 定时任务与自主行为配置
│   ├── USER.md            # 用户偏好与个人上下文
│   └── SKILLS.md          # 技能注册与调用说明
├── knowledge/             # 知识总结与学习笔记
├── skills/                # 自定义 Skill 模板与示例
├── prompts/               # 常用 Prompt 模板
└── examples/              # 实际场景案例
```

## workspace-templates

OpenClaw 工作区的核心文件模板，这是整个养虾体系的骨架：

| 文件 | 作用 | 优先级 |
|------|------|--------|
| `SOUL.md` | 定义 Agent 的身份、思维模式和行为准则 | 必配 |
| `AGENTS.md` | 定义多 Agent 分工、工具权限和协作流程 | 必配 |
| `HEARTBEAT.md` | 配置 Agent 的定时任务和自主行为 | 按需 |
| `USER.md` | 记录用户偏好、技术栈和工作习惯 | 推荐 |
| `SKILLS.md` | 注册和说明可用的自定义技能 | 按需 |

## 使用方式

1. 将 `workspace-templates/` 中的模板复制到你的 OpenClaw 工作区 (`~/.openclaw/workspace/`)
2. 根据自身需求修改各文件内容
3. 参考 `knowledge/` 中的笔记和 `examples/` 中的案例进行调优

## 持续更新

本仓库会随着使用经验的积累持续更新，欢迎 Star & Fork。
