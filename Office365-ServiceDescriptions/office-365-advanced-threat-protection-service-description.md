---
title: Описание службы Microsoft Defender для Office 365
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender для Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, а также включает функции для защиты организации от вредоносных ссылок в режиме реального времени.
ms.openlocfilehash: 4bb1a39fd9369dd2c691a442c351f74c9f544b12
ms.sourcegitcommit: 69bb27491ec44b1c4a01cec94a4e0f353c707593
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/09/2021
ms.locfileid: "49790443"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Описание службы Microsoft Defender для Office 365

Microsoft Defender для Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, а также включает функции для защиты организации от вредоносных ссылок в режиме реального времени. Защитник Office 365 имеет богатые возможности отчетов и трассировки URL-адресов, которые дают администраторам представление о типах атак, происходящих в вашей организации.

Ниже основных способов использования Защитника Для Office 365 для защиты сообщений:

- В сценарии "Защитник только для фильтрации Office 365" Защитник Office 365 обеспечивает облачную защиту электронной почты для локальной среды Exchange Server или любого другого локального решения электронной почты SMTP.

- Защитник Office 365 можно включить для защиты почтовых ящиков, которые можно защитить в облаке Exchange Online. Дополнительные информацию об Exchange Online см. в описании [службы Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- В гибридном развертывании Защитник Office 365 можно настроить для защиты среды обмена сообщениями и управления маршрутидой почты при наборе локального и облачного почтовых ящиков с Exchange Online Protection для фильтрации входящих сообщений электронной почты.

## <a name="microsoft-defender-for-office-365-availability"></a>Доступность Microsoft Defender для Office 365

Microsoft Defender для Office 365 (план 2) входит в состав Office 365 E5, Office 365 A5, Microsoft 365 E5 Security и Microsoft 365 E5, как указано [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) здесь: Защитник Office 365 (план 1) входит в состав Microsoft 365 бизнес премиум.

Вы можете добавить Защитник для Office 365 в следующие планы подписки На Exchange и Microsoft 365:

- Exchange Online (план 1)

- Exchange Online (план 2)

- Базовая подписка на Exchange Online

- Exchange Online Protection

- Microsoft 365 бизнес базовый

- Microsoft 365 бизнес стандарт

- Office 365 корпоративный E1

- Office 365 корпоративный E3

- Office 365 корпоративный F3

- Office 365 A1

- Office 365 A3

Чтобы приобрести Microsoft Defender для Office 365, см. ["Microsoft Defender для Office 365".](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Чтобы сравнить функции в разных планах, см. ["Мощные](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) инструменты для поддержки вашего предприятия" и "Преобразование предприятия [с помощью Microsoft 365".](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Новые возможности Microsoft Defender для Office 365

Мы продолжаем добавлять новые функции в Защитник для Office 365. Чтобы узнать больше о новых функциях, которые будут представлены в Защитнике для Office 365 (или Microsoft 365 в целом), см. следующие ресурсы:

- [Дорожная карта Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Новые возможности Microsoft Defender для Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Требования к Microsoft Defender для Office 365

Защитник office 365 можно использовать с любым агентом передачи почты SMTP, например Microsoft Exchange Server. Сведения об операционных системах, веб-браузерах и языках, поддерживаемых Защитником для Office 365, см. в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" в Центре администрирования Exchange в [Exchange Online Protection.](https://go.microsoft.com/fwlink/p/?LinkId=282381)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Доступность функций в планах Защитника для Office 365

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.<br><br>

| Возможность | Защитник для Office 365 (план 1) | Защитник для Office 365 (план 2) | Безопасность Microsoft 365 E5 и E5|
|:-----|:-----|:-----|:-----|
|*Конфигурация, защита и обнаружение*|
|[Безопасные вложения](#safe-attachments)|Да|Да|Да|
|Безопасные вложения в Teams|Да|Да|Да|
|[Безопасные ссылки](#safe-links)|Да|Да|Да|
|[Безопасные документы](#safe-documents)|Нет|Нет|Да|
|Безопасные ссылки в Teams|Да|Да|Да|
|[ATP для SharePoint, OneDrive и Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Да|Да|Да|
|[Политики защиты от фишинга](#anti-phishing-policies)|Да|Да|Да|
|[Отчеты в режиме реального времени](#real-time-reports)|Да|Да|Да|
|*Автоматизация, исследование, исправление и образование*|
|[Трекеры угроз](#threat-trackers)|Нет|Да|Да|
|Исследование угроз (advanced threat investigation)|[Обнаружение в режиме реального времени](#real-time-detections)|[Обозреватель](#explorer)|[Обозреватель](#explorer)|
|[Автоматическое реагирование на инциденты](#automated-incident-response)|Нет|Да|Да|
|[Эмулятор атак](#attack-simulator)|Нет|Да|Да|
|*Интеграция [с Microsoft 365 Defender](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|Нет|Да|Да|

> [!NOTE]
> Если у вашего клиента есть только пробная лицензия "Защитник для Office 365 план 2" или пробная лицензия Microsoft 365 E5 без другой лицензии на Microsoft 365 Defender, вы не сможете получить доступ к Microsoft 365 Defender. Дополнительные узнать см. в требованиях [к Microsoft 365 Defender.](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Защитник возможностей Office 365

### <a name="safe-attachments"></a>Безопасные вложения

[Безопасные вложения](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) защищают от неизвестных вредоносных программ и вирусов, а также обеспечивают защиту системы обмена сообщениями нулевого дня. Все сообщения и вложения, которые не имеют известной сигнатуры вирусов и вредоносных программ, маршрутизются в специальную среду, где Защитник Office 365 использует различные методы машинного обучения и анализа для обнаружения вредоносных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Сканирование безопасных вложений происходит в том же регионе, где находятся данные Office 365. Дополнительные сведения о географическом расположении центра обработки данных см. в сведениях о [расположении данных?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Безопасные ссылки

Функция [безопасных ссылок](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) заранее защищает пользователей от вредоносных URL-адресов в сообщении или документе Office. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

Безопасные ссылки доступны для URL-адресов в следующих приложениях:

- Приложения Microsoft 365 для предприятий в Windows или Mac

- Office для Интернета (Word для Интернета, Excel для Интернета, PowerPoint для Интернета и OneNote для Интернета)

- Word, Excel и PowerPoint в Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензию на Защитник для Office 365, должны быть включены в политики безопасных ссылок и должны быть вошли на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> <sup>\*</sup> Для лицензий на Office 365 для всей организации (например, ATP_ENTERPRISE_FACULTY) не нужно назначать лицензии "Защитник для Office 365" отдельным пользователям.
>
> Дополнительные сведения о защите безопасных ссылок см. в веб-сайте ["Безопасные ссылки" в Microsoft Defender для Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Безопасные документы

Функция ["Безопасные документы"](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) использует [Microsoft Defender для конечной](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) точки для сканирования документов и файлов, открытых в [защищенного просмотра.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Что нужно знать перед началом работы

- Теперь безопасные документы доступны пользователям Office версии 2004 (12730.x) или более новой версии! Эта функция отключена по умолчанию и должна быть включена администратором безопасности.

- Эта функция доступна только пользователям с лицензией безопасности Microsoft 365 E5 или Microsoft 365 E5 (не включена в планы Defender для Office 365).

- Word, Excel и PowerPoint в Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензию на Microsoft 365 E5 или Microsoft 365 E5 Security, должны быть включены в политики безопасных документов и должны быть вписались на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> Дополнительные сведения о защите безопасных документов см. в документе ["Безопасные документы" в Microsoft 365 E5.](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[ATP для SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  и Microsoft Teams помогает обнаруживать и блокировать файлы, которые определены как вредоносные на сайтах групп и в библиотеках документов. Кроме того, защита безопасных ссылок теперь доступна в каналах и чатах Microsoft Teams.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Средства защиты от фишинга](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) проверяют входящие сообщения на наличие индикаторов того, что сообщение может быть попыткой фишинга. Когда пользователи охвачены политиками Защитника Office 365 (безопасные вложения, безопасные ссылки или защита от фишинга), входящие сообщения оцениваются несколькими моделями машинного обучения, которые анализируют сообщения, и соответствующие действия принимаются на основе настроенных политик.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в Центре безопасности & соответствия требованиям ( ) включают отчеты в режиме реального времени и анализ, которые могут позволить администраторам безопасности и соответствия требованиям сосредоточиться на высокооритетных проблемах, таких как атаки безопасности или повышенная подозрительная [https://protection.office.com](https://protection.office.com) активность. [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) Помимо выделения проблемных областей интеллектуальные отчеты и анализ включают рекомендации и ссылки для просмотра и изучения данных, а также быстрые действия.

### <a name="explorer"></a>Обозреватель

Отчет обозревателя, также именуемого обозревателем угроз, — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. По умолчанию в этом отчете показаны данные за последние семь дней; однако представления можно изменить, чтобы показать данные за последние 30 дней.

Проводник содержит представления, такие как вредоносные программы (для электронной почты и содержимого), отправки, фишинг и все сообщения электронной почты. Чтобы узнать, как проводник сравнивает обнаружение в режиме реального времени, [скачайте этот PDF-файл.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения о проводнике (в Microsoft Defender для Office 365 (план 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 (план 1) см. в обозревателе угроз и обнаружениях в режиме реального [времени.](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и в проводнике, по умолчанию в этом отчете показаны данные за последние семь дней.

Обнаружение в режиме реального времени содержит представления, такие как вредоносные программы (для электронной почты и содержимого), отправки и фишинг. Чтобы узнать, как обнаружения в режиме реального времени сравнивают с Проводником, [скачайте этот PDF-файл.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения о проводнике (в Microsoft Defender для Office 365 (план 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 (план 1) см. в обозревателе угроз (и обнаружениях в режиме реального [времени).](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Журналы учета угроз

[Отслеживание угроз — это](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) информационные виджеты и представления, которые предоставляют авторизованным пользователям аналитику по вопросам кибербезопасности, которые могут повлиять на вашу организацию.

### <a name="automated-incident-response"></a>Автоматическое реагирование на инциденты

[Функции автоматического](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) реагирования на инциденты (AIR), доступные в Защитнике office 365 (план 2), могут позволить вам запускать процессы автоматического расследования в ответ на известные угрозы, которые существуют на сегодняшний день. Автоматизированные задачи исследования могут быть более эффективными и эффективными. Действия по исправлению, например удаление вредоносных сообщений электронной почты, принимаются после утверждения вашей командой операций безопасности. Дополнительные узнать, как [AIR работает в Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Эмулятор атак

[Имитатор](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) атак позволяет авторизованным пользователям запускать реалистичные сценарии атак в вашей организации. Доступно несколько различных видов атак, в том числе атаки с именем на экране, атаки путем распыления пароля и атаки с помощью атак
