---
title: Deploy Dynamics 365 Remote Assist
author: xonatia
description: Remote Assist users can deploy and set up Remote Assist on their devices. 
ms.author: xolee
ms.date: 02/27/2020
ms.service: crm-online
ms.topic: article
ms.reviewer: krbjoran
---
# Deploy Dynamics 365 Remote Assist

Once you have either a [trial](try-remote-assist.md) or have [purchased](buy-remote-assist.md) for Dynamics 365 Remote Assist, you can assign licenses to users. Once assigned, users can deploy Remote Assist on their individual devices.

> [!NOTE]
> There are two types of users for Remote Assist and Remote Assist Attach: remote experts and field service technicians. Field service technicians require a Remote Assist **and** a Microsoft Teams license. When you buy Remote Assist licenses, Micrsoft Teams licenses are included. However, remote experts (who aren't in the field) require only a Microsoft Teams license. For more information, visit the article on [deploying Microsoft Teams licenses in your organization](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/use-microsoft-teams-with-remote-assist).

In this article, we’ll walk through how to deploy Remote Assist or Remote Assist Attach (for Field Service customers): 
-	Assign licenses to users in your organization (for IT Admins)
-	Deploying Remote Assist on your device (for individuals in your organization) 

## Add and assign licenses

### Prerequisites 
- Your organization must have a Microsoft 365 or Office 365 [administrator account](https://www.microsoft.com/microsoft-365/business/office-365-administration). For more information, [learn more about admin permission](https://docs.microsoft.com/office365/admin/admin-overview/admin-overview?redirectSourcePath=%252farticle%252foffice-365-admin-overview-c7228a3e-061f-4575-b1ef-adf1d1669870&view=o365-worldwide). 
- You'll need either a free trial of Remote Assist, or have purchased licenses. Visit our articles on [free trials](try-remote-assist.md) and [buying Remote Assist](buy-remote-assist.md) for more information.
- Make sure that users in your organization have the required licensing and devices. For more information, visit the article on [licensing and product requirement](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/requirements).


### Adding and assigning licenses
Once prerequisites are met, you can now add and assign licenses to *individual users* or a *group of users* in your organization through the Microsoft 365 or Office 365 administrator portal. 

1.	Log into the [Microsoft 365 or Office 365 administrator portal](https://www.microsoft.com/microsoft-365/business/office-365-administration ) using your organization’s admin account.
![Screenshot of the admin portal.](./media/buy_1.png "Admin Portal")

2.	Make sure the **Try the new admin center** toggle is turned off.

3.	In the left navigation bar, select **Billing** > **Subscriptions**. 

![Screenshot showing billing subscriptions](./media/deploy_3.png "Billing subscriptions")

4.	Select **Assign to users**. 
![Screenshot showing assigning users](./media/deploy_4.png "Assign users")

1. Select **Add a user**. For more information, visit the [Office 365 article on adding users](https://docs.microsoft.com/office365/admin/add-users/add-users?view=o365-worldwide). You can find more information about adding users].

6.	Find the users in your organization that you want to add; make sure to provide them with Dynamics 365 Remote Assist and Microsoft Teams licenses under the **Product licenses** section. 

![Screenshot of product licenses](./media/deploy_6.png "Product licenses")

7. To add multiple users, go to **More** > **Import multiple users**. Fill out the CSV file, set user options, and view your results. 
![Screenshot of adding multiple users.](./media/deploy_7.png "Add multiple users")

8.	After you have added a user or users, you can now assign licenses to them through the Microsoft 365 or Office 365 administrator portal. Visit [this Office 365 article for instructions](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users?view=o365-worldwide).

Users in your organization can now set up Remote Assist on their devices! Let's see how. 


## Deploying on your devices

After sorting out your licenses, users can setup and use the app on their HoloLens 1, HoloLens 2, or mobile devices. 

### Prerequisites
- Your organization's IT admin must add you as a user and assign you a Remote Assist license **and** Microsoft Teams license in the Microsoft 365 or Office 365 administrator portal, as described in this article's first section. 
- A [Microsoft Teams account](https://teams.microsoft.com/start). Visit our topic on [using Teams with Remote Assist](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/use-microsoft-teams-with-remote-assist) for more information. 
- Azure Active Directory [Premium Trial](https://azure.microsoft.com/trial/get-started-active-directory/) (for HoloLens users only)
- A HoloLens 1, HoloLens 2, or mobile device. Licensing and product requirements can be found [here](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/requirements).



### Steps for HoloLens 1 and 2
1.	Go to the **Start** menu and then select **Microsoft Store**. 
2.	Search for and download **Dynamics 365 Remote Assist** and launch the app.
3.	Sign into Remote Assist with your Microsoft Teams account. 
4.	You'll be taken to your Contacts page. Note that if you're using a free trial, you'll be prompted to start your **Free Trial of Dynamics 365 Remote Assist**. 
5.	You can now use Dynamics 365 Remote Assist on your HoloLens 1 or 2! 

### Steps for mobile devices
1.	Go to the appropriate iOS and Android app store.
2.	Search for and download **Dynamics 365 Remote Assist** and launch the app.
3.	Sign into Remote Assist with your Microsoft Teams account. 
4.	You'll be taken to your Contacts page. Note that if you're using a free trial, you'll be prompted to start your **Free Trial of Dynamics 365 Remote Assist**.
5.	You can now use Dynamics 365 Remote Assist on your mobile device! Next up, [learn how make calls](mobile-app/making-calls.md) to a remote expert on Microsoft Teams (desktop and mobile). 

## Next steps
- [Learn how to use Dynamics 365 Remote Assist on HoloLens 1 and 2](overview-hololens.md). 
- [Learn how to use Dynamics 365 Remote Assist on mobile devices](mobile-app/remote-assist-mobile-overview.md). 
