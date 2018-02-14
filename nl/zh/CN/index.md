---

 

copyright:

  years: 2015, 2018

lastupdated: "2018-01-19" 

---


{:shortdesc: .shortdesc} 
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} 中的新增功能
{: #whatsnew}

及时获取 {{site.data.keyword.Bluemix}} 中提供的新功能和服务，以便最充分地利用 {{site.data.keyword.Bluemix_notm}} 体验。我们将更新组织为以下类别：[{{site.data.keyword.Bluemix_notm}} 平台](index.html#platform_category)、[{{site.data.keyword.Bluemix_local_notm}} 和 {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal)、[计算](index.html#compute_category)和[服务](index.html#services_category)。
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} 平台
{: #platform_category}

### 现在，{{site.data.keyword.Bluemix_notm}} Foundry 服务在美国东部区域可用
最新更新日期：2017 年 12 月 15 日

现在，新的美国东部数据中心在华盛顿可用。此新区域可以使用 `us-east.bluemix.net` 端点进行访问。有关在此新区域中可购买的服务的详细信息，请参阅[按区域列出的服务](/docs/services/services_region.html#services_region)。

### 支持欧盟中的资源
最新更新日期：2017 年 12 月 14 日

如果您的服务和数据中心位于欧洲，现在 {{site.data.keyword.Bluemix_notm}} 提供了额外的功能来保护您在欧盟的数据。您可以请求位于欧洲的客户成功团队提供支持。此支持全天候可用。有关更多信息，请参阅[启用支持 EU 选项](/docs/pricing/eusupported.html#bill_eusupported)和[请求对欧盟中资源的支持](/docs/support/index.html#eusupported)。

### 撤销对 TLS 1.0 和 1.1 的支持
最新更新日期：2017 年 11 月 28 日

2018 年 3 月 1 日，{{site.data.keyword.Bluemix_notm}} 将撤销对许多云产品和服务上 TLS 1.0 和 TLS 1.1 的支持；我们致力于提供高度安全且符合关于安全和数据隐私的业界最佳实践的云，此更改正是这一工作的一部分。要了解有关此更改如何影响您以及您可能需要采取的措施的更多信息，请参阅[撤销对 TLS 1.0 和 1.1 的支持](/docs/troubleshoot/appsectls.html)。

### 新增组织帐户中资源的方法
最新更新日期：2017 年 11 月 16 日

资源组是供您创建可定制帐户资源分组的新方法，并且对组的访问权以及组内的资源均使用 Identity and Access Management (IAM) 进行管理。所有人一开始只有缺省资源组。您可以重命名此资源组，并且可以在目录中创建新服务实例时，向此资源组添加这些服务实例。 

如果您是使用现买现付或预订帐户的用户，那么可以创建其他资源组，以便更轻松地管理配额以及查看一组资源的计费使用情况。您还可以对资源进行分组，从而更轻松地为用户一次性分配对多个服务的访问权。要了解有关使用帐户的资源组的更多信息，请参阅[管理资源组](/docs/admin/resourcegroups.html#rgs)。

### {{site.data.keyword.Bluemix_notm}} IAM 更新
最新更新日期：2017 年 11 月 16 日

在 {{site.data.keyword.Bluemix_notm}} 帐户内引入的[资源组](/docs/overview/resource-groups.html#whatis)为您分配访问权开辟了一条新的道路。可以为用户和服务标识分配对资源组内所有服务的访问权，从而使您可以一次性快速分配对多个资源的访问权。您还可以通过为每个用户或服务标识只分配对资源组内某些服务的访问权来定制访问权，或者仅选择分配对向下一直到服务实例级别的单个资源的访问权。
 
有关可以通过 IAM 来利用的功能的更多信息，请参阅 [IAM 提供了哪些功能？](/docs/iam/index.html#features)

### 定制仪表板视图 
最新更新日期：2017 年 11 月 16 日

可以在 {{site.data.keyword.Bluemix_notm}} 控制台的仪表板中，查看和管理帐户中的所有资源。现在，可以设置过滤器来定制视图。例如，可以按资源组进行过滤，以查看资源组中的特定资源。还可以按区域或按 Cloud Foundry 空间进行过滤。有关更多详细信息，请参阅[在仪表板上管理资源](/docs/overview/ui.html#dashboardview)。


### 支持中心
最新更新日期：2017 年 11 月 2 日

现在，我们有了新的支持中心，在其中可以搜索信息，向开发者社区发布问题以及管理凭单。在 {{site.data.keyword.Bluemix_notm}} 控制台菜单栏中，转至**支持 > 支持中心**。 

### 推出 IBM Cloud
最新更新日期：2017 年 10 月 31 日

Bluemix 现已更名为 IBM Cloud。除了推出新名称外，没有更改其他任何内容。您仍可以像平时一样，轻松地构建和运行应用程序和服务。有关更多详细信息，请参阅 [IBM Cloud 博客](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 轻量帐户
最新更新日期：2017 年 10 月 31 日

轻量帐户是我们的新帐户类型，让您有权免费试用精选服务，而没有时间限制。这个新帐户还包含使用情况跟踪和效率功能，可帮助您更好地管理资源。要了解可用功能的更多信息，请参阅[帐户类型](/docs/pricing/index.html#liteaccount)。

### Identity and Access Management 应用程序认证功能
最新更新日期：2017 年 10 月 6 日

现在，Identity and Access Management (IAM) 提供了创建服务标识的功能，您可以将其视为可供应用程序用于向 {{site.data.keyword.Bluemix_notm}} 服务进行认证的身份。服务标识可以使用以服务策略形式分配给服务标识的关联 API 密钥和访问许可权（而不使用个人用户凭证）进行创建，以便您可控制使用该标识进行认证的任何应用程序的访问级别。

有关此功能的优点以及如何开始使用的更多信息，请参阅 [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。 

### {{site.data.keyword.Bluemix_notm}} 全局目录 
最新更新日期：2017 年 7 月 27 日

上一次控制台更新后可在控制台中从单个位置管理公共区域，基于此更新进行扩展，{{site.data.keyword.Bluemix_notm}} 现在拥有全局目录，进一步简化了从目录中选择和部署项的过程。不管您在控制台中选择了哪个区域，现在都可以在目录中查看所有公共区域中可用的所有服务。在目录中选择一个磁贴后，即可以看到在其中该服务可用的区域，然后选择要在其中部署该服务的区域。

有关目录最新更新的更多信息，请参阅 [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.Bluemix_notm}} 控制台更新
最新更新日期：2017 年 5 月 23 日

现在，您可以通过更新的 {{site.data.keyword.Bluemix_notm}} 控制台在单个位置管理各公共区域。区域选择器简化了访问资源的过程；其他增强功能包括可用性更高、性能更佳。

有关此更新的更多信息，请查看 [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### Identity and Access Management
最新更新日期：2017 年 5 月 1 日

通过最新的更新和改进，现在 {{site.data.keyword.Bluemix_notm}} 帐户所有者或管理员可以使用新的统一访问控制 UI 来利用以下功能：
 * 采用新的访问控制功能后，可管理用户对 Kubernetes 服务和其他服务的细颗粒度访问权
 * 为其组织内的用户分配服务策略和 Cloud Foundry 角色

此外，{{site.data.keyword.Bluemix_notm}} 平台用户还可以创建、删除和列出与其用户标识关联的 API 密钥。平台用户在使用 API 或 CLI 时，可以使用这些 API 密钥进行认证。

最后，我们增强了统一用户管理能力，确保在链接的 IaaS-PaaS 帐户中统一管理用户，而无需在 SoftLayer 客户门户网站或 {{site.data.keyword.Bluemix_notm}} 控制台中单独添加用户。

有关最近更新的更多信息，请查看 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 更改了 {{site.data.keyword.Bluemix_notm}} 文档的导航设计
最新更新日期：2017 年 4 月 13 日

借助这次导航更新，我们相信您可以更好地了解整个文档中的内容组织方式，并且能够更高效地查找相关内容。由于内容的嵌套层更少，您不必再四处搜寻来查找成功使用 {{site.data.keyword.Bluemix_notm}} 所需的文档。


## {{site.data.keyword.Bluemix_local_notm}} 和 {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### 管理控制台 12 月更新
{: #decemberadminconsole}
最新更新日期：2017 年 12 月 14 日

通过 12 月的最新更新和改进，您可以使用以下新功能：

#### 预订平均 CPU 使用率阈值的通知

平均 CPU 已添加为通知预订中的阈值类型。现在，您可以在 CPU 使用率（在所有 DEA 和 Diego 单元上的平均值）高于或低于特定阈值时收到通知。

#### 控制对欧盟云系统的访问 

现在，管理控制台合并了在欧盟地区（首先是法兰克福）支持云资源的新功能，能够定义用于控制 IBM 人员访问权的策略。您可以管理访问控制策略，查看访问请求，对请求执行操作以及跟踪历史记录。
  
#### 增强了安全报告中的信息

现在，安全报告中除了用户和组织的唯一标识外，还包含用户友好的名称。

### 管理控制台 8 月更新
{: #augustadminconsole}
最新更新日期：2017 年 8 月 31 日

通过 8 月的最新更新和改进，您可以使用以下新功能：

#### {{site.data.keyword.cloudant_short_notm}} 服务使用情况度量值更新

  * 更新了对 {{site.data.keyword.cloudant_short_notm}} 使用情况度量值的计算，以反映出 {{site.data.keyword.cloudant_short_notm}} 集群中所有节点上的已用 GB 和可用 GB 总量。通常，{{site.data.keyword.cloudant_short_notm}} 集群包含 3 个节点，并且数据库中的文档将在集群中的所有节点上进行复制，以实现高可用性和灾难恢复。通过 8 月更新，{{site.data.keyword.cloudant_short_notm}} 对话框（在_资源使用情况 > 服务_视图中提供）中的容量度量值指示集群中所有节点上的空间。例如，如果单个 {{site.data.keyword.cloudant_short_notm}} 集群中包含 3 个节点，每个节点的容量是 1000 GB，那么容量限制将为 3000 GB。如果已使用该容量中的 1500 GB，那么 {{site.data.keyword.cloudant_short_notm}} 使用情况度量值将为 50%。

#### 维护安排更新
  
  * 在 {{site.data.keyword.Bluemix_dedicated_notm}} 中，客户可以管理其专用环境可用于部署系统更新的日期和时间。客户可以定义可用时段，这表示维护更新可以和不可以部署到其专用环境的日期和时间。在 8 月更新中，_可用更新时段_已重命名为_更新时段_，_不可用更新时段_已重命名为_中断时段_。除了术语变化外，现在客户在定义中断（不可用）日期时有更大的灵活性和余地。中断日期在请求后需要 IBM 批准，多长时间能获得批准不一定。IBM 在批准了请求的中断日期之后，会取消当前安排在不可用时段中的所有现有更新。IBM 还会为这些更新创建新记录，并将其安排在批准的中断日期以外的时间。
  
有关更多信息，请参阅[视频演示](https://bit.ly/2eCQNvu){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 管理控制台 7 月更新
{: #julyadminconsole}
最新更新日期：2017 年 7 月 31 日

通过 7 月的最新更新和改进，您可以使用以下新功能：

#### 资源使用情况历史记录功能更新

  * 在之前的更新（6 月）中，内存和磁盘使用情况的“历史记录”视图引入了显示过去 48 小时、30 天和 5 个月使用情况数据的功能。在这次最新的 7 月更新中，资源使用情况历史记录功能经过扩展，允许定制显示其资源使用数据的时间范围。每小时、每天和每月视图仍然保留，但现在用户可以指定显示其内存和磁盘使用情况度量值的开始日期/时间和持续时间（例如，显示自 2017 年 7 月 1 日起 15 天的内存使用情况）。
  * 引入了新的 CLI 命令，用于在 CLI 中显示资源度量值历史记录。该命令的参数以及用法示例可以通过输入以下命令找到：`_cf ba resource-metrics-history -help_`
 
有关更多信息，请参阅[视频演示](https://youtu.be/QBij0jB5qAk){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 管理控制台 6 月更新
{: #mayadminconsole}
最新更新日期：2017 年 6 月 26 日

通过 6 月的最新更新和改进，您可以使用以下新功能：

#### 资源使用情况页面更新

  * 系统资源
    * 更新了内存和磁盘的“历史记录”视图，现在可显示 48 小时、30 天和 5 个月的数据
    * 提供了“了解更多”链接，用于显示管理控制台度量值 API 如何用于生成“历史记录”视图 
  * 应用程序
    * 提供环境中所有应用程序的使用情况信息
    * 按应用程序名称、物理内存、保留内存、物理磁盘、保留磁盘、物理 CPU 或组织名称排序 
    * 提供了搜索功能，用于按应用程序名称和组织名称过滤结果
    * 提供了“了解更多”链接，用于显示管理控制台度量值 API 如何用于生成“应用程序”视图
 
有关更多信息，请参阅[资源使用情况](/docs/hybrid/index.html#resourceusage)。

#### 用于度量值的 API 更新

  * 添加了环境统计信息，可按天或按月提供内存和磁盘消耗量的平均值
  
有关更多信息，请参阅[用于度量值的 API](/docs/hybrid/index.html#envappmetricsapi)。


### 管理控制台 5 月更新
{: #mayadminconsole}
最新更新日期：2017 年 5 月 30 日

通过 5 月的最新更新和改进，您可以使用以下新功能：

 * 改进了“状态”页面，包含对影响 {{site.data.keyword.Bluemix_notm}} 平台和运行时的事件进行更详细的诊断。
 * 改进了安全性“报告和日志”页面：
   * 现在，报告以表格式显示，简化了报告浏览和搜索，包含按报告类别、文件名或创建日期排序的功能。 
   * 增强了过滤功能，包含同时过滤多个类别的功能 
   * 全屏方式显示报告内容
   * 具有“报告写入”许可权的管理员用户可以删除报告
   * 报告列表显示速度更快，可通过连续滚动以渐进方式按需装入，从而提高了总体性能。
 * 可以按需请求时间范围最长为一周，且起始时间早于请求时间最长 3 个月的安全报告。请注意，需要进行一些特定于环境的配置后，管理用户才能使用此功能。管理员用户需要具备“报告写入”许可权才能使用此功能。

### 管理控制台 4 月更新
{: #apriladminconsole}
最新更新日期：2017 年 5 月 2 日

通过 4 月的最新更新和改进，您可以使用以下新功能：

 * 新设计了 {{site.data.keyword.Bluemix_notm}} Dedicated 和 Local 环境的状态应用程序。您可以按组件名称或发布日期快速进行搜索。您还可以在组件状态发布视图和特定于环境的通知之间进行切换。有关更多信息，请参阅 [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 博客帖子。
 * 通过“资源使用情况”磁贴访问精选服务的服务使用情况数据。有关支持哪些服务以及新视图中提供的功能的更多信息，请参阅[服务使用情况详细信息](/docs/hybrid/index.html#servicesresourceusage)。

## 计算
{: #compute_category}

### buildpack 的最新更新

请访问以下页面获取最新更新的累积列表：

* [SDK for Nodejs buildpack 的最新更新](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Liberty buildpack 的最新更新](/docs/runtimes/liberty/updates.html#latest_updates)
* [ASP.NET 核心 buildpack 的最新更新](/docs/runtimes/dotnet/updates.html#latest_updates)
* [IBM XPages for {{site.data.keyword.Bluemix_notm}} buildpack 的最新更新](/docs/starters/xpages/index.html#updates)

### {{site.data.keyword.containerlong_notm}} 的最新更新

{{site.data.keyword.containerlong_notm}} 于 2017 年 5 月推出了其 Kubernetes 体系结构。先前的单个和可扩展容器组体系结构现已[完全弃用（自 2017 年 12 月 5 日开始）](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。  

[有关 {{site.data.keyword.Bluemix_notm}} 上本机 Kubernetes 环境入门的信息，请参阅相关文档](/docs/containers/container_index.html)。如果您有任何疑问，可以将问题发布到 Slack：https://ibm-container-service.slack.com/。

### 新增 Liberty for Java buildpack V3.11
最新更新日期：2017 年 7 月 17 日

Liberty buildpack V3.11 提供了新的每月 Liberty 运行时版本，并包含其他改进。每月 Liberty 运行时版本已更新为 [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) 发行版。IBM JDK 已更新为 8.0.4.7 和 7.1.4.5 版本。该 buildpack 还提供了更新版本的应用程序管理实用程序和 Auto-Scaling 代理程序。缺省的 Cloudant Library 现在是正式的 [java-cloudant](https://github.com/cloudant/java-cloudant)，[Ektorp 库](https://github.com/helun/Ektorp)仍是可用选项；有关此更改的详细信息，请参阅[博客帖子](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)。应用程序内存小于 512 MB 时，缺省堆大小比率现在是 50%。如果大于 512 MB，那么仍是 75%。现在生成了新的编译打包任务日志，这样就更容易对编译打包错误进行调试。有关其他信息，请参阅[最新更新](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html)文档。

### 新增 Liberty for Java buildpack V3.10
最新更新日期：2017 年 6 月 12 日

Liberty buildpack V3.10 提供了新的每季度和每月 Liberty 运行时版本，并包含其他改进。缺省 Liberty 运行时版本已更新为 17.0.0.2。每月 Liberty 运行时版本已更新为 [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 发行版。该 buildpack 还提供了更新版本的应用程序管理实用程序和 Extreme Scale Client。有关其他信息，请参阅[最新更新](/docs/runtimes/liberty/updates.html)文档。

### 新增 SDK for Node.js buildpack V3.12
最新更新日期：2017 年 5 月 16 日

SDK for Node.js buildpack V3.12 提供了 IBM SDK for Node.js V0.12.17、0.12.18、4.8.0、4.8.2、6.10.0 和 6.10.2。缺省值现在已经从最新 4.x 更改为最新 6.x，所以目前是 6.10.2。这是一项主版本更改，可能会影响依赖该缺省值的应用程序。有关如何避免任何问题的更多信息，请参阅 [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

除了新运行时外，此发行版还包含一个 buildpack 错误修订，用于解决使用 App Management Health Center 处理程序以及 Node.js V6.9.5 和 6.10.0 时发生的问题。

### 新增 Liberty for Java buildpack V3.9
最新更新日期：2017 年 4 月 27 日

Liberty buildpack V3.9 提供了新的每月 Liberty 运行时版本，并包含其他改进。缺省 Liberty 运行时版本已更新为包含 PI77770、PI77605、IFPI77438 和 IFPI79275 iFix。每月 Liberty 运行时版本已更新为 [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 发行版。内存计算已从编译打包移动到启动过程，这样更容易在重新启动应用程序时更改堆内存。该 buildpack 还提供了更新版本的 Auto-Scaling 服务代理程序和 Extreme Scale Client。有关其他信息，请参阅[最新更新](/docs/runtimes/liberty/updates.html)文档。

## 服务
{: #services_category}

### {{site.data.keyword.containershort_notm}}：支持 Kubernetes 1.8.x
最新更新日期：2018 年 1 月 19 日

自 2017 年 11 月开始，{{site.data.keyword.containershort_notm}} 支持 Kubernetes `1.8.x`。我们很自豪地宣布，现在 Kubernetes 的缺省版本为 `1.8.6`。在不久的将来，我们将提供对 `1.9.x` 的支持。

### Watson Discovery Visual Insights
最新更新日期：2017 年 11 月 30 日

直观地浏览基于 {{site.data.keyword.discoveryshort}} 对文本中所检测到语义元素（例如实体、关系、概念等）的理解的连接。

使用现成的 {{site.data.keyword.discoveryshort}} News 集合开始浏览全球新闻。或者在 {{site.data.keyword.discoveryshort}} 中浏览您自己的文档集合。只需使用您的 {{site.data.keyword.Bluemix_notm}} 凭证登录即可。有关更多信息，请参阅 [Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 新增 IBM Cloud Managed Database Server Beta 服务
最新更新日期：2017 年 11 月 30 日

通过新的 IBM Cloud Managed Database Server Beta 服务，可以在 {{site.data.keyword.Bluemix_notm}} 上创建 Microsoft SQL Server 实例。您可以像使用任何数据库管理系统一样来使用此 SQL Server 实例，但却没有硬件安装或软件安装与维护的工作及费用。

此服务提供以下功能：
* 可选择 Microsoft SQL Server 2012、2014 和 2016 Enterprise Edition 和 Standard Edition
* 有各种预定义配置或大小，可满足应用程序工作负载需求
* 由 IBM 完全管理，包括监视、打补丁、备份和报告

首先，请参阅 [IBM Cloud Managed Database Server 入门](/docs/services/managed-sql-server/getting-started.html)。

### {{site.data.keyword.mobilepushshort}} 中的新增内容
最新更新日期：2017 年 10 月 26 日

我们在过去几个月里对 {{site.data.keyword.mobilepushshort}} 服务做了若干改进。现在，该服务除了在达拉斯、伦敦和悉尼可用外，还在法兰克福区域可用。下面是增强功能的详细信息：

#### 监视
现在，可以跟踪特定时间段的推送通知性能，以及跟踪发送的通知数和注册的设备总数。您还可以注册 Webhook 以获得关于生命周期内所有事件的通知。更多详细信息可以在以下文档链接和博客帖子中找到：
* [监视通知](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [接收有关 Webhook 活动的警报](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")

#### Web 通知
现在，我们支持 Safari Web 浏览器获取 Web 通知以及 Firefox、Chrome、Chrome 应用和扩展程序。Web SDK 和相关信息可在 [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 上找到。

#### 最新的 Android 和 iOS 通知
我们对 iOS 11 通知提供货币支持。我们还包含了 iOS 10 和 Android N 中与通知相关的多个新的增强功能。

* iOS 10 - 在交互式通知中提供富媒体通知、图像、按钮和地图，支持本地化字符串
* Android N - 可扩展的通知、交互式和静默通知以及 LED 指示灯设置

其他详细信息可以在[富媒体通知](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications)文档、[交互式和静默通知](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications)文档以及[启用高级推送通知](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications)文档中找到。

#### APNS HTTP/2 支持
Apple 推出了对 Apple 通知的 HTTP 协议的支持。现在，{{site.data.keyword.mobilepushshort}} 服务支持 HTTP/2 协议。有了这种支持，通知有效内容可以随着吞吐量上升而达到 4 KB，另外还提供了即时反馈功能。通过支持通用证书，允许应用程序连接到沙箱和生产环境。

#### 新增轻量套餐 
{{site.data.keyword.mobilepushshort}} 服务的轻量套餐提供了每月免费发送 10 万条通知的能力。有关更多信息，请参阅 [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 博客帖子。



### Mobile Analytics 中的新增内容
最新更新日期：2017 年 10 月 26 日

我们在过去几个月里对 {{site.data.keyword.mobileanalytics_short}} 服务进行了增强。现在，该服务除了在达拉斯和伦敦可用外，还在法兰克福和悉尼区域可用。下面是增强功能的详细信息：

#### Web SDK 支持
现在，{{site.data.keyword.mobileanalytics_short}} 是全通道服务，增加了对 Web 应用程序分析的支持。更多详细信息可以在 [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 处找到。

#### 与 {{site.data.keyword.mobilefoundation_short}} 服务集成
现在，{{site.data.keyword.mobilefoundation_short}} 服务利用 {{site.data.keyword.mobileanalytics_short}} 服务进行应用程序、用户和性能分析。用户可以利用导出到 Db2 仓库的选项来构建适配器分析和定制图表。您可以在以下博客帖子中找到其他详细信息：

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")

#### 现在，{{site.data.keyword.mobilefirst_notm}} 样板包含 {{site.data.keyword.mobileanalytics_short}}
移动服务样板是一种模板，用于提供一组移动服务，供用户快速开始使用。{{site.data.keyword.mobileanalytics_short}} 服务现在是[目录](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 中可用样板的一部分。


### {{site.data.keyword.streaminganalyticsshort}} 更新
最新更新日期：2017 年 10 月 20 日

* IBM Streams Runner for Apache Beam：现在，您可以在 Streams 开发环境中本地开发 Beam 应用程序，然后将这些应用程序提交到 {{site.data.keyword.Bluemix_notm}} 中的 {{site.data.keyword.streaminganalyticsshort}} 服务。IBM Streams Runner for Apache Beam 会在 Streams 环境中执行 Beam 管道。使用 Streams Runner 启动的 Beam 应用程序会转换为 Streams 应用程序捆绑软件 (SAB) 文件，然后您可以将该文件部署在 {{site.data.keyword.streaminganalyticsshort}} 中。有关更多详细信息，请查看 [Streaming Analytics 中的 IBM Streams Runner for Apache Beam](/docs/services/StreamingAnalytics/gs_beamrunner.html)。
* 您甚至可以在日志文件中更快查找信息。控制台经过更新，改进了 Python 或 Java 拓扑的应用程序图形显示。请参阅[控制台的增强功能](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
最新更新日期：2017 年 10 月 12 日

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services 是一个试验性产品，通过提供一个平台来创建有针对性的各种受众群体互动，让您能够测量客户体验。通过 App Launch 服务，您可以深入了解作为互动结果的客户偏好和痛点，并帮助您个性化应用程序以获得更好的客户体验。

现在，应用程序所有者可以通过避免发布周期复杂性，加速向移动应用程序交付创新。App Launch 服务支持应用程序所有者通过控制目标受众，快速向移动应用程序发布功能和测量影响。应用程序所有者可以与应用程序开发者合作，为功能定义关键性能指标，测量影响以及根据实时反馈来应用功能和回滚决策。该服务还能够测试应用程序功能、用户界面组件和消息的多个变体，并根据反馈做出决策。

有关更多信息，请参阅[入门教程](/docs/services/app-launch/index.html#gettingstartedtemplate)。

### {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}} 更新
最新更新日期：2017 年 10 月 4 日

通过 {{site.data.keyword.relationshipextractionshort}} 为用户提供了新的定制功能和新的语言模型。新的语言为 WKS 支持的荷兰语、韩语和简体中文。

### {{site.data.keyword.containerlong_notm}} 集群更新
最新更新日期：2017 年 9 月 20 日

现在，您可以将集群更新到 {{site.data.keyword.Bluemix_notm}} 中最新可用版本的 Kubernetes。使用 GUI 或 CLI，将 Kubernetes 主节点和工作程序节点更新到 Kubernetes 1.7，并利用新功能和补丁。

有关更多信息，请查看 [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 新增 IBM Voice Agent with Watson 试验性服务
最新更新日期：2017 年 9 月 15 日

通过新的 {{site.data.keyword.iva_full}} 试验性服务，您可以创建基于 Watson 服务构建的认知语音代理程序，客户可以通过电话呼叫该代理程序并与之通话。通过将 Watson 人工智能应用于主干，语音代理程序能以对话方式进行通信，并在语音代理程序内处理复杂的交互和处理客户呼叫。

{{site.data.keyword.iva_short}} 可无缝连接到 Watson {{site.data.keyword.speechtotextshort}}、{{site.data.keyword.conversationshort}} 和 {{site.data.keyword.texttospeechshort}} 服务并对其进行编排，以模拟自然语言对话。每个语音代理程序会自动扩展以同时处理多个呼叫。在此试验版本中，您可以使用以下主要功能来定制语音代理程序：

* 首先导入样本 {{site.data.keyword.conversationshort}} 对话，然后创建自己的对话来满足您公司的需求。
* 使用 API 从 {{site.data.keyword.conversationshort}} 服务内对语音代理程序行为编程。您可以控制对话中任意节点的一切行为，从打断行为到挂断呼叫。
* 如果要将不同的电话号码连接到针对不同主题专门设计的认知代理程序，可轻松创建和管理多个语音代理程序。
* 通过连接服务编排引擎 (SOE) 来扩展服务的功能，以便可以使用第三方 API。例如，SOE 可以侦听来自 {{site.data.keyword.conversationshort}} 服务的触发器，然后使用您提供的 API 在现有系统中查找信息或提供其他分析。

首先，请参阅 [{{site.data.keyword.iva_short}} 入门](/docs/services/voice-agent/getting-started.html)文档。


### {{site.data.keyword.streaminganalyticsshort}} 服务更新：控制台包含用于查明应用程序中问题的新方法
最新更新日期：2017 年 8 月 14 日
 
对于 Python 和 Java 应用程序，源文件位置根据 @spl_note 注释显示。 
 
有关详细信息，请参阅 [{{site.data.keyword.streaminganalyticsshort}}的最新改进](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 现在，IBM Cloud Monitoring 还在英国区域可用
最新更新日期：2017 年 8 月 1 日

使用 {{site.data.keyword.monitoringlong}} 服务可在 {{site.data.keyword.Bluemix_notm}} 中使用度量值时，扩展收集、保留和分析功能。 

* 提醒执行操作！{{site.data.keyword.monitoringlong}} 提供了一个可用于设置性能阈值并在违反这些阈值时收到通知的 API。定义针对单个服务实例或应用程序实例的警报规则，也可定义针对一组实例进行报告的警报规则。触发警报时，可通过电子邮件、PagerDuty 事件、Webhook 通知或这三者的任意组合来获得通知。

* 添加定制度量值。{{site.data.keyword.monitoringlong}} 高级套餐提供了可用于向 Cloud Monitoring 数据添加相关应用程序和业务度量值的 API。您还可以使用这些 API 将 {{site.data.keyword.IBM_notm}} Cloud 外部的度量值数据发送到 {{site.data.keyword.monitoringlong}} 服务中。

* 构建可复用的仪表板并将其设置为交互式。{{site.data.keyword.monitoringlong}} 的托管 Grafana 支持使用大量可视化选项来构建定制仪表板。通过将度量值查询与变量一起使用来生成模板，可使仪表板动态变化。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}}“目录”的 DevOps 部分中作为服务磁贴提供。对于使用单个容器和容器组的 {{site.data.keyword.containershort}} 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问该服务。

* 选择适合您需要的服务套餐。您可根据自己的使用量需要，选择轻量服务套餐或高级服务套餐。轻量套餐每分钟收集一次度量值，保留时间为 15 天，并免费发出警报。或者，可以选择高级套餐来启用更多使用量、更长度量值保留时间，并获取对服务 API 的访问权，例如通过 {{site.data.keyword.monitoringlong}} 服务发送或检索度量值。{{site.data.keyword.monitoringlong}} 每分钟收集一次度量值。轻量套餐会将完整分辨率的度量值保留 15 天。高级套餐会将完整分辨率的度量值保留 45 天。

旧 {{site.data.keyword.monitoringshort}} 服务按服务定义的频率收集度量值，一开始的频率为 30 秒，在一段时间后将度量值汇总到 1 小时频率。现在，{{site.data.keyword.monitoringlong}} 提供每分钟执行一次的完整分辨率收集。轻量套餐会将度量值保留 15 天。高端套餐会将度量值保留 45 天。

有关 {{site.data.keyword.monitoringlong}} 服务的更多信息，请参阅 [Monitoring 入门文档](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - Service Refresh with New Features ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。


### 现在，IBM Cloud Log Analysis 在美国南部区域可用
最新更新日期：2017 年 7 月 31 日

{{site.data.keyword.loganalysisfull}} 服务为 {{site.data.keyword.Bluemix_notm}} 平台提供了日志收集和日志搜索服务，会自动从所选 {{site.data.keyword.Bluemix_notm}} 服务收集应用程序和 {{site.data.keyword.Bluemix_notm}} 服务的数据。使用 {{site.data.keyword.loganalysisshort}} 服务可实现：

* 根据需要使日志保留任意长的时间。  

    日志存储在 IBM Cloud 存储器中。您可以在需要时下载日志。
	
* 使用新的 API 来管理保留的日志，以及从 {{site.data.keyword.IBM_notm}} Cloud 外部发送日志数据。

* 选择每天可以搜索的日志量。  

    提供了不同的套餐，分别可用于每天搜索最多 500MB、2GB、5GB 和 10GB 的日志。

* 构建可复用的仪表板并将其设置为交互式。 

    {{site.data.keyword.loganalysisshort}} 的托管 Kibana 支持构建定制仪表板。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。  

    对于使用单个容器和容器组的 {{site.data.keyword.loganalysisshort}} 服务以及对于 {{site.data.keyword.IBM_notm}} Cloud Foundry 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问服务。

有关 {{site.data.keyword.loganalysisshort}} 服务的更多信息，请参阅 [{{site.data.keyword.loganalysisfull}} 入门](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis)和 [{{site.data.keyword.loganalysisshort}} 概述](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov)。

### IBM dashDB for Analytics 已重命名
最新更新日期：2017 年 7 月 18 日

下表汇总了新名称：

| 先前名称                    | 新名称                     | 生效日期       |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 2017 年 7 月 18 日|
{: caption="表 1. 服务名称更改" caption-side="top"}
 
有关 Db2 Warehouse on Cloud 和 Db2 on Cloud 更新的累积列表，请参阅：[What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。 

### 现在，IBM Cloud Monitoring 在美国南部区域可用
最新更新日期：2017 年 7 月 17 日

使用 {{site.data.keyword.monitoringlong}} 服务可在 {{site.data.keyword.Bluemix_notm}} 中使用度量值时，扩展收集、保留和分析功能。 

* 提醒执行操作！{{site.data.keyword.monitoringlong}} 提供了一个可用于设置性能阈值并在违反这些阈值时收到通知的 API。定义针对单个服务实例或应用程序实例的警报规则，也可定义针对一组实例进行报告的警报规则。触发警报时，可通过电子邮件、PagerDuty 事件、Webhook 通知或这三者的任意组合来获得通知。

* 添加定制度量值。{{site.data.keyword.monitoringlong}} 高级套餐提供了可用于向 Cloud Monitoring 数据添加相关应用程序和业务度量值的 API。您还可以使用这些 API 将 {{site.data.keyword.IBM_notm}} Cloud 外部的度量值数据发送到 {{site.data.keyword.monitoringlong}} 服务中。

* 构建可复用的仪表板并将其设置为交互式。{{site.data.keyword.monitoringlong}} 的托管 Grafana 支持使用大量可视化选项来构建定制仪表板。通过将度量值查询与变量一起使用来生成模板，可使仪表板动态变化。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}}“目录”的 DevOps 部分中作为服务磁贴提供。对于使用单个容器和容器组的 {{site.data.keyword.containershort}} 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问该服务。

* 选择适合您需要的服务套餐。您可根据自己的使用量需要，选择轻量服务套餐或高级服务套餐。轻量套餐每分钟收集一次度量值，保留时间为 15 天，并免费发出警报。或者，可以选择高级套餐来启用更多使用量、更长度量值保留时间，并获取对服务 API 的访问权，例如通过 {{site.data.keyword.monitoringlong}} 服务发送或检索度量值。{{site.data.keyword.monitoringlong}} 每分钟收集一次度量值。轻量套餐会将完整分辨率的度量值保留 15 天。高级套餐会将完整分辨率的度量值保留 45 天。

旧 {{site.data.keyword.monitoringshort}} 服务按服务定义的频率收集度量值，一开始的频率为 30 秒，在一段时间后将度量值汇总到 1 小时频率。现在，{{site.data.keyword.monitoringlong}} 提供每分钟执行一次的完整分辨率收集。轻量套餐会将度量值保留 15 天。高端套餐会将度量值保留 45 天。

有关 {{site.data.keyword.monitoringlong}} 服务的更多信息，请参阅 [Monitoring 入门文档](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - Service Refresh with New Features ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。

### {{site.data.keyword.contdelivery_short}} 升级
最新更新日期：2017 年 7 月 11 日

升级的优点包括错误修订、性能改进以及对用户体验的优化。值得注意的增强功能（如果尚未在您的环境中提供）包括：
<ul>
<li>修复和改进国际化和辅助功能。</li>
<li>工具链访问控制，通过工具链的“管理”选项卡提供。</li>
<li>Continuous Delivery 工具目录中新的工具集成。</li>
<li>改进了 Orion Web IDE 中多个工作空间的分组。</li>
<li>支持 Orion Web IDE 中的多个编辑器选项卡。</li>
<li>支持 Orion Web IDE 中的 UI 主题。</li>
</ul>

### {{site.data.keyword.uccr_short}} Beta 
最新更新日期：2017 年 6 月 23 日

{{site.data.keyword.uccr_short}} 是一种企业级发布管理解决方案，同时支持云本机和内部部署工具。

Beta 版本的 {{site.data.keyword.uccr_short}} 提供以下主要功能：
* 使用发布来管理多个部署计划和事件，并协作完成多团队发布工作。
* 为任何与发布相关的活动创建事件，并使用日历对其进行管理。
* 导入您自己的事件和发布。
* 定制日历事件以满足您组织的需求。
* 将电子邮件和 Slack 类型的任务用于发布通知。

### dashDB for Transactions 已重命名为 {{site.data.keyword.DB2_on_Cloud_short}}
最新更新日期：2017 年 6 月 14 日

IBM {{site.data.keyword.DB2OnCloud_short}} 是 dashDB for Transactions 的新名称。作为此重命名的一部分，原先自行管理的 IBM {{site.data.keyword.DB2OnCloud_short}} 服务还将重命名为 IBM Db2 Hosted。目前只更新了显示名称，所以任何 API 或命令行界面均保持不变。

### {{site.data.keyword.sparks}} 更新：Stocator-S3 连接器支持 IBM Cloud Object Storage Cross Region 服务 (Beta)
最新更新日期：2017 年 6 月 5 日

现在，{{site.data.keyword.sparks}} 用户可以访问存储在 IBM Cloud Object Storage Cross Region 服务中的数据并对其进行分析。此功能作为 Beta 版提供。IBM Cloud Object Storage 为分析和其他应用程序提供高容量、经济高效的存储，可扩展、非常灵活且易于使用。

Apache Spark 通过基于 Stocator 技术的存储连接器来访问 IBM Cloud Object Storage 数据，这种存储连接器隐式设计用于对象存储，因此比旧的对象存储连接器速度更快。作为用户，您无需更改或重新编译 Apache Spark 代码。

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 博客帖子描述了在 {{site.data.keyword.Bluemix_notm}} 和 IBM Data Science Experience (DSx) 上将 IBM Cloud Object Storage 数据用于 {{site.data.keyword.sparks}} 的情况。

如果您有任何问题或意见，请通过 [sparksrv@us.ibm.com](sparksrv@us.ibm.com) 与我们联系。非常感谢您提供的信息！

### 新增可用于 {{site.data.keyword.dashdbshort_notm}} for Transactions 的可扩展套餐
最新更新日期：2017 年 5 月 31 日

针对 {{site.data.keyword.dashdbshort}} for Transactions 提供了新套餐，此套餐可以随您的数据库需求而增长。新的 Flex 套餐支持您一开始使用小型系统，然后轻松、快速地增加该系统的能力和存储容量。在高可用性套餐上，{{site.data.keyword.dashdbshort}} for Transactions 与 Db2 100% 兼容并提供 99.95% 的 SLA。

### {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服务的新更新
最新更新日期：2017 年 5 月 24 日

下面是可用于 {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服务的新更新。

**轻量套餐**：除了 {{site.data.keyword.mobilepush}} 服务的现有基本套餐外，我们还推出了新的轻量套餐。根据新套餐，用户每个月可以免费发送多达十万条数字消息。从轻量套餐升级到基本套餐后，发送的数字消息超过 100 万条（此计数不算轻量套餐使用量）后，将向用户收取相应费用。

**监视**：现在，您可以深入了解 {{site.data.keyword.mobilepush}} 服务控制台中所发送的通知和注册的设备。您还可以使用 REST API 进行消息级别跟踪。从消息传递到消息分派再到消息接收，可以通过配置 Webhook 来获取详细信息。请参阅[监视 {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications)。

**Web 通知**：现在，您可以将通知发送到 Safari Web 浏览器。

### Secure Gateway 更新
最新更新日期：2017 年 5 月 24 日

最新的 Secure Gateway 维护更新包含 UI 和 API 管理器中的小错误修订以及更新的文档，并且客户机已经更新到 V1.7.1。现在，Secure Gateway 客户机在 AIX 7.1+ 上可用，并且支持通过 squid 代理进行出站连接。

### {{site.data.keyword.streaminganalyticsshort}} 服务更新：在 Python 开发环境中开发 Streams 应用程序
最新更新日期：2017 年 4 月 13 日

过去，您必须安装本地版本的 IBM Streams 来开发 Python 应用程序。现在不必再如此。您现在可以在自己最喜爱的开发环境或 Jupyter 交互式配置页中使用 Python 来开发应用程序。

您可以使用 STREAMING_ANALYTICS_SERVICE 上下文将 Python 应用程序提交给 {{site.data.keyword.streaminganalyticsshort}} 服务。{{site.data.keyword.streaminganalyticsshort}} 服务需要 Python 3.5。

您可以使用 IBM Data Science Experience (DSX) 中的 Jupyter 配置页来创建样本 Python 应用程序，然后将这些应用程序直接从 DSX 提交到 {{site.data.keyword.streaminganalyticsshort}} 实例。请在 [DSX 社区页面](https://datascience.ibm.com/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 上查看配置页中的样本流处理 Python 应用程序。

有关 {{site.data.keyword.streaminganalyticsshort}} 服务更新的更多信息，请参阅 [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.sparks}} 更新：现在支持 Apache Spark 2.1
最新更新日期：2017 年 4 月 21 日

{{site.data.keyword.sparkl}} 将引入对 Apache Spark 2.1 的支持，以创建利用基于复杂数据的洞察的算法。Apache Spark 2.1 增加了对事件时间水印和 Kafka 0.10 的支持，将对结构化流处理十分有利。Apache Spark 2.1 还专注于提高 Spark SQL、SparkR 和 MLlib 模块的稳定性和可用性。有关 Spark 2.1 的更多详细信息，请参阅 [Spark R2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html)。

我们很乐意回答与 {{site.data.keyword.sparkl}} 或 Apache Spark 2.1 更高版本相关的任何问题，您可通过 sparksrv@us.ibm.com 与我们联系。 

### 不推荐使用 {{site.data.keyword.macm_short}}
最新更新日期：2017 年 4 月 18 日

自 2017 年 3 月 30 日开始，{{site.data.keyword.macm_long}} 服务磁贴将从 {{site.data.keyword.Bluemix_notm}}“目录”中除去，您无法再供应新的 MACM 实例。不过，仍将继续支持现有实例。支持结束日期为 2018 年 3 月 30 日。请在支持结束日期前删除 {{site.data.keyword.macm_short}} (MACM) 服务实例。我们鼓励用户迁移到 IBM Watson Content Hub。Watson Content Hub 在 IBM Marketplace 上提供，为用户提供 30 天的免费试用。IBM Watson Content Hub 将提供与 MACM 类似的功能，但新增了资产管理、使用 IBM Watson 服务的认知标记以及随附内容交付网络 (CDN) 等新功能，以确保为您的客户提供最佳体验。IBM 提供了服务互动，可将内容从 MACM 迁移到 Watson Content Hub。

### {{site.data.keyword.streaminganalyticsshort}} 服务更新：在 Python 开发环境中开发 Streams 应用程序
最新更新日期：2017 年 4 月 13 日

过去，您必须安装本地版本的 IBM Streams 来开发 Python 应用程序。现在不必再如此。您现在可以在自己最喜爱的开发环境或 Jupyter 交互式配置页中使用 Python 来开发应用程序。

您可以使用 STREAMING_ANALYTICS_SERVICE 上下文将 Python 应用程序提交给 {{site.data.keyword.streaminganalyticsshort}} 服务。{{site.data.keyword.streaminganalyticsshort}} 服务需要 Python 3.5。

请在 [IBM Data Science Experience 社区页面](http://datascience.ibm.com){: new_window} ![外部链接图标](../icons/launch-glyph.svg " 外部链接图标 ") 上查看配置页中的样本流处理 Python 应用程序。 

### {{site.data.keyword.sparks}} 更新：Data Science Experience 中现在支持配置页
最新更新日期：2017 年 4 月 11 日

您的新平台可使用配置页，并且 Spark 已更名为 Data Science Experience。注册 [Data Science Experience](http://datascience.ibm.com/)，然后开始创建配置页，并与其他数据研究员共享您的专业知识。

如果使用的是 {{site.data.keyword.sparks}} 中的配置页，那么可以将配置页迁移到 Data Science Experience。有关更多信息，请参阅[迁移配置页文档](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx)。
