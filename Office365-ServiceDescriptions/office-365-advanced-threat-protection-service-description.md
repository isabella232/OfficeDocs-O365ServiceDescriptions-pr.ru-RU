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
ms.openlocfilehash: 5781f34419eb697cb97634c55fa486fd141d76dd
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204846"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Описание службы Microsoft Defender для Office 365

Microsoft Defender for Office 365 — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от расширенных угроз для средств электронной почты и совместной работы, таких как фишинг, компрометация бизнес-почты и вредоносные программы. Defender for Office 365 также предоставляет возможности для расследования, охоты и устранения, чтобы помочь группам безопасности эффективно выявлять, определять приоритеты, исследовать и реагировать на угрозы.

Основные способы использования Defender для защиты Office 365:

- В сценарии Defender для Office 365 только для фильтрации Defender for Office 365 предоставляет облачную защиту электронной почты для локальной среды Exchange Server или любого другого локального решения SMTP электронной почты.

- Защитник для Office 365 может быть включен для защиты Exchange Online облачных почтовых ящиков. Дополнительные дополнительные Exchange Online см. в [описании Exchange Online службы.](exchange-online-service-description/exchange-online-service-description.md)

- В гибридном развертывании defender for Office 365 можно настроить для защиты среды обмена сообщениями и управления маршрутией почты, если у вас есть сочетание локального и облачного почтовых ящиков с Exchange Online Protection для входящих фильтрации электронной почты.

## <a name="available-plans"></a>Доступные планы

Подробные сведения о планах подписки, которые позволяют пользователям для Microsoft Defender для Office 365, см. в полной таблице [сравнения подписки.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="feature-availability"></a>Доступность функций

В следующей таблице перечислены основные функции Microsoft Defender для Office 365, доступные в планах. Применяются определенные оговорки. Дополнительные сведения см. в сносках. Эта таблица может измениться без уведомления. Полный список функций Microsoft Defender для Office 365 в планах см. в описании службы [Microsoft Defender для Office 365 features.](microsoft-defender-for-office-365-features.md)

| Функция | Defender для Office 365 (план 1) | Defender для Office 365 (план 2) | Microsoft 365 E5 / A5 Security |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *Конфигурация, защита и обнаружение* | | | |
| Предустановленные политики безопасности и анализатор конфигурации | Да | Да | Да |
| [Безопасные вложения](microsoft-defender-for-office-365-features.md#safe-attachments) | Да | Да | Да |
| Сейф Вложения в Teams | Да | Да | Да |
| [Безопасные ссылки](microsoft-defender-for-office-365-features.md#safe-links) | Да | Да | Да |
| [Безопасные документы](microsoft-defender-for-office-365-features.md#safe-documents) | Нет | Нет | Да |
| Безопасные ссылки в Teams | Да | Да | Да |
| Сообщение Add-In | Да | Да | Да |
| [Защита SharePoint, OneDrive и Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | Да | Да | Да |
| [Политики защиты от фишинга](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | Да | Да | Да |
| [Отчеты в режиме реального времени](microsoft-defender-for-office-365-features.md#real-time-reports) | Да | Да | Да |
| Расширенные средства защиты внутренней почты | Да | Да | Да |
| *Автоматизация, исследование, исправление и образование* | | | |
| [Трекеры угроз](microsoft-defender-for-office-365-features.md#threat-trackers) | Нет | Да | Да |
| Представления кампании | Нет | Да | Да |
| Расследование угроз (предварительное расследование угрозы) | [Обнаружение в режиме реального времени](microsoft-defender-for-office-365-features.md#real-time-detections) | [Обозреватель](microsoft-defender-for-office-365-features.md#threat-explorer) | [Обозреватель](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [Автоматическая проверка & ответа](microsoft-defender-for-office-365-features.md#automated-investigation--response) | Нет | Да | Да |
| [Обучение симуляции атаки](microsoft-defender-for-office-365-features.md#attack-simulation-training) | Нет | Да | Да |
| *Интеграция [с Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)* | Нет | Да | Да |

> [!NOTE]
> Microsoft Defender для Office 365 является компонентом Microsoft 365 Defender. Дополнительные сведения об автоматизированной безопасности между доменами с Microsoft 365 Defender см. в Microsoft 365 Defender [требования.](/microsoft-365/security/mtp/prerequisites)

## <a name="learn-more"></a>Дополнительные сведения

Дополнительные сведения о Microsoft Defender для Office 365, ознакомьтесь с следующими ресурсами:

- [Защитник Майкрософт для Office 365 в Microsoft Docs](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Defender для Office 365 веб Office 365](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Microsoft Defender для Office 365 блог](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Microsoft Defender для Office 365 Форум](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>Условия лицензирования

Условия лицензирования продуктов и служб, приобретенных через Программы лицензирования коммерческих объемов Корпорации Майкрософт, см. на [сайте Условия продукта.](https://www.microsoft.com/licensing/terms/)

### <a name="messaging"></a>Сообщения

Чтобы быть в курсе предстоящих изменений, в том числе новых и измененных функций, планового обслуживания или других важных объявлений, посетите Центр сообщений. Дополнительные сведения см. в [центре сообщений.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Специальные возможности

Корпорация Майкрософт по-прежнему привержена безопасности ваших данных и [доступности](https://www.microsoft.com/trust-center/compliance/accessibility) наших служб. Дополнительные сведения см. в [центре доверия Майкрософт](https://www.microsoft.com/trust-center) и центре Office [доступности.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
