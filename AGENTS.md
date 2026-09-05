# AGENTS 指引

- Commit message 遵守 Conventional Commits 规范，使用 `type(scope): description` 格式，`scope` 可省略；例如 `feat: 添加新技能`、`fix(batch-grill-me): 修正提问逻辑`、`docs: 更新安装说明`。
- 每个 skill 放在 `skills/<name>/SKILL.md`，目录名与 frontmatter 的 `name` 一致，使用小写字母、数字和连字符。
- 描述与正文使用中文，保留工具名、命令和配置字段的原名。翻译保留原始行为，定制内容明确标注。
- skill 依赖的资料和脚本放在自身目录内，使用相对路径；不得依赖仓库根目录、其他 skills 或本机绝对路径。
- 引入或修改社区内容时，保留作者、来源和适用许可证；仅记录已核实的版本信息。
