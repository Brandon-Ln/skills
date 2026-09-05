# Agent Skills

[English](README.md) | 简体中文

由 Brandon 个人维护和定制的 Agent Skills。

## 安装

```bash
npx skills add Brandon-Ln/skills --skill batch-grill-me
```

查看可用 skills，或指定安装到 Codex：

```bash
npx skills add Brandon-Ln/skills --list
npx skills add Brandon-Ln/skills --skill batch-grill-me --agent codex
```

## 开发

运行 `pnpm install` 安装依赖和 Git hooks。提交时自动使用 Prettier 格式化暂存文件。修改 hook 配置后，运行 `pnpm prepare`。
