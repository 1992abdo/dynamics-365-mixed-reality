---
author: Mamaylya
description: Create steps and add 3D content or media to support those steps in the Microsoft Dynamics 365 Guides PC app.
ms.author: mamaylya
ms.date: 02/25/2020
ms.service: crm-online
ms.topic: article
title: Create steps and add 3D models or media in the Dynamics 365 Guides PC app
ms.reviewer: v-brycho
---

# Create steps and add 3D models or 2D media in the Dynamics 365 Guides PC app

Steps are the central building block for creating a guide in [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. After you create the [structure for your guide on the **Outline** page](structure-guide.md), you use the Step Editor to add instructional text and 3D models or media to support those steps. The instructions that you create in the what-you-see-is-what-you-get (WYSIWYG) Step Editor match what the operator will see on the Step card on [!include[pn-hololens](../includes/pn-hololens.md)]. The following illustration shows the Step Editor in the PC app and the Step card that the user sees on [!include[pn-hololens](../includes/pn-hololens.md)].

![Step Editor and Step card](media/step-editor-step-card.PNG "Step Editor and Step card")

## Open the Step Editor and add instructions

You open the **Step Editor** page from the **Outline** page.

1. Select any step on the **Outline** page, or select **Step** in the left navigation.

    ![Step on the Outline page and Step command in the left navigation](media/left-nav-step.PNG "Step on the Outline page and Step command in the left navigation")

2. Enter your instructional text in the blue rectangle in the middle of the page.

    ![Step Editor](media/step-editor.PNG "Step Editor")

3. When you're ready to add another step, select **Add new step** in the upper-right corner of the page.

### Best practices for instructional text and supporting content

- Don't be afraid to add lots of steps, but keep the text short. Instruction text is limited to 280 characters per step.

- For the best results, write your guide in casual human language. Avoid technical jargon.

- Use descriptive words, such as *locate*, *find*, *get*, *go to*, *pick up*, *put down*, *insert*, *attach*, and *remove*.

- **NOTE** steps are useful for quality checks. This type of step can come before or after another step. Just be sure to add it in the right place.

- Add a **WARNING** step for things that could be dangerous or cause a quality issue. To reinforce the warning, you can [add a style in the HoloLens app](create-steps-assign-media.md).

- Sub-steps inside a step can be helpful, but don't be afraid to create separate steps for easier reading.

- When you've finished writing a step, be sure to move the cursor outside the text box to activate AutoSave.

- Try to use limit yourself to one type of content per step. Too much media or 3D content can overwhelm the operator and can be too time-consuming to absorb. Think about the type of content that best gets the point across.

## Go to other pages from the Step Editor page

Use the buttons in the navigation pane on the left side of the **Step Editor** page to go to other pages in the PC app. The following table describes the buttons in the navigation pane.

| Button | Name | Action |
|---|---|---|
| ![Open Navigation button](media/open-navigation-button.png "Open Navigation button") | Open Navigation | Expand the navigation pane so that it includes a description for each button. |
| ![Home button](media/home-button-pc-app.png "Home button") | Home | Go to the **Welcome** page, where you can create a new guide or open an existing guide. |
| ![Analyze button](media/analyze-button-pc-app.png "Analyze button") | Analyze | Go to the **Analyze** page, where you can set up Microsoft Power BI reports (Guides Analytics) to analyze your guides. |
| ![Anchor button](media/anchor-button-pc-app.png "Anchor button")| Anchor | Open the **Choose an anchor method** wizard, where you can select different anchor methods for your guide or change the type of anchoring method. |
| ![Outline button](media/outline-button-pc-app.png "Outline button")| Outline | Go to the **Outline** page, where you can structure or restructure your guide. You can also open the **Choose an anchor method** wizard from that page. |

## What can you add to help operators with a step?

You can add 3D content, media, or website links to help operators complete a step. The following table describes the different types of content that you can add.

| Content type | Description | Example |
|---|---|---|
| 3D models from the 3D toolkit | Ready-to-use 3D models, such as numbers, arrows, and hands | A holographic arrow that helps operators find a focus area |
| 3D part | 3D models that are specific to your company | A 3D part hologram that helps operators find a 3D part in the real world |
| Image | A 2D image file | A diagram that helps operators complete a complex step |
| Video | A video file | A short video that helps operators complete a complex step |
| Website link | A link to an external website | A link to a parts inventory system |

## Add a 3D model from the 3D toolkit

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] includes a library of predefined 3D objects that are optimized to work perfectly with [!include[pn-hololens](../includes/pn-hololens.md)]. The 3D toolkit includes markers, arrows, hands, numbers, symbols, zones, and generic tools. The following illustration shows an example where holographic numbers, arrows, and zones are used to help operators complete a step.

![Example of holographic numbers, arrows, and zones](media/3d-toolkit-example.PNG "Example of holographic numbers, arrows, and zones")

You can mix and match different types of 3D models. You can also use the same object (instance) as many times as you want in a step.

To add a model from the 3D toolkit, follow these steps.

1. On the right side of the page, select the **3D toolkit** tab, and then select the category for the type of item that you want to add.

    ![3D toolkit tab](media/select-3D-toolkit.PNG "3D toolkit tab")

2. Drag the 3D model that you want to one of the **3D parts** boxes.

    ![Dragging a 3D model to a 3D parts box](media/select-arrow.PNG "Dragging a 3D model to a 3D parts box")

> [!NOTE]
> You can also add 3D models from the 3D toolkit directly in the [!include[pn-hololens](../includes/pn-hololens.md)] app.

### Best practices for the 3D toolkit

- Use pointers to communicate simple spatial information, such as position, direction, and translation. You can adjust the size of the pointer, but you should never reduce it below 1 cm. Otherwise, errors can occur.

- Use the arrow when you want the operator to insert a part into something stationary (for example, to hand-tighten a bolt into a tapped hole).

- Use one of the hand poses when you want the operator to use his or her hand in a specific way to influence or manipulate something. There are various poses for specific interactions, such as Pull, Push, Pinch, and Grab. Combine these standard poses with arrows and/or icons to add additional meaning.

For more information about ways to use objects from the 3D toolkit, see [Create a great guide](great-guide.md).

## Add a 3D part

1. On the right side of the page, select the **3D parts** tab.

    ![3D parts tab](media/select-3D-parts.PNG "3D parts tab")

2. Drag the 3D part that you want to one of the **3D parts** boxes.

    ![Dragging a 3D part to a 3D parts box](media/drag-3D-part.PNG "Dragging a 3D part to a 3D parts box")

## Import a custom 3D model to use as a 3D part<a name="import"></a>

You can import your own custom 3D models and add them to the **3D parts** library. To import files, you can drag them from a local file folder or use the **Import** command.

### Import a file by using a drag-and-drop operation

1. Open Windows File Explorer, and go to the folder that contains the 3D models that you want to import.

2. Drag the files to the gallery.

    ![Drag-and-drop animation](media/drag-drop.gif "Drag-and-drop animation")

### Import a file by using the Import command

1.	Select **Import** in the lower-right corner of the page.

    ![Import button](media/import-command.PNG "Import button")

2.	Find the files that you want to import, and then select **Open**.

    ![Importing a custom 3D part](media/import-object.PNG "Importing a custom 3D part")

> [!NOTE]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] supports glTF, GLB, FBX, STL, and PLY file formats. You can use a combination of third-party tools and the [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] to prepare your 3D (computer-aided design \[CAD\]) models, or you can use the [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] concierge service to have [!include[cc-microsoft](../includes/cc-microsoft.md)] convert and optimize the models for you. For more information about [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)], see these topics:
>
> - [Import Tool overview](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/index)
>
> - [Optimize your 3D models](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/optimize-models)
>
> - [Best practices for 3D models](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/best-practices)
>
> - [Use Dynamics 365 Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/import-tool)

## Add media (images or videos)

1. On the right side of the page, select the **Images** or **Videos** tab.

    ![Images and Videos tabs](media/select-image-video.PNG "Images and Videos tabs")

2. Drag the image or video to the **Image or video** box.

    ![Dragging an image or video to the Image or video box](media/drag-image-video.PNG "Dragging an image or video to the Image or video box")

## Add a website or Power Apps link to a step

You can add a website link or a Power Apps link to a step.

- Add a website link so that operators can see and interact with information outside of [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. For example, you might want to provide a link to a parts diagram, parts inventory system, analytics dashboard, or information about Internet of Things (IoT) sensors. Website links let authors create a seamless workflow for operators.

- [Power Apps](https://products.office.com/en-us/business/microsoft-powerapps) enables teams to create custom 
applications with low-code tools to solve unique business workflows. By combining Dynamics 365 Guides and Power Apps, you can extend 
Guides capabilities to create a more seamless end-to-end solution that fits the needs of your operators. For example, you can add a 
link to an interactive quiz app, a parts re-ordering app, or an app that provides the latest status on IoT sensors.  

For more information, see [Add a website link or Power Apps link to a step](pc-app-website-powerapps-link.md).

## What's next?

[Anchor your guide to the real world](anchor.md)<br>
[Structure your guide in the Outline page](structure-guide.md)<br>
[Add a website or Power Apps link to a step](pc-app-website-powerapps-link.md)<br>
[Create and copy a link to a guide or step](pc-app-copy-link-guide-step.md)<br>
[Learn about keyboard shortcuts](keyboard-shortcuts-pc-app.md)<br>
[Deactivate a guide](pc-app-deactivate-guide.md)<br>
[Learn what makes a great mixed reality guide](great-guide.md)
