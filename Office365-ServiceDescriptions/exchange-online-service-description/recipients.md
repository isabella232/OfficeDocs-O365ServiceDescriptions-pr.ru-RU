---
title: Получатели
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: В этой статье описаны компоненты Microsoft Exchange Online, связанные с получателями. Сюда относятся электронная почта, контакты, группы рассылки, а также календарь и возможности планирования.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132643"
---
# <a name="recipients"></a>Получатели

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>Электронная почта

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Адреса регистрации всех сообщений больше не поддерживаются в Exchange Online. Из-за фильтрации получателей для защиты от возможных нежелательных сообщений адреса электронной почты, которые не существуют в вашей организации, будут отклонены. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Типы почтовых ящиков, пределы хранения и оповещения о доступном объеме

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Для получения дополнительных сведений см раздел "пределы хранилища почтовых ящиков" и "оповещения о емкости" в разделе " [Exchange Online Limits](exchange-online-limits.md)".
  
### <a name="mailtips"></a>Подсказки

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Делегированный доступ

Exchange Online поддерживает делегирование доступа  возможность пользователей разрешить другим пользователям управлять своей электронной почтой и календарями. Передача прав доступа обычно используется между руководителем и помощником, где помощник обрабатывает входящие сообщения электронной почты и координирует расписание руководителя. Делегированный доступ может быть включен пользователями Exchange Online в Outlook или Outlook в Интернете или администраторами в центре администрирования Exchange. 
  
Делегаты могут иметь два вида доступа:
  
- **Разрешения на отправку от имени другого лица** Делегат может составить сообщение электронной почты и ввести имя другого пользователя в поле "От", где он будет отображаться в виде "[имя делегата] от имени [имя пользователя]". 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Подробную информацию о делегировании прав доступа см. в статье [Управление разрешениями для получателей](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Правила для папки "Входящие"

Служба Exchange Online позволяет создавать правила для папки входящих сообщений для автоматического выполнения определенных действий над сообщениями на основе критериев в момент их поступления. Например, пользователи могут создать правило для автоматического перемещения всей почты в определенную папку, если почта было отправлена в определенную группу рассылки. Пользователи управляют правилами папки "Входящие" из Outlook или Outlook в Интернете. Администраторы могут блокировать определенные типы правил для папки входящих сообщений на сервере, отключив переадресацию или серверные автоматические ответы. Например, отключение переадресации почты со стороны сервера позволяет предотвратить автоматическую пересылку электронной почты на личные учетные записи. Аналогично, отключение автоматических ответов со стороны сервера позволяет предотвратить автоматические ответы внешним сторонам и возможность идентификации допустимых адресов электронной почты. Эти изменения вносятся через удаленную консоль Windows PowerShell.
  
### <a name="clutter"></a>Папка "Несрочные"

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Подключенные учетные записи

Функция подключенных учетных записей позволяет пользователям Exchange Online связывать внешние учетные записи электронной почты (например, личные учетные записи) с их внутренними учетными записями электронной почты в Exchange Online, а затем использовать Outlook в Интернете для взаимодействия со всеми сообщениями в одном месте. Подключенные учетные записи автоматически синхронизируются при входе в Outlook в Интернете; Кроме того, пользователи могут вручную синхронизировать учетные записи из Outlook в Интернете. Администраторы могут включать и отключать эту функцию для определенных пользователей или всех пользователей с помощью [центра администрирования Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Неактивные почтовые ящики

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
Для включения функции неактивного почтового ящика требуется, чтобы ящик имел активную лицензию Exchange Online (план 2) или подписку на архивацию на базе Exchange Online,  только в этом случае возможно применение функции хранения на месте или хранения для судебного разбирательства к почтовому ящику перед его удалением.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
Дополнительные сведения см. в следующих разделах:
  
- [Управление неактивными почтовыми ящиками в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Хранение на месте и хранение для судебного разбирательства](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Обнаружение электронных данных на месте](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Контакты и группы рассылки

### <a name="offline-address-book"></a>Автономная адресная книга

Функция автономной адресной книги предоставляет моментальный снимок сведений Active Directory, доступных в глобальном списке адресов Outlook (GAL). Она кэшируется локально в Outlook таким образом, чтобы она была доступна, когда пользователь работает в автономном режиме.
  
### <a name="address-book-policies"></a>Политики адресных книг

Exchange Online поддерживает политики адресных книг. Политики адресной книги позволяют разделять пользователей на отдельные группы, чтобы предоставлять каждой из них разные представления глобального списка адресов организации. При создании политики адресной книги ей назначается глобальный список адресов, автономная адресная книга, список помещений и один или несколько списков адресов. Затем вы можете назначить политики АДРЕСНЫХ книг пользователям почтовых ящиков, предоставляя им доступ к настраиваемому глобальному спискам адресов в Outlook и Outlook в Интернете. Администраторы могут настроить политики адресной книги с помощью удаленного сеанса Windows PowerShell. Чтобы узнать больше о политиках адресной книги, ознакомьтесь со статьей " [адресные книги в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203)".
  
### <a name="address-lists"></a>Списки адресов

Exchange Online поддерживает настройку списков адресов и глобальных списков адресов. Глобальный список адресов — это каталог всей организации всех пользователей с включенной поддержкой почты, групп рассылки и внешних контактов. Администраторы могут скрывать пользователей, группы рассылки и контакты из глобального списка адресов с помощью средства синхронизации каталогов или удаленной оболочки Windows PowerShell.
  
### <a name="hierarchical-address-books"></a>Иерархические адресные книги

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Группы рассылки (глобальные)

Группа рассылки (или список рассылки) — это набор пользователей, контактов и других групп рассылки, которые будут доступны всем пользователям в организации. Пользователи отправляют электронную почту на псевдоним группы рассылки для отправки сообщений всем пользователям в группе. Группы рассылки аналогичны личным группам рассылки, которые можно создать в Outlook, но списки их участников доступны в пределах всех организации. Администраторы создают группы рассылки в Центре администрирования Exchange. Группы также могут синхронизироваться с Exchange Online через локальный каталог Active Directory. Они отображаются в глобальном списке адресов в Outlook. Exchange Online поддерживает расширенные возможности групп рассылок, включая описанные ниже:
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Внешние контакты (глобальный список)

Внешний контакт — это запись, содержащая сведения о человеке, который работает за пределами указанной организации. Они аналогичны личным контактам, которые можно создать в Outlook, но доступны в пределах всех организации. Администраторы создают внешние контакты с помощью удаленного сеанса Windows PowerShell или Центра администрирования Exchange. Контакты также могут синхронизироваться с Exchange Online через локальный каталог Active Directory. Они отображаются в глобальном списке адресов в Outlook.
  
Дополнительную информацию о внешних контактах см. в статье [Создание связи организации в Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Календарь и расписание

### <a name="resource-mailboxes"></a>Почтовые ящики ресурса

Почтовые ящики ресурсов (например, конференц-залов и оборудования) служат для представления конференц-залов или иных ресурсов организации. Пользователи могут резервировать комнаты или ресурсы, добавляя псевдоним электронной почты ресурса для приглашений на собрания в Outlook или Outlook в Интернете. Конференц-залов и ресурсы отображаются в глобальном списке адресов в Outlook и Outlook в Интернете.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Дополнительные сведения о почтовых ящиках ресурсов см. в разделе
  
- [Создание почтовых ящиков помещений и управление ими](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Управление почтовыми ящиками оборудования](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Управление конференц-залами

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Администраторы могут настраивать автоматические ответы для конференц-зала и настраивать политики резервирования в Outlook в Интернете. Такая политика указывает, кто может бронировать ресурс, когда он может быть забронирован, какие сведения будут отображены в календаре ресурса, а также допустимый процент конфликтов расписаний. Администраторы могут отключить помощник по резервированию ресурсов и назначить конкретным пользователям возможность вручную контролировать приглашения на собрания для залов.
  
Администраторы управляют параметрами RBA с помощью удаленной консоли Windows PowerShell.
  
### <a name="out-of-office-replies"></a>Ответы об отсутствии на работе

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Общий доступ к календарю

Пользователи могут опубликовать свой личный календарь одним из двух способов:
  
- **Федеративный доступ к календарю** Под федерацией понимается базовая инфраструктура отношений доверия, поддерживающая федеративный общий доступ  простой способ для пользователей Exchange обмениваться сведениями о занятости на основе календаря и контактными данными с получателями во внешних федеративных организациях. Сюда включаются организации, использующие Exchange Online, а также организации с локальными системами Exchange Server 2010 или Exchange Server 2013. Администраторам Exchange Online не требуется настраивать отношения доверия с шлюзом Microsoft Federation Gateway, так как этот уровень доверия предварительно настроен для всех клиентов Exchange Online при создании службы Майкрософт. Политика общего доступа по умолчанию позволяет пользователям отправлять приглашения на общий доступ к календарю из Outlook в Интернете или Outlook 2010. Администраторы используют удаленную консоль Windows PowerShell, чтобы отключить эту политику, а также для настройки уровня данных, к которым пользователи могут открывать общий доступ в календаре. Администраторы также могут создать связь с другой федеративной организацией, которая обеспечивает требуемый уровень сведений о занятости для каждого пользователя без необходимости отправки приглашений на доступ отдельным пользователям. В рамках политик общего доступа, определяемых администратором, и связей организаций пользователи могут отдельно ограничить общий доступ. 
    
- **Доступ к календарю через Интернет** Служба Exchange Online позволяет публиковать календари в формате iCal для анонимного доступа внутри или за пределами организации. Получатели могут использовать Exchange, другую платформу или просто веб-браузер. Пользователи Exchange Online также могут подписаться на календари, опубликованные другими пользователями в Интернет-адресах с помощью iCal. Это отличается от федеративного доступа к календарю, который настраивается администратором и обеспечивает совместный доступ к данным о занятости между организациями. Пользователи не могут публиковать данные календаря в формате iCal до тех пор, пока администратор не настроил и не применит его к политике общего доступа. Администраторы могут отключить публикацию и подписку на iCal для пользователей в организации с помощью удаленной оболочки Windows PowerShell.
    
Дополнительные сведения о федеративном общем доступе см. в разделе [Общий доступ в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Средство поиска помещений Outlook 2010

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Новый список можно создать с помощью удаленной консоли Windows PowerShell. 
    
- Любая группа рассылки, содержащая только помещения, может быть преобразована в список помещений с помощью удаленной оболочки Windows PowerShell.
    
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  