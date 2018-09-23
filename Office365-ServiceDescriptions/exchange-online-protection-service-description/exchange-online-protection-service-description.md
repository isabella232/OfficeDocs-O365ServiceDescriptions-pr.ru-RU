---
title: Описание службы Exchange Online Protection
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Узнайте о компонентах и требованиях для Exchange Online Protection. Ознакомьтесь со списком планов, в которые включена служба Exchange Online Protection, а также со сравнением компонентов, доступных в этих планах.
ms.openlocfilehash: 6e7ffd6a2248acfc763a71e35ce0daba0f9b0308
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036781"
---
# <a name="exchange-online-protection-service-description"></a>Описание службы Exchange Online Protection

Узнайте о компонентах и требованиях для Exchange Online Protection. Ознакомьтесь со списком планов, в которые включена служба Exchange Online Protection, а также со сравнением компонентов, доступных в этих планах.
  
Microsoft Exchange Online Protection (EOP)  это облачная служба фильтрации электронной почты, которая помогает защитить организацию от нежелательной почты и вредоносных программ, передаваемых через электронную почту. К тому же, эта служба обладает функциями для защиты организации от нарушений политик обмена сообщениями. EOP может упростить управление вашей среды обмена сообщениями и облегчить многие тяготы, которые приходят с поддержкой локального аппаратного и программного обеспечения.
  
Ниже приведены основные способы, с помощью которых можно использовать EOP для защиты сообщений.
  
- **В случае автономного** EOP обеспечивает защиту электронной почты на основе облака для локальной среды Exchange Server 2013 прежних версий Exchange Server, или любые другие локального решения электронной почты SMTP. 
    
- **Как часть Microsoft Exchange Online** По умолчанию EOP защищает облачные почтовые ящики Exchange Online. Дополнительные сведения о Exchange Online см. в разделе [Описание службы Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).
    
- **В гибридном развертывании** EOP можно настроить для защиты среды обмена сообщениями и управления маршрутизацией почты, когда есть набор локальных и облачных почтовых ящиков. 
    
Сравнение функций в разных планах см. на странице [Сравнение планов Office 365 для бизнеса](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
Сведения о покупке Exchange Online Protection см. на странице [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Вы можете экспортировать, сохранять и печатать страницы описаний служб Office 365. Узнайте, как [экспортировать несколько страниц](https://go.microsoft.com/fwlink/?LinkId=403349).
  
> [!IMPORTANT]
> EOP заменяет Forefront Online Protection для Exchange (FOPE). Все клиенты FOPE будут перенесены в EOP. EOP обеспечивает защиту и управление, предоставляемые FOPE, а также включает в себя дополнительные функции. Для получения дополнительных сведений о переходе от FOPE к EOP посетите [Центр перехода со службы Forefront Online Protection для Exchange (FOPE)](http://www.movetoeop.com). 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Новые возможности Exchange Online Protection (EOP)

Сведения о новых функциях в EOP см. в статье [Что нового в Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390). Сравнение функций FOPE и EOP см. в статье [Сравнение функций FOPE и EOP](https://go.microsoft.com/fwlink/p/?LinkId=320391).
  
## <a name="exchange-online-protection-eop-plans"></a>Планы Exchange Online Protection (EOP)

EOP предоставляется в рамках подписки на следующие планы:
  
|**План**|**Описание**|
|:-----|:-----|
|[Отдельная служба EOP](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |EOP защищает ваши локальные почтовые ящики;  <br/> |
|[Функции EOP в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |EOP защищает ваши почтовые ящики, размещенные в облаке Exchange Online;  <br/> |
|[Лицензия Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |EOP защищает ваши локальные почтовые ящики, как изолированная EOP, а также включает защиту от потери данных (DLP) и отправку отчетов с помощью веб-служб.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>клиентская лицензия Exchange Enterprise CAL со службами:

предоставляет функции защиты электронной почты EOP для локальной среды обмена сообщениями вместе со следующими функциями.
  
- [Предотвращение потери данных (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Создание отчетов с помощью веб-служб](reporting-and-message-trace.md#reporting-using-web-services)
    
Дополнительные сведения о лицензиях Exchange Enterprise CAL with Services см. в разделе [Лицензирование Exchange Server 2013](https://go.microsoft.com/fwlink/p/?LinkId=293699).
  
Если у вас есть лицензии Exchange Enterprise CAL with Services и вы хотите подготовить службу, следуйте инструкциям в статье [Настройка службы EOP](https://go.microsoft.com/fwlink/p/?LinkId=320397). Действия по настройке такие же, как при настройке отдельной службы EOP.
  
> [!NOTE]
> Новые функции для клиентской лицензии Exchange Enterprise со службами развертываются одновременно с Exchange Online, а не с изолированной службой EOP. Имейте в виду, что графики развертывания изолированной службы EOP и клиентской лицензии Exchange Online или Exchange Enterprise со службами могут немного отличаться. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Требования для Exchange Online Protection (EOP)

EOP можно использовать с любым агентом пересылки почты SMTP, например Microsoft Exchange Server 2013. Сведения о поддерживаемых EOP операционных системах, веб-браузерах и языках см. в подразделах "Поддерживаемые браузеры" и "Поддерживаемые языки" статьи [Центр администрирования Exchange в Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="limits"></a>Ограничения

Сведения об ограничениях EOP см. в статье [Ограничения Exchange Online Protection](exchange-online-protection-limits.md).
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Доступность функций в планах Exchange Online Protection (EOP)

Каждая функция приведена ниже. Более подробные сведения о функциях EOP доступны по ссылкам в таблице. Exchange Online обычно относится к семейству служб Office 365 корпоративный.
  
|||||
|:-----|:-----|:-----|:-----|
|**Функция** <br/> |**Изолированная EOP** <br/> |**Функции EOP в Exchange Online** <br/> |**Клиентская лицензия Exchange Enterprise CAL со службами** <br/> |
|[Получатели почты](recipient-domain-and-company-management.md#mail-recipients) <br/> |Да<sup>1</sup> <br/> |Да<sup>1</sup> <br/> |Да  <br/> |
|[Разрешения для группы ролей администраторов](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Да,<sup>2</sup> <br/> |Да  <br/> |Да  <br/> |
|[Управление доменами](recipient-domain-and-company-management.md#domain-management) <br/> |Да,<sup>3</sup> <br/> |Да,<sup>3</sup> <br/> |Да,<sup>3</sup> <br/> |
|[Соответствующие поддомены](recipient-domain-and-company-management.md#match-subdomains) <br/> |Да  <br/> |Да  <br/> |Нет  <br/> |
|[Пограничная блокировка на основе каталогов](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Правила транспорта](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Да<sup>3, 4, 14</sup> <br/> |Да<sup>3, 4, 14</sup> <br/> |Да  <br/> |
|[Ведение журнала аудита](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Да,<sup>5</sup> <br/> |Да  <br/> |Да  <br/> |
|[Предотвращение потери данных (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |Нет  <br/> |Да  <br/> |Да,<sup>6</sup> <br/> |
|[Шифрование сообщений Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Да,<sup>12</sup> <br/> |Да  <br/> |Да,<sup>12</sup> <br/> |
|[Защита от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (встроенная)  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Настройка политик защиты от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Да,<sup>7</sup> <br/> |Да  <br/> |Да  <br/> |
|[Защита от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (встроенная)  <br/> |Да,<sup>13</sup> <br/> |Да  <br/> |Да  <br/> |
|[Настройка политик защиты от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): управление администраторами  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): самостоятельное управление пользователями  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Надстройка сообщения о нежелательной почте для Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Создание отчетов о нежелательной почте в Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Да,<sup>8</sup> <br/> |Нет<sup>8</sup> <br/> |Нет<sup>8</sup> <br/> |
|[Маршрутизация сообщений между Office 365 и почтовыми серверами пользователя](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Защищенный обмен сообщениями с доверенным партнером](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Добавление IP-адреса партнера в список надежных отправителей](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Условная маршрутизация почты](mail-flow-eop.md#conditional-mail-routing) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Маршрутизация гибридной почты](mail-flow-eop.md#hybrid-mail-routing) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Отчеты Центра администрирования Office 365](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |Yes<sup>9</sup> <br/> |Да,<sup>10</sup> <br/> |Да <sup>9, 10</sup> <br/> |
|[Отчеты о приложениях для скачивания Excel](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Да  <br/> |Да  <br/> |Yes<sup>11</sup> <br/> |
|[Создание отчетов с помощью веб-служб](reporting-and-message-trace.md#reporting-using-web-services) <br/> |Нет  <br/> |Да  <br/> |Да  <br/> |
|[Трассировка сообщений](reporting-and-message-trace.md#message-trace) <br/> |Yes<sup>15</sup> <br/> |Yes<sup>15</sup> <br/> |Да  <br/> |
|[Доступ к центру администрирования Office 365](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Доступ в Центр администрирования Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center)  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|[Удаленный доступ к Windows PowerShell](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Да,<sup>2</sup> <br/> |Да  <br/> |Да  <br/> |
   
> [!NOTE]
> <sup>1</sup> почтовых пользователей определяются как «Почтовые ящики» и, вместе с внешними почтовыми контактам, могут быть добавлены, удалены и управляться иным способом непосредственно в центре администрирования Exchange (EAC). <br/>Настройка No RBAC <sup>2</sup> . Только роли администраторов. <br/> <sup>3</sup> можно просмотреть управляемых доменов и типы домена можно редактировать в центре администрирования Exchange. Все другие Управление доменами необходимо выполнить в центре администрирования Office 365. <br/><sup>4</sup> доступные гибкие условия и действия отличаются в зависимости от EOP и Exchange Online. Список доступных условий и действий в службе EOP в разделе [Условия правил транспорта](https://go.microsoft.com/fwlink/p/?LinkId=320392) и [Действия правил транспорта](https://go.microsoft.com/fwlink/p/?LinkId=320393). Список доступных условий и действий в Exchange Online в разделе [Условия правил транспорта](https://go.microsoft.com/fwlink/p/?LinkId=320394) и [Действия правил транспорта](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/><sup>5</sup> отчеты аудита EOP являются подмножеством отчетов аудита Exchange Online, которые исключают сведения о почтовых ящиках. <br/> <sup>6</sup> советов политики защиты от потери данных, недоступны для клиентских лицензий Exchange Enterprise CAL со службами.<br/><sup>7</sup> действия фильтрации содержимого по умолчанию — перемещение сообщений нежелательной почты в папку нежелательной почты получателей. Для работы с локальными почтовыми ящиками необходимо также настроить два правила транспорта Exchange на локальных серверах для обнаружения нежелательной почты заголовки, добавляемые в EOP. Для получения дополнительных сведений см. [Убедитесь, что нежелательной почты перенаправляется в папку нежелательной электронной почты каждого пользователя](https://go.microsoft.com/fwlink/p/?LinkId=320396). <br/><sup>8</sup> эта функция доступна для клиентов Exchange Server 2013 с пакетом обновления 1 (SP1), почтовые ящики которых фильтруются по EOP и скоро будет доступно для Exchange Online. <br/><sup>9</sup> отчеты EOP являются подмножеством отчетов Exchange Online, которые исключают сведения о почтовых ящиках. <br/><sup>10</sup> отчетов включает в себя защиты от потери данных. <br/><sup>11</sup> клиентская лицензия Exchange Enterprise CAL со службами следует установить книгу, выбрав службу **Exchange Online** вместо службы **Exchange Online Protection** . <br/><sup>12</sup> поддерживается для локальных пользователей, которые приобрели Azure защита информации и использовать Exchange Online Protection для маршрутизации электронной почты через Exchange Online. <br/> <sup>13</sup> сканирует входящие и исходящие сообщения, но не сканирует внутренние сообщения, отправляемые одним сотрудником организации другому сотруднику вашей организации. <br/><sup>14</sup> доступные предикаты и действия отличаются в зависимости от EOP и Exchange Online. <br/> <sup>15</sup> установки гибридной недоступны через мастер гибридной, но можно настроить вручную при наличии Exchange с пакетом обновления 1. 