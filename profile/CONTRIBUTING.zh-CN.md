# 为 TRAE Community 做贡献

**欢迎加入 TRAE Community！我们很高兴有你参与贡献！** 🎉

本指南为 TRAE Community 组织下的所有仓库提供通用贡献指导。每个独立的仓库可能有自己的 `CONTRIBUTING.md` 文件，包含更多具体细节。

## 📋 目录

- [行为准则](#行为准则)
- [开始之前](#开始之前)
- [如何贡献](#如何贡献)
- [开发工作流](#开发工作流)
- [Pull Request 指南](#pull-request-指南)
- [社区](#社区)

---

## 行为准则

请阅读并遵守我们的 [行为准则](./CODE_OF_CONDUCT.zh-CN.md)，以维护一个友好和包容的社区环境。

---

## 开始之前

### 1. 选择你的路径

根据你的兴趣和经验，你可以：

- **👀 探索者**：浏览仓库并从现有代码中学习
- **📖 学习者**：遵循结构化学习路径并构建项目
- **🔨 建设者**：为活跃项目做出贡献
- **💡 创新者**：启动新项目或创建模板

### 2. 找到你的项目

查看我们的 [组织主页](https://github.com/trae-community) 了解所有仓库：

- **核心系统**：[`trae-agents`](https://github.com/trae-community/trae-agents)、[`trae-mcp`](https://github.com/trae-community/trae-mcp)、[`trae-skills`](https://github.com/trae-community/trae-skills)
- **学习与演示**：[`trae-learning`](https://github.com/trae-community/trae-learning)、[`trae-demos`](https://github.com/trae-community/trae-demos)
- **社区与资源**：[`trae-co-creation-projects`](https://github.com/trae-community/trae-co-creation-projects)、[`trae-templates`](https://github.com/trae-community/trae-templates)、[`awesome-trae`](https://github.com/trae-community/awesome-trae)、[`trae-friends-events`](https://github.com/trae-community/trae-friends-events)、[`trae-discussions`](https://github.com/trae-community/trae-discussions)

### 3. 阅读仓库特定指南

每个项目都有自己的贡献指南。务必查看你想要贡献的具体仓库中的 `CONTRIBUTING.md` 文件。

---

## 如何贡献

我们欢迎各种形式的贡献！以下是一些帮助方式：

### 💻 代码贡献

- 修复 bug
- 添加新功能
- 提升性能
- 编写测试

### 📝 文档贡献

- 修正拼写错误
- 澄清解释
- 添加示例
- 翻译内容

### 🎨 设计与用户体验

- 改进 UI/UX
- 创建图表或图示
- 提出设计改进建议

### 💬 社区支持

- 在讨论区回答问题
- 帮助审查 Pull Request
- 欢迎新贡献者
- 分享你的项目

---

## 开发工作流

### 步骤 1：Fork 仓库

点击仓库页面右上角的 "Fork" 按钮，创建你自己的副本。

### 步骤 2：克隆你的 Fork

```bash
git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME
```

### 步骤 3：创建分支

```bash
git checkout -b feature/your-feature-name
```

使用描述性的分支名称，例如：
- `fix/login-bug`
- `feat/add-dark-mode`
- `docs/update-readme`

### 步骤 4：进行修改

按照项目的编码标准进行更改。记住要：

- 编写干净、可读的代码
- 在必要的地方添加注释
- 根据需要更新文档
- 测试你的更改

### 步骤 5：提交更改

```bash
git add .
git commit -m "feat: add new feature description"
```

遵循 [约定式提交](https://www.conventionalcommits.org/) 来编写清晰的提交信息。

### 步骤 6：推送到你的 Fork

```bash
git push origin feature/your-feature-name
```

### 步骤 7：创建 Pull Request

1. 进入原始仓库
2. 点击 "Pull requests" → "New pull request"
3. 选择你的 fork 和分支
4. 填写 PR 模板
5. 提交！

---

## Pull Request 指南

### 提交之前

- ✅ 确保你的代码符合项目的风格指南
- ✅ 根据需要编写或更新测试
- ✅ 更新文档（如适用）
- ✅ 运行所有测试并确保通过
- ✅ 检查 linting 错误

### PR 描述模板

创建 PR 时，请包括：

```markdown
## 描述
简要描述此 PR 的作用

## 相关问题
链接任何相关问题（例如 "Fixes #123"）

## 更改类型
- [ ] Bug 修复
- [ ] 新功能
- [ ] 破坏性更改
- [ ] 文档更新

## 测试
描述你如何测试这些更改

## 检查清单
- [ ] 我已阅读贡献指南
- [ ] 我的代码符合项目的风格指南
- [ ] 我已对自己的代码进行了自我审查
- [ ] 我已在难以理解的地方添加了注释
- [ ] 我的更改没有产生新的警告
- [ ] 我已根据需要更新了测试
- [ ] 所有测试都在本地通过
```

---

## 有问题吗？

需要帮助或有疑问？加入我们的社区讨论！

- 💬 **[trae-discussions](https://github.com/trae-community/trae-discussions)** - 提问、分享想法并与其他贡献者交流
- 📚 **[trae-learning](https://github.com/trae-community/trae-learning)** - 了解更多关于 TRAE 和 AI 原生开发的知识

---

## 谢谢你！

每一份贡献都让 TRAE Community 变得更好。无论是修正拼写错误、添加功能还是启动新项目，你的工作都在帮助我们共同成长。

**由相信 AI 协作的人类构建 🤖**

---

*注意：这是组织级的贡献指南。有关单个项目的详细指南，请务必参考仓库特定的 CONTRIBUTING.md 文件。*
