---
title: 关于团队讨论
intro: 您的团队可以共同计划、互相更新，或者在组织中团队页面的讨论帖子中讨论任何主题。
redirect_from:
  - /articles/about-team-discussions
  - /github/building-a-strong-community/about-team-discussions
  - /github/setting-up-and-managing-organizations-and-teams/about-team-discussions
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Community
---

{% data reusables.organizations.team-discussions-purpose %}

任何组织成员都可以在团队的页面上发帖或参与公共讨论。 {% data reusables.organizations.team-discussions-permissions %}

![具有公共和私人讨论的团队页面的讨论选项卡](/assets/images/help/organizations/team-page-discussions-tab.png)

您可以在其他位置链接到任何团队讨论以引用它。 您可以将重要帖子嵌入到团队页面，便于以后快速参考。 更多信息请参阅“[嵌入团队讨论](/organizations/collaborating-with-your-team/pinning-a-team-discussion)”。

![具有嵌入讨论的团队页面的嵌入讨论选项卡](/assets/images/help/organizations/team-discussions-pinned.png)

{% data reusables.organizations.team-discussions-default %} 所有者可对整个组织禁用团队讨论。 更多信息请参阅“[对组织禁用团队讨论](/articles/disabling-team-discussions-for-your-organization)”。

## 团队讨论通知

当有人在团队页面上发帖或回复公共讨论时，团队成员和任何子团队的成员都会收到电子邮件或 web 通知。 当有人在团队页面上对私人讨论发帧或回复时，只有团队成员才会收到通知。

{% tip %}

**提示：**根据通知设置，您将通过电子邮件和/或 {% data variables.product.product_name %} 上的 web 通知页面收到更新。 更多信息请参阅{% ifversion fpt or ghae or ghes or ghec %}“[配置通知](/github/managing-subscriptions-and-notifications-on-github/configuring-notifications){% else %}“[关于电子邮件通知](/github/receiving-notifications-about-activity-on-github/about-email-notifications)”和“[关于 web 通知](/github/receiving-notifications-about-activity-on-github/about-web-notifications){% endif %}”。

{% endtip %}

默认情况下，如果团队讨论中提及您的用户名，则对于提及您的用户名的帖子，您将收到其通知以及所有回复。 此外，默认情况下，如果您回复帖子，该帖子有其他回复您也会收到通知。

要关闭团队讨论的通知，您可以取消订阅特定的讨论帖子，或者更改通知设置，以取消关注或完全忽略特定团队的讨论。 即使您取消关注团队的讨论，也可订阅特定讨论帖子的通知。

更多信息请参阅{% ifversion fpt or ghae or ghes or ghec %}“[查看您的订阅](/github/managing-subscriptions-and-notifications-on-github/viewing-your-subscriptions){% else %}“[订阅和退订通知](/github/receiving-notifications-about-activity-on-github/subscribing-to-and-unsubscribing-from-notifications){% endif %}”和“[嵌套的团队](/articles/about-teams/#nested-teams)”。

{% ifversion fpt or ghec %}

## 组织讨论

您还可以使用组织讨论来促进整个组织的对话。 更多信息请参阅“[为组织启用或禁用 GitHub Discussions](/organizations/managing-organization-settings/enabling-or-disabling-github-discussions-for-an-organization)”。

{% endif %}

## 延伸阅读

- "[{% data variables.product.prodname_dotcom %} 通信快速入门](/github/collaborating-with-issues-and-pull-requests/quickstart-for-communicating-on-github)"
- "[关于团队](/articles/about-teams)"
- "[创建团队讨论](/organizations/collaborating-with-your-team/creating-a-team-discussion)"
- "[编辑或删除团队讨论](/organizations/collaborating-with-your-team/editing-or-deleting-a-team-discussion)"
