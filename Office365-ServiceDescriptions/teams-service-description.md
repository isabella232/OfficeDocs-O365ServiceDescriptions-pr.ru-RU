---
title: Описание службы Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Узнайте о доступности Microsoft Teams и функций в Microsoft 365 и Office 365 планах.
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074490"
---
# <a name="microsoft-teams-service-description"></a>Описание службы Microsoft Teams

Microsoft Teams является центром командной работы в Microsoft 365. Служба Teams обмена мгновенными сообщениями, аудио- и видеосвязи, богатыми сетевыми собраниями, мобильными возможностями и широкими возможностями веб-конференций. Кроме того, Teams предоставляет функции совместной работы с файлами и данными, а также интегрируется с Microsoft 365 и другими приложениями Майкрософт и партнеров.

Skype для бизнеса 31 июля 2021 г., объявленный 30 июля 2019 г., он уходит в отставку. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams это совершенно новая служба, созданная для облака с нуля, используя Azure и другие инновации службы от Корпорации Майкрософт. Microsoft Teams построена на Microsoft 365, microsoft Graph и с той же безопасностью, соответствием требованиям и управляемостью, что и Office 365. Teams использует удостоверения, хранимые в Azure Active Directory (Azure AD). Эти службы доставляются из центров обработки данных Майкрософт и доступны пользователям на широком диапазоне устройств внутри корпоративной сети или через Интернет. Дополнительные сведения см. в [Microsoft Teams ИТ-архитектуры](/microsoftteams/teams-architecture-solutions-posters)и плакатов решений для телефонии.

В этом описании службы описаны основные различия между службами, предоставляемыми в различных облачных установках. Microsoft Teams основные функции не отличаются между подписками. Доступность возможностей соответствия требованиям зависит от уровня подписки. Дополнительные дополнительные Teams безопасности и соответствия требованиям см. в [Microsoft Teams.](/microsoftteams/security-compliance-overview)

Если пользователи были перенесены полностью в Интернете, они должны иметь лицензии Skype для бизнеса Online для полного Teams, даже если Skype для бизнеса Online не будет использоваться.

## <a name="available-plans"></a>Доступные планы

Подробные сведения о планах подписки, которые позволяют пользователям Teams, см. в Microsoft Teams [для вашего бизнеса.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Дополнительные сведения можно найти в таблице [сравнения решений Майкрософт.](https://go.microsoft.com/fwlink/?linkid=2139145)

Планы правительства, которые Teams включают Office 365 G1 через G5. Дополнительные сведения см. [в Office 365 для государственных организаций планах.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)

Все поддерживаемые планы подписки имеют право на доступ к веб Microsoft Teams клиенту, настольным клиентам и мобильным приложениям.

Microsoft Teams недоступна в качестве автономных служб.

## <a name="feature-availability"></a>Доступность функций

В следующей таблице перечислены основные Teams, доступные в планах. Применяются определенные оговорки. Дополнительные сведения см. в сносках. Эта таблица может измениться без уведомления.

Дополнительные возможности Teams с помощью платформы операционной системы см. в Teams [функций по платформе.](https://aka.ms/teamsfeaturesbyplatform)

Полный список функций Teams различных Microsoft 365 и Office 365 см. в Microsoft Teams. [](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Возможность | Планы малого бизнеса | Enterprise планы | GCC | GCC - High | DOD | Планы образования |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Чат  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Teams  <br/> |Да <br/> |Да <br/> |Да <br/> |Да<sup>1</sup>  <br/> |Да<sup>1</sup>  <br/> |Да  <br/> |
|Каналы — стандартные  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Каналы — частные  <br/> |Да  <br/> |Да<sup>2</sup>  <br/> |Да <br/> |Нет  <br/> |Нет <br/> |Да  <br/> |
|Собрания  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Совместное использование PowerPoint аудио- и видео настольных компьютеров <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Голосовые вызовы  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да<sup>3</sup>  <br/> |Да<sup>3</sup>  <br/> |Да  <br/> |
|Аудиоконференции  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да<sup>3</sup>  <br/> |Да<sup>3</sup>  <br/> |Да  <br/> |
|Приложения, боты, & соединители  <br/> |Да  <br/> |Да  <br/> |Да<sup>4</sup>  <br/> |Да<sup>4</sup>  <br/> |Да<sup>4</sup>  <br/> |Да  <br/> |
|События в прямом эфире  <br/> |Нет  <br/> |Да  <br/> |Да  <br/> |No<sup>5</sup>  <br/> |No<sup>5</sup>  <br/> |Да  <br/> |

<sup>1</sup> Microsoft Teams в GCC-High и doD поддерживают 2500 членов в отдельной команде.<br/>
<sup>2</sup> Microsoft Planner в настоящее время не доступен для доступа в частных каналах.<br/>
<sup>3</sup> Прямая маршрутная маршрутия должна быть настроена для Microsoft Teams голосовых и аудиоконференций для работы в GCCH и DoD.<br/>
<sup>В настоящее</sup> время в этих облаках недоступны 4 сторонних приложения и публикации приложений. Соединители не поддерживаются в GCCH и DOD.<br/>
<sup>5</sup> Live Events в настоящее время GCC-High или в DoD.<br/>

### <a name="cloud-voice-features"></a>Функции облачного голосового голоса

Для аудиоконференций организации необходимо приобрести и назначить лицензию на аудиоконференцию каждому пользователю, который настраивает собрания с диалогом. Для Teams, для которых требуются планы звонков, каждому пользователю требуется телефонная система и внутренний или внутренний и международный план звонков. Дополнительные дополнительные [Microsoft Teams надстройки.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Трансляции

Это предложение в Office 365 заменяет ушедшего в отставку Skype трансляцию собраний. Возможности живых событий доступны для планов лицензирования, как описано в службе Stream. Дополнительные сведения можно получить в обзоре [лицензирования Microsoft Stream.](/stream/license-overview) К службе событий в прямом эфире можно получить доступ через stream, Yammer или Microsoft Teams. Дополнительные информацию о возможностях событий в прямом эфире см. в Microsoft 365 в [Yammer, Microsoft Teams и Microsoft Stream.](/stream/live-event-m365) Дополнительные информацию о планировании живых событий, включая требования к лицензиям, см. в руб. [Plan for live events in Microsoft Teams.](/microsoftteams/teams-live-events/plan-for-teams-live-events)

## <a name="learn-more"></a>Подробнее

Дополнительные сведения о Teams, ознакомьтесь со следующими ресурсами:
 
- [Документы для администраторов Microsoft Teams](/MicrosoftTeams)
- [Microsoft Teams технического сообщества](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams блог](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Условия лицензирования

Условия лицензирования продуктов и служб, приобретенных через Программы лицензирования коммерческих объемов Корпорации Майкрософт, см. на [сайте Условия продукта.](https://www.microsoft.com/licensing/terms/) 

### <a name="messaging"></a>Сообщения

Чтобы быть в курсе предстоящих изменений, в том числе новых и измененных функций, планового обслуживания или других важных объявлений, посетите Центр сообщений. Дополнительные сведения см. в [центре сообщений.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Специальные возможности

Корпорация Майкрософт по-прежнему привержена безопасности ваших данных и доступности наших служб. Дополнительные сведения см. в [центре доверия Майкрософт](https://www.microsoft.com/trust-center) и центре Office [доступности.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
