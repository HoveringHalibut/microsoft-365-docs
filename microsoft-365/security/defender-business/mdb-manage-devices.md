---
title: Manage devices in Microsoft Defender for Business (preview)
description: Learn how to manage devices in Microsoft Defender for Business (preview)
search.appverid: MET150
author: denisebmsft
ms.author: deniseb
manager: dansimp 
audience: Admin
ms.topic: how-to
ms.date: 12/13/2021
ms.prod: m365-security
ms.technology: mdb
localization_priority: Normal
ms.reviewer: inbadian, shlomiakirav
f1.keywords: NOCSH 
ms.collection: 
- SMB
- M365-security-compliance
---

# Manage devices in Microsoft Defender for Business (preview)

> [!IMPORTANT]
> Microsoft Defender for Business is now in preview, and will roll out gradually to customers and IT Partners who [sign-up here](https://aka.ms/mdb-preview) to request it. We will onboard an initial set of customers and partners in the coming weeks and will expand the preview leading up to general availability. Note that preview will launch with an [initial set of scenarios](mdb-tutorials.md#try-these-preview-scenarios), and we will be adding capabilities regularly.
> 
> Some information in this article relates to prereleased products/services that might be substantially modified before they are commercially released. Microsoft makes no warranties, express or implied, for the information provided here. 

In Microsoft Defender for Business (preview), you can manage devices as follows:

- [View a list of onboarded devices](#view-the-list-of-onboarded-devices) to see their risk level, exposure level, and health state
- [Take action on a device](#take-action-on-a-device-that-has-threat-detections) that has threat detections
- [Onboard a device to Defender for Business (preview)](#onboard-a-device)  
- [Offboard a device from Defender for Business (preview)](#offboard-a-device)

## View the list of onboarded devices

:::image type="content" source="../../media/defender-business/mdb-deviceinventory.png" alt-text="Screenshot of device inventory":::

1. Go to the Microsoft 365 Defender portal ([https://security.microsoft.com](https://security.microsoft.com)) and sign in.

2. In the navigation pane, choose **Device inventory**.

3. Select a device to open its flyout panel, where you can learn more about its status and take action. 

   If you don't have any devices listed yet, [Onboard devices to Microsoft Defender for Business (preview)](mdb-onboard-devices.md)

## Take action on a device that has threat detections

:::image type="content" source="../../media/defender-business/mdb-selected-device.png" alt-text="Screenshot of a selected device with details and actions available":::

1. In the Microsoft 365 Defender portal ([https://security.microsoft.com](https://security.microsoft.com)), in the navigation pane, choose **Device inventory**. 

2. Select a device to open its flyout panel, and review the information that is displayed.

3. Select the ellipsis (**...**) to open the actions menu. 

4. Select an action, such as **Run antivirus scan** or **Initiate Automated Investigation**. 

## Onboard a device

See [Onboard devices to Microsoft Defender for Business (preview)](mdb-onboard-devices.md).

## Offboard a device

See [Offboard a device](mdb-onboard-devices.md#what-if-i-want-to-offboard-a-device).

## Next steps

- [View and manage incidents in Microsoft Defender for Business (preview)](mdb-view-manage-incidents.md)

- [Respond to and mitigate threats in Microsoft Defender for Business (preview)](mdb-respond-mitigate-threats.md)

- [Review remediation actions in the Action center](mdb-review-remediation-actions.md)

- [Create or edit device groups](mdb-create-edit-device-groups.md)
