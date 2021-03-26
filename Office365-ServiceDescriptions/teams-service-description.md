---
title: Описание службы Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Узнайте о доступности служб и функций Microsoft Teams в планах Microsoft 365 и Office 365.
ms.openlocfilehash: 59eaee9a36eaff8dd79d5ff9690bf04e966f3dfe
ms.sourcegitcommit: ec02d469f5815efa65bdb4f17bd4a6f89af13d3a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/25/2021
ms.locfileid: "51215732"
---
# <a name="microsoft-teams-service-description"></a>Описание службы Microsoft Teams

Microsoft Teams — это центр командной работы в Microsoft 365. Служба Teams включает мгновенные сообщения, аудио- и видеозвонков, богатые собрания в Интернете, мобильные возможности и широкие возможности веб-собраний. Кроме того, Teams предоставляет функции совместной работы с файлами и данными, а также интегрируется с Microsoft 365 и другими приложениями Microsoft и партнерами.

Skype для бизнеса Online завершится 31 июля 2021 г., о котором было объявлено 30 июля 2019 г. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams — это совершенно новая служба, созданная для облака с нуля, используя Azure и другие инновации службы от Корпорации Майкрософт. Microsoft Teams построена на группах Microsoft 365, Microsoft Graph и с той же безопасностью, соответствием требованиям и управляемостью, что и остальная часть Office 365. Teams использует удостоверения, хранимые в Azure Active Directory (Azure AD). Эти службы доставляются из центров обработки данных Майкрософт и доступны пользователям на широком диапазоне устройств внутри корпоративной сети или через Интернет. Дополнительные сведения см. в [плакатах microsoft Teams ИТ-архитектуры](/microsoftteams/teams-architecture-solutions-posters)и решений для телефонии.

В этом описании службы описаны основные различия между службами, предоставляемыми в различных облачных установках. Основные функциональные возможности Microsoft Teams не отличаются между подписками. Доступность возможностей соответствия требованиям зависит от уровня подписки. Дополнительные информацию о безопасности и соответствии требованиям Teams см. в веб-сайте [Безопасность и соответствие требованиям в Microsoft Teams.](/microsoftteams/security-compliance-overview)

## <a name="available-plans"></a>Доступные планы

Подробные сведения о планах по подпискам, которые позволяют пользователям teams, см. в журнале [Find the right Microsoft Teams for your business.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Дополнительные сведения можно найти в таблице [сравнения решений Майкрософт.](https://go.microsoft.com/fwlink/?linkid=2139145)

Планы правительства, которые поддерживают Teams, включают Office 365 G1 через G5. Дополнительные сведения см. в [сайте Office 365 Government plans.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)

Все поддерживаемые планы подписки имеют право на доступ к веб-клиенту Microsoft Teams, настольным клиентам и мобильным приложениям.

Microsoft Teams недоступна в качестве автономных служб.

## <a name="feature-availability"></a>Доступность функций

В следующей таблице перечислены основные функции Teams, доступные в планах. Применяются определенные оговорки. Дополнительные сведения см. в сносках. Эта таблица может измениться без уведомления.

Дополнительные возможности Teams с помощью платформы операционной системы см. в дополнительных данных [о свойствах Teams по платформе.](https://aka.ms/teamsfeaturesbyplatform)

Полный список функций Teams в планах Microsoft 365 и Office 365 см. в списке Найти правильные microsoft [Teams для бизнеса.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Возможность | Планы малого бизнеса | Корпоративные планы | GCC | GCC - High | DOD | Планы образования |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Чат  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Teams  <br/> |Да <br/> |Да <br/> |Да <br/> |Да<sup>1</sup>  <br/> |Да<sup>1</sup>  <br/> |Да  <br/> |
|Каналы — стандартные  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Каналы — частные  <br/> |Да  <br/> |Да<sup>2</sup>  <br/> |Да <br/> |Нет  <br/> |Нет <br/> |Да  <br/> |
|Собрания  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Screen sharing PowerPoint Audio/Video Desktop <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Голосовые вызовы  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да<sup>3</sup>  <br/> |Да<sup>3</sup>  <br/> |Да  <br/> |
|Аудиоконференции  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да<sup>3</sup>  <br/> |Да<sup>3</sup>  <br/> |Да  <br/> |
|Приложения, боты, & соединители  <br/> |Да  <br/> |Да  <br/> |Да<sup>5</sup>  <br/> |Да<sup>5</sup>  <br/> |Да<sup>4,5</sup>  <br/> |Да  <br/> |
|События в прямом эфире  <br/> |Нет  <br/> |Да  <br/> |Да  <br/> |No<sup>6</sup>  <br/> |No<sup>6</sup>  <br/> |Да  <br/> |

<sup>1</sup> Microsoft Teams в GCC-High и doD поддерживают 2500 членов в отдельной команде.<br/>
<sup>2</sup> Microsoft Planner в настоящее время не доступен для доступа в частных каналах.<br/>
<sup>3</sup> Прямая маршрутная маршрутия должна быть настроена для голосовых и аудиоконференций Microsoft Teams для работы в GCCH и DoD.<br/>
<sup>4</sup> Microsoft OneNote недоступна в облаках DOD.<br/>
<sup>В настоящее</sup> время в этих облаках недоступны 5 сторонних приложений и публикаций приложений.<br/>
<sup>6</sup> Live Events в настоящее время недоступны GCC-High или DoD.<br/>

### <a name="cloud-voice-features"></a>Функции облачного голосового голоса

Для аудиоконференций организации необходимо приобрести и назначить лицензию на аудиоконференцию каждому пользователю, который настраивает собрания с диалогом. Для функций Teams, для которых требуются планы звонков, каждому пользователю требуется телефонная система и внутренний или внутренний и международный план звонков. Дополнительные новости см. [в добавлении Microsoft Teams к лицензиям.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Трансляции

Это предложение в Office 365 заменяет отмененную трансляцию собраний Skype. Возможности живых событий доступны для планов лицензирования, как описано в службе Stream. Дополнительные сведения можно получить в обзоре [лицензирования Microsoft Stream.](/stream/license-overview) К службе событий в прямом эфире можно получить доступ через Stream, Yammer или Microsoft Teams. Дополнительные информацию о возможностях живых событий см. в [live-событиях в Microsoft 365 в Yammer, Microsoft Teams и Microsoft Stream.](/stream/live-event-m365)

## <a name="learn-more"></a>Дополнительные сведения

Дополнительные сведения о Teams ознакомьтесь со следующими ресурсами:
 
- [Документы для администраторов Microsoft Teams](/MicrosoftTeams)
- [Техническое сообщество Microsoft Teams](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Блог Microsoft Teams](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Условия лицензирования

Условия лицензирования продуктов и служб, приобретенных через Программы лицензирования коммерческих объемов Корпорации Майкрософт, см. на [сайте Условия продукта.](https://www.microsoft.com/licensing/terms/) 

### <a name="messaging"></a>Обмен сообщениями 

Чтобы быть в курсе предстоящих изменений, в том числе новых и измененных функций, планового обслуживания или других важных объявлений, посетите Центр сообщений. Дополнительные сведения см. в [центре сообщений.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Специальные возможности

Корпорация Майкрософт по-прежнему привержена безопасности ваших данных и доступности наших служб. Дополнительные сведения см. в [центре доверия Майкрософт](https://www.microsoft.com/trust-center) и Центре [доступности office.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)