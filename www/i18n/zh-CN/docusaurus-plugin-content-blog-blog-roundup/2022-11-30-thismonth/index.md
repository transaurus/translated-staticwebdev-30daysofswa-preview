---
slug: roundup-2022-nov
title: "2022 | November"
authors: [reshmi, nitya, sara]
tags: [swa, thismonth, nov]
draft: false
---

<head>
  <meta name="twitter:url" content="https://www.azurestaticwebapps.dev/blog/roundup-2022-nov" />
  <meta name="twitter:title" content="This Month in Azure Static Web Apps: Nov 2022" />
  <meta name="twitter:description" content="This November in @AzureStaticApps - we cover hybrid rendering with @nextjs, universal rendering with @nuxt_js and put the spotlight on #MicrosoftStudentSummit" />
  <meta name="twitter:image" content="https://www.azurestaticwebapps.dev/img/png/roundup/nov.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:creator" content="@nitya" />
  <meta name="twitter:site" content="@AzureStaticApps" /> 
  <link rel="canonical" href="https://www.azurestaticwebapps.dev/blog/roundup-2022-nov" />
</head>

来了！！我们的**本月SWA动态**十一月特辑 🎉

:::info[关于月度汇总]
本汇总传统上在**每月最后一个星期一**发布——恰好在[**Azure静态Web应用社区站会**](https://www.youtube.com/playlist?list=PLI7iePan8aH7Yo8vo288dAULgjyCCCcEJ)（每月最后一个星期三举行）之前。您可以通过这篇友好的博客文章了解所有新闻和公告，然后加入直播参与互动讨论、演示等。

 * 不想错过下一期汇总？<a href="/thismonth/rss.xml" target="_blank">**订阅Feed**</a>。
 * 想为汇总投稿？[**提交此自定义issue**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)。
 * 想回顾往期内容？[**浏览历史版本**](/roundup#roundups-archive)。
 * 想观看往期直播？[**查看站会录像**](https://aka.ms/swa/community/standups)

别忘了提交_您的_更新以便纳入下一期！

:::

---

![](../../static/img/png/roundup/nov.png)

---

## 产品动态

_本节涵盖产品团队的最新新闻或公告。阅读了解Azure静态Web应用领域的最新动态！_

* **11月08日** | [Azure静态Web应用现已全面支持.NET 7](https://azure.microsoft.com/en-us/updates/generally-available-azure-static-web-apps-now-fully-supports-net-7/?WT.mc_id=academic-7401100000-sagibbon) 对于应用前端，静态Web应用现在可以自动构建和部署.NET 7.0 Blazor WebAssembly应用。对于后端API，您可以使用静态Web应用构建和部署.NET 7.0 Azure Functions。[立即开始](https://learn.microsoft.com/en-us/azure/static-web-apps/deploy-blazor?WT.mc_id=academic-74011-sagibbon)构建您自己的Blazor + 无服务器API应用。

* **11月09日** | [Azure静态Web应用现支持Node 18](https://azure.microsoft.com/en-us/updates/public-preview-azure-static-web-apps-now-supports-node-18/?WT.mc_id=academic-74011-sagibbon) 通过使用Node 18，您可以利用Node最新的语言和运行时改进。要在Azure Functions中使用Node 18，请使用Functions 4.x版本。[了解更多](https://learn.microsoft.com/en-us/azure/static-web-apps/languages-runtimes?WT.mc_id=academic-74011-sagibbon)关于Azure静态Web应用支持的语言。

* **11月09日** | [静态Web应用支持Gitlab和Bitbucket](https://azure.microsoft.com/en-us/updates/generally-available-static-web-apps-support-for-gitlab-and-bitbucket/?WT.mc_id=academic-74011-sagibbon) 您现在可以使用Gitlab和Bitbucket作为静态Web应用的CI/CD提供商。您可以导入Gitlab或Bitbucket项目，使用提供的模板创建简单的YAML文件，并将其链接到使用自定义部署源创建的静态Web应用。通过此[Gitlab教程](https://learn.microsoft.com/en-us/azure/static-web-apps/gitlab?tabs=vanilla-javascript?WT.mc_id=academic-74011-sagibbon)和[Bitbucket教程](https://learn.microsoft.com/en-us/azure/static-web-apps/bitbucket?tabs=vanilla-javascript?WT.mc_id=academic-74011-sagibbon)开始使用。

---

## 开发者资源

_本节涵盖来自Microsoft作者的内容、活动和代码示例。查看相关学习资源和最佳实践。_

* **11月1日** | `github.com` - [Next.js 问答应用](https://github.com/aaronpowell/nextjs-graphql-trivia-demo) 作者 _Aaron Powell_  
  这是一个Next.js问答演示应用，展示了如何在API路由中使用GraphQL与Azure Cosmos DB交互，构建可部署到Azure Static Web Apps的混合模式Next.js应用。
* **11月8日** | `techcommunity.com` - [将React应用部署到Azure Static Web Apps](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/deploy-a-react-app-to-azure-static-web-apps/ba-p/3671939/?WT.mc_id=academic-74011-sagibbon) 作者 _David Ginn和Phil Jirsa_  
  云解决方案架构师David Ginn和Phil Jirsa演示了如何通过GitHub Actions将ReactJS应用部署至Azure Static Web Apps。
* **11月23日** | `microsoft.github.io` - [从自定义应用发起音视频通话加入Teams会议](https://microsoft.github.io/MicrosoftCloud/tutorials/docs/ACS-to-Teams-Meeting) 作者 _Dan Wahlin和Ayca Bas_  
  本教程将展示如何在React应用中使用Azure通信服务，实现用户通过音视频通话加入Microsoft Teams会议的功能。

---

## 社区动态

:::info[开发者共创内容]
_本节精选来自开发者社区的投稿内容，或发布在Tech Community、dev.to等平台且带有相关标签的优质文章。_
:::

* **11月14日** | `dev.to` - [Azure Static Web Apps入门指南](https://dev.to/danwahlin/getting-started-with-azure-static-web-apps-4a8j) 作者 _Dan Wahlin_  
  Dan将逐步演示如何从零开始创建React应用并部署至Azure Static Web Apps。
* **11月14日** | `youtube.com` - [Blazor与.NET的Azure Static Web Apps实践](https://www.youtube.com/watch?v=FjGjguW1Xa0) 作者 _Melissa Houghton_  
  探索如何将Blazor WebAssembly与.NET Azure Functions或Azure容器应用的无服务器能力结合，并通过代码仓库实现自动构建部署到Azure Static Web Apps。
* **11月20日** | `github.com` - [svelte-adapter-azure-swa](https://github.com/geoffrich/svelte-adapter-azure-swa) 作者 _Geoff Rich_  
  专为Svelte应用设计的适配器，可创建支持Azure函数动态渲染的Azure Static Web App。

---

## 2022年度活动精选

_在总结2022年并规划2023年之际，以下SWA相关会议不容错过：_

* [Azure Static Web Apps一周年庆 🥳](https://www.youtube.com/watch?v=1e6k5HNK4F8)
* [使用Static Web Apps为Node应用添加博客功能](https://www.youtube.com/watch?v=vWwjMTeP1kU)
* [通过MSAL.js实现React单页应用与Azure Active Directory集成（2022年7月）](https://www.youtube.com/watch?v=7oPSL5wWeS0)

_有即将举办的活动需要推广？[立即提交](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)，我们将在下期月报中收录！_

---

## 你知道吗？

_每月我们将聚焦一个与Azure Static Web Apps相关的关键资源或人物。_

:::info[🌟 聚焦：Awesome AZD 模板]

Azure Developer CLI (AZD) 是一款开源工具，通过一系列开发者友好的命令（对应开发流程中的关键阶段：编码、构建、部署、监控），助您快速上手 Azure。

不仅如此，AZD 还提供可扩展的应用程序模板（[Awesome AZD 模板](https://azure.github.io/awesome-azd/)），涵盖多种场景下 Azure 部署所需的一切资源。每个模板都提供远超 "Hello World!" 的端到端解决方案。

:::

查看我们创建的静态 Web 应用支持版 [Awesome AZD 模板](https://azure.github.io/awesome-azd/)：

* [使用 Node.js API 和 Azure Cosmos DB API for MongoDB 的待办应用（部署于静态 Web 应用和函数）](https://github.com/Azure-Samples/todo-nodejs-mongo-swa-func)
* [使用 Python API 和 Azure Cosmos DB API for MongoDB 的待办应用（部署于静态 Web 应用和函数）](https://github.com/Azure-Samples/todo-python-mongo-swa-func)

在构建更多静态 Web 应用支持的 [Awesome AZD 模板](https://azure.github.io/awesome-azd/)过程中，我们期待您的参与！**[提交模板创意](https://github.com/Azure/awesome-azd/issues/new?assignees=nitya%2C+savannahostrowski&labels=requested-contribution&template=%F0%9F%A4%94-submit-an-idea-for-a-template.md&title=%5BIdea%5D+%3Cyour-template-name%3E)**，若已有成型模板，**[欢迎贡献您的模板](https://github.com/Azure/awesome-azd/issues/new?assignees=nitya%2C+savannahostrowski&labels=new-contribution&template=%F0%9F%93%B2contribute-an-azd-template-.md&title=%5BNew+azd-template%5D+%3Cyour-template-name%3E)**！

---

## 🚨 | 内容征集

:::tip[下期预告：2022年12月28日]
投稿截止日期：2022年12月21日。

 * 您是否撰写了技术文章或创建了SWA应用/示例？
 * 您是否在策划包含SWA相关议题的活动？
 * 您是否是刚完成首个SWA应用或博客的学生？

请立即通过[**此专用issue提交**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)分享详情，我们期待展示您的成果！
:::