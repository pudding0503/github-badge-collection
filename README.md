<p align="center">
 <img width="100px" src="https://github.githubassets.com/images/mona-loading-default.gif" align="center" alt="Logo" />
 <h3 align="center">Github 常用徽章合集</h3>
 <p align="center">Github Badge Collection</p>
</p>

## 0. 说明

本 README 主要收集一些零散的 Github 常用徽章、图标标识和 Markdown 技巧等，下面是一个简单指引：

+ [Github 支持的 Emoji](Emoji.md)
+ [Github 的 Markdown 用法](Markdown.md)

## 1. [Shields 徽章](https://shields.io/)

Shields 适用于各类现有的或自定义名称的徽章。

```
样式参数，共有5种样式：
style=plastic
style=flat
style=flat-square
style=for-the-badge
style=social

Shields 文档：https://shields.io/badges/static-badge
```

### 1.1 品牌类

```
https://img.shields.io/badge/左侧文字-右侧文字-颜色?logo=图标

本例样式参数：?style=flat

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://shields.io/docs/logos；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色。
```

| ![](https://img.shields.io/badge/Windows-10-2376bc?style=flat&logo=windows&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Stdio-blueviolet?style=flat&logo=visual-studio&logoColor=ffffff) | ![](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue?style=flat&logo=visual-studio-code&logoColor=ffffff) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| **![](https://img.shields.io/badge/Linux-FCC624?style=&logo=linux&logoColor=black)** | ![](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white) | ![](https://img.shields.io/badge/iOS-333?style=flat&logo=apple&logoColor=white) |
| ![](https://img.shields.io/badge/Chrome-4285F4?style=flat&logo=GoogleChrome&logoColor=white) | ![](https://img.shields.io/badge/Edge-0078D7?style=flat&logo=Microsoft-edge&logoColor=white) | ![](https://img.shields.io/badge/-Git-FCC624?style=flat&logo=git) |

### 1.2 开发类

```
https://img.shields.io/badge/-左侧文字-右侧文字-颜色?logo=图标

本例样式参数：?style=flat-square

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://shields.io/docs/logos；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色。
```

| ![](https://img.shields.io/badge/c-%2300599C.svg?style=flat-square&logo=c&logoColor=white) | ![](https://img.shields.io/badge/c%23-%23239120.svg?style=flat-square&logo=c-sharp&logoColor=white) | ![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=ffffff) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | ![](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) | ![](https://img.shields.io/badge/-JavaScript-oringe?style=flat-square&logo=javascript) |
| ![](https://img.shields.io/badge/-Markdown-000000?style=flat-square&logo=Markdown&logoColor=ffffff) | ![](https://img.shields.io/badge/-LaTex-3776AB?style=flat-square&logo=LaTex&logoColor=ffffff) | ![](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white) |
| ![](https://img.shields.io/badge/-Nodejs-c0ebd?style=flat-square&logo=Node.js) | ![](https://img.shields.io/badge/-Docker-FCC624?style=flat-square&logo=docker) | ![](https://img.shields.io/badge/Qt-%23217346.svg?style=flat-square&logo=Qt&logoColor=white) |
| ![](https://img.shields.io/badge/r-%23276DC3.svg?style=flat-square&logo=r&logoColor=white) | ![](https://img.shields.io/badge/jquery-%230769AD.svg?style=flat-square&logo=jquery&logoColor=white) | ![](https://img.shields.io/badge/mysql-%2300f.svg?style=flat-square&logo=mysql&logoColor=white) |

### 1.3 社交类

```
https://img.shields.io/twitter/follow/右侧文字.svg?logo=图标

注：
1.图标库支持主流品牌、也可以使用 base64 嵌入自定义图标；
2.图标库查看文档：https://shields.io/docs/logos；
3.图标支持 logoColor 参数设置颜色，但文字不支持设置颜色。
```

![](https://img.shields.io/twitter/follow/Microsoft.svg?logo=microsoft)

### 1.4 自定义类

```
https://img.shields.io/badge/文字-颜色?logo=图标

本例样式参数：?style=for-the-badge&logo=appveyor

注：
1.任何自定义徽标都可以通过 base64 编码在 URL 参数中传递。
```

| ![](https://img.shields.io/badge/图筑风暻-ED8384?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMS0wMVQyMTo0MDoxOSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDEtMDFUMjE6NDA6NTErMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCIgeG1wTU06T3JpZ2luYWxEb2N1bWVudElEPSJ4bXAuZGlkOjQ5NTc5NDdlLTM4Y2UtNGE0YS05M2UyLWFjYWU0M2NmYWZlOCI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6NDk1Nzk0N2UtMzhjZS00YTRhLTkzZTItYWNhZTQzY2ZhZmU4IiBzdEV2dDp3aGVuPSIyMDIyLTAxLTAxVDIxOjQwOjE5KzA4OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNSAoV2luZG93cykiLz4gPC9yZGY6U2VxPiA8L3htcE1NOkhpc3Rvcnk+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+PUE0fAAAALRJREFUOI3tkz0KAjEQRh+roCC2gldQ2N47WIjWXkI9hIVewMIbeAiPsEew3NpmWYTPIokGNTGg5T4I88vHzECQhKSDDCdJuc2lvExSVxIZhra1c6AAVqTRA0bAQ+iVPbBMEJoACwA34lHvlHb02GqFpLO/2icGwDRS3wE5cImt5hh7fgsYAjPMHdc2f4PnkUN0PH8DbEON3yYKif4kFKURaoT+gfsilbVXr9YHai+uAz0VwB1CgYRUa2LvsQAAAABJRU5ErkJggg==&logoColor=white) | ![](https://img.shields.io/badge/小喵心语-EEA3A0?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAACXBIWXMAAC4jAAAuIwF4pT92AAAHKGlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNy4xLWMwMDAgNzkuN2JhZmNmMCwgMjAyMS8xMC8xMy0wMDo0MToyOCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0RXZ0PSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VFdmVudCMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyMi0wMy0yMFQxNjozMDowMSswODowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjItMDMtMjBUMTY6MzA6MTcrMDg6MDAiIHhtcDpNZXRhZGF0YURhdGU9IjIwMjItMDMtMjBUMTY6MzA6MTcrMDg6MDAiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIiBwaG90b3Nob3A6SUNDUHJvZmlsZT0ic1JHQiBJRUM2MTk2Ni0yLjEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6ZGVhZWYwMmMtODhhNi1iNzQ0LWIxNjMtZTYzMmMwMmE3MTIyIiB4bXBNTTpEb2N1bWVudElEPSJhZG9iZTpkb2NpZDpwaG90b3Nob3A6NTNiNWY4MmMtMjgzOS03YjQ1LTkwOTQtOTljNGRjMTRjYmY4IiB4bXBNTTpPcmlnaW5hbERvY3VtZW50SUQ9InhtcC5kaWQ6ZGU4ZTNmMDktOGFmNS1lYTQxLTk0YjAtMDFiODJmMzRmNGVkIj4gPHBob3Rvc2hvcDpEb2N1bWVudEFuY2VzdG9ycz4gPHJkZjpCYWc+IDxyZGY6bGk+eG1wLmRpZDo2NmJkYTZiYi1jMTg3LTQwYmYtYjA2Ni04Zjk0NjFiY2EyMmY8L3JkZjpsaT4gPHJkZjpsaT54bXAuZGlkOjllYWYwYjMwLTA0ZjUtNDU2Zi05MTlmLTg5Yzc5MjAxY2FhZDwvcmRmOmxpPiA8L3JkZjpCYWc+IDwvcGhvdG9zaG9wOkRvY3VtZW50QW5jZXN0b3JzPiA8eG1wTU06SGlzdG9yeT4gPHJkZjpTZXE+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJjcmVhdGVkIiBzdEV2dDppbnN0YW5jZUlEPSJ4bXAuaWlkOmRlOGUzZjA5LThhZjUtZWE0MS05NGIwLTAxYjgyZjM0ZjRlZCIgc3RFdnQ6d2hlbj0iMjAyMi0wMy0yMFQxNjozMDowMSswODowMCIgc3RFdnQ6c29mdHdhcmVBZ2VudD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIi8+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJjb252ZXJ0ZWQiIHN0RXZ0OnBhcmFtZXRlcnM9ImZyb20gYXBwbGljYXRpb24vdm5kLmFkb2JlLnBob3Rvc2hvcCB0byBpbWFnZS9wbmciLz4gPHJkZjpsaSBzdEV2dDphY3Rpb249InNhdmVkIiBzdEV2dDppbnN0YW5jZUlEPSJ4bXAuaWlkOmRlYWVmMDJjLTg4YTYtYjc0NC1iMTYzLWU2MzJjMDJhNzEyMiIgc3RFdnQ6d2hlbj0iMjAyMi0wMy0yMFQxNjozMDoxNyswODowMCIgc3RFdnQ6c29mdHdhcmVBZ2VudD0iQWRvYmUgUGhvdG9zaG9wIDIyLjUgKFdpbmRvd3MpIiBzdEV2dDpjaGFuZ2VkPSIvIi8+IDwvcmRmOlNlcT4gPC94bXBNTTpIaXN0b3J5PiA8L3JkZjpEZXNjcmlwdGlvbj4gPC9yZGY6UkRGPiA8L3g6eG1wbWV0YT4gPD94cGFja2V0IGVuZD0iciI/PgBEX38AAAD3SURBVDjLrdSxK8ZBGAfwSzJg8o4sStlMJoN/QXYbCyWLLMQqik2kXqX8BYo30xsZbAYpo5R3MSnZfAzucv1635L3vnV1z91zn265CwglR6eNe2zE+Ui34JyfNGM9g54OwCR6s7qvXdN1BN8xhCmMtumbxlJWL6JVbZrwm0/MYxUDlb5BbKIW6/V0qApuZeAXLvCEQyxjFsPxdisYi3spb1Xwxt/SwhUalfXXHBvXfR5zcKcA2MjBZgFwO2H9+CgAriVwQZnsJvCsEHiQwIdC4EmIz6pUzkN8QqVyG3BZELwLeC4IvgScFgSP0o+8jzqO/znq2EPtG7YdvQkznyUHAAAAAElFTkSuQmCC&logoColor=white%color=white) | ![](https://img.shields.io/badge/play-station-blue.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIj48cGF0aCBkPSJNMTI5IDExMWMtNTUgNC05MyA2Ni05MyA3OEwwIDM5OGMtMiA3MCAzNiA5MiA2OSA5MWgxYzc5IDAgODctNTcgMTMwLTEyOGgyMDFjNDMgNzEgNTAgMTI4IDEyOSAxMjhoMWMzMyAxIDcxLTIxIDY5LTkxbC0zNi0yMDljMC0xMi00MC03OC05OC03OGgtMTBjLTYzIDAtOTIgMzUtOTIgNDJIMjM2YzAtNy0yOS00Mi05Mi00MmgtMTV6IiBmaWxsPSIjZmZmIi8+PC9zdmc+) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |

### 1.5 动态类

#### 1.5.1 Release 版本号

```
https://img.shields.io/github/release/用户名/仓库名

注：自动获取最新 Release 的版本号。
```

![](https://img.shields.io/github/release/bitcookies/winrar-keygen)

#### 1.5.2 Issues 开启数量

```
https://img.shields.io/github/issues/用户名/仓库名?color=F48D73

本例样式参数：?color=F48D73

注：自动获取最新 Issues open 的数量。
```

![](https://img.shields.io/github/issues/bitcookies/winrar-keygen?color=F48D73)

#### 1.5.3 License 许可

```
https://img.shields.io/github/license/用户名/仓库名.svg

注：自动获取本仓库的 License 许可及类型。
```

| ![](https://img.shields.io/github/license/bitcookies/winrar-keygen.svg) | ![](https://img.shields.io/github/license/bitcookies/winrar-keygen.svg?logo=github) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |

#### 1.5.4 Github Actions 状态

```
https://github.com/用户名/仓库名/actions/workflows/工作流文件名.yml/badge.svg

注：可在 Github Actions 页面点击 Create status badge 手动创建徽章。
```

![](https://github.com/bitcookies/winrar-keygen/actions/workflows/keygen.yml/badge.svg)



## 2. [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

### 2.1 个人卡片

```
https://github-readme-stats.vercel.app/api?username=用户名

本例主题：default
更多主题：https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md
```

![](https://github-readme-stats.vercel.app/api?username=bitcookies&show_icons=true&count_private=true&hide=prs&theme=default_repocard?colors=#fff)

```
https://github-readme-streak-stats.herokuapp.com/?user=用户名
```

![](https://github-readme-streak-stats.herokuapp.com/?user=bitcookies)

### 2.2 仓库卡片

```
https://github-readme-stats.vercel.app/api/pin/?username=用户名&repo=仓库名
```

![](https://github-readme-stats.vercel.app/api/pin/?username=bitcookies&repo=winrar-keygen&theme=graywhite)

### 2.3 用户语言比例

```
https://github-readme-stats.vercel.app/api/top-langs/?username=用户名

宽度参数：?card_width=445
```

![](https://github-readme-stats.vercel.app/api/top-langs/?username=pudding0503&layout=compact)

### 2.4 **[wakatime-charts](https://github.com/dvjn/wakatime-charts)**

![Weekly Language Stats](https://raw.githubusercontent.com/dvjn/wakatime-charts/master/images/wakatime_weekly_language_stats.svg "Weekly Language Stats")
![Weekly Project Stats](https://raw.githubusercontent.com/dvjn/wakatime-charts/master/images/wakatime_weekly_project_stats.svg "Weekly Project Stats")


## 3. 访问量和趋势

### 3.1 访问量

```
https://komarev.com/ghpvc/?username=用户名
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

### 3.2 [Star 趋势卡片](https://github.com/caarlos0/starcharts)

```
https://starchart.cc/用户名/仓库名.svg
```



![](https://starchart.cc/caarlos0/starcharts.svg)

### 3.3 [Github Socialify 头图](https://socialify.git.ci/)

```
https://socialify.git.ci/用户名/仓库名/image?

参数，直接使用在线生成工具：https://socialify.git.ci/
```

| ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Light) | ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Dark) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Source%20Code%20Pro&forks=1&name=1&pattern=Diagonal%20Stripes&stargazers=1&theme=Light) | ![](https://socialify.git.ci/bitcookies/winrar-keygen/image?font=Source%20Code%20Pro&forks=1&name=1&pattern=Circuit%20Board&stargazers=1&theme=Dark) |

### 3.4 个人贡献版

```
https://ghchart.rshah.org/用户名
```



![](https://ghchart.rshah.org/pudding0503)

### 3.5 [个人贡献版贪吃蛇版](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)

![](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg)

### 3.6 [贡献人员卡片](https://contrib.rocks/preview)

```
https://contrib.rocks/image?repo=用户名/仓库名

注：仅支持 image，分辨率较低。
```

![](https://contrib.rocks/image?repo=bitcookies/winrar-keygen)

### 3.7 [贡献人员卡片](https://opencollective.com/)

```
https://opencollective.com/hexo-theme-fluid/contributors.svg?width=890&button=false

本例样式参数：?width=890&button=false

注：支持 svg，需注册账号后使用。
```

![](https://opencollective.com/hexo-theme-fluid/contributors.svg?width=890&button=false)

### 3.8 [仓库概况](https://repobeats.axiom.co/)

```
https://repobeats.axiom.co/api/embed/55ee65543bb9a0f9c797626c4e66d472a517d17c.svg

注：需注册账号，使用 Github 账号登陆并创建。
```

![](https://repobeats.axiom.co/api/embed/55ee65543bb9a0f9c797626c4e66d472a517d17c.svg)



## 4. [metrics卡片](https://github.com/lowlighter/metrics) 

|                      For user accounts                       |                  For organization accounts                   |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [![img](https://github.com/lowlighter/metrics/raw/examples/metrics.classic.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.classic.svg) | [![img](https://github.com/lowlighter/metrics/raw/examples/metrics.organization.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.organization.svg) |

| [📅 Isometric commit calendar](https://github.com/lowlighter/metrics/blob/master/source/plugins/isocalendar/README.md) | [🈷️ Languages activity](https://github.com/lowlighter/metrics/blob/master/source/plugins/languages/README.md) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| Full year calendar[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.isocalendar.fullyear.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg)Half year calendar[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.isocalendar.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg)[](https://github.com/lowlighter/metrics) | Indepth analysis (clone and analyze repositories)[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.languages.indepth.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.indepth.svg)Recently used (analyze recent activity events)[![img](https://github.com/lowlighter/metrics/raw/examples/metrics.plugin.languages.recent.svg)](https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.recent.svg) |



## 5. [Quotes 名言](https://github.com/PiyushSuthar/github-readme-quotes)

| ![](https://quotes-github-readme.vercel.app/api?type=vertical) | ![](https://quotes-github-readme.vercel.app/api?theme=dark)  |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://quotes-github-readme.vercel.app/api?myquote=My%20Quote) | ![](https://quotes-github-readme.vercel.app/api?theme=dracula) |

![](https://quotes-github-readme.vercel.app/api?type=horizontal)



## 6. 奖杯 🏆

```
https://github-profile-trophy.vercel.app/?username=用户名

主题参数：theme=gruvbox
行与列数：row=1&column=6
边框参数：no-frame=true
背景参数：no-bg=true
```

![](https://github-profile-trophy.vercel.app/?username=bitcookies)

![](https://github-profile-trophy.vercel.app/?username=pudding0503&theme=gruvbox&row=1&column=6&no-frame=true&no-bg=true)

## 7. 3D 个人资料

<div align="center">
    <img src="https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/profile-3d-contrib/profile-night-rainbow.svg" width="100%"/>
</div>

## 8. [Wakatime 图表](https://wakatime.com/)

| ![](https://wakatime.com/share/embeddable/sun0225SUN/d07b5f65-d3e1-4896-897c-1695c560a7dc.svg) | ![](https://wakatime.com/share/@42d0678c-368b-448b-9a77-5d21c5b55352/39a6f115-6058-44ce-95da-c3b2cbc9e831.svg) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |



## 9. 一些 GIF 和 PNG

### 9.1 GIF 动态图标

<div align="center">
  <img alt-"html5" src="https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif" width="80" title="html">
  <img alt="css" src="https://media.giphy.com/media/fsEaZldNC8A1PJ3mwp/giphy.gif" width="80" title="css">
  <img alt="VSCode" src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" width="80" title="vscode">
  <img alt="python" src="https://i.giphy.com/media/LMt9638dO8dftAjtco/200.webp" width="80" title="python">
  <img alt="javascript" src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="80" title="javascript">
  <img alt="sublime" src="https://media.giphy.com/media/jnDKffgCfGYOp6cMTK/giphy.gif" width="80" title="sublime">
  <img alt="github" src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" width="80" title="github">
  <img alt="node" src="https://media.giphy.com/media/kdFc8fubgS31b8DsVu/giphy.gif" width="80" title="node">
</div>

### 9.2 [ProgrammingVTuberLogos](https://github.com/Aikoyori/ProgrammingVTuberLogos)

最近很火的 [Aikoyori](https://github.com/Aikoyori) 画的图标。

| ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/VSCode/VSCode.png?raw=true) | ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/VSCode/VSCode-Thick.png?raw=true) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/IntelliJIDEA/IntellijLogo.png?raw=true) | ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/IntelliJIDEA/intelliJShadow.png?raw=true) |
| ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/Docker/DockerLogo.png?raw=true) | ![](https://github.com/Aikoyori/ProgrammingVTuberLogos/blob/main/Docker/DockerLogoShadowed.png?raw=true) |

