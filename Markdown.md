# Markdown on Github

### 1. [引用提醒框样式](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.



### 2. 点击展开

```
<details>
<summary>点击展开</summary>

折叠内容...

</details>
```

<details>
<summary>点击展开</summary>
折叠内容...



> [!CAUTION]
> 折叠内容下的引用提醒框样式无法正常渲染。



</details>

### 3. 深色模式图片链接替换

```
# 仅在浅色页面背景下显示图片
![Logo](assets/github-black.svg#gh-light-mode-only)

# 仅在深色页面背景下显示图片
![Logo](assets/github-white.svg#gh-dark-mode-only)
```

你应该在深色页面背景下看见白色的 Gtihub Logo，在浅色页面背景下看见深色的 Gtihub Logo，且两种不同颜色的 Logo 不会同时出现。

![Logo](assets/github-black.svg#gh-light-mode-only)

![Logo](assets/github-white.svg#gh-dark-mode-only)
