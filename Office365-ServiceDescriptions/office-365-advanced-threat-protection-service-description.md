---
title: Описание службы Office 365 Advanced Threat Protection
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
description: Microsoft Office 365 Advanced Threat protection (ATP) — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту от вирусов, а также включает функции для защиты Организации от вредоносных ссылок в режиме реального времени.
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318946"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Описание службы Office 365 Advanced Threat Protection

Microsoft Office 365 Advanced Threat protection (ATP) — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту от вирусов, а также включает функции для защиты Организации от вредоносных ссылок в режиме реального времени. ATP обладает богатыми возможностями создания отчетов и трассировки URL-адресов, которые сообщают администраторам о типах атак, происходящих в организации.

Ниже приведены основные способы использования ATP для защиты сообщений.

- В сценарии, предназначенном только для фильтра Office 365 ATP, ATP предоставляет облачную защиту электронной почты для вашей локальной среды Exchange Server или другого локального решения для почты SMTP.

- Office 365 ATP можно включить для защиты облачных почтовых ящиков Exchange Online. Дополнительные сведения об Exchange Online см. в [описании службы Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Для защиты среды обмена сообщениями и управления маршрутизацией почты в гибридном развертывании можно настроить Advanced Threat Protection, если есть локальные и облачные почтовые ящики, а также используется Exchange Online Protection для фильтрации входящих писем.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Доступность Office 365 Advanced Threat Protection

Пакет Office 365 с Планом 2 входит в состав Office 365 E5, Office 365 A5 и Microsoft 365 E5. Office 365 ATP с Планом 1 входит в состав Microsoft 365 бизнес премиум.

Вы можете добавить ATP к следующим планам подписки на Exchange и Microsoft 365:

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

Сведения о приобретении Office 365 Advanced Threat Protection см. на странице [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Чтобы сравнить функции в планах, ознакомьтесь со статьей [мощные средства для поддержки предприятия](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) и [преобразования корпоративной сети в Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Новые возможности Office 365 Advanced Threat Protection (ATP)

Мы продолжаем добавлять новые функции в Office 365 ATP. Дополнительные сведения о новых возможностях, поступающих в ATP (или в Microsoft 365 в целом), можно найти в следующих ресурсах:

- [План выпуска Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Новые возможности Office 365 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Требования для Office 365 Advanced Threat Protection (ATP)

ATP можно использовать с любым агентом передачи почты SMTP, например Microsoft Exchange Server. Сведения о операционных системах, веб-браузерах и языках, поддерживаемых пакетом ATP, можно найти в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" [центра администрирования Exchange в Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Доступность функций в планах Advanced Threat Protection (ATP)

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.

|**Функция**|**План ATP 1**<br>(ранее в автономном режиме ATP)|**План ATP 2**<br>(ранее — аналитика угроз <br>Конфигурация| Microsoft 365 и система безопасности|
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
|Исследование угроз (расширенное исследование угроз)|[Обнаружение в режиме реального времени](#real-time-detections)|[Обозреватель](#explorer)|[Обозреватель](#explorer)|
|[Автоматизированное реагирование на инциденты](#automated-incident-response)|Нет|Да|Да|
|[Эмулятор атак](#attack-simulator)|Нет|Да|Да|

> [!TIP]
> Нужен доступный для загрузки список различий между Office 365 ATP 1 (план 1) и план 2? [Получите PDF-файл](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="advanced-threat-protection-atp-capabilities"></a>Возможности Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Безопасные вложения

[Безопасное вложение ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) защищает от неизвестных вредоносных программ и вирусов и обеспечивает нулевую защиту для защиты системы обмена сообщениями. Все сообщения и вложения, не содержащие известную сигнатуру вируса или вредоносной программы, направляются в специальную среду, где ATP использует ряд методик машинного обучения и анализа для обнаружения преступных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.

> [!NOTE]
> Проверка безопасных вложений ATP выполняется в том же регионе, в котором хранятся данные Office 365. Для получения дополнительных сведений о географическом отношении центра обработки данных Узнайте, [где находятся ваши данные?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Безопасные ссылки

Функция [безопасных ссылок ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) защищает пользователей от вредоносных URL-адресов в сообщении или в документе Office. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

Безопасные ссылки доступны для URL-адресов в следующих приложениях:

- Приложения Microsoft 365 для предприятий в Windows или Mac

- Office для Интернета (Word для Интернета, Excel для Интернета, PowerPoint для Интернета и OneNote для Интернета)

- Word, Excel, PowerPoint и Visio в Windows, а также приложения Office на устройствах с iOS и Android

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны быть лицензированы для ATP <sup>\*</sup> , должны быть включены в политики безопасных ссылок ATP, и их необходимо войти в систему на своих устройствах, чтобы обеспечить защиту на месте.
>
> <sup>\*</sup> Для лицензий ATP на уровне Организации (например, ATP_ENTERPRISE_FACULTY) не требуется назначать лицензии ATP отдельным пользователям.
>
> Чтобы получить дополнительные сведения о защите с помощью безопасных ссылок ATP, посмотрите, [как безопасные ссылки ATP работают с URL-адресами в документах Office](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).

### <a name="safe-documents"></a>Безопасные документы

Функция " [безопасные документы ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) [" использует Advanced Threat Protection в защитнике Майкрософт](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) для сканирования документов и файлов, которые открываются в [режиме защищенного просмотра](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

Что нужно знать перед началом работы

- Безопасные документы теперь доступны пользователям Office версии 2004 (12730. x) или выше. Эта функция отключена по умолчанию и должна быть включена администратором безопасности.

- Эта функция доступна только пользователям, у которых есть лицензия на систему безопасности Microsoft 365 и Microsoft 365 (не входит в планы ATP Office 365).

- Word, Excel, PowerPoint и Visio в Windows, а также приложения Office на устройствах с iOS и Android

- Чаты и каналы Microsoft Teams

> [!NOTE]
> Пользователи должны быть лицензированы для обеспечения безопасности Microsoft 365, а также Microsoft 365 <sup>\*</sup> , необходимо включить в политику безопасных документов ATP и войти в систему на своих устройствах для защиты на месте.
>
> Для получения дополнительных сведений о защите документов, защищенных с пакетом ATP, ознакомьтесь со статьей [безопасные документы в Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[ATP для SharePoint, OneDrive и Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  помогает обнаруживать и блокировать файлы, которые определены как вредоносные на сайтах групп и библиотеках документов. Кроме того, защита от безопасных ссылок ATP теперь доступна в каналах и беседах Microsoft Teams.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Защита от фишинга](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) проверяет входящие сообщения на наличие индикаторов, которые могут быть попыток фишинга. Если на пользователей распространяются политики ATP (безопасные вложения, безопасные ссылки или защита от фишинга), входящие сообщения оцениваются при помощи нескольких моделей машинного обучения, анализирующих сообщения, и на основе настроенных политик предпринимаются соответствующие действия.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в центре безопасности & соответствия требованиям, включают [отчеты в режиме реального времени и аналитические](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) сведения, которые позволяют администраторам системы безопасности и соответствия требованиям в отношении высокоприоритетных проблем, таких как атаки безопасности или повышенное состояние подозрительных действий. В дополнение к выделению проблемных областей, интеллектуальные отчеты и аналитические отчеты включают рекомендации и ссылки на просмотр и изучение данных, а также быстрое выполнение действий.

### <a name="explorer"></a>Обозреватель

Отчет обозревателя, также именуемого обозревателем угроз, — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. По умолчанию в этом отчете отображаются данные за последние 7 дней. Однако представление можно изменить, чтобы отображались данные за последние 30 дней.

Explorer содержит представления, такие как вредоносные программы (для электронной почты и контента), отправки, фишинга и все сообщения электронной почты. Чтобы узнать, как проводник сравнивает с обнаружением в режиме реального времени, [Скачайте этот PDF-файл](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Дополнительные сведения о Explorer (в статье Office 365 Advanced Threat Protection Plan 2) и обнаружении в реальном времени (в статье Office 365 Advanced Threat Protection Plan 1) можно найти в [обозревателе угроз и обнаружения в режиме реального времени](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Обнаружение в режиме реального времени

Обнаружение в режиме реального времени — это отчет в режиме реального времени, который позволяет авторизованным пользователям определить и проанализировать последние угрозы. Как и в отчете обозревателя, в нем по умолчанию отображаются данные за последние 7 дней.

Обнаружение в режиме реального времени содержит представления, такие как вредоносные программы (для электронной почты и контента), отправки и фишинга. Чтобы просмотреть сравнение обнаружений в режиме реального времени с Explorer, [Скачайте этот PDF-файл](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Для получения дополнительных сведений о проводнике (в статье Office 365 Advanced Threat Protection Plan 2) и обнаружении в режиме реального времени (в статье Office 365 Advanced Threat Protection Plan 1), ознакомьтесь со статьей ["Обозреватель угроз" (и обнаружением в режиме реального времени)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Журналы учета угроз

Средства [отслеживания угроз](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) представляют собой информативные элементы и представления, которые предоставляют авторизованным пользователям доступ к проблемам циберсекурити, которые могут повлиять на вашу организацию.

### <a name="automated-incident-response"></a>Автоматизированное реагирование на инциденты

Возможности [автоматизированного реагирования на инциденты](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR), доступные в Office 365 ATP (план 2), позволяют выполнять автоматизированные процессы расследования в ответ на известные угрозы, существующие сегодня. Благодаря автоматическому определению задач по обеспечению безопасности Группа операций безопасности может работать эффективнее и эффективно. Действия по исправлению, такие как удаление вредоносных сообщений электронной почты, берутся после утверждения вашей группой действий по обеспечению безопасности. Чтобы узнать больше, посмотрите, [как Air работает в Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Эмулятор атак

[Имитатор атаки](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) позволяет авторизованным пользователям запускать сценарии с реалистичными атаками в Организации. Доступны различные виды атак, включая отображаемое имя спеар-фишинга, атаки с использованием пароля и атаки методом грубой силы пароля.
