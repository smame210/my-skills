# my-skills

用于统一管理个人 skills 的仓库。

## 目录结构

```text
my-skills/
├── skills/      # 各类技能定义
├── templates/   # 可复用模板
├── scripts/     # 自动化脚本
├── .gitignore
├── LICENSE
└── README.md
```

## 使用方式

1. 在 `skills/` 下按主题创建技能目录。
2. 在 `templates/` 中维护可复用模板。
3. 在 `scripts/` 中放置管理与校验脚本。

## 版本管理建议

- 每次新增/更新一个 skill 使用独立提交。
- 提交信息建议：`feat(skill): add xxx` / `docs(skill): update xxx`。
