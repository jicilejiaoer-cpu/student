# 赵庆 · 个人主页

简洁的 GitHub Pages 个人简介页面。页面内容在 `index.html`，头像在 `portrait.jpg`。

个人主页：<https://jicilejiaoer-cpu.github.io/student/>

GitHub Pages 仓库设置：将 `main` 分支的根目录设为发布源。

## 更新学习清单

当前清单根据提供的 AI Agent 开发岗位截图整理，分为 7 个阶段：

1. 工程基础：Python、Git、Terminal / Shell、开发环境。
2. 大模型应用基础：LLM、API、Prompt、Context、工具调用。
3. RAG 检索增强：文档切分、Embedding、向量检索、Top-K、Rerank。
4. Agent 核心能力：Workflow、Tools / Skills、MCP、Runtime、Memory。
5. 框架与多 Agent：LangChain、LangGraph、AutoGen / CrewAI、多 Agent 协作。
6. 本地能力与系统集成：文件与命令行、后台任务、Browser Use、Computer Use、企业系统。
7. 开源项目与工程实践：Hermes Agent、OpenClaw、二次开发、测试调试、性能与兼容性、AI Coding。

清单共 34 项，保留已有的 Python 基础完成标记，其余项目待完成。AutoGen 和 CrewAI 可以先选一个做实验。

完成一项后，在 `index.html` 搜索条目名称或 `learn-` 开头的 ID，把其中的：

```html
<input type="checkbox" disabled>
```

改为：

```html
<input type="checkbox" checked disabled>
```

在 GitHub 仓库中编辑 `index.html` 并提交后，GitHub Pages 会自动发布更新。复选框设为 `disabled`，因此直接点击网页不会误以为进度已经保存。
