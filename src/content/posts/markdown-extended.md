---
#  true false
title: Markdown扩展功能 # 标题
published: 2025-12-12T04:40:26.381Z # 发布日期
updated: 2025-11-14 #更新日期
description: 阅读更多关于Mizuki中Markdown功能的信息 # 描述
#encrypted: true # 加密
#password: "123456" # 密码
#alias: "加密示例" # 别名
#pinned: true # 置顶
#priority: 0 # 置顶优先级,数字越小优先级越高(0、1、2...)
#image: ./cover.jpg # 封面图片路径。<br/>1。以“http://”或“https://”开头：使用网络图像<br/>2。以“/”开头：用于“public”目录中的图像<br/>3。没有前缀：相对于markdown文件
tags: [演示，示例，Markdown，mizuki] # 标签
category: 示例 # 类别
#licenseName: "未经许可" # 许可证名称 不使用时默认为 CC BY-NC-SA 4.0
#author: 原作者 # 作者 引用别人的文章时使用
#sourceLink: "https://github.com/emn178/markdown" # 源链接 引用别人的文章时使用
draft: false # 草稿 如果这篇文章仍然是草稿，则不会显
---

## GitHub存储库卡
您可以添加链接到GitHub存储库的动态卡，在页面加载时，存储库信息是从GitHub API获取的 

::github{repo="matsuzaka-yuki/Mizuki"}

创建 GitHub repository card 使用代码 `::github{repo="matsuzaka-yuki/Mizuki"}`.


```markdown
::github{repo="matsuzaka-yuki/Mizuki"}
```

## 警告

支持以下类型的警告：`note`注意、`tip`提示、`important`重要、`warning`警告、`caution`小心

:::note
突出显示用户应该考虑的信息，即使在浏览时也是如此
:::

:::tip
帮助用户取得更大成功的可选信息
:::

:::important
用户成功所必需的关键信息
:::

:::warning
由于潜在风险，需要用户立即关注的关键内容
:::

:::caution
行动的负面潜在后果
:::

### 基本语法

```markdown
:::note
突出显示用户应该考虑的信息，即使在浏览时也是如此
:::

:::tip
帮助用户取得更大成功的可选信息
:::
```

### 自定义标题

警告的标题可以自定义

:::note[我的定制头衔]
这是一个带有自定义标题的注释
:::

```markdown
:::note[我的定制头衔]
这是一个带有自定义标题的注释
:::
```

### GitHub Syntax

> [!TIP]
> [The GitHub syntax](https://github.com/orgs/community/discussions/16925) 也得到了支持.

```
> [!NOTE]
> GitHub语法也受支持
> [!TIP]
> GitHub语法也受支持
```




### 剧透

你可以在文本中添加剧透。文本还支持**Markdown**语法

内容：剧透[隐藏 **ayyy**]!

```markdown
内容：剧透[隐藏 **ayyy**]!
