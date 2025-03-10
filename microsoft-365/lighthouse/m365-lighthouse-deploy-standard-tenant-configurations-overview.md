---
title: "Overview of using baselines to deploy standard tenant configurations"
f1.keywords: CSH
ms.author: sharik
author: SKjerland
manager: scotv
audience: Admin
ms.topic: article
ms.prod: microsoft-365-lighthouse
ms.localizationpriority: medium
ms.collection:
- M365-subscription-management
- Adm_O365
ms.custom:
- AdminSurgePortfolio
- M365-Lighthouse                         
search.appverid: MET150
description: "For Managed Service Providers (MSPs) using Microsoft 365 Lighthouse, learn about using baselines to deploy standard tenant configurations."
---

# Overview of using baselines to deploy standard tenant configurations 

> [!NOTE]
> The features described in this article are in Preview, are subject to change, and are only available to partners who meet the [requirements](m365-lighthouse-requirements.md). If your organization does not have Microsoft 365 Lighthouse, see [Sign up for Microsoft 365 Lighthouse](m365-lighthouse-sign-up.md).

Microsoft 365 Lighthouse baselines provide a repeatable and scalable way for you to assess and manage Microsoft 365 security settings across multiple customer tenants. Baselines also help monitor core security policies and tenant compliance standards with configurations that secure users, devices, and data.

Designed to help partners enable customer adoption of security at their own pace, Lighthouse provides a standard set of baseline parameters and pre-defined configurations for Microsoft 365 services. These security configurations help measure your tenants' Microsoft 365 security and compliance progress.

You can view the default baseline and its deployment steps from within Lighthouse. To apply baselines to a tenant, select **Tenants** in the left navigation pane, and then select a tenant. Next, go to the **Deployment plans** tab and implement the desired baseline.

## Standard baseline security templates

Lighthouse standard baseline configurations for security workloads are designed to help all managed tenants reach an acceptable state of security coverage and compliance.

The baseline configurations in the following table come standard with the Lighthouse default baseline.<br><br>

| Baseline configuration | Description |
|--|--|
| Require MFA for admins | A Conditional Access policy requiring multifactor authentication for admins. It's required for all cloud applications. |
| Require MFA for end users | A Conditional Access policy that requires multifactor authentication for users. It's required for all cloud applications. |
| Block legacy authentication | A Conditional Access policy to block legacy client authentication. |
| Set up device enrollment | Device enrollment to allow your tenant devices to enroll in Microsoft Endpoint Manager. This is done by setting up Auto Enrollment between Azure Active Directory and Microsoft Endpoint Manager. |
| Configure Microsoft Defender Antivirus for Windows 10 and later | A Device Configuration profile for Windows devices with pre-configured Microsoft Defender Antivirus settings. |
| Configure a device compliance policy for Windows 10 and later | A Windows device policy with pre-configured settings to meet basic compliance requirements. |

## Related content

[Deploy Microsoft 365 Lighthouse baselines](m365-lighthouse-deploy-baselines.md) (article)\
[Microsoft 365 Lighthouse FAQ](m365-lighthouse-faq.yml) (article)
