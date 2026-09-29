# 赵庆 · 个人主页

简洁的 GitHub Pages 个人简介页面。页面内容在 `index.html`，头像在 `portrait.jpg`。

个人主页：<https://jicilejiaoer-cpu.github.io/student/>

GitHub Pages 仓库设置：将 `main` 分支的根目录设为发布源。

## 更新学习清单

所有学习项目初始均未勾选。完成一项后，在 `index.html` 找到对应条目，把其中的：

```html
<input type="checkbox" disabled>
```

改为：

```html
<input type="checkbox" checked disabled>
```

在 GitHub 仓库中编辑 `index.html` 并提交后，GitHub Pages 会自动发布更新。复选框设为 `disabled`，因此直接点击网页不会误以为进度已经保存。
