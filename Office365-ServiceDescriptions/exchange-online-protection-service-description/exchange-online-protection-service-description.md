---
title: Описание службы Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Узнайте о компонентах и требованиях для Exchange Online Protection. В этот список входят планы, обеспечивающие защиту Exchange Online, а также сравнение функций в этих планах.
ms.openlocfilehash: 462e1f100382ffddd9f456f38525158826720f53
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581915"
---
# <a name="exchange-online-protection-service-description"></a>Описание службы Exchange Online Protection

Узнайте о компонентах и требованиях для Exchange Online Protection. В этот список входят планы, обеспечивающие защиту Exchange Online, а также сравнение функций в этих планах.

Microsoft Exchange Online Protection (EOP)  это облачная служба фильтрации электронной почты, которая помогает защитить организацию от нежелательной почты и вредоносных программ, передаваемых через электронную почту. К тому же, эта служба обладает функциями для защиты организации от нарушений политик обмена сообщениями. EOP может упростить управление вашей среды обмена сообщениями и облегчить многие тяготы, которые приходят с поддержкой локального аппаратного и программного обеспечения.

Ниже приведены основные способы, с помощью которых можно использовать EOP для защиты сообщений.

- **В автономном сценарии**: EOP предоставляет облачную защиту электронной почты для локальной среды exchange Server 2013 или более поздней версии, устаревших версий Exchange Server или для любого другого локального решения электронной почты SMTP.

- **Как часть Microsoft Exchange Online**: по умолчанию EOP защищает облачные почтовые ящики Exchange Online. Дополнительные сведения об Exchange Online см. в [описании службы Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).

- **В гибридном развертывании**: EOP можно настроить для защиты среды обмена сообщениями и управления маршрутизацией почты при наличии смешанных локальных и облачных почтовых ящиков.

Сравнение функций в разных планах см. на странице [Сравнение планов Office 365 для бизнеса](https://products.office.com/business/compare-more-office-365-for-business-plans).

Сведения о покупке Exchange Online Protection см. на странице [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP заменила Forefront Online Protection для Exchange (FOPE). Все клиенты FOPE перенесены в EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Новые возможности Exchange Online Protection (EOP)

[План Office 365 для бизнеса](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) — это хороший ресурс для получения сведений о будущих новых возможностях.

## <a name="exchange-online-protection-eop-plans"></a>Планы Exchange Online Protection (EOP)

EOP предоставляется в рамках подписки на следующие планы:

|**План**|**Описание**|
|:-----|:-----|
|[Отдельная служба EOP](https://products.office.com/exchange/exchange-email-security-spam-protection)|EOP защищает ваши локальные почтовые ящики;|
|[Функции EOP в Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|EOP защищает ваши почтовые ящики, размещенные в облаке Exchange Online;|
|[Лицензия Exchange Enterprise CAL with Services](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|EOP защищает ваши локальные почтовые ящики, как изолированная EOP, а также включает защиту от потери данных (DLP) и отправку отчетов с помощью веб-служб.|

### <a name="exchange-enterprise-cal-with-services-features"></a>клиентская лицензия Exchange Enterprise CAL со службами:

предоставляет функции защиты электронной почты EOP для локальной среды обмена сообщениями вместе со следующими функциями.

- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Создание отчетов с помощью веб-служб](reporting-and-message-trace.md#reporting-using-web-services)

Дополнительные сведения о лицензировании служб Exchange Enterprise CAL со службами можно найти в разделе [Лицензирование Exchange Server](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Если у вас есть лицензии на Exchange Enterprise CAL со службами и вы хотите подготовить службу, следуйте инструкциям в статье [Настройка службы EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service). Действия по настройке такие же, как при настройке отдельной службы EOP.

> [!NOTE]
> Новые функции для клиентской лицензии Exchange Enterprise со службами развертываются одновременно с Exchange Online, а не с изолированной службой EOP. Имейте в виду, что графики развертывания изолированной службы EOP и клиентской лицензии Exchange Online или Exchange Enterprise со службами могут немного отличаться.

## <a name="requirements-for-exchange-online-protection-eop"></a>Требования для Exchange Online Protection (EOP)

EOP можно использовать с любым агентом передачи почты SMTP, например Microsoft Exchange Server. Сведения о операционных системах, веб-браузерах и языках, поддерживаемых EOP, можно найти в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" в [центре администрирования Exchange в Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Ограничения

Сведения об ограничениях EOP см. в статье [Ограничения Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Доступность функций в планах Exchange Online Protection (EOP)

Каждая функция приведена ниже. Более подробные сведения о функциях EOP доступны по ссылкам в таблице. Exchange Online обычно относится к семейству служб Office 365 корпоративный.

|||||
|:-----|:-----|:-----|:-----|
|**Функция**|**Изолированная EOP**|**Функции EOP в <br/> Exchange Online**|**Клиентская <br/> лицензия Exchange Enterprise CAL со службами**|
|[Получатели почты](recipient-domain-and-company-management.md#mail-recipients)|Да<sup>1</sup>|Да<sup>1</sup>|Да|
|[Разрешения для группы ролей администраторов](recipient-domain-and-company-management.md#admin-role-group-permissions)|Да<sup>2</sup>|Да|Да|
|[Управление доменами](recipient-domain-and-company-management.md#domain-management)|Да,<sup>3</sup>|Да,<sup>3</sup>|Да,<sup>3</sup>|
|[Соответствующие поддомены](recipient-domain-and-company-management.md#match-subdomains)|Да|Да|Нет|
|[Пограничная блокировка на основе каталогов](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Да|Да|Да|
|[Правила потока обработки почты](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Да<sup>4</sup>|Да<sup>, 4, 6</sup>|Да|
|[Ведение журнала аудита](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Да<sup>5</sup>|Да|Да|
|[Предотвращение потери данных (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|Нет|Да|Да,<sup>6</sup>|
|[Шифрование сообщений Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Да<sup>12</sup>|Да|Да<sup>12</sup>|
|[Защита от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (встроенная)|Да|Да|Да|
|[Настройка политик защиты от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Да<sup>7</sup>|Да|Да|
|[Защита от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (встроенная)|Да,<sup>13</sup>|Да|Да|
|[Настройка политик защиты от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Да|Да|Да|
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): управление администраторами|Да|Да|Да|
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): самостоятельное управление пользователями|Да|Да|Да|
|[Надстройка Report Message для Outlook](anti-spam-and-anti-malware-protection-eop.md#report-message-add-in-for-outlook)|Да|Да|Да|
|[Создание отчетов о нежелательной почте в Outlook в Интернете](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-on-the-web)|Да|Да|Да|
|[Маршрутизация сообщений между Office 365 и почтовыми серверами пользователя](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers)|Да|Да|Да|
|[Защищенный обмен сообщениями с доверенным партнером](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Да|Да|Да|
|[Добавление IP-адреса партнера в список надежных отправителей](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Да|Да|Да|
|[Условная маршрутизация почты](mail-flow-eop.md#conditional-mail-routing)|Да|Да|Да|
|[Маршрутизация гибридной почты](mail-flow-eop.md#hybrid-mail-routing)|Да|Да|Да|
|[Отчеты центра администрирования Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Да<sup>9</sup>|Да<sup>10</sup>|Да <sup>9, 10</sup>|
|[Создание отчетов с помощью веб-служб](reporting-and-message-trace.md#reporting-using-web-services)|Нет|Да|Да|
|[Трассировка сообщений](reporting-and-message-trace.md#message-trace)|Да<sup>15</sup>|Да<sup>15</sup>|Да|
|[Доступ к центру администрирования Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Да|Да|Да|
|[Доступ к центру администрирования Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Да|Да|Да|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Да|Да|Да|

<sup>1</sup> почтовые пользователи определены как "почтовые ящики", а вместе с внешними почтовыми контактами можно добавлять, удалять и иным образом управлять непосредственно в центре администрирования Exchange. <br/>
<sup>2</sup> Настройка RBAC отсутствует. Только роли администратора. <br/>
<sup>3</sup> управляемые домены можно просматривать, а типы доменов можно редактировать в центре администрирования Exchange. Все остальные операции управления доменами должны выполняться в центре администрирования Microsoft 365.<br/>
<sup>4</sup> правила для почтовых ящиков (также называемые правилами транспорта) в EOP описаны в разделе [правила обработки почтового ящика (правила транспорта) в Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). Доступные условия, исключения и действия правила обработки почтового процесса незначительно отличаются в EOP и Exchange Online. Эти отличия отмечены в [правилах обработки обработки почты и исключения (предикаты) в](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) почтовых действиях в Exchange Online и [почтовых ящиках в Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>5</sup> отчеты аудита EOP являются подмножеством отчетов об аудите Exchange Online, которые исключают сведения о почтовых ящиках. <br/>
<sup>6</sup> подсказки политики DLP недоступны для клиентов Exchange Enterprise CAL со службами.  <br/>
<sup>7</sup> фильтр содержимого по умолчанию — перемещение нежелательных сообщений в папку нежелательной почты получателей. Чтобы это работало с локальными почтовыми ящиками Exchange, также необходимо настроить два правила транспорта в локальной организации Exchange, чтобы обнаружить заголовки нежелательной почты, добавленные в EOP. Чтобы получить дополнительные сведения, [Убедитесь, что спам направляется в папку нежелательной почты каждого пользователя](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> отчеты EOP являются подмножеством отчетов Exchange Online, которые исключают сведения о почтовых ящиках.<br/>
<sup>10</sup> включает отчеты DLP. <br/>
<sup>12</sup> поддерживается для локальных пользователей, которые приобрели Azure Information Protection и используют Exchange Online Protection для маршрутизации электронной почты через Exchange Online. <br/>
<sup>13</sup> сканирует входящие и исходящие сообщения, но не сканирует внутренние сообщения, отправленные от отправителя в вашей организации получателю в вашей организации. <br/>
<sup>15</sup> Гибридная Настройка недоступна при использовании мастера гибридного развертывания, но ее можно настроить вручную, если у вас Exchange с пакетом обновления 1 (SP1).
