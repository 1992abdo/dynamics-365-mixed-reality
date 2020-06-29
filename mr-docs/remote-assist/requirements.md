---
author: sophiasysun
description:  Technical requirements for deploying and using Microsoft Dynamics 365 Remote Assist
ms.author: sopsun
ms.date: 05/27/2020
ms.service: crm-online
ms.topic: article
title: Requirements for Dynamics 365 Remote Assist
ms.reviewer: krbjoran
---

# Technical requirements for deploying and using Dynamics 365 Remote Assist

The following tables list technical requirements for deploying and using Microsoft Dynamics 365 Remote Assist.

## Device requirements

A Remote Assist call is between a Remote Assist user and a Microsoft Teams user.

Remote Assist is available on HoloLens, HoloLens 2, and qualifying Android or iOS mobile devices.

To collaborate with a Remote Assist user, a Microsoft Teams user may only use the Teams application on Windows 10 PC or mobile devices.

### Device options and requirements for a Remote Assist user

| Device                                   | OS requirements                                                                                                                                                                                                          | Details                                                                                                                                                                                                                  |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Remote Assist on HoloLens or HoloLens 2 | HoloLens or HoloLens 2 running 10.0.17134.0 (that is, Windows 10 April 2018) build or later. We recommend [updating](https://docs.microsoft.com/hololens/hololens-updates) HoloLens to newer versions when available. | See [Manage updates to HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) for instructions on using Windows Update for Business, Mobile Device Management (MDM), and Windows Server Update Services (WSUS). |
| Remote Assist on mobile devices          | Dynamics 365 Remote Assist mobile is available on all devices, including ARCore-enabled Android phones or tablets, ARKit-enabled iOS iPhones or iPads, and mobile devices without AR support.                                                                               | These are the lists of AR-supported devices on [Android](https://developers.google.com/ar/discover/supported-devices) and [iOS](https://developers.google.com/ar/discover/supported-devices#ios). For more details on how to use Remote Assist on devices without AR support, see the documentation [here](mobile-app/using-devices-without-AR.md).                                         |

### Device options and requirements for a remote collaborator using Teams

| Device                             | OS requirements                                             | Details                                                                                                                                                                                                                                                                                 |
| ---------------------------------- | ----------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Teams application on Windows 10 PC | Any Windows 10 build.                                       | A Windows 10 PC running the Teams PC application can collaborate with Remote Assist on HoloLens, HoloLens 2, or qualifying [Android](https://developers.google.com/ar/discover/supported-devices) or [iOS](https://www.apple.com/ios/augmented-reality/) mobile devices.                |
| Teams application on mobile device | Any iOS or Android phone or tablet running  Teams. | A phone or tablet running the Teams mobile application can collaborate with Remote Assist on HoloLens, HoloLens 2, or qualifying [Android](https://developers.google.com/ar/discover/supported-devices) or [iOS](https://www.apple.com/ios/augmented-reality/) mobile devices. |

## Licensing and product requirements per role

| Role                                       | Software needed                                                                                                                                                                             |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Administrator                              | - [Azure Active Directory (AAD)](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis) account to assign licenses in M365 Admin portal and distribute applications through Microsoft Store for Business. Learn more about how to deploy Remote Assist [here](https:/docs.microsoft.com/dynamics365/mixed-reality/remote-assist/deploy-remote-assist).                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Dynamics 365 Remote Assist user            | - [Azure Active Directory (AAD)](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis) account  </br> - Teams license\*\*  </br> - OneDrive for business\*\* </br> - Remote Assist license  </br> - Remote Assist application on HoloLens, HoloLens 2, or qualifying [Android](https://developers.google.com/ar/discover/supported-devices) or [iOS](https://www.apple.com/ios/augmented-reality/) device  </br> - (Optional) Dynamics 365 Field Service license\*\*\*\*  </br> -  (Optional) Power BI license\*\*\*\*\*                                                                                                                                                                                                                                                                                                                             |
| Remote collaborator (Uses Microsoft Teams) | - [Azure Active Directory (AAD)](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis) account  </br> - Teams license\*\*\* </br> - OneDrive for business\*\*\* </br> - Teams application on Windows 10 PC or mobile devices </br></br> Note: It is possible to use Teams to communicate with a Remote Assist user without acquiring a Teams license. Teams supports [guest access](https://docs.microsoft.com/MicrosoftTeams/guest-access), which lets an organization add individual users from outside their organization into their teams and channels. Anyone with a business or consumer email account, such as Outlook, Gmail, or others, can use Teams as a guest in another organization's tenant. </br></br> Note: The remote collaborator can use Teams for free, which offers [limited functionality](https://docs.microsoft.com/microsoftteams/upgrade-freemium#how-does-teams-free-compare-to-the-full-version-of-teams).

\*\*The Teams license that is included with a Remote Assist license enables Remote Assist users to join a Remote Assist call, use mixed reality annotations, and use most Remote Assist features. However, some features, such as sharing files from OneDrive and saving snapshots to OneDrive, require the Remote Assist user to have a [OneDrive for Business](https://products.office.com/onedrive/onedrive-for-business) license. To use all Remote Assist features, a Remote Assist user may, for example, use the Teams license, [Microsoft Stream license](https://docs.microsoft.com/microsoftteams/cloud-recording#prerequisites-for-teams-cloud-meeting-recording), and OneDrive for Business license that are included with [Office 365 Business Premium or Office 365 Business Essentials](https://products.office.com/en-us/compare-all-microsoft-office-products?&activetab=tab:primaryr2).

\*\*\*A Teams license enables remote collaborators to join a Remote Assist call, use mixed reality annotations, and use other features. However, some features, such as sharing files from OneDrive, require the Teams user to have a [OneDrive for Business](https://products.office.com/onedrive/onedrive-for-business) license. To use all features in a Remote Assist call, a Teams user may, for example, use the Teams license, [Microsoft Stream license](https://docs.microsoft.com/microsoftteams/cloud-recording#prerequisites-for-teams-cloud-meeting-recording), and OneDrive for Business license that are included with [Office 365 Business Premium or Office 365 Business Essentials](https://products.office.com/compare-all-microsoft-office-products?&activetab=tab:primaryr2).

\*\*\*\*To use Remote Assist to view Dynamics 365 Field Service bookings, users will also need a Field Service license (version 8.2 or later). [Learn more about Dynamics 365 Field Service](https://dynamics.microsoft.com/field-service/overview/).

\*\*\*\*\*To use Remote Assist to open Power BI dashboards linked to Dynamics 365 Field Service bookings, users will also need a Power BI license. [Learn more about Power BI.](https://powerbi.microsoft.com/)

## Network requirements

A variety of network conditions, including bandwidth, latency, jitter, and packet loss, can impact your video calling experience. Although audio and video calls might be possible in environments with reduced bandwidth, you might experience feature degradation.

In most circumstances:

-   [1.5Mbps up/down is required](https://docs.microsoft.com/MicrosoftTeams/prepare-network#bandwidth-requirements).
-   When more bandwidth is available, quality and usage will increase to deliver the best experience.
-   4-5Mbps up/down is required for peer-to-peer HD quality video calling with resolution of HD 1080p.

However, in some circumstances, even 4-5Mbps up/down does not guarantee 1080p video calling at full quality. Circumstances include using HoloLens (1st gen).

You can use Remote Assist on mobile devices in low-bandwidth environments between 150 kbps and 1.5 Mbps. For more information, see the [low bandwidth documentation](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/mobile-app/poor-network-connectivity).

### Network optimization recommendations

The following tasks serve as a checklist for other potential optimizations for Remote Assist:

- [Monitor your network using CQD and call analytics](https://docs.microsoft.com/MicrosoftTeams/prepare-network#best-practice-monitor-your-network-using-cqd-and-call-analytics).
- Review Teams' recommendations [for optimizing your network](https://docs.microsoft.com/MicrosoftTeams/prepare-network#network-optimization).
- Be on a dedicated SSID. The dedicated SSID should be on the 5-Ghz band only; disable 2.4 Ghz.
- Use a router with MU-MIMO capabilities.

### Additional resources

- Learn how to troubleshoot and address internal infrastructure issues using [Teams Call Analytics](https://docs.microsoft.com/MicrosoftTeams/use-call-analytics-to-troubleshoot-poor-call-quality#troubleshoot-call-quality-problems-using-call-analytics) or [Teams Call Quality Dashboard (CQD)](https://docs.microsoft.com/MicrosoftTeams/quality-of-experience-review-guide).

- See [Prepare your organization's network for Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/prepare-network) to learn more.

## See also

- [Overview of Dynamics 365 Remote Assist](ra-overview.md)
- [Try Dynamics 365 Remote Assist for free](try-remote-assist.md)
- [Buy Dynamics 365 Remote Assist](deploy-remote-assist.md)
- [Using Remote Assist on HoloLens](overview-hololens.md)
- [Set up and use Microsoft Teams with Dynamics 365 Remote Assist](teams-pc-all.md)
- [How-to videos](videos.md)
- [FAQ](faq.md)
