---
title: Функции обеспечения соответствия требованиям и безопасности в архивации на базе Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132743"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Функции обеспечения соответствия требованиям и безопасности в архивации на базе Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Функции контроля соответствия требованиям в архивации на базе Exchange Online

В следующих разделах описаны функции контроля соответствия требованиям Microsoft Архивация на базе Exchange Online.
  
### <a name="retention-policies"></a>Политики хранения

Архивация на базе Exchange Online предлагает политики хранения, которые смогут помочь организациям снизить обязательства, связанные с обменом электронными и другими сообщениями. С помощью этих политик администраторы могут применить параметры хранения к конкретным папкам в папках пользователей "Входящие". Администраторы также могут предоставить пользователям меню политик хранения и разрешить им применять политики к определенным элементам, беседам или папкам с помощью Outlook 2010 или более поздней версии или Outlook в Интернете. В Архивация на базе Exchange Online администраторы управляют политиками хранения из локальной инфраструктуры.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
В Outlook 2010 и более поздних версий и Outlook в Интернете пользователи могут применять политики хранения к папкам, беседам или отдельным сообщениям, а также просматривать примененные политики хранения и ожидаемые даты удаления сообщений. Сообщения пользователей в других почтовых клиентах могут удаляться или архивироваться на основе серверных политик хранения, создаваемых администратором, но они не предоставляют такого же уровня наглядности и управляемости.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Хранение на месте и хранение для судебного разбирательства

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
В Exchange Online хранение на месте и судебное удержание можно использовать для достижения следующих целей:
  
- помещения пользователей на удержание и сохранения элементов почтовых ящиков без возможности изменения;
    
- сохранения элементов почтовых ящиков, удаленных пользователями или автоматическими процессами удаления, такими как управление записями сообщений;
    
- защиты элементов почтового ящика от изменения и редактирования пользователями или автоматическими процессами путем сохранения копии исходного элемента;
    
- сохранения элементов на неограниченный или определенный срок;
    
- удержания, не затрагивающего пользователей (служба управления записями не приостанавливается);
    
- использования обнаружения электронных данных на месте для поиска элементов в почтовых ящиках, включая элементы, помещенные на удержание.
    
Кроме того, хранение на месте можно использовать для:
  
- поиска и удержания элементов, удовлетворяющих заданным условиям;
    
- помещения пользователя на удержание в нескольких местах для разных дел и расследований.
    
> [!NOTE]
> Если вы помещаете почтовый ящик на хранение на месте или хранение для судебного разбирательства, удержание распространяется как на основной, так и на архивный почтовые ящики. 
  
Дополнительные сведения см. в статье [Удержание на месте и хранение для судебного разбирательства](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> Квота по умолчанию для папки восстанавливаемых элементов  100 ГБ для пользователей Архивация на базе Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Обнаружение электронных данных на месте

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Функции безопасности в архивации на базе Exchange Online

В следующих разделах описаны функции безопасности Microsoft Архивация на базе Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Шифрование между локальными серверами и средством архивации на базе Exchange Online

Протокол TLS позволяет шифровать подключения между почтовыми серверами для предотвращения спуфинга и защиты конфиденциальности передаваемых сообщений. Протокол TLS также используется для обеспечения безопасности локального трафика почтовых серверов в центрах обработки данных Майкрософт для архивации на базе Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Шифрование между клиентами и средством архивации на базе Exchange Online

В клиентских соединениях с Архивация на базе Exchange Online используются следующие методы шифрования для повышения безопасности:
  
- Протокол SSL используется для защиты Outlook, Outlook в Интернете и трафика веб-служб Exchange с помощью TCP-порта 443.
    
- клиентские подключения к локальным серверам не изменяются с введением Архивация на базе Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Шифрование: S/MIME и PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
Аналогично, Архивация на базе Exchange Online будет хранить сообщения, зашифрованные с помощью сторонних клиентских решений по шифрованию, таких как PGP.
  
### <a name="information-rights-management"></a>Управление правами на доступ к данным

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Поддержка управления правами на доступ к данным в Outlook в Интернете

Пользователи могут читать и создавать сообщения, защищенные с помощью IRM, в Outlook в Интернете так же, как и в Outlook. Доступ к сообщениям с защитой IRM в Outlook в Интернете возможен через Internet Explorer, Firefox, Safari и Chrome (при этом не требуется подключаемый модуль). Для сообщений доступен полнотекстовый поиск, представление беседы и панель просмотра. Для этого необходимо настроить взаимодействие между сервером службы управления правами Active Directory и локальной средой Exchange.
  
#### <a name="irm-search"></a>поиск IRM;

Сообщения, защищенные IRM, индексируются, и по ним можно выполнять поиск, в том числе по заголовкам, теме, основному тексту и вложениям. Пользователи могут искать элементы, защищенные с помощью IRM, в Outlook и Outlook в Интернете, а администраторы могут искать элементы, защищенные с помощью IRM, с помощью обнаружения электронных данных на месте или командлета **Search-Mailbox** .
  
### <a name="auditing"></a>Аудит

Архивация на базе Exchange Online предоставляет встроенные возможности аудита двух типов.
  
- **Журнал аудита администратора**. Он позволяет клиентам отслеживать изменения, внесенные администраторами в среде Архивация на базе Exchange Online, в том числе изменения ролей RBAC, политик и параметров Exchange. 
    
- **Журнал аудита почтовых ящиков** Он позволяет клиентам отслеживать доступ к почтовым ящикам пользователей, которые не являются владельцами этих почтовых ящиков. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Описание службы архивации на базе Exchange Online](exchange-online-archiving-service-description.md).
  

