# Story to Game 模板

> 一个简单的 [Docsify](https://github.com/docsifyjs/docsify/) 模板，用于创建基于 Markdown 的文档网站，无需构建过程。

## 网站设置

### 静态 Web 服务器
将这些模板文件上传到任何静态 Web 服务器。`.nojekyll` 文件仅在 GitHub Pages 上托管站点时需要，否则可以删除。

### GitHub Pages

#### 托管站点

要在 GitHub Pages 上托管此模板，请执行以下操作：

1. 如果尚未登录，请登录 GitHub
2. 点击此 GitHub 仓库右上角的 **Use this template** 按钮，然后选择 **Create a new repository**
3. 为您的新仓库输入名称，然后点击 **Create repository** 按钮
4. 新仓库创建后，转到 **Settings**，然后从左侧边栏选择 **Pages**，在 **Branch** 下选择 **main**，然后点击 **Save** 按钮
5. 等待一两分钟，然后刷新同一个 **Pages** 页面 - 站点准备就绪后，屏幕顶部将显示一条消息，其中包含站点链接和 **Visit site** 按钮

#### 编辑内容

如何在 GitHub Pages 上编辑新 Docsify 站点的内容？查看您要编辑的 Markdown 页面（例如 **README.md**），点击 **铅笔图标**，然后点击绿色的 **Commit changes...** 按钮保存任何更改。只需片刻，Docsify 站点就会自动更新以反映这些更改。

### 本地查看
在仓库文件夹中运行 `npx serve .` (Node.js 用户) 或 `python -m http.server 8000` (Python 用户) 以在本地运行。

## Docsify 文档

要了解有关使用 Docsify 的更多信息，请访问 https://docsify.js.org。