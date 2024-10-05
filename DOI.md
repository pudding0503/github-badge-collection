# DOI by Github

### 1. [Figshare](https://mozillascience.github.io/code-research-object/)

[Figshare](https://mozillascience.github.io/code-research-object/) 是 [Nature 等期刊](https://www.nature.com/sdata/policies/editorial-and-publishing-policies#code-avail)常用于生成 Github 仓库代码 DOI 号的工具，可以安装浏览器插件获取 DOI 号或者输入 Github repo 地址生成 DOI 徽章：

```
生成页面：https://mozillascience.github.io/code-research-object/
```

这种生成 DOI 徽章的缺点是无法动态的进行更新，一般推荐使用 [Zenodo](https://about.zenodo.org/)。

### 2. [Zenodo](https://about.zenodo.org/)

为了使您的存储库更易于在学术文献中引用，您可以创建持久标识符，也称为数字对象标识符 (DOI)。您可以使用数据归档工具 [Zenodo](https://about.zenodo.org/) 在 GitHub 上归档存储库并为该归档发布 DOI。

> [!TIP]
> - Zenodo 只能访问公共存储库，因此请确保您要存档的存储库是[公共的](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility)。
> - 如果您想存档属于某个组织的存储库，组织所有者可能需要批准 Zenodo 应用程序的[访问权限](https://docs.github.com/en/organizations/managing-oauth-access-to-your-organizations-data/approving-oauth-apps-for-your-organization)。
> - 确保在您的存储库中包含[许可证](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)，以便读者知道如何重复使用您的作品。

**步骤：**

1. 导航到 Zenodo 的[登录页面](https://zenodo.org/login)
2. 单击**使用 GitHub 登录**
3. 查看访问权限的信息，然后单击**授权 Zenodo**
4. 导航到 [Zenodo GitHub 页面](https://zenodo.org/account/settings/github/)
5. 在您要存档的存储库名称右侧，将按钮切换为 **“开”**

每次创建新的 GitHub [发布版本](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases)时，Zenodo 都会将版本库存档并发布新的 DOI（在授权关联前创建的发布版本不会生成相应的 DOI）。请按照 [“管理版本库中的发布版本”](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository) 中的步骤创建一个新版本。
