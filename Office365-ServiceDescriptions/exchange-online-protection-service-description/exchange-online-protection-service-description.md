---
title: Описание службы Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Узнайте о компонентах и требованиях для Exchange Online Protection. Включен список планов, которые предоставляют Exchange Online Protection, а также сравнение функций в этих планах.
ms.openlocfilehash: 187ec7cee1b045a9e859e1157cddef29059cac2b
ms.sourcegitcommit: ab82834030929e1583074b3f5b0b27182746fff4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/19/2021
ms.locfileid: "50901944"
---
# <a name="exchange-online-protection-service-description"></a>Описание службы Exchange Online Protection

Узнайте о компонентах и требованиях для Exchange Online Protection. Включен список планов, которые предоставляют Exchange Online Protection, а также сравнение функций в этих планах.

Microsoft Exchange Online Protection (EOP)  это облачная служба фильтрации электронной почты, которая помогает защитить организацию от нежелательной почты и вредоносных программ, передаваемых через электронную почту. К тому же, эта служба обладает функциями для защиты организации от нарушений политик обмена сообщениями. EOP может упростить управление вашей среды обмена сообщениями и облегчить многие тяготы, которые приходят с поддержкой локального аппаратного и программного обеспечения.

В следующем списке описаны основные способы использования EOP для защиты сообщений:

- **В автономный** сценарий: EOP обеспечивает облачную защиту электронной почты для локальной среды электронной почты (Exchange Server или других решений электронной почты SMTP на локальной основе).

- **В рамках Microsoft Exchange Online** по умолчанию EOP защищает облачные почтовые ящики Exchange Online. Дополнительные информацию о Exchange Online см. в описании [службы Exchange Online.](../exchange-online-service-description/exchange-online-service-description.md)

- **В гибридном** развертывании EOP можно настроить для защиты среды обмена сообщениями и управления маршрутией почты при наборе локального и облачного почтовых ящиков.

## <a name="available-plans"></a>Доступные планы

Подробные сведения о планах подписки, которые позволяют пользователям Exchange Online Protection, см. в полной таблице [сравнения подписки.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

Сведения о покупке Exchange Online Protection см. на странице [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP заменила Forefront Online Protection for Exchange (FOPE). Все клиенты FOPE перенесены в EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Новые возможности Exchange Online Protection (EOP)

[Дорожная карта Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) является хорошим ресурсом для получения сведений о предстоящих новых функций.

## <a name="exchange-online-protection-eop-plans"></a>Планы Exchange Online Protection (EOP)

EOP предоставляется в рамках подписки на следующие планы:<br><br>

| Планирование | Description |
|:-----|:-----|
|[Изолированная EOP](https://products.office.com/exchange/exchange-email-security-spam-protection)|Отдельная облачная служба, защищающая организацию локальной электронной почты.|
|[Функции EOP в Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Встроенная защита для облачных почтовых ящиков Exchange Online.|
|[Клиентская лицензия Exchange Enterprise CAL со службами](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Лицензии надстройки, которые вы приобретаете для локальной организации Exchange, которые включают EOP и другие облачные функции (подробнее см. в следующем разделе).|

### <a name="exchange-enterprise-cal-with-services-features"></a>клиентская лицензия Exchange Enterprise CAL со службами:

Microsoft Exchange Enterprise CAL с службами предоставляет функции защиты электронной почты EOP и следующие дополнительные облачные функции:

- [Предотвращение потери данных (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Создание отчетов с помощью веб-служб](reporting-and-message-trace.md#reporting-using-web-services)

Дополнительные сведения о exchange Enterprise CAL с лицензированием служб см. в [faqs.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Если у вас есть лицензии Exchange Enterprise CAL с лицензиями служб и вы хотите получить EOP, следуйте инструкциям в Настройка службы [EOP.](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service) Действия по настройке такие же, как при настройке отдельной службы EOP.

> [!NOTE]
> Новые функции для клиентской лицензии Exchange Enterprise со службами развертываются одновременно с Exchange Online, а не с изолированной службой EOP. Имейте в виду, что графики развертывания изолированной службы EOP и клиентской лицензии Exchange Online или Exchange Enterprise со службами могут немного отличаться.

## <a name="requirements-for-exchange-online-protection-eop"></a>Требования для Exchange Online Protection (EOP)

EOP можно использовать с любым агентом передачи почты SMTP, например с Microsoft Exchange Server. Сведения об операционных системах, веб-браузерах и языках, поддерживаемых EOP, см. в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" в центре администрирования Exchange в [Exchange Online Protection.](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>Ограничения

Ограничения в EOP см. в [веб-сайте Exchange Online Protection limits.](exchange-online-protection-limits.md)

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Доступность функций в планах Exchange Online Protection (EOP)

Каждая функция приведена ниже. Более подробные сведения о функциях EOP доступны по ссылкам в таблице. Exchange Online обычно относится к семейству служб Office 365 корпоративный.<br><br>

| Функция | Изолированная EOP | Функции EOP в Exchange Online | Клиентская лицензия Exchange Enterprise CAL со службами|
|:-----|:-----|:-----|:-----|
|[Получатели почты](recipient-domain-and-company-management.md#mail-recipients)|Да<sup>1</sup>|Да<sup>1</sup>|Да|
|[Разрешения для группы ролей администраторов](recipient-domain-and-company-management.md#admin-role-group-permissions)|Да<sup>2</sup>|Да|Да|
|[Управление доменами](recipient-domain-and-company-management.md#domain-management)|Да<sup>3</sup>|Да<sup>3</sup>|Да<sup>3</sup>|
|[Соответствующие поддомены](recipient-domain-and-company-management.md#match-subdomains)|Да|Да|Нет|
|[Пограничная блокировка на основе каталогов](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Да|Да|Да|
|[Правила потока обработки почты](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Да<sup>4</sup>|Да<sup>4, 6</sup>|Да|
|[Ведение журнала аудита](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Да<sup>5</sup>|Да|Да|
|[Предотвращение потери данных (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|Нет|Да|Да<sup>6</sup>|
|[Шифрование сообщений Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Да<sup>12</sup>|Да|Да<sup>12</sup>|
|[Защита от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (встроенная)|Да|Да|Да|
|[Настройка политик защиты от нежелательной почты](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Да<sup>7</sup>|Да|Да|
|[Защита от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (встроенная)|Да<sup>13</sup>|Да|Да|
|[Настройка политик защиты от вредоносных программ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Да|Да|Да|
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): управление администраторами|Да|Да|Да|
|[Карантин](anti-spam-and-anti-malware-protection-eop.md#quarantine): самостоятельное управление пользователями|Да|Да|Да|
|[Сданная работа](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|Нет|Да|Нет|
|[Надстройка сообщения отчетов для Outlook](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Да|Да|Да|
|[Нежелательные сообщения электронной почты в Outlook в Интернете](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Да|Да|Да|
|[Маршрутивка электронной почты между Корпорацией Майкрософт и собственными серверами электронной почты](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Да|Да|Да|
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

<sup>1</sup> Пользователи почты определяются как "почтовые ящики", и наряду с внешними контактами почты можно добавлять, удалять и управлять им непосредственно в центре администрирования Exchange (EAC). <br/>
<sup>2</sup> Нет настройки RBAC. Только роли администратора. <br/>
<sup>3</sup> Управляемые домены можно просматривать и изменять типы доменов в EAC. Все остальные управления доменами должны быть сделаны в центре администрирования Microsoft 365.<br/>
<sup>4</sup> Правила потока почты (также известные как правила транспорта) в EOP описаны в правилах потока почты [(правила транспорта) в Exchange Online Protection.](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0) Доступные условия правил потока почты, исключения и действия немного отличаются между EOP и Exchange Online. Эти различия отмечены в правилах правил потока почты и [исключениях (предикатах)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) в действиях правил потока Exchange Online и [Mail в Exchange Online.](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)<br/>
<sup>5</sup> Отчеты о аудите EOP — это подмножество отчетов аудита Exchange Online, которые исключают сведения о почтовых ящиках. <br/>
<sup>6 советов</sup> по политике DLP недоступны для Exchange Enterprise CAL с клиентами служб.  <br/>
<sup>7</sup> Действие фильтра контента по умолчанию — перемещение сообщений нежелательной почты в папку нежелательной почты получателей. Для работы с почтовыми ящиками Exchange на локальной основе также необходимо настроить два правила транспорта в локальной организации Exchange для обнаружения заглавных сообщений нежелательной почты, добавленных EOP. Дополнительные сведения см. в [сообщении Configure standalone EOP для](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)доставки нежелательной почты в папку нежелательной почты в гибридных средах. <br/>
<sup>9</sup> отчетов EOP — это подмножество отчетов Exchange Online, которые исключают сведения о почтовых ящиках.<br/>
<sup>10</sup> Включает отчеты DLP. <br/>
<sup>12</sup> Поддерживается для локального клиента, приобретавшего azure Information Protection и использую службу Exchange Online Protection для маршрутной почты через Exchange Online. <br/>
<sup>13</sup> сканирует входящие и исходящие сообщения, но не сканирует внутренние сообщения, отправленные от отправщика в организации получателю в организации. <br/>
<sup>15</sup> Гибридная настройка недоступна с помощью гибридного мастера, но может быть настроена вручную, если у вас есть SP1 Exchange.
