# Aidoku 中文使用教程

> Aidoku 是一款开源、无广告的漫画阅读器，支持 iPhone、iPad 和 Mac。
> 官方网站：[aidoku.app](https://aidoku.app/)　|　开源仓库：[github.com/Aidoku/Aidoku](https://github.com/Aidoku/Aidoku)

Aidoku 本体是阅读器，漫画内容通过“源（Source）”提供。本教程介绍如何安装 Aidoku、安装漫画源，以及基础使用方法。

本文是社区用户整理的非官方中文教程，与 Aidoku 官方项目无关。Aidoku 的版本、安装方式和界面可能会变化，请以官方页面和你设备上的实际显示为准。

---

## 一、安装 Aidoku

Aidoku 的安装方式会因设备和系统版本而不同。请先查看官方说明和最新发布版本：

- [Aidoku 官网](https://aidoku.app/)
- [Aidoku Releases（下载页面）](https://github.com/Aidoku/Aidoku/releases)
- [Aidoku 官方 Discord](https://discord.com/invite/9U8cC5Zk3s)

常见方式包括：

- **TestFlight**：通过官方测试邀请安装，更新较方便；名额和版本以官方公告为准。
- **AltStore / SideStore**：使用 IPA 安装，免费签名通常需要定期重新签名。
- **TrollStore 或其他签名方式**：仅适用于符合条件的设备或账号，具体限制请查看对应工具说明。

安装 Aidoku 后，请先打开一次 App，确认它可以正常运行，再继续安装漫画源。

---

## 二、安装漫画源

安装好 Aidoku 后，需要安装“源”才能浏览漫画内容。

### 1. 添加 Aidoku Community 源列表

Aidoku Community 维护了一个可供 Aidoku 使用的源列表：

1. 打开 Aidoku，进入「设置」→「图源」→「图源列表（Source Lists）」。
2. 添加以下地址：

   `https://aidoku-community.github.io/sources/index.min.json`

3. 回到「浏览」页面，即可查看和安装列表中的源。

社区源包含多种语言和不同内容评级。安装前请查看源的语言和内容分级，并遵守所在地区的法律法规。

### 2. 导入 `.aix` 源包

`.aix` 是 Aidoku 的源安装包。下载后可用以下任一方式导入：

- **方式 A**：在 iOS「文件」App 中打开 `.aix` 文件，选择用 Aidoku 打开。
- **方式 B**：打开 Aidoku，进入「设置」→「图源」，选择「导入 .aix 文件」。

### 3. 本项目提供的源

本项目目前仅提供 **拷貝漫畫 Plus** 一个源。

它是在 Aidoku 原版拷贝漫画源基础上独立维护的增强版本，提供：

- CopyManga 账号登录；
- 查看账户收藏的漫画；
- 在漫画详情页加入或取消收藏；
- 支持地区、状态和排序筛选；
- 在漫画详情页直接打开评论区（使用 Aidoku 内置浏览器）。

请前往 [aidoku-copymanga-plus](https://github.com/rereva0611/aidoku-copymanga-plus) 查看完整说明，并在 [Releases](https://github.com/rereva0611/aidoku-copymanga-plus/releases/latest) 下载最新的 `package.aix`。

下载后按上文「导入 `.aix` 源包」操作即可。

### 4. 第三方源说明

第三方源由不同作者维护，可能会因源站改版、网络环境或维护状态变化而暂时无法使用。请自行判断来源是否可信，并遵守所在地区的法律法规。

---

## 三、基础使用

1. **浏览 / 搜索**：进入「浏览」页面，选择一个图源，可按列表浏览，也可使用搜索栏搜索。
2. **收藏到本地书架**：打开漫画详情页，点击书签图标或选择「加入书架」，即可在「书架」中查看。
3. **阅读**：打开章节开始阅读；阅读方向、翻页模式等可在 Aidoku 设置中调整。
4. **备份**：如果你的 Aidoku 版本提供备份功能，可在设置中导出或导入书架、历史和设置。

---

## 四、常见问题

- **安装失败或 App 无法验证**：检查签名是否过期、设备系统是否满足官方要求，并重新查看官方安装说明。
- **源无法加载或一直转圈**：可能是源站维护、域名变化、网络连接或访问限制导致。稍后重试，或查看源项目是否有更新。
- **评论区打不开**：CopyManga 评论区由站点页面提供，需要网络可以访问 CopyManga；也可以稍后重试。
- **TestFlight 显示没有名额**：关注官方 Discord 或官网公告，等待新的测试名额。
- **其他问题**：Aidoku 本体问题可到官方 Discord 的支持频道询问；具体源的问题请到对应源的 GitHub 项目反馈。

---

## 五、相关链接

| 内容 | 地址 |
|---|---|
| Aidoku 官网 | [aidoku.app](https://aidoku.app/) |
| Aidoku 开源仓库 | [github.com/Aidoku/Aidoku](https://github.com/Aidoku/Aidoku) |
| Aidoku 下载页面 | [GitHub Releases](https://github.com/Aidoku/Aidoku/releases) |
| Aidoku Community 源列表 | [index.min.json](https://aidoku-community.github.io/sources/index.min.json) |
| 拷貝漫畫 Plus 项目 | [aidoku-copymanga-plus](https://github.com/rereva0611/aidoku-copymanga-plus) |
| 拷貝漫畫 Plus 下载 | [Releases](https://github.com/rereva0611/aidoku-copymanga-plus/releases/latest) |
| Aidoku 官方 Discord | [加入 Discord](https://discord.com/invite/9U8cC5Zk3s) |

## 免责声明

本教程及其中介绍的第三方源均为非官方内容，与 Aidoku、CopyManga 或其他漫画网站没有隶属关系。使用者应自行确认软件、源和漫画内容是否适合自己，并遵守所在地区的法律法规。
