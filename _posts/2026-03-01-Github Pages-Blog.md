---
layout: post
title:  "Github pages - Blog"
date:   2026-03-01 08:00:00 -0500
categories:
  - Pages
  - Github
tags:
  - Blog
  - Github Pages
---

### 用户指南：用模板快速创建 GitHub Pages 博客（零本地安装）

#### 第1步：用模板创建仓库（3分钟，最关键一步）

1. 打开这个模板仓库（推荐的 Jekyll Now 模板，简单、美观、维护活跃）：  
   https://github.com/barryclark/jekyll-now

2. 点击绿色按钮 **Use this template** → **Create a new repository**

3. 在创建页面：
   - Owner：你的 GitHub 账号
   - Repository name：必须写成 **你的用户名.github.io**  
     （例如 User 就写 user.github.io）
   - Description：随便写，例如 “我的 Rust 技术博客”
   - Public
   - Include all branches：不用勾
   - 点击 **Create repository from template**

创建完后，你就拥有一个完整、可直接运行的博客仓库了。

#### 第2步：修改基本信息（2–3分钟）

1. 进入新仓库，找到文件 **_config.yml**，点击编辑（铅笔图标）

2. 修改这些关键地方（其他可以先不动）：

```yaml
title:  My Rust 与系统编程笔记
description: Rust、性能优化、二进制序列化、零拷贝等话题
url: "https://你的用户名.github.io"   # 改成你的真实用户名
author:
  name: user
  email: user@example.com           # 可选，改成你的邮箱
```

3. 保存（Commit changes）

#### 第3步：替换“关于”页面（2分钟）

1. 找到文件 **about.md**，点击编辑

2. 把内容全部替换成我们之前写的 about.md（从 `# 嘿，我是 Owen` 开始的那段）

3. 保存

#### 第4步：添加你的 bincode-next 文章（3–5分钟）

1. 在仓库里找到文件夹 **_posts**（如果没有就新建一个）

2. 点击 **Add file** → **Create new file**

3. 文件路径写：  
   _posts/2026-02-28-bincode-next-v3.md

4. 把我们之前写好的完整中文文章 Markdown 贴进去  
   （记得最上面要有 front matter，例如：）

```yaml
---
layout: post
title:  深入探索 bincode-next v3.0：Rust 二进制序列化下一代方案
date:   2026-02-28 08:00:00 -0500
categories: rust 序列化 性能优化
---
```

5. 下面直接接文章正文  
   保存（Commit new file）

#### 第5步：访问你的博客

等 1–3 分钟（GitHub Pages 部署需要一点时间），打开浏览器：

- 主页：https://你的用户名.github.io  
- 关于页：https://你的用户名.github.io/about/  
- 文章：https://你的用户名.github.io/2026/02/28/bincode-next-v3/

如果几分钟后还没出现，刷新页面或检查 Settings → Pages 是否显示 "Your site is live at https://..."

#### 以后怎么加新文章（最简单方式）

1. 在浏览器里进仓库
2. 点击 **Add file** → **Create new file**
3. 路径：_posts/2026-03-01-新文章标题.md
4. 贴 Markdown + front matter
5. Commit
6. 等 1–2 分钟，刷新网站就看到了

这样就完全搞定了：模板自动处理主题、布局、导航，你只需要写 Markdown。

如果想换更现代的主题（例如 Chirpy、Minimal Mistakes），可以以后再 fork 其他模板覆盖，但 Jekyll Now 已经足够好用且稳定。

🚀