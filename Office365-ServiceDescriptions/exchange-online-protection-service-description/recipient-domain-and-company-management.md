---
title: Управление получателями, доменами и компаниями
ms.author: sharik
author: skjerland
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
description: Microsoft Exchange Online Protection (EOP) предлагает несколько средств управления сведениями о получателях, доменах и компаниях. Как администратор вы можете выполнять определенные задачи управления в центре администрирования Exchange и проверять другие задачи управления, выполняемые в центре администрирования Microsoft 365.
ms.openlocfilehash: ff773ca3e19c9f9419ad907ed102f6af8a3567c2
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246275"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="9ac25-104">Управление получателями, доменами и компаниями</span><span class="sxs-lookup"><span data-stu-id="9ac25-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="9ac25-105">Microsoft Exchange Online Protection (EOP) предлагает несколько средств управления сведениями о получателях, доменах и компаниях.</span><span class="sxs-lookup"><span data-stu-id="9ac25-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="9ac25-106">Как администратор вы можете выполнять определенные задачи управления в центре администрирования Exchange и проверять другие задачи управления, выполняемые в центре администрирования Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="9ac25-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="9ac25-107">Ищете сведения обо всех функциях EOP?</span><span class="sxs-lookup"><span data-stu-id="9ac25-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="9ac25-108">Ознакомьтесь с [описанием службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="9ac25-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="9ac25-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="9ac25-109">Mail recipients</span></span>
<span data-ttu-id="9ac25-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-110"></span></span>

<span data-ttu-id="9ac25-111">Получатели электронной почты классифицируются как почтовые пользователи или группы и могут управляться с помощью синхронизации службы каталогов, непосредственно в центре администрирования Exchange или с помощью удаленной оболочки Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="9ac25-111">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="9ac25-112">Если вы управляете получателями в локальной среде, необходимо выполнить синхронизацию службы каталогов, чтобы получатели почты отражались в центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="9ac25-112">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="9ac25-113">Пользователи, управляемые только в центре администрирования Microsoft 365, не отображаются в центре администрирования Exchange, но их можно добавить или удалить из группы ролей администраторов в центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="9ac25-113">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="9ac25-114">Для получения дополнительных сведений о получателях в EOP, обратитесь к разделу [получатели в EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="9ac25-114">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="9ac25-115">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="9ac25-115">Admin role group permissions</span></span>
<span data-ttu-id="9ac25-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-116"></span></span>

<span data-ttu-id="9ac25-p105">В службе Exchange Online Protection можно настраивать только роли администраторов. Пользователей можно добавить в группы ролей администраторов по умолчанию и удалить из них непосредственно в Центре администрирования Exchange. Настройка RBAC недоступна. Дополнительные сведения см. в статье, посвященной [управлению разрешениями группы ролей администраторов в EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="9ac25-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="9ac25-121">Domain management</span><span class="sxs-lookup"><span data-stu-id="9ac25-121">Domain management</span></span>
<span data-ttu-id="9ac25-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-122"></span></span>

<span data-ttu-id="9ac25-123">Управляемые домены — это домены, защищенные EOP.</span><span class="sxs-lookup"><span data-stu-id="9ac25-123">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="9ac25-124">Управляемые домены можно просматривать, а типы доменов можно изменять в Центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="9ac25-124">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="9ac25-125">Подготовка доменов и управление ими происходят в центре администрирования Microsoft 365, и изменения отражаются в центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="9ac25-125">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="9ac25-126">Дополнительные сведения см в разделе [Просмотр или изменение управляемых доменов в EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="9ac25-126">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="9ac25-127">Соответствующие поддомены</span><span class="sxs-lookup"><span data-stu-id="9ac25-127">Match subdomains</span></span>
<span data-ttu-id="9ac25-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-128"></span></span>

<span data-ttu-id="9ac25-p107">В службе EOP можно включить поток почты к поддоменам управляемого домена. Дополнительные сведения см. в статье [Включение потока почты к поддоменам в службе EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="9ac25-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="9ac25-131">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="9ac25-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="9ac25-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-132"></span></span>

<span data-ttu-id="9ac25-p108">Функция пограничной блокировки на основе каталогов позволяет отклонять сообщения для недопустимых получателей в сети периметра службы. С помощью функции пограничной блокировки на основе каталогов администраторы могут добавлять получателей, поддерживающих почту, в Office 365 и блокировать все сообщения, отправляемые на адреса электронной почты, которые отсутствуют в Office 365. Если сообщение отправляется на допустимый адрес электронной почты, присутствующий в Office 365, сообщение проходит через все остальные слои фильтрации службы (защита от вредоносных программ и нежелательной почты, правила транспорта). Если адрес отсутствует, служба блокирует сообщение еще до фильтрации, а отправителю отправляется отчет о недоставке сообщения.</span><span class="sxs-lookup"><span data-stu-id="9ac25-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="9ac25-p109">Включение функции пограничной блокировки на основе каталогов требует настройки доменов и учетных записей пользователей. Дополнительные сведения см. в статье, посвященной [применению пограничной блокировки на основе каталогов для отклонения сообщений, отправленных недопустимым получателям](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="9ac25-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="9ac25-139">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="9ac25-139">Feature Availability</span></span>
<span data-ttu-id="9ac25-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="9ac25-140"></span></span>

<span data-ttu-id="9ac25-141">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="9ac25-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

