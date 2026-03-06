# 贡献指南 | Contributing to OpenClaw-project

首先，感谢你考虑为 OpenClaw-project 做出贡献！🎉

本项目是 OpenClaw 工作区管理和配置的核心仓库，用于支持公司 AI 助手系统的运行。

## 📋 目录

- [行为准则](#行为准则)
- [我能如何贡献？](#我能如何贡献)
- [开发环境设置](#开发环境设置)
- [提交代码流程](#提交代码流程)
- [代码风格](#代码风格)
- [提交信息规范](#提交信息规范)

---

## 行为准则

本项目致力于提供一个开放、友好、包容的社区环境。请尊重所有贡献者和用户。

---

## 我能如何贡献？

### 🐛 报告 Bug

发现 Bug？请创建 Issue 并提供：
- 清晰的标题和描述
- 复现步骤
- 环境信息（OS、OpenClaw 版本等）
- 相关日志或截图

### 💡 提出功能建议

有好想法？欢迎提交 Feature Request：
- 描述功能和使用场景
- 说明为什么需要这个功能
- 如果可能，提供实现建议

### 📝 改进文档

文档同样重要！你可以帮助：
- 修正拼写和语法错误
- 补充缺失的说明
- 添加示例配置
- 更新技能文档

### 🔧 提交代码

准备好贡献代码？请遵循以下流程。

---

## 开发环境设置

### 前置要求

- OpenClaw 已安装并配置
- Git
- Node.js 18+ (可选，用于某些工具)

### 安装步骤

```bash
# 1. Fork 项目
# 在 GitHub 上点击 Fork 按钮

# 2. 克隆你的 Fork
git clone https://github.com/YOUR_USERNAME/OpenClaw-project.git
cd OpenClaw-project

# 3. 添加上游远程仓库
git remote add upstream https://github.com/ENDcodeworld/OpenClaw-project.git

# 4. 安装 OpenClaw (如果尚未安装)
# 参考：https://docs.openclaw.ai/getting-started

# 5. 验证 OpenClaw 安装
openclaw --version
```

---

## 提交代码流程

### 1. 创建分支

```bash
# 确保基于最新的主分支
git checkout main
git pull upstream main

# 创建功能分支
git checkout -b feature/amazing-feature
# 或修复分支
git checkout -b fix/bug-description
```

### 2. 进行更改

- 保持代码整洁
- 添加必要的注释
- 更新相关文档
- 测试配置变更

### 3. 提交更改

```bash
# 添加更改的文件
git add .

# 提交（遵循提交信息规范）
git commit -m "feat: add amazing feature"
```

### 4. 推送到 GitHub

```bash
git push origin feature/amazing-feature
```

### 5. 创建 Pull Request

1. 访问你的 Fork 页面
2. 点击 "Compare & pull request"
3. 填写 PR 描述
4. 等待 CI 检查通过
5. 等待维护者审核

---

## 代码风格

### 配置文件

- 使用 YAML 格式时保持缩进一致（2 空格）
- 使用 JSON 格式时保持格式整洁
- 添加必要的注释说明配置用途

### Markdown 文档

- 使用清晰的标题层级
- 代码块标注语言类型
- 保持文档结构一致

---

## 提交信息规范

我们遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范。

### 格式

```
<type>(<scope>): <subject>
```

### 类型 (Type)

- `feat`: 新功能
- `fix`: Bug 修复
- `docs`: 文档更新
- `style`: 格式调整
- `refactor`: 代码重构
- `chore`: 构建/配置变动
- `ci`: CI/CD 配置

### 示例

```bash
feat(workspace): add new skill configuration
fix(config): resolve API key loading issue
docs(readme): update installation instructions
chore(ci): update GitHub Actions workflow
```

---

## 🎉 感谢你的贡献！

每一个贡献，无论大小，都让 OpenClaw-project 变得更好。

如果你有任何问题，欢迎随时通过 Issue 联系我们！

---

**Happy Coding!** 🚀
