# 必定AI (BuidAI) 官方文档

本项目是 [必定AI (BuidAI)](https://buidai.com) 的官方文档仓库，基于 [Mintlify](https://mintlify.com/) 构建。

必定AI 是企业级专业稳定的 AI 大模型 API 中转站，基于统一的 OpenAI API 标准，支持 300+ 热门 AI 模型，包括 OpenAI, Claude, Gemini, DeepSeek 等。

## 📚 文档内容

文档主要包含以下几个部分：

- **产品基础**: 快速开始、API 手册、定价信息等。
- **自定义配置**: Mintlify 的配置指南。
- **内容编写**: Markdown 编写规范、代码块、图片等使用说明。
- **AI 工具**: Cursor, Claude Code, Windsurf 等 AI 辅助编程工具的集成指南。
- **使用场景**: 对话型 AI、编程开发、技术工程、翻译等场景的最佳实践。
- **API 参考**: 详细的 API 接口文档和示例。
- **更新日志**: 产品功能更新记录。

## 📂 目录结构

```text
e:\Github\mintlify-docs
├── ai-tools/           # AI 工具相关文档 (Claude Code, Cursor, Windsurf)
├── api/                # API 参考文档及 OpenAPI 定义
├── essentials/         # 基础文档 (Markdown, 导航, 设置等)
├── images/             # 图片资源
├── logo/               # 网站 Logo
├── scenarios/          # 各种使用场景文档 (CherryStudio, 编程, 翻译等)
├── snippets/           # 可复用的文档片段
├── update/             # 更新日志
├── docs.json           # Mintlify 项目配置文件 (导航, 主题, 页脚等)
├── index.mdx           # 文档首页
└── ...                 # 其他顶级页面 (pricing, start, development 等)
```

## 🛠️ 本地开发

按照以下步骤在本地预览文档：

1.  **安装 Mintlify CLI**

    需要安装 Node.js，然后运行：

    ```bash
    npm i -g mint
    ```

2.  **启动开发服务器**

    在项目根目录下运行：

    ```bash
    mint dev
    ```

3.  **预览**

    打开浏览器访问 `http://localhost:3000` 查看文档预览。

## ⚙️ 配置说明

项目的主要配置位于 `docs.json` 文件中，包括：

- **导航栏 (Navigation)**: 定义顶部和侧边栏菜单结构。
- **主题 (Theme)**: 设置颜色、Logo、Favicon 等。
- **链接 (Links)**: 社交媒体链接、外部链接等。
- **API 配置**: OpenAPI 规范文件的位置。

## 🚀 发布更改

文档托管在 Mintlify 平台。更改推送到 `main` (或默认) 分支后，Mintlify 会自动部署更新到生产环境。

## 🤝 帮助与支持

- **官方网站**: [https://buidai.com](https://buidai.com)
- **API 控制台**: [https://api.buidai.com](https://api.buidai.com)
- **Mintlify 文档**: [https://mintlify.com/docs](https://mintlify.com/docs)
