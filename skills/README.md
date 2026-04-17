# 自定义 Skill 模板

存放自定义 OpenClaw Skill 的模板和示例。

## Skill 标准结构

```
skills/
└── my-skill/
    ├── SKILL.md       # Skill 定义文件（必需）
    ├── scripts/       # 辅助脚本
    ├── references/    # 参考资料
    └── assets/        # 静态资源
```

## SKILL.md 基本格式

```markdown
name: my-skill
description: 一句话描述 Skill 的用途和触发条件

# Skill 名称

## Workflow
### Step 1: ...
### Step 2: ...

## Tools
### tool_name
描述工具的输入输出

## Quick Start
常见使用场景示例
```
