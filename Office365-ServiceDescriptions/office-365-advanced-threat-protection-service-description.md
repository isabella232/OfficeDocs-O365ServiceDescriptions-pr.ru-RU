---
title: Описание службы Microsoft Defender для Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender для Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, и включает функции для защиты организации от вредных ссылок в режиме реального времени.
ms.openlocfilehash: 16d9b5ac54513493c0438009ff772df3073d0dd0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653421"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Описание службы Microsoft Defender для Office 365

Microsoft Defender для Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, и включает функции для защиты организации от вредных ссылок в режиме реального времени. Defender for Office 365 обладает богатыми возможностями отслеживания отчетов и URL-адресов, которые дают администраторам представление о том, какие атаки происходят в вашей организации.

Основные способы использования Defender для Office 365 для защиты сообщений:

- В сценарии только для защиты от фильтрации Office 365 Defender for Office 365 обеспечивает облачную защиту электронной почты для локальной Exchange Server среды или любого другого локального решения smTP электронной почты.

- Защитник для Office 365 может быть включен для защиты облачных почтовых ящиков Exchange Online. Дополнительные информацию о Exchange Online см. в описании [службы Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- В гибридном развертывании Defender for Office 365 можно настроить для защиты среды обмена сообщениями и управления маршрутией почты, если у вас есть сочетание локального и облачного почтовых ящиков с Exchange Online Protection для фильтрации входящих сообщений.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender для доступности Office 365

Microsoft Defender для Office 365 Plan 2 включен в Office 365 E5, Office 365 A5, Microsoft 365 E5 Security и Microsoft 365 E5, как указано здесь: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender for Office 365 Plan 1 включен в Microsoft 365 Business Premium.

Вы можете добавить Defender для Office 365 в следующие планы подписки Exchange и Microsoft 365:

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

Чтобы купить Microsoft Defender для Office 365, см. в [записи Microsoft Defender для Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Подробные сведения о планах подписки, которые позволяют пользователям для Microsoft Defender для Office 365, см. в полной таблице [сравнения подписки.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Новые возможности в Microsoft Defender для Office 365

Мы продолжаем добавлять новые функции в Defender для Office 365. Дополнительные информацию о новых функциях, которые приходят в Defender для Office 365 (или Microsoft 365 в целом), см. в следующих ресурсах:

- [Дорожная карта Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Новые возможности в Microsoft Defender для Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Требования к Microsoft Defender для Office 365

Defender для Office 365 можно использовать с любым агентом по передаче почты SMTP, например с Microsoft Exchange Server. Сведения об операционных системах, веб-браузерах и языках, поддерживаемых Defender для Office 365, см. в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" в центре администрирования Exchange в [Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Доступность функций в планах Defender для Office 365

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.<br><br>

| Функция | Defender для Office 365 (план 1) | Defender для Office 365 (план 2) | Microsoft 365 E5 / A5 Security|
|:-----|:-----|:-----|:-----|
|*Конфигурация, защита и обнаружение*|
|[Безопасные вложения](#safe-attachments)|Да|Да|Да|
|Безопасные вложения в teams|Да|Да|Да|
|[Безопасные ссылки](#safe-links)|Да|Да|Да|
|[Безопасные документы](#safe-documents)|Нет|Нет|Да|
|Безопасные ссылки в Teams|Да|Да|Да|
|[ATP для SharePoint, OneDrive и Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Да|Да|Да|
|[Политики защиты от фишинга](#anti-phishing-policies)|Да|Да|Да|
|[Отчеты в режиме реального времени](#real-time-reports)|Да|Да|Да|
|*Автоматизация, исследование, исправление и образование*|
|[Трекеры угроз](#threat-trackers)|Нет|Да|Да|
|Расследование угроз (предварительное расследование угрозы)|[Обнаружение в режиме реального времени](#real-time-detections)|[Обозреватель](#explorer)|[Обозреватель](#explorer)|
|[Автоматическая реакция на инциденты](#automated-incident-response)|Нет|Да|Да|
|[Эмулятор атак](#attack-simulator)|Нет|Да|Да|
|*Интеграция [с Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Нет|Да|Да|

> [!NOTE]
> Если у клиента есть только пробная лицензия Microsoft Defender для Office Plan P2 или пробная лицензия Office 365 E5 без другой лицензии для Microsoft 365 Defender, вы не сможете получить доступ к Microsoft 365 Defender. Дополнительные новости о лицензии MTP см. в [сайте Microsoft 365 Defender.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Возможности Defender для Office 365

### <a name="safe-attachments"></a>Безопасные вложения

[Безопасные вложения](/microsoft-365/security/office-365-security/atp-safe-attachments) защищают от неизвестных вредоносных программ и вирусов и обеспечивают защиту нулевого дня для защиты системы обмена сообщениями. Все сообщения и вложения, которые не имеют известной подписи вирусов и вредоносных программ, будут перенастроенными в специальную среду, где Defender для Office 365 использует различные методы машинного обучения и анализа для обнаружения вредоносных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Сканирование безопасных вложений происходит в том же регионе, где находятся данные Office 365. Дополнительные сведения о географии центра обработки данных см. в дополнительных сведениях [о расположении данных?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Безопасные ссылки

Функция ["Безопасные ссылки"](/microsoft-365/security/office-365-security/atp-safe-links) активно защищает пользователей от вредоносных URL-адресов в сообщении или в документе Office. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

Безопасные ссылки доступны для URL-адресов в следующих приложениях:

- Приложения Microsoft 365 для предприятия в Windows или Mac

- Office для Интернета (Word для Интернета, Excel для Интернета, PowerPoint для Интернета и OneNote для Интернета)

- Word, Excel и PowerPoint в Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензию на Defender для Office 365, должны быть включены в политики безопасных ссылок и должны быть включены на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> <sup>\*</sup> Для лицензий Defender для Office 365 (например, ATP_ENTERPRISE_FACULTY) не требуется назначать лицензии Defender для Office 365 отдельным пользователям.
>
> Дополнительные сведения о защите безопасных ссылок см. в [веб-сайте Безопасные ссылки в Microsoft Defender для Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Безопасные документы

Функция ["Безопасные документы"](/microsoft-365/security/office-365-security/safe-docs) использует [Microsoft Defender для конечной точки](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) для сканирования документов и файлов, открытых в [защищенной точке зрения.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Что нужно знать перед началом работы

- Безопасные документы теперь, как правило, доступны пользователям с Office Version 2004 (12730.x) или больше! Эта функция отключена по умолчанию и должна быть включена администратором безопасности.

- Эта функция доступна только пользователям с лицензией безопасности Microsoft 365 E5 или Microsoft 365 E5 (не включена в планы Defender for Office 365).

- Word, Excel и PowerPoint в Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензии на безопасность Microsoft 365 E5 или Microsoft 365 E5, должны быть включены в политики безопасных документов и должны быть включены на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> Дополнительные сведения о защите безопасных документов см. в документе [Safe Documents in Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[AtP для SharePoint, OneDrive и Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  помогает обнаруживать и блокировать файлы, которые идентифицированы как вредоносные на сайтах групп и библиотеках документов. Кроме того, защита безопасных ссылок теперь доступна в каналах и чатах Microsoft Teams.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Антифишинг](/microsoft-365/security/office-365-security/atp-anti-phishing) проверяет входящие сообщения на наличие индикаторов того, что сообщение может быть попыткой фишинга. Когда пользователи охвачены политиками Defender для Office 365 (безопасные вложения, безопасные ссылки или анти-фишинг), входящие сообщения оцениваются несколькими моделями машинного обучения, которые анализируют сообщения и принимаются соответствующие меры на основе настроенных политик.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в Центре & безопасности ( ) включают отчеты и сведения в режиме реального времени, которые могут позволить администраторам безопасности и соответствия требованиям сосредоточиться на приоритетных проблемах, таких как атаки безопасности или повышенная подозрительная [https://protection.office.com](https://protection.office.com) активность. [](/microsoft-365/security/office-365-security/view-reports-for-atp) В дополнение к выделению проблемных областей интеллектуальные отчеты и сведения включают рекомендации и ссылки для просмотра и изучения данных, а также быстрые действия.

### <a name="explorer"></a>Обозреватель

Отчет обозревателя, также именуемого обозревателем угроз, — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. По умолчанию в этом отчете показаны данные за последние семь дней; однако представления можно изменить, чтобы показать данные за последние 30 дней.

Обозреватель содержит представления, такие как вредоносные программы (для электронной почты и контента), Отправки, Фишинг и Все сообщения электронной почты. Чтобы узнать, как Explorer сравнивает с обнаружениями в режиме реального времени, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения о Explorer (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 Plan 1) см. в руб. [Обозреватель](/microsoft-365/security/office-365-security/threat-explorer)угроз и обнаружения в режиме реального времени.

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и в Explorer, по умолчанию в этом отчете показаны данные за последние семь дней.

Обнаружения в режиме реального времени содержат представления, такие как вредоносные программы (для электронной почты и контента), Представления и Фишинг. Чтобы узнать, как обнаружения в режиме реального времени сравнивают с Explorer, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения о Explorer (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме [](/microsoft-365/security/office-365-security/threat-explorer)реального времени (в Microsoft Defender для Office 365 Plan 1) см .

### <a name="threat-trackers"></a>Журналы учета угроз

[Отслеживание угроз —](/microsoft-365/security/office-365-security/threat-trackers) это информационные виджеты и представления, которые предоставляют уполномоченным пользователям сведения о проблемах кибербезопасности, которые могут повлиять на организацию.

### <a name="automated-incident-response"></a>Автоматическая реакция на инциденты

[Возможности автоматического](/microsoft-365/security/office-365-security/office-365-air) реагирования на инциденты (AIR), доступные в Defender for Office 365 Plan 2, могут запускать автоматизированные процессы расследования в ответ на известные угрозы, которые существуют сегодня. Автоматизация определенных задач расследования может привести к более эффективной и эффективной работе группы операций безопасности. Действия по исправлению, например удаление вредоносных сообщений электронной почты, принимаются после утверждения вашей командой операций безопасности. Дополнительные дополнительные информации см. в см. в руб. [Как air работает в Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Эмулятор атак

[Симулятор атак](/microsoft-365/security/office-365-security/attack-simulator) позволяет авторизованным пользователям запускать реалистичные сценарии атак в вашей организации. Доступны несколько различных типов атак, в том числе атака с именем копье-фишинга, атака с помощью спрея паролей и атака паролей с грубой силой.