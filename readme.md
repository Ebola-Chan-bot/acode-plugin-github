# GitHub 插件

无需克隆或下载，直接在 Acode 中浏览和编辑 GitHub 仓库与 Gist。

基于原版 [acode-plugin-github](https://github.com/Acode-Foundation/acode-plugin-github) 开发，新增侧边栏面板、中文本地化、令牌校验等多项改进。

## 功能特性

### 侧边栏面板
插件安装后会在 Acode 侧边栏添加 GitHub 图标，点击即可访问所有操作，无需打开命令面板：

- **打开仓库** — 浏览你的 GitHub 仓库，选择分支后在文件浏览器中查看文件
- **打开 Gist** — 浏览、创建和编辑 Gist 文件
- **删除 Gist** — 删除选定的 Gist
- **删除 Gist 文件** — 删除 Gist 中的单个文件
- **更新令牌** — 设置或更换 GitHub Personal Access Token
- **清空缓存** — 清除已缓存的仓库和 Gist 列表

## 命令

所有操作也可通过命令面板（`Ctrl+Shift+P` 或快捷工具栏 `...`）使用：

| 命令 | 说明 |
|------|------|
| Open repository | 打开仓库 |
| Open gist | 打开 Gist |
| Delete gist | 删除 Gist |
| Delete gist file | 删除 Gist 文件 |
| Update github token | 更新 GitHub 令牌 |
| Clear github cache | 清空 GitHub 缓存 |