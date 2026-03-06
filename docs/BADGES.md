# GitHub 徽章参考 | Badges Reference

本文档提供常用的 GitHub 项目徽章代码，可直接复制到 README 中使用。

---

## 📊 基础徽章

### 许可证

```markdown
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![License: GPL 3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
```

### 构建状态

```markdown
[![Build Status](https://github.com/USER/REPO/actions/workflows/ci.yml/badge.svg)](https://github.com/USER/REPO/actions)
[![CI/CD](https://github.com/USER/REPO/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/USER/REPO/actions)
[![Coverage Status](https://coveralls.io/repos/github/USER/REPO/badge.svg)](https://coveralls.io/github/USER/REPO)
```

### 版本

```markdown
[![Version](https://img.shields.io/github/v/release/USER/REPO)](https://github.com/USER/REPO/releases)
[![Last Commit](https://img.shields.io/github/last-commit/USER/REPO)](https://github.com/USER/REPO/commits)
[![Release Date](https://img.shields.io/github/release-date/USER/REPO)](https://github.com/USER/REPO/releases)
```

---

## ⭐ 社区徽章

### Stars & Issues

```markdown
[![GitHub stars](https://img.shields.io/github/stars/USER/REPO.svg)](https://github.com/USER/REPO/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/USER/REPO.svg)](https://github.com/USER/REPO/network)
[![GitHub issues](https://img.shields.io/github/issues/USER/REPO.svg)](https://github.com/USER/REPO/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/USER/REPO.svg)](https://github.com/USER/REPO/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/USER/REPO.svg)](https://github.com/USER/REPO/pulls)
```

### 贡献者

```markdown
[![Contributors](https://img.shields.io/github/contributors/USER/REPO.svg)](https://github.com/USER/REPO/graphs/contributors)
[![All Contributors](https://img.shields.io/badge/all_contributors-10-orange.svg)](#contributors)
```

---

## 💻 技术栈徽章

### 编程语言

```markdown
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Node.js 18+](https://img.shields.io/badge/node-18+-green.svg)](https://nodejs.org/)
[![TypeScript 5+](https://img.shields.io/badge/typescript-5+-blue.svg)](https://www.typescriptlang.org/)
[![Rust 1.70+](https://img.shields.io/badge/rust-1.70+-orange.svg)](https://www.rust-lang.org/)
```

### 框架

```markdown
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109.0-green.svg)](https://fastapi.tiangolo.com/)
[![React 18](https://img.shields.io/badge/react-18-blue.svg)](https://react.dev/)
[![Vue 3](https://img.shields.io/badge/vue-3-green.svg)](https://vuejs.org/)
[![Next.js 14](https://img.shields.io/badge/next.js-14-black.svg)](https://nextjs.org/)
```

### 工具

```markdown
[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-ready-blue.svg)](https://kubernetes.io/)
[![Redis](https://img.shields.io/badge/redis-ready-red.svg)](https://redis.io/)
[![PostgreSQL](https://img.shields.io/badge/postgresql-ready-blue.svg)](https://www.postgresql.org/)
```

---

## 🤝 社区徽章

### 贡献欢迎

```markdown
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Good First Issues](https://img.shields.io/github/issues/USER/REPO/good%20first%20issue)](https://github.com/USER/REPO/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
```

### 社交

```markdown
[![Discord](https://img.shields.io/discord/CHANNEL_ID?label=Discord&logo=discord)](https://discord.gg/INVITE)
[![Twitter](https://img.shields.io/twitter/follow/USERNAME?style=social)](https://twitter.com/USERNAME)
[![WeChat](https://img.shields.io/badge/WeChat-Official-brightgreen.svg)](https://weixin.qq.com/)
```

---

## 📈 分析徽章

### 代码质量

```markdown
[![Code Quality](https://img.shields.io/codacy/grade/REPO_ID)](https://www.codacy.com/)
[![CodeFactor](https://www.codefactor.io/repository/github/USER/REPO/badge)](https://www.codefactor.io/repository/github/USER/REPO)
[![Maintainability](https://api.codeclimate.com/v1/badges/REPO_ID/maintainability)](https://codeclimate.com/)
```

### 下载量

```markdown
[![Downloads](https://img.shields.io/npm/dm/package.svg)](https://www.npmjs.com/package/package)
[![Downloads](https://img.shields.io/pypi/dm/package.svg)](https://pypi.org/project/package/)
[![Downloads](https://img.shields.io/docker/pulls/image.svg)](https://hub.docker.com/r/image/)
```

---

## 🎨 自定义徽章

使用 shields.io 创建自定义徽章：

```markdown
[![Custom Badge](https://img.shields.io/badge/custom-value-color)](https://shields.io/)
```

### 颜色选项

- `brightgreen` / `green`
- `yellow` / `orange` / `red`
- `blue` / `lightblue`
- `purple` / `pink`
- `black` / `white` / `grey`
- 或十六进制颜色：`color=ff69b4`

### 样式选项

- `flat` (默认)
- `flat-square`
- `plastic`
- `for-the-badge`
- `social`

示例：
```markdown
[![Badge](https://img.shields.io/badge/style-for_the_badge-ff69b4?style=for-the-badge)](https://shields.io/)
```

---

## 📝 使用建议

### 最佳实践

1. **适度使用** - 5-8 个关键徽章即可，避免过多
2. **位置** - 放在 README 顶部，标题下方
3. **相关性** - 只添加与项目相关的徽章
4. **可点击** - 确保徽章链接到相关页面
5. **更新** - 定期检查徽章链接是否有效

### 推荐组合

```markdown
# 基础组合
[![License](license-badge)]()
[![Build](build-badge)]()
[![Stars](stars-badge)]()
[![Issues](issues-badge)]()

# 完整组合
[![License](license-badge)]()
[![Build](build-badge)]()
[![Coverage](coverage-badge)]()
[![Version](version-badge)]()
[![Stars](stars-badge)]()
[![Issues](issues-badge)]()
[![PRs](prs-badge)]()
[![Discord](discord-badge)]()
```

---

## 🔗 相关资源

- [Shields.io](https://shields.io/) - 徽章生成服务
- [GitHub Badges](https://github.com/badges) - GitHub 官方徽章
- [For the Badge](https://forthebadge.com/) - 风格化徽章
- [Simple Icons](https://simpleicons.org/) - 品牌图标

---

**最后更新**: 2026-03-05
