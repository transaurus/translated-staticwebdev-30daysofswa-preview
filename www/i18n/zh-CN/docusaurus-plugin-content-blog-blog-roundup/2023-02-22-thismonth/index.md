---
slug: roundup-2023-feb
title: "2023 | February"
authors: [reshmi, nitya, sara]
tags: [swa, thismonth, jan]
draft: false
---

<head>
  <meta name="twitter:url" content="https://www.azurestaticwebapps.dev/blog/roundup-2023-feb" />
  <meta name="twitter:title" content="This Month in Azure Static Web Apps: Feb 2023" />
  <meta name="twitter:description" content="This February in @AzureStaticApps - we cover Azure Static Web Apps Diagnostics, authentication, deploying from Codespaces and SWA CLI" />
  <meta name="twitter:image" content="https://www.azurestaticwebapps.dev/img/png/roundup/feb.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:creator" content="@nitya" />
  <meta name="twitter:site" content="@AzureStaticApps" /> 
  <link rel="canonical" href="https://www.azurestaticwebapps.dev/thismonth/roundup-2023-feb" />
</head>

欢迎阅读 **2023年2月** 的 **Azure静态Web应用月度简报** 🎉

:::info[关于本简报]

本简报传统上于**每月最后一个周一**发布——恰好在[**Azure静态Web应用社区站会**](https://www.youtube.com/playlist?list=PLI7iePan8aH7Yo8vo288dAULgjyCCCcEJ)（每月最后一个周三举行）之前。您可以通过这篇友好的博客文章了解所有新闻和公告，然后加入直播参与互动讨论、演示等。

 * 不想错过下一期简报？<a href="/thismonth/rss.xml" target="_blank">**订阅RSS源**</a>。
 * 想为简报投稿？[**提交此定制议题**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)。
 * 想回顾往期内容？[**浏览历史版本**](/roundup#roundups-archive)。
 * 想观看往期直播？[**查看站会录像**](https://aka.ms/swa/community/standups)

别忘了提交_您的_更新内容以便纳入下一期！

:::

---

![](../../static/img/png/roundup/feb.png)

---

## 产品动态

_本节涵盖产品团队的最新新闻或公告。阅读以下内容，了解Azure静态Web应用领域的最新动态！_

* **2月15日** | [公开预览：Python 3.10支持](https://azure.microsoft.com/updates/public-preview-python-310-support/?WT.mc_id=javascript-74011-ninarasi) 通过使用Python 3.10，您可以利用Python最新的语言和运行时改进。要在Azure函数中使用Python 3.10，请使用[Functions 4.x版本](https://learn.microsoft.com/azure/azure-functions/functions-versions?tabs=v4&pivots=programming-language-python&WT.mc_id=javascript-74011-ninarasi)。Azure静态Web应用对Python 3.10的支持遵循Python 3.10的生命周期。| _**[阅读详情！](https://aka.ms/swa-language-runtime)**_

* **2月8日** | [更新：静态Web应用中增强的Next.js混合渲染支持](https://github.com/Azure/static-web-apps/discussions/1066) 静态Web应用近期增强了对Next.js混合渲染的支持。现在支持[独立模式](https://nextjs.org/docs/advanced-features/output-file-tracing)和拆分部署（静态与动态内容）。这些变更将在您重新部署Next.js SSR应用时生效。| _**[在讨论中留言反馈](https://github.com/Azure/static-web-apps/discussions/1066)**_

* **1月26日** | [欢迎参加Azure静态Web应用社区站会！](https://youtu.be/7hTQJs9Ku5Y?list=PLI7iePan8aH7Yo8vo288dAULgjyCCCcEJ&t=143/?WT.mc_id=javascript-74011-ninarasi) 这是每月一次的直播活动，涵盖新闻、演示和产品更新！在首期SWA社区站会中，您将认识团队、深入了解产品、探索社区资源，并通过您喜爱的开发工具观看快速入门演示！| _**[收藏播放列表！](https://aka.ms/swa/community/standups)**_

---

## 开发资源

_本节涵盖来自微软作者的内容、活动和代码示例。查看这些资源以获取相关学习资料和最佳实践。_

* **2月16日** | `youtube.com` - [**为何我爱上了Azure静态Web应用 | 完整初学者指南**](https://www.youtube.com/watch?v=AgP4p8qhi4s) 作者：_James Montemagno_。
无论您使用Blazor、Angular、React、Svelte、Vue、Next.js、Nuxt.js、Gatsby、Hugo、VuePress等库或Web框架构建Web应用，还是任何包含静态内容（HTML、CSS、JavaScript）的项目，都可以充分利用Azure静态Web应用的优势。本视频将带您逐步创建首个Azure静态Web应用，通过GitHub Actions部署，与Azure Functions后端通信，并配置完整的自定义域名及SSL证书——全程不到30分钟！

* **2月7日** | `techcommunity.microsoft.com` - [**如何为Azure静态Web应用配置基于Azure Active Directory的内置身份验证**](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/how-to-setup-built-in-authentication-for-azure-static-web-apps/ba-p/3734709?WT.mc_id=javascript-74011-ninarasi) 作者：_Joey Huang_。Azure静态Web应用提供两种身份验证机制：内置验证和自定义验证。仅需在_staticwebapp.config.json_配置文件中定义路由规则和角色即可启用身份验证。本文将逐步演示如何使用Azure AD配置内置验证！

* **1月24日** | `techcommunity.microsoft.com` - [**将网络隔离的后端与Azure静态Web应用集成**](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/integrating-network-isolated-backends-with-azure-static-web-apps/ba-p/3721136?WT.mc_id=javascript-74011-ninarasi) 作者：_Thomas Gauvin_。Azure静态Web应用可轻松实现全球化托管，内置API支持、暂存环境等功能。通过新的API集成特性，您还能关联网络隔离的后端，享受无缝路由和集成安全等核心优势。阅读全文获取详情！

---

## 社区动态

:::info[开发者共创内容]
_本节聚焦开发者社区提交或通过Tech Community、dev.to等平台Azure静态Web应用标签发现的优质内容。_
:::

* **2月17日** | `medium` - [**免费在Azure静态Web应用上托管你的学生作品集**](https://medium.com/@kevin_comba/hosting-your-student-portfolio-for-free-on-azure-static-web-apps-ecac2b75300c) 作为一名学生，向潜在雇主展示你的作品可能很困难😒😒，尤其是当你没有个人网站或托管手段时。通过在Azure静态Web应用上托管作品集，你可以获得专业且易于访问的展示平台，从而在求职者中脱颖而出。快来学习如何操作吧！
* **1月16日** | `dev.to` - [**使用Azure静态Web应用、函数和Cosmos DB实现无服务器架构**](https://dev.to/c_arnab/serverless-in-azure-using-static-web-apps-functions-and-cosmos-db-506j) 作者_Arnab Choudhuri_ 本文探讨了Azure上的无服务器开发——从本地开发工具、内置身份验证支持、HTTP触发的函数，到与CosmosDB构建的数据层无缝集成。最后我们通过一个真实场景，演示了如何利用GitHub Actions实现CI/CD全流程。
* **1月3日** | `dev.to` - [**通过TeamCity/Jenkins/命令行将单页应用部署到Azure静态Web应用**](https://dev.to/gkarwchan/deploy-a-single-page-application-to-azure-static-website-using-cicd-and-cli-3o7b) 作者_Ghassan Karwchan_ 当我尝试通过TeamCity部署SPA应用到Azure静态Web应用时，发现大多数教程都使用GitHub Actions的CI/CD流程。但如果我们需要通过TeamCity或其他CI/CD工具按需部署呢？使用[Azure静态Web应用CLI](https://github.com/Azure/static-web-apps-cli)就能实现！本文将详细讲解方法。

* **案例研究:** | `github.com` - [Peacock VS Code扩展文档托管于SWA](https://peacockcode.dev/) 作者_John Papa_ 想了解可复用的真实案例吗？[vscode-peacock](https://github.com/johnpapa/vscode-peacock)是一款能根据上下文智能调整编辑器配色的VS Code扩展，拥有超210万安装量和850万+下载量——其文档正是托管在Azure静态Web应用上。

---

## 近期活动

_本节收录包含Azure静态Web应用相关内容或开发者交流的线上线下活动，欢迎提交CFP或注册链接！_

* **2月22日** | ✨ **实时参与[Azure静态Web应用社区站会](https://www.youtube.com/watch?v=7hTQJs9Ku5Y)** ✨ 与Azure静态Web应用团队成员面对面，在直播中获取最新动态、演示和公告（美国东部时间中午12点）。
* **2月1日-3月1日** | 专业开发者想参与低代码革命？整个二月加入[低代码二月](https://microsoft.github.io/Low-Code/blog/2023-kickoff/)开启#30DaysOfLowCode学习之旅！

---

## 你知道吗？

_每月我们将重点推荐一个与Azure静态Web应用相关的关键资源或人物。_

:::info[🌟 聚焦：适用于SWA的SVELTEKIT适配器]

[**SvelteKit 1.0于2022年12月正式发布**](https://svelte.dev/blog/announcing-sveltekit-1.0)，这是构建Svelte应用推荐方式的里程碑——配套的[交互式教程](https://learn.svelte.dev/)可助您快速入门。

要部署SvelteKit应用，您需要使用[适配器](https://kit.svelte.dev/docs/adapters)将其适配到目标部署环境，这类插件能将构建好的应用转换为可部署的站点。**您知道吗**？SvelteKit默认支持一些[零配置部署适配器](https://kit.svelte.dev/docs/adapter-auto)，包括专为Azure静态Web应用设计的**[svelte-adapter-azure-swa](https://github.com/geoffrich/svelte-adapter-azure-swa)！**

:::

想要亲身体验Azure SWA适配器与SvelteKit？请查看  
**[为Azure静态Web应用创建SvelteKit应用](https://sveltekit.blogspot.com/2022/11/creating-sveltekit-app-for-azure-static.html)**——这是来自Svelte团队成员的四部分系列教程，完整演示了从本地开发到Azure SWA部署的全流程，如下图所示。

- 第一部分 - [创建Svelte应用](https://sveltekit.blogspot.com/2022/11/creating-sveltekit-app-for-azure-static.html)
  - 第二部分 - [添加API](https://sveltekit.blogspot.com/2022/11/creating-sveltekit-app-for-azure-static_5.html)
  - 第三部分 - [使用Azure SWA适配器](https://sveltekit.blogspot.com/2022/11/creating-sveltekit-app-for-azure-static_13.html)
  - 第四部分 - [部署到Azure](https://sveltekit.blogspot.com/2022/11/creating-sveltekit-app-for-azure-static_17.html)

🚨 注意：本教程发布于2022年11月，早于SvelteKit 1.0正式版。如果您尝试时发现需要更新或有心得，欢迎通过下期汇总投稿分享！

![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEia4MjlHAY0tg8gMEmAlyv4b16OHviYHZX54dkr46ShIeUzzKvCPFR4ZFDm19alGdTnZUrfHeryOvMot3ULTIaYISTgNb3h4AXoQU57uHZFJrsQ92VC3Ve0KFGqmtt5ac8VLhlugakdmJ617Zr0D74D701nS0RM9vS24crSJ_3NnBTZVlGMkIUEdCBJ/w640-h512/SvelteKitBlog2.drawio.png)

---

## 🚨 | 内容征集

:::tip[下期汇总：2023年3月20日]
投稿截止日期：2023年3月15日。

 * 您是否撰写了技术文章、创建了SWA应用或示例？
 * 您是否在策划包含SWA相关议题的活动？
 * 您是否是刚完成首个SWA应用或博客的学生？

请尽快通过[**此专用issue提交**](https://github.com/staticwebdev/30DaysOfSWA/issues/new?assignees=&labels=ThisMonthIn+-+Community&template=---this-month-in-swa--community-submission.md&title=This+Month+In%3A+Community)详情。我们期待展示您的成果！
:::