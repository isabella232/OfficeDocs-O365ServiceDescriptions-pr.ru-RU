---
title: Функции соответствия требованиям и безопасности в Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
description: Ознакомьтесь с этой статьей, чтобы ознакомиться с функциями соответствия требованиям, доступными в Microsoft Exchange Online архива.
ms.openlocfilehash: e3dbf6db56830186324470714d76a05fc38c111f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670738"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Функции соответствия требованиям и безопасности в Exchange Online Archiving

## <a name="compliance-features-in-exchange-online-archiving"></a>Функции контроля соответствия требованиям в архивации на базе Exchange Online

В этой статье описываются функции соответствия требованиям Microsoft Exchange Online архива.
  
### <a name="retention-policies"></a>Политики хранения

Архивация на базе Exchange Online предлагает политики хранения, которые смогут помочь организациям снизить обязательства, связанные с обменом электронными и другими сообщениями. С помощью этих политик администраторы могут применить параметры хранения к конкретным папкам в папках пользователей "Входящие". Администраторы также могут предоставить пользователям меню политик хранения и позволить им применять политики к определенным пунктам, беседам или папок с помощью Outlook 2010 или более позднего или Outlook в Интернете. В Архивация на базе Exchange Online администраторы управляют политиками хранения из локальной инфраструктуры.
  
Архивация на базе Exchange Online предлагает два типа политик: политики архивации и политики удаления. Оба типа могут применяться к одному и тому же элементу или папке. Например, пользователь может пометить сообщение электронной почты таким образом, чтобы оно автоматически перемещалось в личный архив через указанное количество дней, а затем удалялось через другое количество дней.
  
С Outlook 2010 и более поздних и Outlook в Интернете пользователи могут применять политики хранения к папкам, беседам или отдельным сообщениям, а также просматривать примененные политики хранения и ожидаемые даты удаления сообщений. Сообщения пользователей в других почтовых клиентах могут удаляться или архивироваться на основе серверных политик хранения, создаваемых администратором, но они не предоставляют такого же уровня наглядности и управляемости.
  
Возможности политики хранения, предлагаемые в Exchange Online Archiving, такие же, как и в Exchange Server 2010 Пакет обновления 2 (SP2) и более поздней. Администраторы могут управлять политиками хранения из локальной Exchange Server 2010 и более поздних средах. Управляемые папки, более старый подход к управлению записями сообщений, введенный в Exchange 2007 г., недоступны и не совместимы с Exchange Online Archiving. Дополнительные сведения см. в статье [Теги хранения и политики хранения](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
  
### <a name="in-place-hold-and-litigation-hold"></a>Хранение на месте и хранение для судебного разбирательства

При наличии обоснованных предпосылок для судебных исков организациям требуется сохранять электронные данные (включая почту), связанные с делом. Такие предпосылки могут возникать до уточнения подробностей дела, и сохранение часто охватывает широкие области. Организации могут сохранять всю почту, относящуюся к конкретному вопросу, или всю электронную почту отдельных лиц.
  
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
  
Дополнительные сведения см. в статье [Удержание на месте и хранение для судебного разбирательства](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
> [!NOTE]
> Квота по умолчанию для папки восстанавливаемых элементов  100 ГБ для пользователей Архивация на базе Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Обнаружение электронных данных на месте

Exchange Online Archiving поддерживает In-Place для поиска содержимого почтовых ящиков в организации. Используя центр администрирования Exchange или удаленный Windows PowerShell с локального сервера Exchange 2013 г., администраторы или уполномоченные руководители discovery могут искать различные элементы почтовых ящиков, включая сообщения электронной почты, вложения, встречи в календаре, задачи и контакты. Функция обнаружения электронных данных на месте может одновременно выполнять поиск в основных почтовых ящиках и архивах. Богатые возможности фильтрации включают отправитель, приемник, типы сообщений, дату отправки, дату получения, копию углерода и слепую копию углерода, а также синтаксис "Язык запросов ключевых слов" (KQL). Дополнительные сведения см. в статье [Обнаружение электронных данных на месте](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
С помощью Центра администрирования Exchange и удаленного сеанса Windows PowerShell можно выполнять поиск в 5000 почтовых ящиках одновременно при выполнении одного запроса на обнаружение электронных данных на месте. Дополнительные сведения об использовании удаленного сеанса Windows PowerShell для обнаружения электронных данных на месте см. в статье [New-MailboxSearch](/powershell/module/exchange/new-mailboxsearch). 
  
> [!NOTE]
> В удаленном сеансе Windows PowerShell командлет  `Search-Mailbox` позволяет выполнять поиск данных в более чем 5000 почтовых ящиков. Дополнительные сведения о поиске в большом количестве почтовых ящиков с помощью удаленного сеанса Windows PowerShell см. в статье [Search-Mailbox](/powershell/module/exchange/search-mailbox). 
  
Результаты обнаружения электронных данных на месте можно просмотреть в Центре администрирования Exchange, экспортировать в PST-файл или скопировать в специальный почтовый ящик, который называется почтовым ящиком найденных сообщений. Сотрудники, ответственные за обеспечение соответствия требованиям, или администраторы могут подключиться к почтовому ящику найденных сообщений, чтобы просмотреть сообщения. Дополнительные сведения см. в статье [Создание поискового запроса на обнаружение электронных данных на месте](/microsoft-365/compliance/content-search).
  
> [!NOTE]
> Копируя результаты поиска для поиска методом обнаружения электронных данных на месте, который выполняется среди локальных и облачных почтовых ящиков или архивов, вы должны выбрать почтовый ящик найденных сообщений. Сообщения из локального основного почтового ящика и облачного архива копируются в локальный почтовый ящик найденных сообщений. 
  
Администраторы могут также искать и удалять недопустимые сообщения, отправленные на несколько почтовых ящиков в организации. Например, если конфиденциальные зарплатные данные будут случайно отправлены всем сотрудникам, администратор сможет удалить сообщение из почтовых ящиков пользователей. Такой тип поиска недоступен в Центре администрирования Exchange. Он должен выполняться с помощью удаленного сеанса PowerShell. Подробные инструкции по удалению сообщений из почтовых ящиков пользователей см. в статье [Поиск и удаление сообщений](/Exchange/policy-and-compliance/ediscovery/delete-messages).
  
## <a name="security-features-in-exchange-online-archiving"></a>Функции безопасности в архивации на базе Exchange Online

В следующих разделах описаны функции безопасности Microsoft Архивация на базе Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Шифрование между локальными серверами и средством архивации на базе Exchange Online

Протокол TLS позволяет шифровать подключения между почтовыми серверами для предотвращения спуфинга и защиты конфиденциальности передаваемых сообщений. TLS также используется для обеспечения безопасности локального трафика почтовых серверов в центрах обработки данных Майкрософт для Exchange Online Archiving.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Шифрование между клиентами и средством архивации на базе Exchange Online

В клиентских соединениях с Архивация на базе Exchange Online используются следующие методы шифрования для повышения безопасности:
  
- SSL используется для обеспечения безопасности Outlook, Outlook в Интернете и Exchange веб-служб с помощью порта TCP 443.
    
- клиентские подключения к локальным серверам не изменяются с введением Архивация на базе Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Шифрование: S/MIME и PGP

Архивация на базе Exchange Online будет хранить сообщения S/MIME. Но Архивация на базе Exchange Online не размещает функции S/MIME, не хранит открытые ключи, не предоставляет службы репозиториев ключей, управления ключами и каталогов ключей, так как все эти службы привязаны к локальной инфраструктуре Exchange.
  
Аналогично, Архивация на базе Exchange Online будет хранить сообщения, зашифрованные с помощью сторонних клиентских решений по шифрованию, таких как PGP.
  
### <a name="information-rights-management"></a>Управление правами на доступ к данным

Архивация на базе Exchange Online не предоставляет размещенные службы управления правами на доступ к данным (IRM), но администраторы могут использовать локальную службу управления правами Active Directory. Если сервер службы управления правами Active Directory развернут, Outlook может подключаться непосредственно к серверу, позволяя пользователям создавать и читать сообщения, защищенные с помощью IRM. Если настроено взаимодействие между сервером службы управления правами Active Directory и локальной средой Exchange, пользователи смогут создавать и читать сообщения, защищенные с помощью IRM.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Поддержка IRM в Outlook в Интернете

Пользователи могут читать и создавать сообщения, защищенные от IRM, в Outlook в Интернете, как и в Outlook. Сообщения с защитой IRM в Outlook в Интернете можно получить через Internet Explorer, Firefox, Safari и Chrome (без необходимости подключения). Для сообщений доступен полнотекстовый поиск, представление беседы и панель просмотра. Для этого необходимо настроить взаимодействие между сервером службы управления правами Active Directory и локальной средой Exchange.
  
#### <a name="irm-search"></a>поиск IRM;

Сообщения, защищенные IRM, индексируются, и по ним можно выполнять поиск, в том числе по заголовкам, теме, основному тексту и вложениям. Пользователи могут искать элементы, защищенные от IRM Outlook и Outlook в Интернете, а администраторы могут искать элементы, защищенные от IRM, с помощью In-Place eDiscovery или cmdlet **Search-Mailbox.**
  
### <a name="auditing"></a>Аудит

Архивация на базе Exchange Online предоставляет встроенные возможности аудита двух типов.
  
- **Журнал** аудита администратора . Журнал аудита администратора позволяет клиентам отслеживать изменения, внесенные их администраторами в Exchange Online Archiving среде, включая изменения ролей RBAC или Exchange политик и параметров. 
    
- **Ведение журнала аудита** почтовых ящиков — журнал аудита почтовых ящиков позволяет пользователям отслеживать доступ к почтовым ящикам другими пользователями, кроме владельца почтового ящика. 
    
В Центре администрирования Exchange доступно несколько предварительно заданных отчетов аудита, в том числе "Изменения ролей администратора", "Судебное удержание" и "Доступ к чужим почтовым ящикам". Администраторы могут фильтровать отчеты по дате и роли, а также экспортировать все события аудита для указанных почтовых ящиков в формате XML для долгосрочного хранения или создания специальных отчетов.
  
Ведение журнала аудита действий администратора включено по умолчанию, а ведение журнала аудита почтового ящика по умолчанию отключено. Администраторы с помощью удаленного сеанса Windows PowerShell могут включить ведение журнала аудита почтового ящика для выбранных или всех почтовых ящиков в своей организации. Дополнительные сведения см. в статье [Отчеты аудита](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. Exchange Online Archiving [службы.](exchange-online-archiving-service-description.md)
