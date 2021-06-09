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
description: Microsoft Defender for Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня и включает функции для защиты организации от вредных ссылок в режиме реального времени.
ms.openlocfilehash: 2f93551be9df45e6108d81da9d7a50bba53be549
ms.sourcegitcommit: 25b208f02689d4ef4b37d36a49135c1b4b5a8204
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/07/2021
ms.locfileid: "52798455"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Описание службы Microsoft Defender для Office 365

Microsoft Defender for Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня и включает функции для защиты организации от вредных ссылок в режиме реального времени. Defender for Office 365 обладает богатыми возможностями для отслеживания отчетов и URL-адресов, которые дают администраторам представление о том, какие атаки происходят в вашей организации.

Основные способы использования Defender для защиты Office 365:

- В сценарии Defender для Office 365 только для фильтрации Defender for Office 365 предоставляет облачную защиту электронной почты для локальной среды Exchange Server или любого другого локального решения SMTP электронной почты.

- Защитник для Office 365 может быть включен для защиты Exchange Online облачных почтовых ящиков. Дополнительные дополнительные Exchange Online см. в [описании Exchange Online службы.](exchange-online-service-description/exchange-online-service-description.md)

- В гибридном развертывании defender for Office 365 можно настроить для защиты среды обмена сообщениями и управления маршрутией почты, если у вас есть сочетание локального и облачного почтовых ящиков с Exchange Online Protection для входящих фильтрации электронной почты.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender для Office 365 доступности

Microsoft Defender для Office 365 Plan 2 включен в Office 365 E5, Office 365 A5, Безопасность Microsoft 365 E5 и Microsoft 365 E5, как указано здесь: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender for Office 365 Plan 1 включен в Microsoft 365 бизнес премиум.

Вы можете добавить Defender для Office 365 в следующие Exchange и Microsoft 365 подписки:

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

Чтобы купить Microsoft Defender для Office 365, см. [в Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Подробные сведения о планах подписки, которые позволяют пользователям для Microsoft Defender для Office 365, см. в полной таблице [сравнения подписки.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Что нового в Microsoft Defender для Office 365

Мы продолжаем добавлять новые функции в Defender для Office 365. Дополнительные информацию о новых функциях, которые приходят в Defender для Office 365 (или Microsoft 365 в целом), см. в следующих ресурсах:

- [Дорожная карта Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Что нового в Microsoft Defender для Office 365 - Office 365 | Документы Майкрософт](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Требования к Microsoft Defender для Office 365

Defender for Office 365 можно использовать с любым агентом smTP по передаче почты, например Microsoft Exchange Server. Сведения об операционных системах, веб-браузерах и языках, поддерживаемых Defender для Office 365, см. в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" в центре администрирования Exchange в [Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Доступность функций в Defender для Office 365 планов

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.<br><br>

| Возможность | Defender для Office 365 (план 1) | Defender для Office 365 (план 2) | Microsoft 365 E5 / A5 Security|
|:-----|:-----|:-----|:-----|
|*Конфигурация, защита и обнаружение*|
|[Безопасные вложения](#safe-attachments)|Да|Да|Да|
|Сейф Вложения в Teams|Да|Да|Да|
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
|[Обучение имитации атаки](#attack-simulation-training)|Нет|Да|Да|
|*Интеграция [с Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Нет|Да|Да|

> [!NOTE]
> Если у клиента есть только пробная лицензия Microsoft Defender для Office Plan P2 или Office 365 пробная лицензия E5 без другой лицензии Microsoft 365 Defender, вы не сможете получить доступ к Microsoft 365 Defender. Подробнее о лицензии MTP см. в Microsoft 365 [Defender.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Defender для Office 365 возможностей

### <a name="safe-attachments"></a>Безопасные вложения

[Сейф Вложения](/microsoft-365/security/office-365-security/atp-safe-attachments) защищают от неизвестных вредоносных программ и вирусов и обеспечивают защиту нулевого дня для защиты системы обмена сообщениями. Все сообщения и вложения, которые не имеют известной подписи вирусов и вредоносных программ, будут перенастроенными в специальную среду, в которой Defender для Office 365 использует различные методы машинного обучения и анализа для обнаружения вредоносных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Сейф Сканирование вложений происходит в том же регионе, где Office 365 данных. Дополнительные сведения о географии центра обработки данных см. в дополнительных сведениях [о расположении данных?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Безопасные ссылки

Функция [Сейф ссылки](/microsoft-365/security/office-365-security/atp-safe-links) активно защищает пользователей от вредоносных URL-адресов в сообщении или Office документе. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

Безопасные ссылки доступны для URL-адресов в следующих приложениях:

- Приложения Microsoft 365 для предприятий на Windows Mac

- Office для Интернета (Word для Интернета, Excel для Интернета, PowerPoint для Интернета и OneNote для Интернета)

- Word, Excel и PowerPoint на Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензию на defender для Office 365, должны быть включены в Сейф ссылки и должны быть подписаны на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> <sup>\*</sup>Для всей организации Defender для Office 365 лицензий (например, ATP_ENTERPRISE_FACULTY), вам не нужно назначать Defender для Office 365 лицензий отдельным пользователям.
>
> Дополнительные сведения о защите Сейф ссылок см. в [Сейф Ссылки в Microsoft Defender для Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Безопасные документы

Функция [Сейф документов](/microsoft-365/security/office-365-security/safe-docs) использует Microsoft Defender для [конечной](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) точки для сканирования документов и файлов, открытых в [защищенной точке зрения.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Что нужно знать перед началом работы

- Сейф Документы теперь, как правило, доступны пользователям с Office версии 2004 (12730.x) или больше! Эта функция отключена по умолчанию и должна быть включена администратором безопасности.

- Эта функция доступна только пользователям с Microsoft 365 E5 или Безопасность Microsoft 365 E5 лицензией (не включена в Defender для Office 365 планов).

- Word, Excel и PowerPoint на Windows

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны иметь лицензии на Microsoft 365 E5 или Безопасность Microsoft 365 E5, должны быть включены в политики Сейф документов и должны быть подписаны на своих устройствах для обеспечения <sup>\*</sup> защиты.
>
> Дополнительные сведения о защите Сейф документов см. в [Сейф documents in Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[ATP для SharePoint, OneDrive и Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) помогает обнаруживать и блокировать файлы, которые идентифицированы как вредоносные на сайтах команд и библиотеках документов. Кроме того, Сейф ссылки теперь доступны в Microsoft Teams каналах и чатах.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Антифишинг](/microsoft-365/security/office-365-security/atp-anti-phishing) проверяет входящие сообщения на наличие индикаторов того, что сообщение может быть попыткой фишинга. Когда пользователи охвачены политиками Defender для Office 365 (Сейф вложения, Сейф ссылки или анти-фишинг), входящие сообщения оцениваются несколькими моделями машинного обучения, которые анализируют сообщения и принимаются соответствующие меры на основе настроенных политик.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в Центре & безопасности ( ) включают отчеты и сведения в режиме реального времени, которые могут позволить администраторам безопасности и соответствия требованиям сосредоточиться на приоритетных проблемах, таких как атаки безопасности или повышенная подозрительная [https://protection.office.com](https://protection.office.com) активность. [](/microsoft-365/security/office-365-security/view-reports-for-atp) В дополнение к выделению проблемных областей интеллектуальные отчеты и сведения включают рекомендации и ссылки для просмотра и изучения данных, а также быстрые действия.

### <a name="explorer"></a>Обозреватель

Отчет обозревателя, также именуемого обозревателем угроз, — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. По умолчанию в этом отчете показаны данные за последние семь дней; однако представления можно изменить, чтобы показать данные за последние 30 дней.

Обозреватель содержит представления, такие как вредоносные программы (для электронной почты и контента), Отправки, Фишинг и Все сообщения электронной почты. Чтобы узнать, как Explorer сравнивает с обнаружениями в режиме реального времени, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения об Обозревателе (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 Plan 1) см. в руб. [Обозреватель](/microsoft-365/security/office-365-security/threat-explorer)угроз и обнаружения в режиме реального времени.

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и в Explorer, по умолчанию в этом отчете показаны данные за последние семь дней.

Обнаружения в режиме реального времени содержат представления, такие как вредоносные программы (для электронной почты и контента), Представления и Фишинг. Чтобы узнать, как обнаружения в режиме реального времени сравнивают с Explorer, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения о Explorer (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 Plan 1) см. в руб. Обозреватель угроз (и обнаружения в режиме реального [времени).](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Журналы учета угроз

[Отслеживание угроз —](/microsoft-365/security/office-365-security/threat-trackers) это информационные виджеты и представления, которые предоставляют уполномоченным пользователям сведения о проблемах кибербезопасности, которые могут повлиять на организацию.

### <a name="automated-incident-response"></a>Автоматическая реакция на инциденты

[Возможности автоматического](/microsoft-365/security/office-365-security/office-365-air) реагирования на инциденты (AIR), доступные в Defender для Office 365 Plan 2, позволяют запускать автоматизированные процессы расследования в ответ на известные угрозы, которые существуют сегодня. Автоматизация определенных задач расследования может привести к более эффективной и эффективной работе группы операций безопасности. Действия по исправлению, например удаление вредоносных сообщений электронной почты, принимаются после утверждения вашей командой операций безопасности. Дополнительные дополнительные информации см. [в Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>Обучение имитации атаки

[Обучение моделированию атак](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) — это интеллектуальный инструмент управления социальными рисками, который автоматизирует создание и управление фишинговыми симуляциями. Моделирование помогает клиентам обнаруживать, приоритизировать и устранять риски фишинга, используя реальные фишинговые приманки и гипернацелевую подготовку для изменения поведения сотрудников.

- Обучение имитации атак теперь доступно в WW и GCC (будет в GCC с 21 июня).
- Дополнительные сведения о том, как начать работу, см. в сайте [Get started using Attack simulation training.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Доступны различные методы атак, применяющие де-веружизованные, реальные фишинговые нагрузки, которые реплицируются в реальном мире, чтобы сделать фишинговое моделирование актуальным.
- Эта служба доступна организациям с лицензиями Microsoft 365 E5, Office 365 E5 или [Microsoft Defender для Office 365 Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Клиенты E3 предлагают подмножество возможностей в качестве пробной пробной части.
- Дополнительные дополнительные уроки и имитация см. в [примере Имитация фишинговой атаки.](/microsoft-365/security/office-365-security/attack-simulation-training)