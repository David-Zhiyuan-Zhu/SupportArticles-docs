---
title: Language features not displayed to standard users
description: Provides the information that language features aren't displayed to standard users starting from Windows 10, version 1809.
ms.date: 6/25/2021
author: v-lianna
ms.author: delhan
manager: dcscontentpm
audience: itpro
ms.topic: troubleshooting
ms.prod: windows-client
localization_priority: medium
ms.reviewer: kaushika, kimberj, arrenc
ms.custom: sap:setup, csstroubleshoot
ms.technology: windows-client-deployment
---
# Language features aren't displayed in Windows 10

_Applies to:_ &nbsp; Windows 10, version 1809  
_Original KB number:_ &nbsp; 4507173

In versions of Windows prior to Windows 10, version 1809, language features such as **Speech** and **Handwriting** are visible to standard users. When standard users try to add a language feature, a User Account Control (UAC) is prompted and admin credentials are required. Starting from version 1809, language features aren't displayed to standard users as shown here:

:::image type="content" source="./media/language-features-not-displayed/install-language-features.png" alt-text="Screenshot of install language features.":::

Use the [Deployment Image Servicing and Management (DISM) cmdlet](/windows-hardware/manufacture/desktop/dism-operating-system-package-servicing-command-line-options) to include these features in a Windows image.
