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
description: В следующих разделах описываются функции архивации архивации Microsoft Exchange Online.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131533"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Функции архивации в архивации на базе Exchange Online

В следующих разделах описываются функции архивации архивации Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Архивный почтовый ящик

Архивация на базе Exchange Online предлагает пользователям расширенные возможности архивирования благодаря функции архивирования почтового ящика. Архивный почтовый ящик — это специализированный почтовый ящик, который появляется рядом с основными папками почтовых ящиков пользователей в Outlook или Outlook в Интернете. Пользователи могут получать доступ к архиву таким же способом, как и к своему основному почтовому ящику. Кроме того, они могут выполнять поиск как в основных почтовых ящиках, так и в архивах.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  Не разрешается использовать функцию ведения журнала, правила транспорта и правила автоматической пересылки, чтобы копировать сообщения на Архивация на базе Exchange Online для создания архива. <br/>
>  Архивный почтовый ящик пользователя предназначен только для этого пользователя. Корпорация Майкрософт оставляет за собой право отказаться от неограниченного архивирования в случаях, когда архивный почтовый ящик пользователя используется для хранения архивных данных для других пользователей или в других случаях недопустимого использования.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Перемещение сообщений для архивации на базе Exchange Online

Пользователи могут перетаскивать сообщения из PST-файлов в архив, чтобы они всегда были под рукой. Они также могут автоматически перемещать письма из основного почтового ящика в архивный с помощью политик архивации, что уменьшает его размер и повышает производительность. 
  
### <a name="import-data-to-the-archive"></a>Импорт данных в архив

Пользователи могут импортировать данные в архив следующими способами:
  
- импортировать данные из PST-файла с помощью мастера импорта и экспорта Outlook;
    
- перетаскивать сообщения электронной почты из PST-файлов в архив;
    
- перетаскивать сообщения из основного почтового ящика в архив;
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Восстановление удаленных элементов

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
После удаления элемента из папки архива "Удаленные" он хранится в папке архива "Элементы, подлежащие восстановлению" в течение еще 14 дней до окончательного удаления. Пользователи могут восстановить эти элементы с помощью функции **восстановления удаленных элементов** в Microsoft Outlook или Outlook в Интернете. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  Для периода восстановления одного элемента по умолчанию установлено 14 дней, но при определенных обстоятельствах это значение можно настраивать. <br/>
>  Если администратор поместил почтовый ящик пользователя на хранение на месте или хранение для судебного разбирательства, удаленные элементы будут храниться в течение неограниченного времени, а окно 14 дней не применяется. 
  
## <a name="deleted-mailbox-recovery"></a>Восстановление удаленного почтового ящика

Когда администраторы удаляют пользователей из локального сервера Exchange Server, архивы пользователей также удаляются. Если необходимо восстановить удаленные архивные почтовые ящики, Группа поддержки Майкрософт может выполнить это восстановление. Восстановленный архив будет содержать всю почту, которая хранилась в нем на момент удаления.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Избыточность службы почтового ящика

Архивные почтовые ящики в архивации на базе Exchange Online реплицируются на несколько копий баз данных (в географически распределенных центрах обработки данных Майкрософт), чтобы обеспечить возможность восстановления данных в случае сбоя инфраструктуры обмена сообщениями. В случае крупномасштабных сбоев инициируется управление непрерывностью бизнеса. 
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Описание службы архивации на базе Exchange Online](exchange-online-archiving-service-description.md).
  
