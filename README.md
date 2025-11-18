# 智瞰碳踪-工业碳排监管决策支持系统

(Intelligent-carbon-tracking-government)

这是一个纯前端的 HTML 网页项目。本项目的所有 CSS 和 JavaScript 代码均内联在 `index.html` 文件中。

## 🚀 如何在 GitHub 上部署和预览

本指南将说明如何将一个纯前端的 `.html` 文件上传到 GitHub，并使用 GitHub Pages 功能将其发布为一个可以公开访问的网站。

### 步骤一：上传文件

对于一个**空仓库**：

1.  在仓库主页 (Code 页面)，找到 "Quick setup" 蓝色提示框。
2.  点击 **`uploading an existing file`** (上传一个已存在的文件) 链接。
3.  **拖拽**你的 `.html` 文件到上传区域。
4.  **（关键步骤）** 在上传界面，点击文件名旁边的铅笔 ✏️ 图标，将你的文件名（例如 `智瞰碳踪-工业碳排监管决策支持系统.html`）**重命名为 `index.html`**。
      * > **为什么？** GitHub Pages 默认会寻找 `index.html` 作为网站的首页。
5.  在下方的 "Commit changes" (提交更改) 框中，输入提交信息（例如 `Add index.html`），然后点击 **"Commit changes"** 按钮。

### 步骤二：启用 GitHub Pages

1.  **确保仓库为 Public (公开)**

      * 免费版的 GitHub Pages 必须在公开仓库上才能启用。
      * 前往仓库的 **`Settings`** (设置) \> **`General`** (常规)。
      * 拉到最下方的 "Danger Zone" (危险区域)。
      * 点击 "Change repository visibility" (更改仓库可见性)，并将其设置为 **`Public`**。

2.  **配置 Pages 部署源**

      * 在 **`Settings`** (设置) 页面，点击左侧菜单的 **`Pages`** 选项。
      * 在 "Build and deployment" (构建和部署) 下，将 "Source" (源) 选为 **`Deploy from a branch`** (从分支部署)。
      * 在 "Branch" (分支) 部分，选择：
          * Branch: **`main`**
          * Folder: **`/ (root)`**
      * 点击 **`Save`** (保存)。

### 步骤三：访问你的网站

1.  **等待部署：** 保存后，GitHub 需要 1-2 分钟来部署你的网站。
2.  **获取链接：** 刷新 `Settings` \> `Pages` 页面，当部署成功后，页面顶部会出现一个**绿色**的提示框，写着：
    > "Your site is live at: [你的网站链接]"
3.  **访问：** 点击该链接即可访问你的网页。

**本项目的预览链接：**

[https://github.com/xiaojiu0214/Intelligent-carbon-tracking-government/]

-----

### 常见问题 (FAQ)

**Q: 为什么我打开链接是 404 (Not Found)？**

**A:** 最大的可能是你的 HTML 文件**没有被命名为 `index.html`**。

  * **解决方法 1 (推荐):** 按照 "步骤一" 的说明，返回仓库，将你的 `.html` 文件重命名为 `index.html`。
  * **解决方法 2:** 你也可以通过访问完整路径来打开它，例如：
    `https://.../Intelligent-carbon-tracking-government/智瞰碳踪-工业碳排监管决策支持系统.html`
    (但这样很不方便，且 URL 中的中文会被转码)。
