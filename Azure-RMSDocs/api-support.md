---
# required metadata

title: Other apps that support RMS APIs - Install & config - AIP
description: Understand how the Azure Rights Management service from Azure Information Protection can support other applications to protect your organization's data.
author: batamig
ms.author: bagol
manager: rkarlin
ms.date: 11/08/2020
ms.topic: conceptual
ms.collection: M365-security-compliance
ms.service: information-protection
ms.assetid: c50a8cbb-d12f-4a0e-bc29-74c463e6ac3e

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: esaggese
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: admin

---

# Other applications that support the Rights Management APIs

>***Applies to**: [Azure Information Protection](https://azure.microsoft.com/pricing/details/information-protection), [Office 365](https://download.microsoft.com/download/E/C/F/ECF42E71-4EC0-48FF-AA00-577AC14D5B5C/Azure_Information_Protection_licensing_datasheet_EN-US.pdf)*
>
>***Relevant for**: [AIP unified labeling client and classic client](faqs.md#whats-the-difference-between-the-azure-information-protection-classic-and-unified-labeling-clients).*

>[!NOTE] 
> To provide a unified and streamlined customer experience, **Azure Information Protection classic client** and **Label Management** in the Azure Portal are being **deprecated** as of **March 31, 2021**. This time-frame allows all current Azure Information Protection customers to transition to our unified labeling solution using the Microsoft Information Protection Unified Labeling platform. Learn more in the official [deprecation notice](https://aka.ms/aipclassicsunset).

Use the following information to help you understand how the Azure Rights Management service from Azure Information Protection can support other applications to protect your organization's data.

By using the Azure Information Protection SDKs, your internal developers can write line-of-business applications to natively support the Azure Rights Management service. How information protection is integrated with these applications depends on how they are written. For example, the integration might be automatically applied with minimal user interaction required, or for a more customized experience, users might be prompted to configure settings to apply information protection to files. For more information, see the [Developer's Guide](./develop/developers-guide.md).

Similarly, many software vendors provide applications to provide information protection solutions, also known as enterprise rights management (ERM) products. A popular example is a PDF reader that supports the Azure Rights Management service for specific platforms. You can use the table in [Applications that support Azure Rights Management data protection](./requirements-applications.md) to identify applications that support Rights Management (RMS-enlightened applications), and then use a web search to purchase or download the application.

## Next steps

To see how other applications and services support the Azure Rights Management service, see [How Applications Support the Azure Rights Management service](applications-support.md).
