# 拾要 · 文章精读

创意文章精读落地页与 `article-close-reading` Skill。

## 页面

直接打开 `index.html`。首屏对话框可摘取核心原句、关键词、数字时间、行动要求与限制条件，支持复制及下载 Markdown。

对话框使用浏览器本地规则处理，不上传输入内容，也未接入 AI。完整精读使用 Skill。

## Skill 安装与调用

入口：仓库根目录 `SKILL.md`。

项目级安装：创建 `.agents/skills/article-close-reading/` 并将 `SKILL.md` 放入。

用户级安装：创建 `~/.agents/skills/article-close-reading/` 并将 `SKILL.md` 放入。

```text
$article-close-reading 帮我精读这篇文章，做结构化拆解：[文章链接或正文]
```

## GitHub Pages

在仓库 Settings → Pages 将 Source 设置为 Deploy from a branch，选择 `main` 和 `/ (root)`，保存后由 GitHub 自动发布。

本仓库不包含 Sites 托管配置或凭证。视觉参考 MotionSites 的免费 Neuralyn 模板，页面图形与交互由本地 HTML/CSS/JS 实现。
