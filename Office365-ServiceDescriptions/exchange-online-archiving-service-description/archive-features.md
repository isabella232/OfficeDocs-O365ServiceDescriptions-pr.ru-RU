---
title: Функции архивации в архивации на базе Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: Сведения о функциях архивации, доступных в разделе Архивация Microsoft Exchange Online.
ms.openlocfilehash: da7b9fd7583904424300dff010117e50a6193552
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293655"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="d5a7c-103">Функции архивации в архивации на базе Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d5a7c-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="d5a7c-104">В следующих разделах описываются функции архивации архивации Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="d5a7c-105">Архивный почтовый ящик</span><span class="sxs-lookup"><span data-stu-id="d5a7c-105">Archive mailbox</span></span>

<span data-ttu-id="d5a7c-106">Архивация на базе Exchange Online предлагает пользователям расширенные возможности архивирования благодаря функции архивирования почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="d5a7c-107">Архивный почтовый ящик — это специализированный почтовый ящик, который появляется рядом с основными папками почтовых ящиков пользователей в Outlook или Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="d5a7c-108">Пользователи могут получать доступ к архиву таким же способом, как и к своему основному почтовому ящику.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="d5a7c-109">Кроме того, они могут выполнять поиск как в основных почтовых ящиках, так и в архивах.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="d5a7c-p102">Администраторы могут включить функцию архива для отдельных пользователей с помощью Центра администрирования Exchange или Windows PowerShell. Дополнительные сведения см. в статье [Включение и отключение архивного почтового ящика в Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="d5a7c-112">Не разрешается использовать функцию ведения журнала, правила транспорта и правила автоматической пересылки, чтобы копировать сообщения на Архивация на базе Exchange Online для создания архива.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="d5a7c-113">Архивный почтовый ящик пользователя предназначен только для этого пользователя.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="d5a7c-114">Корпорация Майкрософт оставляет за собой право отказаться от неограниченного архивирования в случаях, когда архивный почтовый ящик пользователя используется для хранения архивных данных для других пользователей или в других случаях недопустимого использования.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="d5a7c-115">Перемещение сообщений для архивации на базе Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d5a7c-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="d5a7c-116">Пользователи могут перетаскивать сообщения из PST-файлов в архив, чтобы они всегда были под рукой.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="d5a7c-117">Они также могут автоматически перемещать письма из основного почтового ящика в архивный с помощью политик архивации, что уменьшает его размер и повышает производительность.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="d5a7c-118">Импорт данных в архив</span><span class="sxs-lookup"><span data-stu-id="d5a7c-118">Import data to the archive</span></span>

<span data-ttu-id="d5a7c-119">Пользователи могут импортировать данные в архив следующими способами:</span><span class="sxs-lookup"><span data-stu-id="d5a7c-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="d5a7c-120">импортировать данные из PST-файла с помощью мастера импорта и экспорта Outlook;</span><span class="sxs-lookup"><span data-stu-id="d5a7c-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="d5a7c-121">перетаскивать сообщения электронной почты из PST-файлов в архив;</span><span class="sxs-lookup"><span data-stu-id="d5a7c-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="d5a7c-122">перетаскивать сообщения из основного почтового ящика в архив;</span><span class="sxs-lookup"><span data-stu-id="d5a7c-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="d5a7c-p106">разрешать политикам архивации автоматически перемещать сообщения в основной почтовый ящик, основываясь на времени создания сообщений. Дополнительные сведения см. в статье [Теги хранения и политики хранения](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="d5a7c-p107">Администраторы также могут использовать службу импорта Office 365 для импорта PST-файлов в облачные архивные почтовые ящики пользователей. Дополнительные сведения см. в статье [Импорт PST-файлов в Office 365 с помощью отправки по сети](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="d5a7c-127">Восстановление удаленных элементов</span><span class="sxs-lookup"><span data-stu-id="d5a7c-127">Deleted item recovery</span></span>

<span data-ttu-id="d5a7c-p108">Пользователи могут восстанавливать в своем архиве элементы, которые они удалили из любой папки почты. После удаления элемент хранится в папке архива "Удаленные". Он остается там, пока пользователь не удалит его вручную или это не произойдет автоматически согласно политикам хранения.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="d5a7c-131">После удаления элемента из папки архива "Удаленные" он хранится в папке архива "Элементы, подлежащие восстановлению" в течение еще 14 дней до окончательного удаления.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="d5a7c-132">Пользователи могут восстановить эти элементы с помощью функции **восстановления удаленных элементов** в Microsoft Outlook или Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="d5a7c-p110">Если пользователь вручную удалил элемент из папки "Элементы, подлежащие восстановлению", администратор может восстановить элемент в течение тех же 14 дней, используя функцию восстановления одного элемента. Эта функция позволяет администраторам выполнять поиск в нескольких почтовых ящиках, чтобы находить удаленные элементы, а затем с помощью командлета  `Search-Mailbox` в Windows PowerShell перемещать элементы из почтового ящика найденных сообщений в почтовые ящики пользователя. Дополнительные сведения см. в статье [Включение или отключение восстановления одного элемента в почтовом ящике](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="d5a7c-136">Для периода восстановления одного элемента по умолчанию установлено 14 дней, но при определенных обстоятельствах это значение можно настраивать.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="d5a7c-137">Если администратор поместил почтовый ящик пользователя на хранение на месте или хранение для судебного разбирательства, удаленные элементы будут храниться в течение неограниченного времени, а окно 14 дней не применяется.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="d5a7c-138">Восстановление удаленного почтового ящика</span><span class="sxs-lookup"><span data-stu-id="d5a7c-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="d5a7c-139">Когда администраторы удаляют пользователей из локального сервера Exchange Server, архивы пользователей также удаляются.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="d5a7c-140">Если необходимо восстановить удаленные архивные почтовые ящики, Группа поддержки Майкрософт может выполнить это восстановление.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="d5a7c-141">Восстановленный архив будет содержать всю почту, которая хранилась в нем на момент удаления.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d5a7c-p113">Администраторы могут запросить восстановление архивного почтового ящика пользователя в течение 30 дней с момента его удаления. Через 30 дней архивный почтовый ящик не подлежит восстановлению.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="d5a7c-144">Избыточность службы почтового ящика</span><span class="sxs-lookup"><span data-stu-id="d5a7c-144">Mailbox service redundancy</span></span>

<span data-ttu-id="d5a7c-145">Архивные почтовые ящики в архивации на базе Exchange Online реплицируются на несколько копий баз данных (в географически распределенных центрах обработки данных Майкрософт), чтобы обеспечить возможность восстановления данных в случае сбоя инфраструктуры обмена сообщениями.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="d5a7c-146">В случае крупномасштабных сбоев инициируется управление непрерывностью бизнеса.</span><span class="sxs-lookup"><span data-stu-id="d5a7c-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="d5a7c-147">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="d5a7c-147">Feature availability</span></span>

<span data-ttu-id="d5a7c-148">Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Описание службы архивации на базе Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="d5a7c-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
