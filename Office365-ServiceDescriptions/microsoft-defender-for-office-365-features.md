---
title: Описание службы функций Microsoft Defender для Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Узнайте о функциях, доступных в Microsoft Defender для Office 365.
ms.openlocfilehash: 591236d6028d57025d2dd7a9cfc5ef80d3617176
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671459"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Описание службы функций Microsoft Defender для Office 365

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Что нового в Microsoft Defender для Office 365

Мы продолжаем добавлять новые функции в Defender для Office 365. Дополнительные информацию о новых функциях, которые приходят в Defender для Office 365 (или Microsoft 365 в целом), см. в следующих ресурсах:

- [Дорожная карта Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap)

- [Что нового в Microsoft Defender для Office 365 - Office 365 | Документы Майкрософт](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender для Office 365 возможностей

### <a name="safe-attachments"></a>Безопасные вложения

[Сейф Вложения](/microsoft-365/security/office-365-security/atp-safe-attachments) защищают от неизвестных вредоносных программ и вирусов и обеспечивают защиту нулевого дня для защиты системы обмена сообщениями. Все сообщения и вложения, которые не имеют известной подписи вирусов и вредоносных программ, будут перенастроенными в специальную среду, в которой Defender для Office 365 использует различные методы машинного обучения и анализа для обнаружения вредоносных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Сейф Сканирование вложений происходит в том же регионе, где Office 365 данных. Дополнительные сведения о географии центра обработки данных см. в дополнительных сведениях [о расположении данных?](/microsoft-365/enterprise/o365-data-locations)

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

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Защита SharePoint, OneDrive и Microsoft Teams

[Защита для SharePoint, OneDrive и Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) помогает обнаруживать и блокировать файлы, идентифицированные как вредоносные на сайтах группы и библиотеках документов. Кроме того, Сейф ссылки теперь доступны в Microsoft Teams каналах и чатах.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Антифишинг](/microsoft-365/security/office-365-security/atp-anti-phishing) проверяет входящие сообщения на наличие индикаторов того, что сообщение может быть попыткой фишинга. Когда пользователи охвачены политиками Defender для Office 365 (Сейф вложения, Сейф ссылки или анти-фишинг), входящие сообщения оцениваются несколькими моделями машинного обучения, которые анализируют сообщения и принимаются соответствующие меры на основе настроенных политик.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в Центре & безопасности, включают отчеты и сведения в [режиме](https://protection.office.com) реального времени, которые могут позволить администраторам безопасности и соответствия требованиям сосредоточиться на приоритетных проблемах, например атаках на безопасность или повышенной подозрительной активности. [](/microsoft-365/security/office-365-security/view-reports-for-atp) В дополнение к выделению проблемных областей интеллектуальные отчеты и сведения включают рекомендации и ссылки для просмотра и изучения данных, а также быстрые действия.

### <a name="threat-explorer"></a>Обозреватель угроз

Обозреватель угроз (также именуется Explorer) — это отчет в режиме реального времени, который позволяет уполномоченным пользователям идентифицировать и анализировать недавние угрозы. По умолчанию в этом отчете показаны данные за последние семь дней; однако представления можно изменить, чтобы показать данные за последние 30 дней.

Обозреватель содержит представления, такие как вредоносные программы (для электронной почты и контента), Отправки, Фишинг и Все сообщения электронной почты. Чтобы узнать, как Explorer сравнивает с обнаружениями в режиме реального времени, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения об Обозревателе (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 Plan 1) см. в руб. [Обозреватель](/microsoft-365/security/office-365-security/threat-explorer)угроз и обнаружения в режиме реального времени.

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и в Explorer, по умолчанию в этом отчете показаны данные за последние семь дней.

Обнаружения в режиме реального времени содержат представления, такие как вредоносные программы (для электронной почты и контента), Представления и Фишинг. Чтобы узнать, как обнаружения в режиме реального времени сравнивают с Explorer, [скачайте этот PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Дополнительные сведения об Обозревателе (в Microsoft Defender для Office 365 Plan 2) и обнаружениях в режиме реального времени (в Microsoft Defender для Office 365 Plan 1) см. в руб. [Обозреватель](/microsoft-365/security/office-365-security/threat-explorer)угроз и обнаружения в режиме реального времени.

### <a name="threat-trackers"></a>Журналы учета угроз

[Отслеживание угроз —](/microsoft-365/security/office-365-security/threat-trackers) это информационные виджеты и представления, которые предоставляют уполномоченным пользователям сведения о проблемах кибербезопасности, которые могут повлиять на организацию.

### <a name="automated-investigation--response"></a>Автоматическая проверка & ответа

Возможности автоматического & [ответа](/microsoft-365/security/office-365-security/office-365-air) (AIR), доступные в Defender для Office 365 Plan 2, позволяют запускать автоматизированные процессы расследования в ответ на известные угрозы, которые существуют сегодня. Автоматизация определенных задач по расследованию может работать более эффективно и эффективно. Действия по исправлению, например удаление вредоносных сообщений электронной почты, принимаются после утверждения вашей командой операций безопасности. Дополнительные дополнительные информации см. [в Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>Обучение симуляции атаки

[Обучение моделированию атак](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) — это интеллектуальный инструмент управления социальными рисками, который автоматизирует создание и управление фишинговыми симуляциями. Моделирование помогает клиентам обнаруживать, приоритизировать и устранять риски фишинга, используя реальные фишинговые приманки и гипернацелевую подготовку для изменения поведения сотрудников.

- Обучение имитации атак теперь доступно в WW и GCC (будет в GCC с 21 июня).
- Дополнительные сведения о том, как начать работу, см. в сайте [Get started using Attack simulation training.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Доступны различные методы атак, применяющие де-веружизованные, реальные фишинговые нагрузки, которые реплицируются в реальном мире, чтобы сделать фишинговое моделирование актуальным.
- Эта служба доступна организациям, у Microsoft 365 E5, Office 365 E5 или Microsoft Defender для [Office 365 плана 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Клиенты E3 предлагают подмножество возможностей в качестве пробной пробной части.
- Дополнительные дополнительные уроки и имитация см. в [примере Имитация фишинговой атаки.](/microsoft-365/security/office-365-security/attack-simulation-training)