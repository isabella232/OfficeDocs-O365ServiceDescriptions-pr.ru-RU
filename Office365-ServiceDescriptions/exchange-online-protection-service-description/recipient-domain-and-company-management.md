---
title: Управление получателями, доменами и компаниями
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) предлагает несколько средств управления сведениями о получателях, доменах и компаниях. Как администратор вы можете выполнять определенные задачи управления в центре администрирования Exchange и проверять другие задачи управления, выполняемые в центре администрирования Microsoft 365.
ms.openlocfilehash: 4a2d2d091a6170e0606702a4a8047a21ad57ac11
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132773"
---
# <a name="recipient-domain-and-company-management"></a>Управление получателями, доменами и компаниями

Microsoft Exchange Online Protection (EOP) предлагает несколько средств управления сведениями о получателях, доменах и компаниях. Как администратор вы можете выполнять определенные задачи управления в центре администрирования Exchange и проверять другие задачи управления, выполняемые в центре администрирования Microsoft 365.
  
Ищете сведения обо всех функциях EOP? Ознакомьтесь с [описанием службы Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

Получатели электронной почты классифицируются как почтовые пользователи или группы и могут управляться с помощью синхронизации службы каталогов, непосредственно в центре администрирования Exchange или с помощью удаленной оболочки Windows PowerShell. Если вы управляете получателями в локальной среде, необходимо выполнить синхронизацию службы каталогов, чтобы получатели почты отражались в центре администрирования Exchange. Пользователи, управляемые только в центре администрирования Microsoft 365, не отображаются в центре администрирования Exchange, но их можно добавить или удалить из группы ролей администраторов в центре администрирования Exchange. Для получения дополнительных сведений о получателях в EOP, обратитесь к разделу [получатели в EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Управление доменами

Управляемые домены — это домены, защищенные EOP. Управляемые домены можно просматривать, а типы доменов можно изменять в Центре администрирования Exchange. Подготовка доменов и управление ими происходят в центре администрирования Microsoft 365, и изменения отражаются в центре администрирования Exchange. Дополнительные сведения см в разделе [Просмотр или изменение управляемых доменов в EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Соответствующие поддомены

In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Пограничная блокировка на основе каталогов

Функция пограничной блокировки на основе каталогов позволяет отклонять сообщения для недопустимых получателей в сети периметра службы. DBEB позволяет администраторам добавлять получателей с включенной поддержкой почты в корпорацию Майкрософт и блокировать все сообщения, отправленные на адреса электронной почты, которые отсутствуют в корпорации Майкрософт. Если сообщение отправляется на действительный адрес электронной почты в корпорации Майкрософт, сообщение пройдет через остальные слои фильтрации служб (защита от вредоносных программ, защита от нежелательной почты, правила транспорта). Если адрес отсутствует, служба блокирует сообщение еще до фильтрации, а отправителю отправляется отчет о недоставке сообщения. 
  
Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, отдельных параметрах и локальных решениях, ознакомьтесь с [описанием службы Exchange Online Protection](exchange-online-protection-service-description.md).
