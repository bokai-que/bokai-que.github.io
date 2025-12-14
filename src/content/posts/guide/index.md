---
#  true false
title: Mizuki的简单指南 # 标题
published: 2025-12-12 # 发布日期
updated: 2025-12-14 #更新日期
description: 如何使用此博客模板. # 描述
#encrypted: true # 加密
#password: "123456" # 密码
#alias: "加密示例" # 别名
#pinned: true # 置顶
#priority: 0 # 置顶优先级,数字越小优先级越高(0、1、2...)
#image: ./cover.jpg # 封面图片路径。<br/>1。以“http://”或“https://”开头：使用网络图像<br/>2。以“/”开头：用于“public”目录中的图像<br/>3。没有前缀：相对于markdown文件
tags: ["Mizuki", "博客", "定制"] # 标签
category: 指南 # 类别
#licenseName: "未经许可" # 许可证名称 不使用时默认为 CC BY-NC-SA 4.0
#author: 原作者 # 作者 引用别人的文章时使用
#sourceLink: "https://github.com/emn178/markdown" # 源链接 引用别人的文章时使用
draft: false # 草稿 如果这篇文章仍然是草稿，则不会显
---



这个博客模板是用[Astro](https://astro.build/)构建的。对于本指南中未提及的内容，
您可以在[Astro Docs](https://docs.astro.build/)中找到答案。

## 文章属性

```yaml
---
title: 我的第一篇博客文章
published: 2023-09-09
description: 这是我新的Astro博客的第一篇文章.
image: ./cover.jpg
tags: [Foo, Bar]
category: 前端
draft: false
---
```




| 属性     | 描述                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 文章的标题                                                                                                                                                                                      |
| `published`   | 文章发布的日期                                                                                                                                                                            |
| `pinned`      | 此文章是否固定在文章列表的顶部                                                                                                                                                   |
| `priority`    | 固定文章的优先级。较小的值意味着较高的优先级（0、1、2…）                                                                                                                          |
| `description` | 对文章的简短描述。显示在索引页上                                                                                                                                                   |
| `image`       | 文章的封面图片路径。<br/>1。以“http://”或“https://”开头：使用网络图像<br/>2。以“/”开头：用于“public”目录中的图像<br/>3。没有前缀：相对于markdown文件 |
| `tags`        | 文章的标签                                                                                                                                                                                       |
| `category`    | 文章的类别                                                                                                                                                                                   |
| `licenseName` | 文章内容的许可证名称                                                                                                                                                                      |
| `author`      | 文章的作者                                                                                                                                                                                     |
| `sourceLink`  | 文章内容的源链接或引用                                                                                                                                                          |
| `draft`       | 如果这篇文章仍然是草稿，则不会显示。                                                                                                                                                    |

## 文件放在哪里



您的文章文件应该放在`src/content/posts/`目录中。您还可以创建子目录来更好地组织您的文章

```
src/content/posts/
├── post-1.md
└── guide/
    ├── cover.png
    └── index.md
```