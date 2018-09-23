---
title: Управление получателями, доменами и компаниями
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) предлагает несколько средства управления получателя, домена и сведения о компании. С правами администратора можно выполнять определенные задачи управления в центре администрирования Exchange (EAC) и проверьте другие задачи управления, выполняемые в центре администрирования Microsoft Office 365.
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036844"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="ea871-104">Управление получателями, доменами и компаниями</span><span class="sxs-lookup"><span data-stu-id="ea871-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="ea871-p102">Microsoft Exchange Online Protection (EOP) предлагает несколько средства управления получателя, домена и сведения о компании. С правами администратора можно выполнять определенные задачи управления в центре администрирования Exchange (EAC) и проверьте другие задачи управления, выполняемые в центре администрирования Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="ea871-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft Office 365 admin center.</span></span>
  
<span data-ttu-id="ea871-p103">Хотите узнать подробнее обо всех функциях EOP? См. раздел [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="ea871-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="ea871-109">Получатели почты</span><span class="sxs-lookup"><span data-stu-id="ea871-109">Mail recipients</span></span>
<span data-ttu-id="ea871-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-110"></span></span>

<span data-ttu-id="ea871-p104">Получатели почты классифицируются как пользователи почты или почтовые группы и могут управляться посредством синхронизации каталога напрямую в EAC или через удаленный экземпляр Windows PowerShell. Если вы управляете получателями локально, необходимо запустить синхронизацию службы каталогов, чтобы отобразить получателей почты в Центре администрирования Exchange. Пользователей, для управления которыми используется исключительно Центр администрирования Office 365, невозможно просмотреть в Центре администрирования Exchange, но их можно добавить в группу ролей администраторов в Центре администрирования Exchange или удалить из нее. Дополнительные сведения о получателях в службе Exchange Online Protection см. в статье, посвященной [получателям в EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="ea871-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Office 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="ea871-115">Разрешения для группы ролей администраторов</span><span class="sxs-lookup"><span data-stu-id="ea871-115">Admin role group permissions</span></span>
<span data-ttu-id="ea871-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-116"></span></span>

<span data-ttu-id="ea871-p105">В службе Exchange Online Protection можно настраивать только роли администраторов. Пользователей можно добавить в группы ролей администраторов по умолчанию и удалить из них непосредственно в Центре администрирования Exchange. Настройка RBAC недоступна. Дополнительные сведения см. в статье, посвященной [управлению разрешениями группы ролей администраторов в EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="ea871-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="ea871-121">Управление доменами</span><span class="sxs-lookup"><span data-stu-id="ea871-121">Domain management</span></span>
<span data-ttu-id="ea871-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-122"></span></span>

<span data-ttu-id="ea871-p106">Управляемые домены  это домены, защищенные с помощью Exchange Online Protection. В Центре администрирования Exchange можно просматривать управляемые домены и изменять типы доменов. Подготовка доменов и управление доменами выполняется в Центре администрирования Office 365. Эти изменения отражаются в Центре администрирования Exchange. Дополнительные сведения см. в статье, в которой рассматривается [просмотр и изменение управляемых доменов в EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="ea871-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Office 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="ea871-127">Соответствующие поддомены</span><span class="sxs-lookup"><span data-stu-id="ea871-127">Match subdomains</span></span>
<span data-ttu-id="ea871-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-128"></span></span>

<span data-ttu-id="ea871-p107">В службе EOP можно включить поток почты к поддоменам управляемого домена. Дополнительные сведения см. в статье [Включение потока почты к поддоменам в службе EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="ea871-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="ea871-131">Пограничная блокировка на основе каталогов</span><span class="sxs-lookup"><span data-stu-id="ea871-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="ea871-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-132"></span></span>

<span data-ttu-id="ea871-p108">Функция пограничной блокировки на основе каталогов позволяет отклонять сообщения для недопустимых получателей в сети периметра службы. С помощью функции пограничной блокировки на основе каталогов администраторы могут добавлять получателей, поддерживающих почту, в Office 365 и блокировать все сообщения, отправляемые на адреса электронной почты, которые отсутствуют в Office 365. Если сообщение отправляется на допустимый адрес электронной почты, присутствующий в Office 365, сообщение проходит через все остальные слои фильтрации службы (защита от вредоносных программ и нежелательной почты, правила транспорта). Если адрес отсутствует, служба блокирует сообщение еще до фильтрации, а отправителю отправляется отчет о недоставке сообщения.</span><span class="sxs-lookup"><span data-stu-id="ea871-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="ea871-p109">Включение функции пограничной блокировки на основе каталогов требует настройки доменов и учетных записей пользователей. Дополнительные сведения см. в статье, посвященной [применению пограничной блокировки на основе каталогов для отклонения сообщений, отправленных недопустимым получателям](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="ea871-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="ea871-139">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="ea871-139">Feature Availability</span></span>
<span data-ttu-id="ea871-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="ea871-140"></span></span>

<span data-ttu-id="ea871-141">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="ea871-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

