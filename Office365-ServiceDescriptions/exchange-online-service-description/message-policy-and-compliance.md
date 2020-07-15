---
title: Политика обработки сообщений и соответствие требованиям
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132703"
---
# <a name="message-policy-and-compliance"></a>Политика обработки сообщений и соответствие требованиям

## <a name="archiving-exchange-online-based-mailboxes"></a>Архивирование почтовых ящиков на основе сервера Exchange Online

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online предоставляет встроенные возможности архивирования для облачных почтовых ящиков, в том числе архив на месте, обеспечивающий пользователей удобным местом для хранения старых электронных сообщений. Архив на месте — это специальный тип почтового ящика, который появляется рядом с основными папками почтовых ящиков пользователя в Outlook и Outlook в Интернете. Пользователи могут открывать архив и выполнять в нем поиск таким же способом, как и в основных почтовых ящиках. Доступные функции зависят от используемого клиента:
  
- **Outlook 2016, outlook 2013, outlook 2010 и Outlook в Интернете** У пользователей есть доступ ко всем функциям архива, а также связанным функциям соответствия, таким как управление хранением и политиками архивации. 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
Администраторы включают для отдельных пользователей функцию личного архива с помощью Центра администрирования Exchange или удаленной оболочки Windows PowerShell.
  
Дополнительные сведения см. в следующих разделах:
  
- [Архивные почтовые ящики в Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Включение и отключение архивного почтового ящика в Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Размеры архива

В каждом личном архиве могут храниться только данные обмена сообщениями одного пользователя. Распределение хранилища зависит от плана подписки. Дополнительные сведения о размерах архивных почтовых ящиков приведены в разделе "пределы хранилища почтовых ящиков" в разделе [Exchange Online Limits](exchange-online-limits.md).
  
> [!IMPORTANT]
> - Не разрешается использование функции ведения журнала, правил транспорта или правил автоматической пересылки для копирования сообщений на почтовый ящик Exchange Online, чтобы создать архив. Корпорация Майкрософт оставляет за собой право отказаться от неограниченного архивирования в случаях, когда Архив почтовых ящиков не используется в личном сценарии или в других случаях недопустимого использования.
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online не поддерживает командлет _New-MailboxImportRequest_ Windows PowerShell для Exchange Server 2010 с пакетом обновления 1 (SP1) или более поздней версии для импорта PST-файлов с помощью администратора в личный архив. Если у пользователя имеется и основной почтовый ящик, и архив в Exchange Online, администратор может использовать бесплатный инструмент PST Capture для импорта данных PST-файлов в основной или архивный почтовый ящик пользователя.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Архивация сообщений в облаке для локальных почтовых ящиков

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> Пользователи с локальным почтовым ящиком на сервере почтовых ящиков Exchange 2010 с примененной политикой управляемых папок не могут активировать локальный или облачный архив на месте. 
  
## <a name="retention-tags-and-retention-policies"></a>Теги хранения и политики хранения

Exchange Online предлагает политики хранения, которые смогут помочь организациям снизить обязательства, связанные с обменом электронными и другими сообщениями. С помощью этих политик администраторы могут применить параметры хранения к конкретным папкам в папках пользователей "Входящие". Администраторы также могут предоставить пользователям меню политик хранения и разрешить им применять политики к определенным элементам, беседам или папкам с помощью Outlook 2010 или более поздней версии или Outlook в Интернете.
  
В Exchange Online администраторы могут управлять политиками хранения с помощью Центра администрирования Exchange (EAC) или удаленной оболочки Windows PowerShell.
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
В Outlook 2010 или более поздней версии и Outlook в Интернете пользователи могут применять политики хранения к папкам, беседам или отдельным сообщениям. Они также могут просматривать примененные политики хранения и даты ожидаемого удаления сообщений. Пользователи других почтовых клиентов могут только удалять или архивировать сообщения на основе серверных политик хранения, установленных администратором.
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> Управляемые папки  предыдущий подход к управлению записями сообщений, который использовался в Exchange Server 2007,  не доступны в Exchange Online. 
  
Дополнительные сведения см. в статье [Теги хранения и политики хранения](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Шифрование статических данных

Шифрование данных клиента на REST предоставляется несколькими технологиями на стороне службы, включая BitLocker, DKM, шифрование службы хранилища Azure и шифрование служб в Exchange Online, Skype для бизнеса, OneDrive для бизнеса и SharePoint Online. Шифрование службы Office 365 включает в себя возможность использования ключей шифрования, которые хранятся в Azure Key Vault. Этот параметр, который называется ключом [клиента](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697), доступен для Exchange Online, SharePoint Online и OneDrive для бизнеса. 
  
### <a name="bitlocker"></a>BitLocker

Microsoft Servers использует BitLocker для шифрования дисков, содержащих данные о клиентах, в оставшейся части уровня громкости. Шифрование BitLocker — это функция защиты данных, встроенная в Windows. BitLocker — это одна из технологий, используемых для защиты от угроз, в случае возникновения промежутков в других процессах или элементах управления (например, управления доступом или повторном использовании оборудования), которые могут привести к тому, что кто-то получает физический доступ к дискам с данными клиента. В этом случае BitLocker исключает возможность кражи или разглашения данных из-за потери, кражи или неправильного списания компьютеров и дисков. 
  
### <a name="distributed-key-manager"></a>Диспетчер распределенных ключей

Кроме BitLocker, мы используем технологию, именуемую диспетчером распределенных ключей (DKM). DKM — это клиентская функциональность, которая использует набор секретных ключей для шифрования и расшифровки информации. Только члены определенной группы безопасности в доменных службах Active Directory могут получить доступ к этим ключам для расшифровки данных, зашифрованных с помощью DKM. В Exchange Online только некоторые учетные записи служб, под которыми выполняются процессы Exchange, входят в эту группу безопасности. В рамках стандартной процедуры в центре обработки данных ни один человек не получает учетные данные, включенные в эту группу безопасности, и поэтому ни один человек не получает доступ к ключам, которые могут расшифровать эти секреты.
  
## <a name="customer-key"></a>Ключ клиента

С помощью ключа клиента вы можете управлять ключами шифрования вашей организации, а затем настраивать их для шифрования данных на REST в центрах обработки данных Майкрософт. К ним относятся данные из Exchange Online и Skype для бизнеса, хранящиеся в почтовых ящиках, а также файлы, хранящиеся в SharePoint Online и OneDrive для бизнеса. Дополнительные сведения см в разделе [Управление данными с помощью ключа клиента](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) и [шифрования службы с помощью ключевых вопросов клиента](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Шифрование сообщений Office 365

Шифрование сообщений Office 365 позволяет пользователям электронной почты отправлять зашифрованные сообщения электронной почты всем пользователям. Мы объявили о новых возможностях шифрования сообщений Office, которые используют функции защиты в службе шифрования данных Azure. Это новые возможности, обеспечивающие расширенные возможности для пользователей, упрощающие совместное использование и совместную работу с защищенными сообщениями, которые находятся внутри или за пределами Организации. Новые возможности шифрования сообщений Office имеют некоторые требования к установке. Узнайте, как настроить новые возможности шифрования сообщений Office 365 на основе Azure Information Protection. Клиенты, которые используют устаревшее шифрование сообщений Office 365, не получают новые возможности без соблюдения указанных выше рекомендаций по настройке. Прочитайте [вопросы и ответы](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) для получения дополнительных сведений о том, что входит в новые возможности шифрования сообщений в Office 365 и более ранних версий. 

Расширенное шифрование сообщений Office 365 обеспечивает дополнительную защиту, предоставляя срок действия и отзыв сообщений.  Вы также можете создать несколько шаблонов для зашифрованных сообщений электронной почты, исходящих из вашей организации.  Расширенное шифрование сообщений включено в Microsoft 365, Office 365, Microsoft 365, Microsoft, Microsoft и Office 365 Enterprise, а также Office 365 для образования A5. Если в вашей организации есть подписка, не включающая в себя приложение Office 365 Advanced Message Encryption, вы можете приобрести соответствие корпорации Майкрософт 365 о том или дополнительной конфигурации соответствия Office 365 с надстройкой.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME поддерживается в Microsoft EDGE и Internet Explorer 11. В настоящее время браузеры Firefox, Opera и Chrome не поддерживают протокол S/MIME. Дополнительные сведения см. в статье [S/MIME для подписи и шифрования сообщений](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Хранение на месте и хранение для судебного разбирательства

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
  
Дополнительные сведения см. в статье [Удержание на месте и хранение для судебного разбирательства](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Обнаружение электронных данных на месте

Exchange Online позволяет клиентам искать содержимое почтовых ящиков в Организации с помощью веб-интерфейса. Администраторы или представители службы обеспечения безопасности и соответствия, уполномоченные выполнять поиск электронных данных на месте (по назначению), могут осуществлять поиск в сообщениях электронной почты, вложениях, встречах в календаре, заданиях, контактах и других элементах. Функция обнаружения электронных данных на месте может одновременно выполнять поиск в основных почтовых ящиках и архивах. Разнообразные возможности фильтрации включают отправителей, получателей, типы сообщений, даты отправки и получения, копии и скрытые копии, а также синтаксис KQL. Результаты поиска также включают элементы в папке "Удаленные", если они совпадают с запросом поиска.
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
Администраторы могут использовать Центр администрирования Exchange или удаленную консоль Windows PowerShell для поиска 10 000 почтовых ящиков одновременно при обнаружении электронных данных на месте. 
  
В Exchange Online авторизованные пользователи могут выполнять электронное обнаружение на месте и выбирать одно из следующих действий.
  
- **Оценка результатов поиска** Получение оценки количества сообщений, которые будут возвращены в результате поиска, включая статистики ключевых слов, чтобы определить эффективность ключевых слов, используемых в поиске, и при необходимости настроить параметры поиска. 
    
- **Просмотр результатов поиска**
    
- Копирование сообщений, возвращенных в результатах поиска, в почтовый ящик обнаружения.
    
Дополнительные сведения см. в статье [Обнаружение электронных данных на месте](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Правила потока обработки почты

Правила для обработки почтового процесса можно использовать для поиска определенных условий в сообщениях, которые проходят через организацию и действуют на них. Правила обработки почтового процесса позволяют применять политики обмена сообщениями к сообщениям электронной почты, защищенные сообщения, защищать системы обмена сообщениями и предотвращать утечку информации.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- предотвращение поступления в организацию или передачи из нее несоответствующего содержимого
    
- фильтрация конфиденциальных данных организации
    
- отслеживание или копирование сообщений, отправленных или принятых определенными людьми
    
- переадресация входящих и исходящих сообщений для проверки перед доставкой
    
- добавление в сообщения, проходящие через организацию, заявлений об отказе от ответственности
    
> [!IMPORTANT]
> Типы файлов вложения, которые требуют установки сторонних интерфейсов iFilter на сервере электронной почты (например, Adobe. PDF), не могут быть проверены с помощью правил обработки почтового процесса до установки соответствующего фильтра iFilter. Для получения дополнительных сведений о типах файлов, поддерживаемых правилами для почтового процесса, ознакомьтесь со статьей [Использование правил для обработки почтового ящика для проверки вложений в сообщениях в Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Дополнительные сведения о правилах потока обработки почты см. в статье [Mail flow rules in Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Защита от потери данных

Функция защиты от потери данных (DLP) помогает определять, просматривать и защищать конфиденциальную информацию в организации с помощью глубокого анализа содержимого. Защита от потери данных  это расширенная функция, все более важная для корпоративных систем обмена сообщениями, поскольку важные для бизнеса сообщения электронной почты содержат конфиденциальные данные, для которых требуется защита. Функция DLP в Exchange Online позволяет защищать конфиденциальные данные, не влияя на производительность сотрудников.
  
Политики защиты от потери данных можно настроить в интерфейсе управления Центра администрирования Exchange (EAC), что позволит выполнять следующие действия. 
  
- Начинать с предварительно настроенным шаблоном политики, что может помочь при обнаружении определенных типов конфиденциальной информации, таких как данные PCI-DSS (стандарт безопасности данных индустрии платежных карт), данные Акта Грэма-Лича-Блили или даже персональные сведения для языкового стандарта.
    
- Использовать все возможности существующих условий и действий правил транспорта, а также добавлять новые правила транспорта.
    
- Проверять эффективность политик защиты от потери данных до их полного принудительного применения.
    
- Включать собственные пользовательские шаблоны политики защиты от потери данных и типы конфиденциальной информации.
    
- Определять конфиденциальную информацию во вложениях, тексте или теме сообщения и изменять уровень вероятности, на котором работает Exchange Online.
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- Добавление подсказок политики, которые помогают уменьшить потерю данных за счет отображения уведомления для пользователей Outlook 2016, Outlook 2013, Outlook в Интернете и OWA для устройств, а также для повышения эффективности политик путем предоставления ложных положительных отчетов. 
    
- Просматривать данные об инциденте в отчетах защиты от потери данных или добавлять собственные специальные отчеты с помощью действия для создания отчета об инциденте.
    
Подробнее о [защите от потери данных](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Ведение журнала

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
Чтобы обеспечить успешное и надежное решение для ведения журнала, необходимо выполнить следующие задачи:
  
- Убедитесь, что назначение ведения журнала не является почтовым ящиком Exchange Online.
    
- Создание в каталоге пользователя контактного объекта для целевого адреса электронной почты SMTP для ведения журнала.
    
- Создание второго контактного объекта в качестве альтернативного почтового ящика журнала для записи отчетов журнала, когда основной почтовый ящик журнала недоступен.
    
- Обеспечьте правильное управление, избыточность, доступность, производительность и функциональные уровни целевого SMTP-сервера, чтобы обеспечить успешную прием почты.
    
- Обеспечение соответствующего взаимодействия с сервером Exchange Server и транспортом Exchange, в том числе форматы сообщений, интеграция информации отправителя и получателя и соответствующее преобразование содержимого.
    
Подробнее о [ведении журнала](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  

