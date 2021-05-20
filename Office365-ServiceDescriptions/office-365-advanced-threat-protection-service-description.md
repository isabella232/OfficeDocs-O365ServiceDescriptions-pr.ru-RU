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
description: Microsoft Defender for Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, и включает в себя функции для защиты организации от вредных ссылок в режиме реального времени.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545976"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Описание службы Microsoft Defender для Office 365

Microsoft Defender for Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня, и включает в себя функции для защиты организации от вредных ссылок в режиме реального времени. Defender for Office 365 имеет богатые возможности отслеживания отчетности и URL, которые дают администраторам представление о видах атак, происходящих в вашей организации.

Ниже приведены основные способы использования Defender для защиты Office 365 сообщений:

- В сценарии «Защитник Office 365 только для фильтрации» Defender for Office 365 обеспечивает облачную защиту электронной почты для вашей среды Exchange Server на территории страны или любого другого решения smTP по электронной почте.

- Защита Office 365 может быть включена для защиты Exchange Online почтовых ящиков, размещенных в облаке. Чтобы узнать больше Exchange Online, [см. Exchange Online сервиса](exchange-online-service-description/exchange-online-service-description.md).

- В гибридном развертывании Defender for Office 365 может быть настроен для защиты среды обмена сообщениями и управления маршрутизацией почты, если у вас есть сочетание почтовых ящиков на территории и облачных почтовых ящиков с Exchange Online Protection для входящих почтовых фильтров.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender для Office 365 доступности

Microsoft Defender for Office 365 Plan 2 включена в Office 365 E5, Office 365 A5, Безопасность Microsoft 365 E5 и Microsoft 365 E5, как указано здесь: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Защитник Office 365 плана 1 включен в Microsoft 365 бизнес премиум.

Вы можете добавить Defender для Office 365 к следующим Exchange и Microsoft 365 планам подписки:

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

Чтобы купить Microsoft Defender для Office 365, [см. Microsoft Defender для Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Подробную информацию о планах подписки, позволяющей пользователям Microsoft Defender Office 365, можно посмотреть [полную таблицу сравнения подписки.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Что нового в Microsoft Defender для Office 365

Мы продолжаем добавлять новые функции в Defender для Office 365. Чтобы узнать больше о новых функциях, поступающих в Defender Office 365 (или Microsoft 365 в целом), см. следующие ресурсы:

- [Дорожная карта Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Что нового в Microsoft Defender для Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Требования к Microsoft Defender для Office 365

Защитник для Office 365 может быть использован с любым агентом SMTP передачи почты, таких как Microsoft Exchange Server. Для получения информации об операционных системах, веб-браузерах и языках, поддерживаемых Defender for Office 365, в Exchange Online Protection г. [в разделе «Поддерживаемые браузеры» и «Поддерживаемые языки» Exchange-центре Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Доступность функций в планах Defender Office 365 безопасности

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.<br><br>

| Функция | Defender для Office 365 (план 1) | Defender для Office 365 (план 2) | Microsoft 365 E5 / Безопасность A5|
|:-----|:-----|:-----|:-----|
|*Конфигурация, защита и обнаружение*|
|[Безопасные вложения](#safe-attachments)|Да|Да|Да|
|Сейф Приложения в Teams|Да|Да|Да|
|[Безопасные ссылки](#safe-links)|Да|Да|Да|
|[Безопасные документы](#safe-documents)|Нет|Нет|Да|
|Безопасные ссылки в Teams|Да|Да|Да|
|[ATP для SharePoint, OneDrive и Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Да|Да|Да|
|[Политики защиты от фишинга](#anti-phishing-policies)|Да|Да|Да|
|[Отчеты в режиме реального времени](#real-time-reports)|Да|Да|Да|
|*Автоматизация, исследования, восстановление и образование*|
|[Трекеры угроз](#threat-trackers)|Нет|Да|Да|
|Расследование угроз (продвинутое расследование угрозы)|[Обнаружение в режиме реального времени](#real-time-detections)|[Обозреватель](#explorer)|[Обозреватель](#explorer)|
|[Автоматизированная реакция на инциденты](#automated-incident-response)|Нет|Да|Да|
|[Тренировка по моделированию атак](#attack-simulation-training)|Нет|Да|Да|
|*Интеграция с [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Нет|Да|Да|

> [!NOTE]
> Если у вашего арендатора есть только Microsoft Defender для пробной лицензии Office Plan P2 или пробная лицензия Office 365 E5, не имею никакой другой лицензии на Microsoft 365 Defender, вы не сможете получить доступ к Microsoft 365 Defender. Чтобы узнать больше о лицензии MTP, [см. Microsoft 365 Defender.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Защитник возможностей Office 365 безопасности

### <a name="safe-attachments"></a>Безопасные вложения

[Сейф Вложения защищает от](/microsoft-365/security/office-365-security/atp-safe-attachments) неизвестных вредоносных программ и вирусов и обеспечивает защиту от нулевого дня для защиты вашей системы обмена сообщениями. Все сообщения и вложения, не имеют известной подписи вируса/вредоносного ПО, отправляются в специальную среду, где Defender for Office 365 использует различные методы машинного обучения и анализа для обнаружения злого умысла. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Сейф Сканирование вложений происходит в том же регионе, где находится Office 365 данных. Для получения дополнительной информации о географии центров обработки данных, [см. Где находятся ваши данные?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Безопасные ссылки

Функция [Сейф Links](/microsoft-365/security/office-365-security/atp-safe-links) активно защищает пользователей от вредоносных URL-адресов в сообщении или в Office документе. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

Безопасные ссылки доступны для URL-адресов в следующих приложениях:

- Приложения Microsoft 365 для предприятий на Windows или Mac

- Office для Интернета (Word для Интернета, Excel для Интернета, PowerPoint для Интернета и OneNote для Интернета)

- Слово, Excel, и PowerPoint на Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны быть лицензированы для Защитника в течение Office 365 <sup>\*</sup> года, должны быть включены в Сейф Ссылки, и должны быть включены на свои устройства для защиты, чтобы быть на месте.
>
> <sup>\*</sup>Для всей организации Defender для Office 365 лицензий (например, ATP_ENTERPRISE_FACULTY) не нужно назначать Defender для Office 365 лицензий отдельным пользователям.
>
> Для получения дополнительной информации о Сейф ссылок, [см. Сейф ссылки в Microsoft Defender для Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Безопасные документы

Функция [Сейф использует](/microsoft-365/security/office-365-security/safe-docs) Microsoft [Defender for Endpoint для сканирования документов](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) и файлов, открытых в [защищенном представлении.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Что нужно знать перед началом работы

- Сейф Документы теперь, как правило, доступны для пользователей с Office версии 2004 (12730.x) или больше! Эта функция выключена по умолчанию и должна быть включена Администратором безопасности.

- Эта функция доступна только пользователям с лицензией Microsoft 365 E5 или Безопасность Microsoft 365 E5 (не включенной в Defender для Office 365 планов).

- Слово, Excel, и PowerPoint на Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензию на Microsoft 365 E5 или <sup>\*</sup> Безопасность Microsoft 365 E5, должны быть включены в политики Сейф Documents и должны быть включены на свои устройства для защиты.
>
> Подробнее о защите Сейф документов в [Сейф в Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[СПС для SharePoint, OneDrive и Microsoft Teams помогает обнаруживать](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) и блокировать файлы, которые идентифицируются как вредоносные на сайтах групп и библиотеках документов. Кроме того, Сейф ссылки теперь доступна в Microsoft Teams каналах и чатах.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Антифишинг проверяет](/microsoft-365/security/office-365-security/atp-anti-phishing) входящие сообщения на показатели того, что сообщение может быть попыткой фишинга. Когда пользователи охвачены политиками Defender for Office 365 (Сейф Attachments, Сейф Links или anti-phishing), входящие сообщения оцениваются несколькими моделями машинного обучения, которые анализируют сообщения и принимаются соответствующие меры на основе настроенных политик.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в Центре соответствия требованиям Security & () включают в себя отчеты в режиме реального времени и информацию, которые позволяют администраторам безопасности и соответствия сосредоточиться [https://protection.office.com](https://protection.office.com) на приоритетных вопросах, таких как атаки безопасности или повышенная подозрительная активность. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Помимо выделения проблемных областей, интеллектуальные отчеты и аналитические идеи включают рекомендации и ссылки для просмотра и изучения данных, а также для быстрого реагирования.

### <a name="explorer"></a>Обозреватель

Отчет обозревателя, также именуемого обозревателем угроз, — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. По умолчанию в этом отчете показаны данные за последние семь дней; однако представления могут быть изменены, чтобы показать данные за последние 30 дней.

Explorer содержит представления, такие как вредоносные программы (для электронной почты и контента), материалы, Phish и все сообщения электронной почты. Чтобы увидеть, как Explorer сравнивает с обнаружением в режиме реального времени, [загрузите этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Для получения дополнительной информации о Explorer (в Microsoft Defender for Office 365 Plan 2) и обнаружении в [](/microsoft-365/security/office-365-security/threat-explorer)режиме реального времени (в Microsoft Defender for Office 365 Plan 1) см.

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и Explorer, по умолчанию в этом отчете показаны данные за последние семь дней.

Обнаружение в режиме реального времени содержит представления, такие как вредоносные программы (для электронной почты и контента), Материалы и Phish. Чтобы увидеть, как обнаружение в режиме реального времени сравнивается с Explorer, [загрузите этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Для получения дополнительной информации об Explorer (в Microsoft Defender for Office 365 Plan 2) и обнаружении в [](/microsoft-365/security/office-365-security/threat-explorer)режиме реального времени (в Microsoft Defender for Office 365 Plan 1) см.

### <a name="threat-trackers"></a>Журналы учета угроз

[Отслеживание угроз — это](/microsoft-365/security/office-365-security/threat-trackers) информативные виджеты и представления, которые предоставляют авторизованным пользователям информацию по вопросам кибербезопасности, которые могут повлиять на вашу организацию.

### <a name="automated-incident-response"></a>Автоматизированная реакция на инциденты

[Возможности автоматического реагирования](/microsoft-365/security/office-365-security/office-365-air) на инциденты (AIR), доступные в Defender for Office 365 Plan 2, позволяют запускать автоматизированные процессы расследования в ответ на известные угрозы, которые существуют сегодня. Автоматизированные определенные задачи расследования, ваша команда операций безопасности может работать более эффективно и эффективно. Восстановительные действия, такие как удаление вредоносных сообщений электронной почты, принимаются после утверждения вашей группой операций безопасности. Чтобы узнать больше, [посмотрите, как работает AIR в Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>Тренировка по моделированию атак

[Обучение моделированию атак](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) — это интеллектуальный инструмент управления социальными рисками, который автоматизирует создание и управление фишинговыми симуляторами. Моделирование помогает клиентам обнаруживать, расставлять приоритеты и исправлять фишинговые риски, используя фишинговые приманки реального мира и гипер-целевое обучение для изменения поведения сотрудников.

- Тренировка моделирования атак теперь доступна в WW и GCC (будет в GCC 21 июня).
- Для получения дополнительной информации о том, как начать работу, [см.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Различные методы атаки, которые применяют де-оружейных, реальных фишинг полезной нагрузки доступны, которые повторяют поведение злоумышленника в реальном мире, чтобы сделать фишинг моделирования актуальными.
- Эта услуга доступна организациям, которые имеют либо Microsoft 365 E5, Office 365 E5, либо [Microsoft Defender для Office 365 Плана 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Подмножество возможностей предлагается клиентам E3 в качестве пробной версии.
- Чтобы узнать больше и опробовать симуляцию, [см.](/microsoft-365/security/office-365-security/attack-simulation-training)