---
slug: roundup-2022-nov
title: "SWA Roundup: Nov 2022"
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

来了！！我们的十一月 **SWA月度精选** 🎉

:::info[关于月度精选]

我们**每月最后一个星期三**发布Azure静态Web应用的产品动态、公告和内容更新精选。在一篇友好的文章中了解所有更新——别忘了提交_你的_更新内容以便纳入下一期！

 * 不想错过更新？<a href="/blog/rss.xml" target="_blank">**订阅Feed**</a>。
 * 想投稿？[**提交此定制issue**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)。
 * 想查看往期内容？[**浏览历史版本**](/thismonth#view-past-editions)。

:::

---

![](../../static/img/png/roundup/nov.png)

---

## 产品动态

_本节涵盖产品团队的最新动态和公告。阅读了解Azure静态Web应用的最新资讯！_

* **11月08日** | [Azure静态Web应用现已全面支持.NET 7](https://azure.microsoft.com/en-us/updates/generally-available-azure-static-web-apps-now-fully-supports-net-7/?WT.mc_id=academic-7401100000-sagibbon) 对于应用前端，静态Web应用现在可以自动构建和部署.NET 7.0 Blazor WebAssembly应用。对于后端API，你可以使用静态Web应用构建和部署.NET 7.0 Azure Functions。[开始使用](https://learn.microsoft.com/en-us/azure/static-web-apps/deploy-blazor?WT.mc_id=academic-74011-sagibbon)构建你自己的Blazor+无服务器API应用。

* **11月09日** | [Azure静态Web应用现支持Node 18](https://azure.microsoft.com/en-us/updates/public-preview-azure-static-web-apps-now-supports-node-18/?WT.mc_id=academic-74011-sagibbon) 通过使用Node 18，你可以利用Node最新的语言和运行时改进。要在Azure Functions中使用Node 18，请使用Functions 4.x版本。[了解更多](https://learn.microsoft.com/en-us/azure/static-web-apps/languages-runtimes?WT.mc_id=academic-74011-sagibbon)关于Azure静态Web应用支持的语言。

* **11月09日** | [静态Web应用支持Gitlab和Bitbucket](https://azure.microsoft.com/en-us/updates/generally-available-static-web-apps-support-for-gitlab-and-bitbucket/?WT.mc_id=academic-74011-sagibbon) 现在你可以使用Gitlab和Bitbucket作为静态Web应用的CI/CD提供商。你可以导入Gitlab或Bitbucket项目，使用提供的模板创建一个简单的YAML文件，并将其链接到使用自定义部署源创建的静态Web应用。通过这个[Gitlab教程](https://learn.microsoft.com/en-us/azure/static-web-apps/gitlab?tabs=vanilla-javascript?WT.mc_id=academic-74011-sagibbon)和[Bitbucket教程](https://learn.microsoft.com/en-us/azure/static-web-apps/bitbucket?tabs=vanilla-javascript?WT.mc_id=academic-74011-sagibbon)开始使用。

---

## 开发资源

_本节涵盖来自Microsoft作者的内容、活动和代码示例。查看相关学习资源和最佳实践。_

* **11月1日** | `github.com` - [Next.js 知识问答应用](https://github.com/aaronpowell/nextjs-graphql-trivia-demo) 作者：_Aaron Powell_  
  这是一个使用 Next.js 构建的知识问答演示应用，展示了如何通过 API 路由中的 GraphQL 与 Azure Cosmos DB 交互，并利用 Next.js 混合应用支持部署到 Azure Static Web Apps。

* **11月8日** | `techcommunity.com` - [将 React 应用部署到 Azure Static Web Apps](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/deploy-a-react-app-to-azure-static-web-apps/ba-p/3671939/?WT.mc_id=academic-74011-sagibbon) 作者：_David Ginn 和 Phil Jirsa_  
  跟随云解决方案架构师 David Ginn 和 Phil Jirsa 的演示，学习如何通过 GitHub Actions 将 ReactJS 应用部署到 Azure Static Web Apps。

* **11月23日** | `microsoft.github.io` - [从自定义应用发起音视频通话加入 Teams 会议](https://microsoft.github.io/MicrosoftCloud/tutorials/docs/ACS-to-Teams-Meeting) 作者：_Dan Wahlin 和 Ayca Bas_  
  本教程将介绍如何在 React 应用中使用 Azure Communication Services，实现用户通过音视频通话加入 Microsoft Teams 会议的功能。

---

## 社区动态

:::info[开发者共创内容]
_本节精选来自开发者社区的优质内容——包括直接投稿或发布在 Tech Community、dev.to 等平台的相关标签下的文章。_
:::

* **11月14日** | `dev.to` - [Azure Static Web Apps 入门指南](https://dev.to/danwahlin/getting-started-with-azure-static-web-apps-4a8j) 作者：_Dan Wahlin_  
  跟随 Dan 的步骤，从零开始学习如何创建 React 应用并部署到 Azure Static Web Apps。

* **11月14日** | `youtube.com` - [Blazor 与 .NET 的 Azure Static Web Apps 实践](https://www.youtube.com/watch?v=FjGjguW1Xa0) 作者：_Melissa Houghton_  
  探索如何将 Blazor WebAssembly 与 .NET Azure Functions 或 Azure Container Apps 的无服务器能力结合，并通过代码仓库自动构建部署到 Azure Static Web Apps。

* **11月20日** | `github.com` - [svelte-adapter-azure-swa](https://github.com/geoffrich/svelte-adapter-azure-swa) 作者：_Geoff Rich_  
  专为 Svelte 应用设计的适配器，通过 Azure 函数实现动态服务端渲染，快速创建 Azure Static Web App。

---

## 2022 年活动精选

_在总结 2022 年并规划 2023 年之际，以下 SWA 相关会议不容错过！_

* [Azure Static Web Apps 一周年庆典 🥳](https://www.youtube.com/watch?v=1e6k5HNK4F8)
* [使用 Static Web Apps 为 Node 应用添加博客并关联](https://www.youtube.com/watch?v=vWwjMTeP1kU)
* [通过 MSAL.js 实现 React 单页应用与 Azure Active Directory 的集成（2022年7月）](https://www.youtube.com/watch?v=7oPSL5wWeS0)

_有即将举办的活动需要推广？[立即投稿](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)，我们将在下期汇总中展示！_

---

## 你知道吗？

_每月我们会重点推荐一个与 Azure Static Web Apps 相关的关键资源或人物。_

:::info[🌟 聚焦：Awesome AZD 模板]

Azure 开发者命令行工具 (AZD) 是一款开源工具，通过一系列开发者友好的命令（对应开发工作流中的关键阶段：编码、构建、部署、监控），助您快速上手 Azure。

不仅如此，AZD 还提供可扩展的应用模板（[Awesome AZD 模板集](https://azure.github.io/awesome-azd/)），包含多场景下 Azure 应用开发所需的全套资源。每个模板都覆盖了远超 "Hello World!" 的端到端场景。

:::

查看我们已创建的静态 Web 应用支持版 [Awesome AZD 模板](https://azure.github.io/awesome-azd/)：

* [采用 Node.js API 和 Azure Cosmos DB API for MongoDB 的待办应用（部署于静态 Web 应用与函数）](https://github.com/Azure-Samples/todo-nodejs-mongo-swa-func)
* [采用 Python API 和 Azure Cosmos DB API for MongoDB 的待办应用（部署于静态 Web 应用与函数）](https://github.com/Azure-Samples/todo-python-mongo-swa-func)

在持续扩充静态 Web 应用版 [Awesome AZD 模板集](https://azure.github.io/awesome-azd/)的过程中，我们期待您的参与！**[提交模板创意](https://github.com/Azure/awesome-azd/issues/new?assignees=nitya%2C+savannahostrowski&labels=requested-contribution&template=%F0%9F%A4%94-submit-an-idea-for-a-template.md&title=%5BIdea%5D+%3Cyour-template-name%3E)**，若您已有成型模板，**[欢迎提交至模板库](https://github.com/Azure/awesome-azd/issues/new?assignees=nitya%2C+savannahostrowski&labels=new-contribution&template=%F0%9F%93%B2contribute-an-azd-template-.md&title=%5BNew+azd-template%5D+%3Cyour-template-name%3E)**！

---

## 🚨 | 内容征集

:::tip[下期截稿：2022年12月28日]
投稿截止：2022年12月21日

 * 您是否撰写了技术文章/开发了SWA应用或示例？
 * 您是否在筹备含SWA相关议题的活动？
 * 您是否是刚完成首个SWA应用或博客的学生？

立即通过[**此专用issue提交**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)分享您的成果，我们期待为您传播！
:::