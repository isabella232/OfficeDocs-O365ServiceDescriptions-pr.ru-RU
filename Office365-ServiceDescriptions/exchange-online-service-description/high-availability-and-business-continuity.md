---
title: Высокая доступность и непрерывность бизнес-процессов
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online обеспечивает расширенную поддержку хранения и восстановления для инфраструктуры электронной почты организации. Сюда входят репликация почтовых ящиков в центрах обработки данных и возможность восстановления удаленных почтовых ящиков и элементов.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131973"
---
# <a name="high-availability-and-business-continuity"></a>Высокая доступность и непрерывность бизнес-процессов

Microsoft Exchange Online обеспечивает расширенную поддержку хранения и восстановления для инфраструктуры электронной почты организации. Сюда входят репликация почтовых ящиков в центрах обработки данных и возможность восстановления удаленных почтовых ящиков и элементов.
  
## <a name="mailbox-replication-at-data-centers"></a>Репликация почтовых ящиков в центрах обработки данных

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Восстановление удаленного почтового ящика

Администраторы могут удалять почтовые ящики Exchange Online с помощью центра администрирования Microsoft 365, чтобы удалить соответствующую учетную запись пользователя или удалить лицензию Exchange Online, или с помощью командлета **Remove-Mailbox** в удаленной оболочке Windows PowerShell. При удалении почтового ящика Exchange Online по умолчанию хранит его и его содержимое в течение 30 дней. Через 30 дней почтовый ящик не подлежит восстановлению. Восстановленный почтовый ящик содержит все данные, которые хранились в нем на момент удаления. Администраторы могут восстанавливать удаленные почтовые ящики в течение срока хранения с помощью центра администрирования Microsoft 365. Для восстановления удаленного почтового ящика администраторы должны восстановить соответствующую учетную запись пользователя или переназначить лицензию Exchange Online учетной записи пользователя. Дополнительные сведения см. в статье [Delete or Restore User Mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Восстановление удаленных элементов

Exchange Online позволяет пользователям восстанавливать удаленные элементы из папки электронной почты, в том числе из папки "Удаленные". После удаления элемент хранится в пользовательской папке "Удаленные". Он остается там до удаления пользователем вручную или автоматического удаления согласно политикам хранения. Администраторы могут изменять политики хранения с помощью Центра администрирования Exchange или удаленного Windows PowerShell.
  
После удаления элемента из папки "Удаленные" он остается в папке "элементы с возможностью восстановления" в течение 14 дней до окончательного удаления, но администраторы могут увеличить это до 30 дней с помощью удаленной оболочки Windows PowerShell. Пользователи могут восстановить элемент в течение этого периода времени с помощью функции восстановления удаленных элементов в Outlook в Интернете или Outlook. Узнайте, как [изменить срок хранения удаленных элементов](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  