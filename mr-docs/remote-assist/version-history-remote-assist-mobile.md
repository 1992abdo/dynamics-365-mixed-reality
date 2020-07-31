---
title: "Remote Assist mobile version history | MicrosoftDocs"
ms.custom: 
  - dyn365-mixed-reality-remote-assist
ms.date: 07/01/2020
ms.reviewer: krbjoran
ms.service: dynamics-365-mixed-reality-remote-assist
ms.suite: ""
ms.technology: 
  - "remote-assist"
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
author: FieldServiceDave
ms.assetid: f7e513fc-047f-4a88-ab83-76fae5e583e2
caps.latest.revision: 42
ms.author: daclar
manager: shellyha
search.audienceType: 
  - admin
  - customizer
search.app: 
  - MRRA
  - MRRA
---

# Remote Assist mobile version history

## iOS - 2020.7.30 + Android - 2020.07.23

Date: July 31, 2020

- Fix for not displaying the Remote Assist mobile user's video feed on the Microsoft Teams desktop or mobile user's screen.
- Fix for placing the arrow annotation at the incorrect angle for Microsoft Teams desktop or mobile users.
- Optimized frequency of error messages guiding user to track their environment better.
- Fix for authentication taking a long time.
- Fix for annotations inaccuracy in calls between two Remote Assists clients.
- Fix for Undo and Delete buttons in the incorrect state.
- Fix for memory issues caused by screen rotation.
- Improved application memory usage.

## iOS - 2020.7.1 + Android - 2020.06.27

Date: July 1, 2020

-	Improved incoming call experience for Remote Assist mobile users who do not have the app open when a call comes in from Microsoft Teams desktop or mobile clients.
-	Fix for app crashing on mobile devices without augmented reality (AR) support, especially iPhone 5 and iPhone 6 devices.
-	Dynamics 365 Field Service customers can now view the service account names on the bookings screen. 
-	Updated the User Guide and Dynamics 365 Integration links in the app.
-	Update for authentication library on iOS.
-	Fix for “Just a moment” message blocking users after sign-in.
-	Fix for ArgumentNullException showing up when user don’t have any recent contacts and search query returns empty list.
-	Fix for Graphics.CopyTexture exception showing after annotating on the snapshot.
-	Fixes for application localization (e.g. “Retry sign-in” button, “Don’t show again” button and tracking error state messages).
-	Performance improvements for the application memory usage.

## iOS - 2020.5.28 + Android - 2020.05.22

Date: May 28, 2020

-	Fix for network error “HTTP 401 TeamsChatService.GetMessagesAsync”
-	Fix for application not being responsive during launch
-	Improvement for the recent contacts list 
-	Fix for not being able to find contacts in some countries, such as Egypt
-	Improvement for the voicemail card
-	Localization improvements
-	Accessibility improvements and fixes

## iOS – 2020.5.7 + Android - 2020.05.04 

Date: May 4, 2020

### Bug fixes
- Improved flighting implementation and enabling per company app customizations.
- Fix for sign in problem for users on mobile networks.
- Improved user feedback questionnaire experience.

## iOS – 2020.4.1 + Android - 2002.03.18

Date: April 1, 2020

### Bug fixes

- Fix for yellow tracking dots. Yellow tracking dots will not show up on the mobile device screen.
- Improved quality of annotations placement in the near field of 1 meter (three feet).
- Improved loading for cached recent contacts when users are in poor network condition. 
- Improved authentication handling and messaging. Better support for offline scenario and better error description.
- Fixed incorrect annotations position on tablet devices. Annotations were shifted on the sides of the screen.
- Enabled saving a snapshot if a call ends unexpectedly.
- Fixed incoming video feed position on the screen.
- Improved messaging and handling when group call is detected.
- Fixed NullReferenceException showing up during app termination and in the contacts search page.
- Fix for ArgumentOutOfRange exception showing up when typing text in the text chat.

## iOS – 2020.02.27 + Android - 2020.02.20

Date: February 27, 2020

### Bug fixes

- In low bandwidth environments with a satellite network of 1000/256 kbps for bandwidth, 600/600ms for latency, and 10% of packet loss, users will not receive an 'Update Check Failed' pop-up and can continue to share their environment.  
- Users trying the 90-day license-free Remote Assist Mobile trial who do not have a Microsoft Teams license (free or paid) will be prompted to sign up for one. After they sign up, the app will recognize their Microsoft Teams account and they can sign in.  
- With Remote Assist mobile app downloaded on your device, users can launch the app from Safari web browser via “ramobile:/” deep linking.  
- Users can view their snapshots with annotations on it in both landscape and portrait orientations. These snapshots will save to users’ mobile device’s Photo Gallery.  
- In the text chat, the keyboard remains open after sending a message. 
- The ‘Lost Tracking' pop-up is localized in our supported languages. 
- The correct year is shown when users’ mobile device is set to the future in Thai. 
- Error message improvements.  

## iOS – 2020.12.12 + Android - 2019.12.09

Date: December 12, 2020

### Bug fixes

- If you don’t have the Company Portal or the Microsoft Authenticatorapp installed, the app doesn’t crash when you sign in. 
- After tapping the Search buttonwhen searching for contacts, the “Start type to search text” doesn’t overlap with the Recentlist of contacts. 
- You cansign in with an MSA account. 
- The app is localized into 43 languages. 
- When you disconnect from a call by closing the app, you’re notified of subsequent calls.
- The app is available in the Apple and Google Playapp stores for all supported devices. 
- When you take a snapshot for the first time,the snapshot is saved to the camera roll and the video feed doesn’t freeze. 
- The Taskbar at the bottom of the screen is now visible on Android 10. 
- When you send a message in text chat, the keyboard is automatically closed.
- Calls from Teams desktop to the app are connected and continuewith no problems. 
- When using Teams on a tablet, annotations are normal size. 
- The Speakerbutton is only visible when there is more than one audio output source. 
- All buttons are responsive and tappable. 
- Fixed app crashes.

## iOS – 2020.10.31 + Android - 2019.10.22

Date: October 31, 2020

- The Screenshot button is removed from the toolbar. You can edit a screenshot by selecting the Snapshot and annotate button instead.
- In the case of a network disconnection, you’re automatically rejoined to the call when the network is restored. If there’s no network connection ,the call is ended.
- If you’re using a screen reader and access the tutorialpageaccessed from the Learn the Toolsor Try Itbutton, you can access the Arrowtool. 
- Ifyou tapthe Try Itbuttonon the Sign-inpage,and then select the back button on yourdevice, you return to theSign-inpage. 
- The end-user license agreement (EULA)link on the Sign-inpagegoes to the appropriate page (Android or iOS) based on yourdevice.
- On the tutorial page, the buttons now read:Restart Tutorialand Exit Practice.
- If you’re using Dynamics 365 Field Service with Dynamics 365 Remote Assist, the Post to Dynamicspop-up will disappearwhen youreceive or accepta call, butwill reappear after the call hasended.
- The“NullReferenceException: Object reference not set to an instance of an object”error message does not appearwhen startinga call, whethersystem-generated logs are enabled or not.

## Locate your version number

To find which version of Remote Assist mobile you have, go to the menu and select the **Information** option. You'll see the **App Version** there. See the following screenshot for reference. 

> [!div class="mx-imgBorder"]
> ![Screenshot of Remote Assist on a mobile device, showing the information option and the app version listed.](./media/ram-version-history-locate.png)
