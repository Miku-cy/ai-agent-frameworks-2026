# 贡献指南 | Contributing Guide

[English](#english) | [中文](#中文)

---

## 中文

感谢你对本项目的关注！我们欢迎任何形式的贡献。

### 📋 目录

- [行为准则](#行为准则)
- [如何贡献](#如何贡献)
- [贡献类型](#贡献类型)
- [开发流程](#开发流程)
- [代码规范](#代码规范)
- [提交信息规范](#提交信息规范)
- [Pull Request 流程](#pull-request-流程)
- [问题反馈](#问题反馈)

### 🤝 行为准则

本项目采用 [Contributor Covenant](https://www.contributor-covenant.org/) 行为准则，以确保所有参与者都能获得友好和尊重的体验。

### 🚀 如何贡献

1. **Fork** 本仓库
2. **克隆** 你的 Fork：`git clone https://github.com/你的用户名/ai-agent-frameworks-2026.git`
3. **创建** 特性分支：`git checkout -b feature/你的特性名称` 或 `git checkout -b fix/你的修复名称`
4. **提交** 更改：`git commit -m 'Add your feature'`
5. **推送** 到你的 Fork：`git push origin feature/你的特性名称`
6. **创建** Pull Request

### 📝 贡献类型

欢迎以下类型的贡献：

- 📝 **文档改进**：修正错别字、改进文档结构、补充说明
- 🐛 **Bug 修复**：修复发现的问题
- ✨ **新功能**：添加新的框架、新的示例、新的章节
- 📊 **数据更新**：更新框架的 Stars 数据、新增框架信息
- 🌐 **翻译支持**：补充其他语言的翻译、改进现有翻译
- 🎨 **样式优化**：改进文档的可读性、添加图表
- 📚 **最佳实践**：分享你的使用经验和最佳实践

### 💻 开发流程

```
需求分析 → 分支创建 → 开发实现 → 测试验证 → 提交代码 → PR 创建
```

#### 文档编辑建议

- 编辑中文文档时，请同时考虑英文文档是否需要同步更新
- 保持中英文文档的结构一致
- 使用清晰的标题层级
- 添加适当的代码示例
- 确保链接有效

### 📐 代码规范

- **Python**：遵循 [PEP 8](https://peps.python.org/pep-0008/) 规范
- **TypeScript/JavaScript**：使用 ESLint + Prettier
- **Markdown**：使用清晰的标题层级，代码块指定语言
- **提交信息**：使用清晰的描述

### 📋 提交信息规范

建议使用以下格式：

```
<类型>: <简短描述>

<详细描述>
```

类型包括：
- `feat`：新功能
- `fix`：修复
- `docs`：文档更新
- `style`：格式调整
- `refactor`：重构
- `test`：测试相关
- `chore`：构建/工具相关

示例：
```
docs: 更新 LangChain 框架信息

- 更新 Stars 数量为 123,456
- 补充新特性说明
```

### 🔄 Pull Request 流程

1. 确保你的 PR 描述清晰，说明修改的内容和原因
2. 如果修改涉及多个方面，建议拆分成多个 PR
3. PR 标题应简洁明了
4. 等待维护者审核
5. 根据反馈进行修改
6. 合并！🎉

### 🐛 问题反馈

如果你发现问题或有建议，请：

1. 先搜索 [Issues](../../issues) 看是否已有相关问题
2. 如果没有，创建新的 Issue，使用合适的模板
3. 提供清晰的描述和复现步骤（如果适用）

---

## English

Thank you for your interest in contributing to this project! We welcome contributions of all kinds.

### 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Contribution Types](#contribution-types)
- [Development Workflow](#development-workflow)
- [Code Standards](#code-standards)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Pull Request Process](#pull-request-process)
- [Issue Reporting](#issue-reporting)

### 🤝 Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) to ensure a welcoming and respectful experience for all participants.

### 🚀 How to Contribute

1. **Fork** this repository
2. **Clone** your fork: `git clone https://github.com/your-username/ai-agent-frameworks-2026.git`
3. **Create** a feature branch: `git checkout -b feature/your-feature-name` or `git checkout -b fix/your-fix-name`
4. **Commit** your changes: `git commit -m 'Add your feature'`
5. **Push** to your fork: `git push origin feature/your-feature-name`
6. **Create** a Pull Request

### 📝 Contribution Types

The following types of contributions are welcome:

- 📝 **Documentation improvements**: Fix typos, improve structure, add explanations
- 🐛 **Bug fixes**: Fix issues you find
- ✨ **New features**: Add new frameworks, examples, or sections
- 📊 **Data updates**: Update framework Stars data, add new framework info
- 🌐 **Translation support**: Add other languages, improve existing translations
- 🎨 **Style improvements**: Enhance readability, add diagrams
- 📚 **Best practices**: Share your experience and best practices

### 💻 Development Workflow

```
Requirement Analysis → Branch Creation → Implementation → Testing → Commit → PR Creation
```

#### Documentation Editing Tips

- When editing Chinese docs, consider if English docs need syncing
- Keep structure consistent between languages
- Use clear heading hierarchy
- Add appropriate code examples
- Ensure links are valid

### 📐 Code Standards

- **Python**: Follow [PEP 8](https://peps.python.org/pep-0008/)
- **TypeScript/JavaScript**: Use ESLint + Prettier
- **Markdown**: Use clear headings, specify language for code blocks
- **Commit messages**: Use clear descriptions

### 📋 Commit Message Guidelines

Suggested format:

```
<type>: <short description>

<detailed description>
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation update
- `style`: Formatting
- `refactor`: Refactoring
- `test`: Testing
- `chore`: Build/tools

Example:
```
docs: update LangChain framework info

- Update Stars count to 123,456
- Add new feature description
```

### 🔄 Pull Request Process

1. Ensure your PR description is clear, explaining what and why you changed
2. If changes cover multiple areas, consider splitting into multiple PRs
3. Keep PR title concise
4. Wait for maintainer review
5. Address feedback
6. Merge! 🎉

### 🐛 Issue Reporting

If you find issues or have suggestions:

1. Search [Issues](../../issues) first to see if it's already reported
2. If not, create a new Issue using appropriate template
3. Provide clear description and reproduction steps (if applicable)

---

**再次感谢你的贡献！ | Thank you again for your contribution!** 🙏
