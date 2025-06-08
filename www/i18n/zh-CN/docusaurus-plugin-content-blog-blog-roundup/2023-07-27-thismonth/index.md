---
slug: roundup-2023-jul
title: "2023 | July"
authors: [nitya, sara, thomas, matt, dina]
tags: [swa, thismonth, mar]
draft: false
---

<head>
  <meta name="twitter:url" content="https://www.azurestaticwebapps.dev/blog/roundup-2023-jul" />
  <meta name="twitter:title" content="This Month in Azure Static Web Apps: Jul 2023" />
  <meta name="twitter:description" content="This Month in @AzureStaticApps - join us and catch up on the latest news, demos, announcements and community content for Azure Static Web Apps!" />
  <meta name="twitter:image" content="https://www.azurestaticwebapps.dev/img/png/roundup/tmis-banner.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:creator" content="@nitya" />
  <meta name="twitter:site" content="@AzureStaticApps" /> 
  <link rel="canonical" href="https://techcommunity.microsoft.com/t5/apps-on-azure-blog/this-month-in-azure-static-web-apps-july-2023/ba-p/3883710" />
</head>

:::info[欢迎阅读本月简报]

我们汇总了最新动态、产品公告、技术内容和社区亮点——浓缩在这一篇简报中。错过往期内容？我们已为您备好存档！
 - 查看博客归档：**https://aka.ms/swa/thismonth**  
 - 观看往期直播回放：**https://aka.ms/swa/community/standups** 
 - 订阅博客源：**https://aka.ms/swa/thismonth/rss.xml**

我们珍视社区声音，期待您的参与！！
 - 想贡献资源链接？[提交此定制工单](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)。
 - 想与我们交流？[加入每月直播站会](https://aka.ms/swa/community/standups)
:::

---

## 社区站会

社区站会直播于每月最后一个周四举行。欢迎参加**2023年7月27日**的下一期活动，我们将演示如何通过Azure Functions为单页应用添加后端功能。查看往期视频存档，获取更多精彩演示和嘉宾分享！

> 直播时间：**太平洋时间上午9点/美国东部时间中午12点/格林尼治时间下午5点**，也可观看回放。

<iframe width="800" height="480" src="https://www.youtube.com/embed/fZljYaqGPy0" title="Azure Static Web Apps Community Standup - Beyond the frontend with Static Web Apps &amp; Azure Functions" frameborder="0" allowfullscreen></iframe>

---

## 本月精选

![](../../static/img/png/roundup/tmis-links.png)

首先带来**社区亮点**

### 社区：博客文章

- [Azure Static Web Apps、Next.js与Azure DevOps（日语）](https://zenn.dev/yusu29/articles/azuredevops_staticapps_next) - `7月5日`
- [利用预览环境测试静态Web应用](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/use-preview-environment-for-test-in-static-web-app/ba-p/3870476) – `7月11日` 
- [通过新版HTML预设实现更快速的静态应用部署](https://techcommunity.microsoft.com/t5/educator-developer-blog/deploying-with-azure-static-apps-is-even-faster-with-the-new/ba-p/3872796) – `7月17日`

### 社区：视频资源

- [构建部署静态Web应用（Angular、Azure Functions、ALM与DevOps）](https://www.youtube.com/watch?v=TNA2T62Xqtc) - `7月`
- [基于Blazor和.NET的Azure静态Web应用（NDC奥斯陆大会）](https://www.youtube.com/watch?v=r3IKpPe36nY) - `7月`
- [Burke学Blazor](https://www.youtube.com/watch?v=JdlYnylzFqM) – `6月`
- [通过REST或GraphQL连接静态Web应用与Azure数据库](https://www.youtube.com/watch?v=gCrBSSOezSQ) - `6月`

### 社区：活动预告

- [全球黑客松：JavaScript on Azure](https://developer.microsoft.com/en-us/reactor/series/S-1173/) - 与学生、初学者和经验丰富的开发者共同参与为期两周的虚拟黑客马拉松，学习构建类似上文Contoso房地产应用的企业级应用。8月16日-8月31日。
- [Azure静态Web应用社区站会](https://www.youtube.com/watch?v=fZljYaqGPy0&list=PLI7iePan8aH4AiiQ6UejZ4lxmbK3QX4Dy&index=6) – 获取最新动态、参与互动演示并探讨Azure静态Web应用技术。YouTube直播。7月27日。

---

## 本月聚焦

_每个月，我们都希望聚焦一个在Azure Static Web Apps领域值得关注的关键资源或个人。_

:::info[🌟 聚焦推荐：CONTOSO房地产应用参考示例]

您是否知道我们在Microsoft Build大会上发布了一个[开源企业级应用](https://aka.ms/contoso-real-estate-github)？该项目采用可组合架构，展示了如何集成Azure Static Web Apps、Azure Functions、Azure Cosmos DB等技术。

![](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/472260i73D150FAF1149769/image-size/large?v=v2&px=999)
:::

如果您错过了该会议，我们为您准备了可自主探索的资源。

### 架构解析

![Contoso参考架构图](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/485315i8026FF8814B1B393/image-size/large?v=v2&px=999)

### 预告视频

先睹为快：了解您将构建的内容

<iframe width="800" height="480" src="https://www.youtube.com/embed/GxeENsvwZrI" title="Contoso Real Estate Teaser" frameborder="0" allowfullscreen></iframe>

### 图解指南

想了解我们构建该应用的初衷和学习要点？这里有一份视觉概览。您可以查看或下载[高清版本图片](https://github.com/SketchTheDocs/cloud-skills/blob/main/gallery/MSBuild-2023-ContosoRealEstate.png)近距离观察。

![](../../static/img/png/contoso-sketchnote.png)

### 🚨 | 行动号召！

- 阅读[发布公告](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/announcing-contoso-real-estate-javascript-composable-application/ba-p/3827097)  
- 克隆[开源代码库](https://aka.ms/contoso-real-estate-github?source=techcommunity)进行探索（如果喜欢请给我们点星！）
- 参加[重构代码的实况编码系列](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wu6g_B-QJrvWOe8RdNCmio2)（葡萄牙语）

请持续关注[Microsoft Learn](https://learn.microsoft.com/en-us/azure/developer/javascript/composable-cloud-contoso-real-estate)文档站点获取更新。