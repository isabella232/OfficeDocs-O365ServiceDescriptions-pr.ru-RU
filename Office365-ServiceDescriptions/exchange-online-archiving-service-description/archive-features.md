---
title: Функции архивирования в архивации на базе Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: В следующих разделах функции архивов архивации Microsoft Exchange Online.
ms.openlocfilehash: 2bffa9fccb2c040fde4edcf8a5c80f3bc109bba2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036794"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="a8a17-103">Функции архивирования в архивации на базе Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a8a17-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="a8a17-104">В следующих разделах функции архивов архивации Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a8a17-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="a8a17-105">Архивный почтовый ящик</span><span class="sxs-lookup"><span data-stu-id="a8a17-105">Archive mailbox</span></span>

<span data-ttu-id="a8a17-p101">Архивация на базе Exchange Online предлагает пользователям расширенные возможности архивирования благодаря функции архивирования почтового ящика. Архивный почтовый ящик  это специальный почтовый ящик, который отображается наряду с папками основного почтового ящика пользователей в Outlook или Outlook Web App. Пользователи могут получать доступ к архиву таким же способом, как и к своему основному почтовому ящику. Кроме того, они могут выполнять поиск как в основных почтовых ящиках, так и в архивах.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="a8a17-p102">Администраторы могут включить функцию архива для отдельных пользователей с помощью Центра администрирования Exchange или Windows PowerShell. Дополнительные сведения см. в статье [Включение и отключение архивного почтового ящика в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span><span class="sxs-lookup"><span data-stu-id="a8a17-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="a8a17-p103">Не разрешается использовать функцию ведения журнала, правила транспорта и правила автоматической пересылки, чтобы копировать сообщения на Архивация на базе Exchange Online для создания архива. >  Архивный почтовый ящик пользователя предназначен только для этого пользователя. Майкрософт оставляет за собой право отказать в неограниченном архивировании, если архивный почтовый ящик пользователя используется для хранения архивных данных других пользователей.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="a8a17-115">Перемещение сообщений для архивации на базе Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a8a17-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="a8a17-p104">Пользователи могут перетаскивать сообщения из PST-файлов в архив, чтобы они всегда были под рукой. Они также могут автоматически перемещать письма из основного почтового ящика в архивный с помощью политик архивации, что уменьшает его размер и повышает производительность. Такой сценарий отличается от использования службы Exchange Hosted Archive, которая создает копию каждого сообщения в архиве, но оба позволяют соблюдать требования по хранению. Подробнее о дополнительных методах перемещения сообщений в архив можно узнать из статьи [Архивные почтовые ящики в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).</span><span class="sxs-lookup"><span data-stu-id="a8a17-p104">Users can drag and drop messages from .pst files into the archive, for easy online access. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. While this behavior is different than Exchange Hosted Archive, which will create a secondary copy of each message in the archive, retention requirements can be achieved in either scenario. For details on additional methods to move messages into the archive, see [Archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).</span></span>
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="a8a17-120">Импорт данных в архив</span><span class="sxs-lookup"><span data-stu-id="a8a17-120">Import data to the archive</span></span>

<span data-ttu-id="a8a17-121">Пользователи могут импортировать данные в архив следующими способами:</span><span class="sxs-lookup"><span data-stu-id="a8a17-121">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="a8a17-122">импортировать данные из PST-файла с помощью мастера импорта и экспорта Outlook;</span><span class="sxs-lookup"><span data-stu-id="a8a17-122">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="a8a17-123">перетаскивать сообщения электронной почты из PST-файлов в архив;</span><span class="sxs-lookup"><span data-stu-id="a8a17-123">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="a8a17-124">перетаскивать сообщения из основного почтового ящика в архив;</span><span class="sxs-lookup"><span data-stu-id="a8a17-124">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="a8a17-p105">разрешать политикам архивации автоматически перемещать сообщения в основной почтовый ящик, основываясь на времени создания сообщений. Дополнительные сведения см. в статье [Теги хранения и политики хранения](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span><span class="sxs-lookup"><span data-stu-id="a8a17-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="a8a17-p106">Администраторы также могут использовать службу импорта Office 365 для импорта PST-файлов в облачные архивные почтовые ящики пользователей. Дополнительные сведения см. в статье [Импорт PST-файлов в Office 365 с помощью отправки по сети](https://go.microsoft.com/fwlink/p/?linkid=823074).</span><span class="sxs-lookup"><span data-stu-id="a8a17-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="a8a17-129">Восстановление удаленных элементов</span><span class="sxs-lookup"><span data-stu-id="a8a17-129">Deleted item recovery</span></span>

<span data-ttu-id="a8a17-p107">Пользователи могут восстанавливать в своем архиве элементы, которые они удалили из любой папки почты. После удаления элемент хранится в папке архива "Удаленные". Он остается там, пока пользователь не удалит его вручную или это не произойдет автоматически согласно политикам хранения.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="a8a17-p108">После удаления элемента из папки архива "Удаленные" он хранится в папке архива "Элементы, подлежащие восстановлению" в течение еще 14 дней до окончательного удаления. Пользователи могут восстанавливать эти элементы, используя функцию **Восстановить удаленные элементы** в Microsoft Outlook или Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="a8a17-p109">Если пользователь вручную удалил элемент из папки "Элементы, подлежащие восстановлению", администратор может восстановить элемент в течение тех же 14 дней, используя функцию восстановления одного элемента. Эта функция позволяет администраторам выполнять поиск в нескольких почтовых ящиках, чтобы находить удаленные элементы, а затем с помощью командлета  `Search-Mailbox` в Windows PowerShell перемещать элементы из почтового ящика найденных сообщений в почтовые ящики пользователя. Дополнительные сведения см. в статье [Включение или отключение восстановления одного элемента в почтовом ящике](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span><span class="sxs-lookup"><span data-stu-id="a8a17-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="a8a17-p110">Для периода восстановления одного элемента по умолчанию установлено 14 дней, но при определенных обстоятельствах это значение можно настраивать. >  Если администратор поместил почтовый ящик пользователя на хранение на месте или для судебного разбирательства, удаленные элементы будут храниться в течение неограниченного срока.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="a8a17-140">Восстановление удаленного почтового ящика</span><span class="sxs-lookup"><span data-stu-id="a8a17-140">Deleted mailbox recovery</span></span>

<span data-ttu-id="a8a17-p111">Когда администраторы удаляют пользователей из локального сервера Exchange Server, архивы пользователей также удаляются. Если необходимо восстановить удаленные архивные почтовые ящики, это может сделать группа поддержки Office 365:. Восстановленный архив будет содержать всю почту, которая хранилась в нем на момент удаления.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a8a17-p112">Администраторы могут запросить восстановление архивного почтового ящика пользователя в течение 30 дней с момента его удаления. Через 30 дней архивный почтовый ящик не подлежит восстановлению.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="a8a17-146">Избыточность службы почтового ящика</span><span class="sxs-lookup"><span data-stu-id="a8a17-146">Mailbox service redundancy</span></span>

<span data-ttu-id="a8a17-p113">Архивные почтовые ящики в архивации Exchange Online, реплицируются на нескольких копий базы данных, в географически распределенных центрах обработки данных Майкрософт, чтобы обеспечить возможность восстановления данных в случае сбоя инфраструктуры обмена сообщениями. Для крупномасштабных сбоев запускается для обеспечения непрерывности бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a8a17-p113">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure. For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="a8a17-149">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="a8a17-149">Feature Availability</span></span>

<span data-ttu-id="a8a17-150">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы архивации на базе Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="a8a17-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
