<p align="center">
 <img width="100px" src="https://github.githubassets.com/images/mona-loading-default.gif" align="center" alt="Logo" />
 <h3 align="center">Github 常用徽章合集</h3>
 <p align="center">Github Badge Collection</p>
</p>

## 说明

本 README 主要收集一些零散的 Github 常用徽章和活动图等。

DOI 号、标识图标、Emoji 和 Github 的 Markdown 技巧等都在单独的文件中，下面是一个简单指引：

+ [Github 生成 DOI 徽章](DOI.md)
+ [Github 一些可用的标识](GIF.md)
+ [Github 支持的 Emoji](Emoji.md)
+ [Github 的 Markdown 用法](Markdown.md)

<br><br>

<p align="center">
 <h3 align="center">> 1 徽章类 <</h3>
</p>



### 1. [Shields 徽章](https://shields.io/)

Shields 适用于各类现有的或自定义名称的徽章。

```
style样式参数，共有5种样式：
style=plastic
style=flat
style=flat-square
style=for-the-badge
style=social

logo来自simple-icons：https://simpleicons.org
logo自定义：https://shields.io/docs/logos

Shields文档：https://shields.io/badges/static-badge
```

#### 1.1 品牌类（静态）

```
https://img.shields.io/badge/左侧文字-右侧文字-颜色?logo=图标

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://simpleicons.org；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色；
4.空格需要替换为 `%20`；
5.微软和Adobe家族图标被 simple-icons 除名了，现在无法使用。
```
|                           plastic                            |                             flat                             |                         flat-square                          |                        for-the-badge                         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://img.shields.io/badge/Linux-FCC624?style=plastic&logo=linux&logoColor=black) | ![](https://img.shields.io/badge/Linux-FCC624?style=&logo=linux&logoColor=black) | ![](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) | ![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| ![](https://img.shields.io/badge/Android-3DDC84?style=plastic&logo=android&logoColor=white) | ![](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white) | ![](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) | ![](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) |
| ![](https://img.shields.io/badge/iOS-333?style=plastic&logo=apple&logoColor=white) | ![](https://img.shields.io/badge/iOS-333?style=flat&logo=apple&logoColor=white) | ![](https://img.shields.io/badge/iOS-333?style=flat-square&logo=apple&logoColor=white) | ![](https://img.shields.io/badge/iOS-333?style=for-the-badge&logo=apple&logoColor=white) |
| ![](https://img.shields.io/badge/Chrome-4285F4?style=plastic&logo=GoogleChrome&logoColor=white) | ![](https://img.shields.io/badge/Chrome-4285F4?style=flat&logo=GoogleChrome&logoColor=white) | ![](https://img.shields.io/badge/Chrome-4285F4?style=flat-square&logo=GoogleChrome&logoColor=white) | ![](https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white) |
| ![](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white) | ![](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white) | ![](https://img.shields.io/badge/Github-181717?style=flat-square&logo=github&logoColor=white) | ![](https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white) |
| ![](https://img.shields.io/badge/Adobe-FF0000?style=plastic&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=flat&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=flat-square&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=for-the-badge&logo=adobe) |

需要注意的是微软和 Adobe 家族图标被 simple-icons 除名了，会出现如下表所示的标识缺失的问题：


|                           plastic                            |                             flat                             |                         flat-square                          |                        for-the-badge                         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://img.shields.io/badge/Windows-10-2376bc?style=plastic&logo=microsoft&logoColor=ffffff) | ![](https://img.shields.io/badge/Windows-10-2376bc?style=flat&logo=windows&logoColor=ffffff) | ![](https://img.shields.io/badge/Windows-10-2376bc?style=flat-square&logo=windows&logoColor=ffffff) | ![](https://img.shields.io/badge/Windows-10-2376bc?style=for-the-badge&logo=windows&logoColor=ffffff) |
| ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=plastic&logo=visual-studio&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=flat&logo=visual-studio&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=flat-square&logo=visual-studio&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=for-the-badge&logo=visual-studio&logoColor=ffffff) |
| ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=plastic&logo=visual-studio-code&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=flat&logo=visual-studio-code&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=flat-square&logo=visual-studio-code&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=for-the-badge&logo=visual-studio-code&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Adobe-FF0000?style=plastic&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=flat&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=flat-square&logo=adobe) | ![](https://img.shields.io/badge/Adobe-FF0000?style=for-the-badge&logo=adobe) |

#### 1.2 开发类（静态）

```
https://img.shields.io/badge/左侧文字-右侧文字-颜色?logo=图标

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://simpleicons.org；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色；
4.空格需要替换为 `%20`；
5.微软和Adobe家族图标被 simple-icons 除名了，现在无法使用。
```
|                           plastic                            |                             flat                             |                         flat-square                          |                        for-the-badge                         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=ffffff) | ![](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=ffffff) | ![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=ffffff) | ![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Markdown-000000?style=plastic&logo=Markdown&logoColor=ffffff) | ![](https://img.shields.io/badge/Markdown-000000?style=flat&logo=Markdown&logoColor=ffffff) | ![](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=Markdown&logoColor=ffffff) | ![](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=Markdown&logoColor=ffffff) |
| ![](https://img.shields.io/badge/LaTex-3776AB?style=plastic&logo=LaTex&logoColor=ffffff) | ![](https://img.shields.io/badge/LaTex-3776AB?style=flat&logo=LaTex&logoColor=ffffff) | ![](https://img.shields.io/badge/LaTex-3776AB?style=flat-square&logo=LaTex&logoColor=ffffff) | ![](https://img.shields.io/badge/LaTex-3776AB?style=for-the-badge&logo=LaTex&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Typescript-%23007ACC.svg?style=plastic&logo=typescript&logoColor=white) | ![](https://img.shields.io/badge/Typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) | ![](https://img.shields.io/badge/Typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white) | ![](https://img.shields.io/badge/Typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) |
| ![](https://img.shields.io/badge/Node.js-5FA04E?style=plastic&logo=Node.js&logoColor=ffffff) | ![](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=Node.js&logoColor=ffffff) | ![](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=Node.js&logoColor=ffffff) | ![](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=Node.js&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Docker-2496ED?style=plastic&logo=docker&logoColor=ffffff) | ![](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=ffffff) | ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=ffffff) | ![](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Qt-%23217346.svg?style=plastic&logo=Qt&logoColor=white) | ![](https://img.shields.io/badge/Qt-%23217346.svg?style=flat&logo=Qt&logoColor=white) | ![](https://img.shields.io/badge/Qt-%23217346.svg?style=flat-square&logo=Qt&logoColor=white) | ![](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white) |
| ![](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=plastic&logo=intellijidea&logoColor=ffffff) | ![](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=flat&logo=intellijidea&logoColor=ffffff) | ![](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=flat-square&logo=intellijidea&logoColor=ffffff) | ![](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=for-the-badge&logo=intellijidea&logoColor=ffffff) |
| ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=plastic&logo=mysql&logoColor=ffffff) | ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat&logo=mysql&logoColor=ffffff) | ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat-square&logo=mysql&logoColor=ffffff) | ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=ffffff) |
| ![](https://img.shields.io/badge/Swift-F05138.svg?style=plastic&logo=swift&logoColor=ffffff) | ![](https://img.shields.io/badge/Swift-F05138.svg?style=flat&logo=swift&logoColor=ffffff) | ![](https://img.shields.io/badge/Swift-F05138.svg?style=flat-square&logo=swift&logoColor=ffffff) | ![](https://img.shields.io/badge/Swift-F05138.svg?style=for-the-badge&logo=swift&logoColor=ffffff) |

#### 1.3 社交类（动态更新）

```
https://img.shields.io/twitter/follow/:user
或
https://img.shields.io/badge/左侧文字-右侧文字-颜色?logo=图标&style=social

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://simpleicons.org；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色；
4.空格需要替换为 `%20`；
5.微软和Adobe家族图标被 simple-icons 除名了，现在无法使用。
```

|                            Views                             |                            Follow                            |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|  ![](https://img.shields.io/github/stars/microsoft/vscode)   | ![](https://img.shields.io/twitter/follow/:realDonaldTrump)  |
| ![](https://img.shields.io/youtube/channel/subscribers/UCUZHFZ9jIKrLroW8LcyJEQQ) | ![](https://img.shields.io/twitter/follow/Microsoft.svg?logo=microsoft) |

#### 1.4 自定义类（静态）

```
https://img.shields.io/badge/文字-颜色?logo=data:image/...

注：
1.任何自定义徽标都可以通过 base64 编码在 URL 参数中传递；
2.支持 jpg, png, svg 等格式；
3.使用 base64 编码后 logoColor 参数将会失效。
```
微软和 Adobe 家族图标等，需要自行用 base64 编码定义：


|                           plastic                            |                             flat                             |                         flat-square                          |                        for-the-badge                         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://img.shields.io/badge/Microsoft-000000?style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5MDY3MTMwIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjQyNTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik0wIDBoNDg2LjU5MnY0ODYuNTkySDB6IiBmaWxsPSIjRjI1MDIyIiBwLWlkPSI0MjUxIj48L3BhdGg+PHBhdGggZD0iTTUzNy40MDggMEgxMDI0djQ4Ni41OTJINTM3LjQwOHoiIGZpbGw9IiM3RkJBMDAiIHAtaWQ9IjQyNTIiPjwvcGF0aD48cGF0aCBkPSJNMCA1MzcuNDA4aDQ4Ni41OTJWMTAyNEgweiIgZmlsbD0iIzAwQTRFRiIgcC1pZD0iNDI1MyI+PC9wYXRoPjxwYXRoIGQ9Ik01MzcuNDA4IDUzNy40MDhIMTAyNFYxMDI0SDUzNy40MDh6IiBmaWxsPSIjRkZCOTAwIiBwLWlkPSI0MjU0Ij48L3BhdGg+PC9zdmc+) | ![](https://img.shields.io/badge/Microsoft-000000?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5MDY3MTMwIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjQyNTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik0wIDBoNDg2LjU5MnY0ODYuNTkySDB6IiBmaWxsPSIjRjI1MDIyIiBwLWlkPSI0MjUxIj48L3BhdGg+PHBhdGggZD0iTTUzNy40MDggMEgxMDI0djQ4Ni41OTJINTM3LjQwOHoiIGZpbGw9IiM3RkJBMDAiIHAtaWQ9IjQyNTIiPjwvcGF0aD48cGF0aCBkPSJNMCA1MzcuNDA4aDQ4Ni41OTJWMTAyNEgweiIgZmlsbD0iIzAwQTRFRiIgcC1pZD0iNDI1MyI+PC9wYXRoPjxwYXRoIGQ9Ik01MzcuNDA4IDUzNy40MDhIMTAyNFYxMDI0SDUzNy40MDh6IiBmaWxsPSIjRkZCOTAwIiBwLWlkPSI0MjU0Ij48L3BhdGg+PC9zdmc+) | ![](https://img.shields.io/badge/Microsoft-000000?style=flat-square&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5MDY3MTMwIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjQyNTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik0wIDBoNDg2LjU5MnY0ODYuNTkySDB6IiBmaWxsPSIjRjI1MDIyIiBwLWlkPSI0MjUxIj48L3BhdGg+PHBhdGggZD0iTTUzNy40MDggMEgxMDI0djQ4Ni41OTJINTM3LjQwOHoiIGZpbGw9IiM3RkJBMDAiIHAtaWQ9IjQyNTIiPjwvcGF0aD48cGF0aCBkPSJNMCA1MzcuNDA4aDQ4Ni41OTJWMTAyNEgweiIgZmlsbD0iIzAwQTRFRiIgcC1pZD0iNDI1MyI+PC9wYXRoPjxwYXRoIGQ9Ik01MzcuNDA4IDUzNy40MDhIMTAyNFYxMDI0SDUzNy40MDh6IiBmaWxsPSIjRkZCOTAwIiBwLWlkPSI0MjU0Ij48L3BhdGg+PC9zdmc+) | ![](https://img.shields.io/badge/Microsoft-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5MDY3MTMwIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjQyNTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik0wIDBoNDg2LjU5MnY0ODYuNTkySDB6IiBmaWxsPSIjRjI1MDIyIiBwLWlkPSI0MjUxIj48L3BhdGg+PHBhdGggZD0iTTUzNy40MDggMEgxMDI0djQ4Ni41OTJINTM3LjQwOHoiIGZpbGw9IiM3RkJBMDAiIHAtaWQ9IjQyNTIiPjwvcGF0aD48cGF0aCBkPSJNMCA1MzcuNDA4aDQ4Ni41OTJWMTAyNEgweiIgZmlsbD0iIzAwQTRFRiIgcC1pZD0iNDI1MyI+PC9wYXRoPjxwYXRoIGQ9Ik01MzcuNDA4IDUzNy40MDhIMTAyNFYxMDI0SDUzNy40MDh6IiBmaWxsPSIjRkZCOTAwIiBwLWlkPSI0MjU0Ij48L3BhdGg+PC9zdmc+) |
| ![](https://img.shields.io/badge/VSCode-0f81c2?style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/VSCode-0f81c2?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/VSCode-0f81c2?style=flat-square&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/VSCode-0f81c2?style=for-the-badge&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) |
| ![](https://img.shields.io/badge/图筑风暻-ED8384?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMS0wMVQyMTo0MDoxOSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCIgeG1wTU06T3JpZ2luYWxEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiBzdEV2dDp3aGVuPSIyMDIyLTAxLTAxVDIxOjQwOjE5KzA4OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNSAoV2luZG93cykiLz4gPC9yZGY6U2VxPiA8L3htcE1NOkhpc3Rvcnk+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+PUE0fAAAALRJREFUOI3tkz0KAjEQRh+roCC2gldQ2N47WIjWXkI9hIVewMIbeAiPsEew3NpmWYTPIokGNTGg5T4I88vHzECQhKSDDCdJuc2lvExSVxIZhra1c6AAVqTRA0bAQ+iVPbBMEJoACwA34lHvlHb02GqFpLO/2icGwDRS3wE5cImt5hh7fgsYAjPMHdc2f4PnkUN0PH8DbEON3yYKif4kFKURaoT+gfsilbVXr9YHai+uAz0VwB1CgYRUa2LvsQAAAABJRU5ErkJggg==&logoColor=white) | ![](https://img.shields.io/badge/图筑风暻-ED8384?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMS0wMVQyMTo0MDoxOSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCIgeG1wTU06T3JpZ2luYWxEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiBzdEV2dDp3aGVuPSIyMDIyLTAxLTAxVDIxOjQwOjE5KzA4OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNSAoV2luZG93cykiLz4gPC9yZGY6U2VxPiA8L3htcE1NOkhpc3Rvcnk+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+PUE0fAAAALRJREFUOI3tkz0KAjEQRh+roCC2gldQ2N47WIjWXkI9hIVewMIbeAiPsEew3NpmWYTPIokGNTGg5T4I88vHzECQhKSDDCdJuc2lvExSVxIZhra1c6AAVqTRA0bAQ+iVPbBMEJoACwA34lHvlHb02GqFpLO/2icGwDRS3wE5cImt5hh7fgsYAjPMHdc2f4PnkUN0PH8DbEON3yYKif4kFKURaoT+gfsilbVXr9YHai+uAz0VwB1CgYRUa2LvsQAAAABJRU5ErkJggg==&logoColor=white) | ![](https://img.shields.io/badge/图筑风暻-ED8384?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMS0wMVQyMTo0MDoxOSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCIgeG1wTU06T3JpZ2luYWxEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiBzdEV2dDp3aGVuPSIyMDIyLTAxLTAxVDIxOjQwOjE5KzA4OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNSAoV2luZG93cykiLz4gPC9yZGY6U2VxPiA8L3htcE1NOkhpc3Rvcnk+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+PUE0fAAAALRJREFUOI3tkz0KAjEQRh+roCC2gldQ2N47WIjWXkI9hIVewMIbeAiPsEew3NpmWYTPIokGNTGg5T4I88vHzECQhKSDDCdJuc2lvExSVxIZhra1c6AAVqTRA0bAQ+iVPbBMEJoACwA34lHvlHb02GqFpLO/2icGwDRS3wE5cImt5hh7fgsYAjPMHdc2f4PnkUN0PH8DbEON3yYKif4kFKURaoT+gfsilbVXr9YHai+uAz0VwB1CgYRUa2LvsQAAAABJRU5ErkJggg==&logoColor=white) | ![](https://img.shields.io/badge/图筑风暻-ED8384?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMS0wMVQyMTo0MDoxOSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCIgeG1wTU06T3JpZ2luYWxEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiBzdEV2dDp3aGVuPSIyMDIyLTAxLTAxVDIxOjQwOjE5KzA4OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNSAoV2luZG93cykiLz4gPC9yZGY6U2VxPiA8L3htcE1NOkhpc3Rvcnk+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+PUE0fAAAALRJREFUOI3tkz0KAjEQRh+roCC2gldQ2N47WIjWXkI9hIVewMIbeAiPsEew3NpmWYTPIokGNTGg5T4I88vHzECQhKSDDCdJuc2lvExSVxIZhra1c6AAVqTRA0bAQ+iVPbBMEJoACwA34lHvlHb02GqFpLO/2icGwDRS3wE5cImt5hh7fgsYAjPMHdc2f4PnkUN0PH8DbEON3yYKif4kFKURaoT+gfsilbVXr9YHai+uAz0VwB1CgYRUa2LvsQAAAABJRU5ErkJggg==&logoColor=white) |
| ![](https://img.shields.io/badge/play-station-blue.svg?style=plastic&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIj48cGF0aCBkPSJNMTI5IDExMWMtNTUgNC05MyA2Ni05MyA3OEwwIDM5OGMtMiA3MCAzNiA5MiA2OSA5MWgxYzc5IDAgODctNTcgMTMwLTEyOGgyMDFjNDMgNzEgNTAgMTI4IDEyOSAxMjhoMWMzMyAxIDcxLTIxIDY5LTkxbC0zNi0yMDljMC0xMi00MC03OC05OC03OGgtMTBjLTYzIDAtOTIgMzUtOTIgNDJIMjM2YzAtNy0yOS00Mi05Mi00MmgtMTV6IiBmaWxsPSIjZmZmIi8+PC9zdmc+) | ![](https://img.shields.io/badge/play-station-blue.svg?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIj48cGF0aCBkPSJNMTI5IDExMWMtNTUgNC05MyA2Ni05MyA3OEwwIDM5OGMtMiA3MCAzNiA5MiA2OSA5MWgxYzc5IDAgODctNTcgMTMwLTEyOGgyMDFjNDMgNzEgNTAgMTI4IDEyOSAxMjhoMWMzMyAxIDcxLTIxIDY5LTkxbC0zNi0yMDljMC0xMi00MC03OC05OC03OGgtMTBjLTYzIDAtOTIgMzUtOTIgNDJIMjM2YzAtNy0yOS00Mi05Mi00MmgtMTV6IiBmaWxsPSIjZmZmIi8+PC9zdmc+) | ![](https://img.shields.io/badge/play-station-blue.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIj48cGF0aCBkPSJNMTI5IDExMWMtNTUgNC05MyA2Ni05MyA3OEwwIDM5OGMtMiA3MCAzNiA5MiA2OSA5MWgxYzc5IDAgODctNTcgMTMwLTEyOGgyMDFjNDMgNzEgNTAgMTI4IDEyOSAxMjhoMWMzMyAxIDcxLTIxIDY5LTkxbC0zNi0yMDljMC0xMi00MC03OC05OC03OGgtMTBjLTYzIDAtOTIgMzUtOTIgNDJIMjM2YzAtNy0yOS00Mi05Mi00MmgtMTV6IiBmaWxsPSIjZmZmIi8+PC9zdmc+) | ![](https://img.shields.io/badge/play-station-blue.svg?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIj48cGF0aCBkPSJNMTI5IDExMWMtNTUgNC05MyA2Ni05MyA3OEwwIDM5OGMtMiA3MCAzNiA5MiA2OSA5MWgxYzc5IDAgODctNTcgMTMwLTEyOGgyMDFjNDMgNzEgNTAgMTI4IDEyOSAxMjhoMWMzMyAxIDcxLTIxIDY5LTkxbC0zNi0yMDljMC0xMi00MC03OC05OC03OGgtMTBjLTYzIDAtOTIgMzUtOTIgNDJIMjM2YzAtNy0yOS00Mi05Mi00MmgtMTV6IiBmaWxsPSIjZmZmIi8+PC9zdmc+) |
| ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NjA3MzUyIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjYxMjAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MTguOTMzMzMzIDg1LjMzMzMzM0wzODcuODQgNDE2Ljg1MzMzM2wtMjA5LjA2NjY2Ny0xNjQuNjkzMzMzTDg3LjQ2NjY2NyAyOTguNjY2NjY3djQyNi42NjY2NjZsOTEuNzMzMzMzIDQ2LjUwNjY2NyAyMTAuMzQ2NjY3LTE2NC4yNjY2NjdMNzE5Ljc4NjY2NyA5MzguNjY2NjY3IDkzOC42NjY2NjcgODUwLjM0NjY2N1YxNzAuNjY2NjY3ek0xODYuNDUzMzMzIDYxMC4xMzMzMzNWNDExLjczMzMzM2wxMDQuMTA2NjY3IDEwMy42OHogbTUyNi4wOCA1NS4wNEw1MTQuMTMzMzMzIDUxMmwxOTguNC0xNTMuMTczMzMzeiIgcC1pZD0iNjEyMSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg==) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NjA3MzUyIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjYxMjAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MTguOTMzMzMzIDg1LjMzMzMzM0wzODcuODQgNDE2Ljg1MzMzM2wtMjA5LjA2NjY2Ny0xNjQuNjkzMzMzTDg3LjQ2NjY2NyAyOTguNjY2NjY3djQyNi42NjY2NjZsOTEuNzMzMzMzIDQ2LjUwNjY2NyAyMTAuMzQ2NjY3LTE2NC4yNjY2NjdMNzE5Ljc4NjY2NyA5MzguNjY2NjY3IDkzOC42NjY2NjcgODUwLjM0NjY2N1YxNzAuNjY2NjY3ek0xODYuNDUzMzMzIDYxMC4xMzMzMzNWNDExLjczMzMzM2wxMDQuMTA2NjY3IDEwMy42OHogbTUyNi4wOCA1NS4wNEw1MTQuMTMzMzMzIDUxMmwxOTguNC0xNTMuMTczMzMzeiIgcC1pZD0iNjEyMSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg==) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=flat-square&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NjA3MzUyIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjYxMjAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MTguOTMzMzMzIDg1LjMzMzMzM0wzODcuODQgNDE2Ljg1MzMzM2wtMjA5LjA2NjY2Ny0xNjQuNjkzMzMzTDg3LjQ2NjY2NyAyOTguNjY2NjY3djQyNi42NjY2NjZsOTEuNzMzMzMzIDQ2LjUwNjY2NyAyMTAuMzQ2NjY3LTE2NC4yNjY2NjdMNzE5Ljc4NjY2NyA5MzguNjY2NjY3IDkzOC42NjY2NjcgODUwLjM0NjY2N1YxNzAuNjY2NjY3ek0xODYuNDUzMzMzIDYxMC4xMzMzMzNWNDExLjczMzMzM2wxMDQuMTA2NjY3IDEwMy42OHogbTUyNi4wOCA1NS4wNEw1MTQuMTMzMzMzIDUxMmwxOTguNC0xNTMuMTczMzMzeiIgcC1pZD0iNjEyMSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg==) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=for-the-badge&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NjA3MzUyIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjYxMjAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MTguOTMzMzMzIDg1LjMzMzMzM0wzODcuODQgNDE2Ljg1MzMzM2wtMjA5LjA2NjY2Ny0xNjQuNjkzMzMzTDg3LjQ2NjY2NyAyOTguNjY2NjY3djQyNi42NjY2NjZsOTEuNzMzMzMzIDQ2LjUwNjY2NyAyMTAuMzQ2NjY3LTE2NC4yNjY2NjdMNzE5Ljc4NjY2NyA5MzguNjY2NjY3IDkzOC42NjY2NjcgODUwLjM0NjY2N1YxNzAuNjY2NjY3ek0xODYuNDUzMzMzIDYxMC4xMzMzMzNWNDExLjczMzMzM2wxMDQuMTA2NjY3IDEwMy42OHogbTUyNi4wOCA1NS4wNEw1MTQuMTMzMzMzIDUxMmwxOTguNC0xNTMuMTczMzMzeiIgcC1pZD0iNjEyMSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg==) |
| ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=**plastic**&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=flat-square&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNzI4MTA5NDQzMzg2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5OTAiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiPjxwYXRoIGQ9Ik03MjUuMzMzMzMzIDcwMi43MlYzMTUuMzA2NjY3bC0yNTYgMTkzLjcwNjY2Nk05NC43MiAzOTIuMTA2NjY3YTM2LjYwOCAzNi42MDggMCAwIDEtMC44NTMzMzMtNDkuMDY2NjY3bDUxLjItNDcuMzZjOC41MzMzMzMtNy42OCAyOS40NC0xMS4wOTMzMzMgNDQuOCAwbDE0NS45MiAxMTEuMzYgMzM4LjM0NjY2Ni0zMDkuMzMzMzMzYzEzLjY1MzMzMy0xMy42NTMzMzMgMzcuMTItMTkuMiA2NC01LjEybDE3MC42NjY2NjcgODEuNDkzMzMzYzE1LjM2IDguOTYgMjkuODY2NjY3IDIzLjA0IDI5Ljg2NjY2NyA0OS4wNjY2Njd2NTc2YzAgMTcuMDY2NjY3LTEyLjM3MzMzMyAzNS40MTMzMzMtMjUuNiA0Mi42NjY2NjZsLTE4Ny43MzMzMzQgODkuNmMtMTMuNjUzMzMzIDUuNTQ2NjY3LTM5LjI1MzMzMyAwLjQyNjY2Ny00OC4yMTMzMzMtOC41MzMzMzNsLTM0Mi4xODY2NjctMzExLjQ2NjY2Ny0xNDUuMDY2NjY2IDExMC45MzMzMzRjLTE2LjIxMzMzMyAxMS4wOTMzMzMtMzYuMjY2NjY3IDguMTA2NjY3LTQ0LjggMGwtNTEuMi00Ni45MzMzMzRjLTEzLjY1MzMzMy0xNC4wOC0xMS45NDY2NjctMzcuMTIgMi4xMzMzMzMtNTEuMmwxMjgtMTE1LjIiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9IjU5OTEiPjwvcGF0aD48L3N2Zz4=) |

#### 1.5 仓库类（动态更新）

##### 1.5.1 Release 版本号

```
https://img.shields.io/github/release/用户名/仓库名

注：自动获取最新 Release 的版本号。
```

![](https://img.shields.io/github/release/bitcookies/winrar-keygen)

##### 1.5.2 Issues 开启数量

```
https://img.shields.io/github/issues/用户名/仓库名?color=F48D73

本例样式参数：?color=F48D73

注：自动获取最新 Issues open 的数量。
```

![](https://img.shields.io/github/issues/bitcookies/winrar-keygen?color=F48D73)

##### 1.5.3 License 许可

```
https://img.shields.io/github/license/用户名/仓库名.svg

注：自动获取本仓库的 License 许可及类型。
```

| ![](https://img.shields.io/github/license/bitcookies/winrar-keygen.svg) | ![](https://img.shields.io/github/license/bitcookies/winrar-keygen.svg?logo=github) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |

##### 1.5.4 Github Actions 状态

```
https://github.com/用户名/仓库名/actions/workflows/工作流文件名.yml/badge.svg

注：可在 Github Actions 页面点击 Create status badge 手动创建徽章。
```

![](https://github.com/bitcookies/winrar-keygen/actions/workflows/keygen.yml/badge.svg)

<br><br>

<p align="center">
 <h3 align="center">> 2 活动图类 <</h3>
</p>


### 2. [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

#### 2.1 个人状态卡片

```
https://github-readme-stats.vercel.app/api?username=用户名

本例主题：default
更多主题：https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md
```
![](https://github-readme-stats.vercel.app/api?username=bitcookies&show_icons=true&count_private=true&hide=prs&theme=default_repocard?colors=#fff)

#### 2.2 [个人 Streak Stats 卡片](https://github-readme-streak-stats.herokuapp.com/demo/)

```
https://github-readme-streak-stats.herokuapp.com/?user=用户名

更多主题：https://github-readme-streak-stats.herokuapp.com/demo/
Github仓库：https://github.com/DenverCoder1/github-readme-streak-stats
```

![](https://github-readme-streak-stats.herokuapp.com?user=bitcookies)

#### 2.3 [仓库卡片](https://github.com/anuraghazra/github-readme-stats)

```
https://github-readme-stats.vercel.app/api/pin/?username=用户名&repo=仓库名
```

![](https://github-readme-stats.vercel.app/api/pin/?username=bitcookies&repo=winrar-keygen&theme=graywhite)

#### 2.4 [语言比例卡片](https://github.com/anuraghazra/github-readme-stats)

```
https://github-readme-stats.vercel.app/api/top-langs/?username=用户名

宽度参数：?card_width=445
```

![](https://github-readme-stats.vercel.app/api/top-langs/?username=pudding0503&layout=compact)

#### 2.5 **[Wakatime charts](https://github.com/dvjn/wakatime-charts)**

![Weekly Language Stats](https://raw.githubusercontent.com/dvjn/wakatime-charts/master/images/wakatime_weekly_language_stats.svg "Weekly Language Stats")

![Weekly Project Stats](https://raw.githubusercontent.com/dvjn/wakatime-charts/master/images/wakatime_weekly_project_stats.svg "Weekly Project Stats")

### 2.6 **[Summary Cards](https://github-profile-summary-cards.vercel.app/demo.html)**

```
生成页面：https://github-profile-summary-cards.vercel.app/demo.html
Github仓库：https://github.com/vn7n24fzkq/github-profile-summary-cards
```

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bitcookies&theme=default)

| ![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=bitcookies&theme=default) | ![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=bitcookies&theme=default) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=bitcookies&theme=default) | ![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=bitcookies&theme=default&utcOffset=8) |

<br><br>

<p align="center">
 <h3 align="center">> 3 统计类 <</h3>
</p>


### 3. 访问量和趋势

#### 3.1 访问量

```
https://komarev.com/ghpvc/?username=用户名

Github仓库：https://github.com/antonkomarev/github-profile-views-counter
```

![](https://komarev.com/ghpvc/?username=pudding0503)

```
https://api.visitorbadge.io/api/visitors?path=仓库链接
```

![](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpudding0503%2Fpudding-illustration&label=%E6%B5%8F%E8%A7%88%E9%87%8F&labelColor=%23152136&countColor=%23ff8a65)

```
https://profile-counter.glitch.me/用户名/count.svg
```

![](https://profile-counter.glitch.me/pudding0503/count.svg)

```
https://api.moedog.org/count/@用户名.readme
```

![](https://api.moedog.org/count/@pudding0503.readme)

#### 3.2 [Star 趋势卡片](https://github.com/caarlos0/starcharts)

```
https://starchart.cc/用户名/仓库名.svg

Github仓库：https://github.com/caarlos0/starcharts
```



![](https://starchart.cc/caarlos0/starcharts.svg)

```
趋势卡片生成：https://star-history.com/
```

[![Star History Chart](https://api.star-history.com/svg?repos=bitcookies/winrar-keygen&type=Date)](https://star-history.com/#bitcookies/winrar-keygen&Date)

#### 3.3 个人贡献版

```
https://ghchart.rshah.org/用户名
```



![](https://ghchart.rshah.org/pudding0503)

#### 3.4 [个人贡献版贪吃蛇版](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)

![](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg)

#### 3.5 [个人活动图](https://ashutosh00710.github.io/github-readme-activity-graph/)

[![github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=bitcookies&bg_color=ffffff&color=9e4c98&line=9992f7&point=1e6794&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

#### 3.6 [贡献人员卡片](https://contrib.rocks/preview)

```
https://contrib.rocks/image?repo=用户名/仓库名

注：仅支持 image，分辨率较低。
```

![](https://contrib.rocks/image?repo=bitcookies/winrar-keygen)

#### 3.7 [贡献人员卡片](https://opencollective.com/)

```
https://opencollective.com/hexo-theme-fluid/contributors.svg?width=890&button=false

本例样式参数：?width=890&button=false

注：支持 svg，需注册账号后使用。
```

![](https://opencollective.com/hexo-theme-fluid/contributors.svg?width=890&button=false)

#### 3.8 [仓库概况](https://repobeats.axiom.co/)

```
生成地址：https://repobeats.axiom.co/

注：需使用 Github 账号登录注册。
```

![](https://repobeats.axiom.co/api/embed/55ee65543bb9a0f9c797626c4e66d472a517d17c.svg)

#### 3.9 [metrics卡片](https://github.com/lowlighter/metrics) 

|                      For user accounts                       |                  For organization accounts                   |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [![img](https://github.com/lowlighter/metrics/raw/examples/metrics.classic.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.classic.svg) | [![img](https://github.com/lowlighter/metrics/raw/examples/metrics.organization.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.organization.svg) |

| [📅 Isometric commit calendar](https://github.com/lowlighter/metrics/blob/master/source/plugins/isocalendar/README.md) | [🈷️ Languages activity](https://github.com/lowlighter/metrics/blob/master/source/plugins/languages/README.md) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| Full year calendar[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.isocalendar.fullyear.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg)Half year calendar[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.isocalendar.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg)[](https://github.com/lowlighter/metrics) | Indepth analysis (clone and analyze repositories)[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.languages.indepth.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.indepth.svg)Recently used (analyze recent activity events)[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.languages.recent.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.recent.svg) |

#### 3.10 [Wakatime 图表](https://wakatime.com/)

| ![](assets/wakatime-demo-1.svg) | ![](assets/wakatime-demo-2.svg) |
| :-----------------------------: | :-----------------------------: |

<br><br>

<p align="center">
 <h3 align="center">> 4 其他装饰类 <</h3>
</p>


#### 4.1 [Github Socialify](https://socialify.git.ci/) 头图

```
https://socialify.git.ci/用户名/仓库名/image?

参数，直接使用在线生成工具：https://socialify.git.ci/
```

| ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Light) | ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Dark) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Source%20Code%20Pro&forks=1&name=1&pattern=Diagonal%20Stripes&stargazers=1&theme=Light) | ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Source%20Code%20Pro&forks=1&name=1&pattern=Circuit%20Board&stargazers=1&theme=Dark) |

#### 4.2 [Quotes 名言](https://github.com/PiyushSuthar/github-readme-quotes)

| ![](https://quotes-github-readme.vercel.app/api?type=vertical) | ![](https://quotes-github-readme.vercel.app/api?theme=dark)  |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://quotes-github-readme.vercel.app/api?myquote=My%20Quote) | ![](https://quotes-github-readme.vercel.app/api?theme=dracula) |

![](https://quotes-github-readme.vercel.app/api?type=horizontal)

#### 4.3 奖杯 🏆

```
https://github-profile-trophy.vercel.app/?username=用户名

主题参数：theme=gruvbox
行与列数：row=1&column=6
边框参数：no-frame=true
背景参数：no-bg=true
```

![](https://github-profile-trophy.vercel.app/?username=bitcookies)

![](https://github-profile-trophy.vercel.app/?username=pudding0503&theme=gruvbox&row=1&column=6&no-frame=true&no-bg=true)

<br><br>

<p align="center">
 <h3 align="center">> 5 Github Actions 类 <</h3>
</p>


#### 5.1 3D 个人贡献图

```
Github仓库：https://github.com/yoshi389111/github-profile-3d-contrib
```

<div align="center">
    <img src="https://raw.githubusercontent.com/yoshi389111/github-profile-3d-contrib/main/docs/demo/profile-gitblock.svg" width="100%"/>
</div>
