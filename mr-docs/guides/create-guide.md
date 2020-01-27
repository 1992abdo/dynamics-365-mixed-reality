---
author: Mamaylya
description: Use the PC app in Microsoft Dynamics 365 Guides as the first step in creating a guide. 
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Create a guide by using the Dynamics 365 Guides PC app
ms.reviewer: v-brycho
---

# Create a guide by using the Dynamics 365 Guides PC app

1. [Open the Microsoft Dynamics 365 Guides PC app](install-sign-in-pc-app.md).

2. Select **Create new guide**.

    ![Create new guide button](media/create-guide.PNG "Create new guide button")

3. Enter a name for the guide, and then select **Create**.

    > [!TIP]
    > If you're planning to create multiple versions of the guide, you might want to add **\_v2**, **\_v3**, and so on, as part of the name. You can also use the **Save a Copy** command on the **File** menu if you're creating multiple versions of the same guide.

    ![Naming the guide](media/name-guide.PNG "Naming the guide")

    > [!NOTE]
    > When you create a guide by using the PC app, a JavaScript Object Notation (JSON) data file is automatically created in Common Data Service. This file is for internal use only. We don't recommend that you build functionality on top of this file, because it might change over time.

After you create your guide, the **Outline** page appears. To learn more about how to work on the **Outline** page, see [Structure your guide in the Outline page](structure-guide.md).

## How changes are synced between the PC app and the HoloLens app

The PC authoring app and the [!include[pn-hololens](../includes/pn-hololens.md)] app are connected through the cloud, where your [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] files and content are stored.

When you author a guide, all changes are saved on both the computer and the [!include[pn-hololens](../includes/pn-hololens.md)]. Therefore, it's easy to switch between devices. Autosave checks for changes every four seconds.

You must be online to use [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

> [!NOTE]
> When you switch from one device to the other, it's a good idea to close the guide, to make sure that you don't lose any work.

## What's next?

[Anchor your guide to the real world](anchor.md)<br>
[Structure your guide in the Outline page](structure-guide.md)<br>
[Create steps and add 3D content or 2D media](create-steps-assign-media.md)<br>
[Learn about keyboard shortcuts](keyboard-shortcuts-pc-app.md)
