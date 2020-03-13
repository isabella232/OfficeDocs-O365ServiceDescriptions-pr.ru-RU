---
title: Описание службы Microsoft Teams
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft Teams обеспечивает обмен мгновенными сообщениями, совместной работы с файлами и данными, аудио-и видеозвонки, полнофункциональные интерактивные собрания, мобильные взаимодействия и расширенные возможности веб-конференций.
ms.openlocfilehash: cd16f511c5bd0af7c8e64cf4efd383ca48f74b30
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609990"
---
# <a name="microsoft-teams-service-description"></a>Описание службы Microsoft Teams

Microsoft Teams это центр для работы в Microsoft 365. Служба Teams позволяет осуществлять обмен мгновенными сообщениями, аудио-и видеозвонки, полнофункциональные интерактивные собрания, мобильные взаимодействия и расширенные возможности веб-конференций. Кроме того, Teams предоставляет возможности для совместной работы с файлами и данными и их расширения, а также интегрируется с Microsoft 365 и другими приложениями Майкрософт и партнерами.

Skype для бизнеса Online будет выпущен 31 июля 2021 г., [который был выпущен](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 30 июля 2019 г. Microsoft Teams — это полностью новая служба, созданная для облака с нуля с помощью Azure и других нововведений в службах Майкрософт. Microsoft Teams основан на группах Office 365, Microsoft Graph и на уровне корпоративного уровня безопасности, соответствия требованиям и управляемости, как и в остальных версиях Office 365. Teams использует удостоверения, хранящиеся в Azure Active Directory (Azure AD). Эти службы доставляются из центров обработки данных Майкрософт и доступны пользователям на широком диапазоне устройств из корпоративной сети или через Интернет. Дополнительные сведения можно найти в статье [архитектура и схема решений для архитектуры Teams](https://docs.microsoft.com/microsoftteams/teams-architecture-solutions-posters).

Корпорация Майкрософт остается в обеспечении безопасности ваших данных и [специальных возможностей](https://www.microsoft.com/trust-center/compliance/accessibility) наших услуг. Дополнительные сведения можно найти в [центре управления безопасностью Майкрософт](https://www.microsoft.com/trust-center) и [центре специальных возможностей Office](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Для вашей справки мы включили эту основную таблицу подписок на Office 365, которые позволяют пользователям Microsoft Teams. Полную информацию можно найти в [статье Лицензирование Office 365 для Microsoft Teams](https://docs.microsoft.com/microsoftteams/office-365-licensing). Дополнительные сведения о планах Office 365 в государственных планах представлены в статье [office 365 для государственных организаций](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). В Office 365 с G1 по G5 есть доступ к функциям Teams.

|||||
|:-----|:-----|:-----|:-----|
|**Планы для малого бизнеса** <br/> |**Планы предприятия** <br/> |**Планы образования** <br/> |**Планы для разработчиков** <br/> |
|Office 365 бизнес базовый  <br/> |Office 365 корпоративный E1  <br/> |Office 365 для образовательных учреждений  <br/> |Office 365 для разработчиков  <br/> |
|Office 365 бизнес премиум  <br/> |Office 365 корпоративный E3  <br/> |Office 365 для образования плюс  <br/> |   <br/> |
|Microsoft 365 для бизнеса  <br/> |Office 365 корпоративный E4 (с прекращением)  <br/> |Office 365 для образования E3 (с прекращением)  <br/> |  <br/> |
|  <br/> |Office 365 корпоративный E5  <br/> |Office 365 для образования E5  <br/> |  <br/> |
|  <br/> |Office 365 корпоративный F1  <br/> |  <br/> |  <br/> |

Подробные инструкции по реализации функций продукции представлены в [документации для администраторов Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams). В этом описании службы описываются основные различия между службами, предоставляемыми для различных облачных установок. Основные функциональные возможности Microsoft Teams не отличаются между подписками на Office 365. Доступность возможностей соответствия зависит от уровня подписки. Чтобы узнать больше, ознакомьтесь со статьей [безопасность и соответствие требованиям в Microsoft Teams](https://docs.microsoft.com/microsoftteams/security-compliance-overview). Подробный список функций, доступных в каждой подписке, представлен в статье [Описание службы платформы Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description).

**Функции облачной голосовой связи**: для конференций с аудио-и видеоконференциями в Организации необходимо приобрести и назначить лицензию на голосовую конференцию каждому пользователю, который будет настраивать собрания с телефонным подключением. Для функций Teams, которым требуются планы звонков, каждому пользователю необходима телефонная система, а также план внутреннего или внутреннего звонка. Чтобы узнать больше, ознакомьтесь [со статьей лицензирование надстроек Microsoft Teams](https://docs.microsoft.com/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

**События Live**: это предложение в Office 365 заменяет отмененное вещание собраний Skype. Возможности Live Events доступны для планов лицензирования, как описано в службе потока. Ознакомьтесь со [сведениями о лицензировании](https://docs.microsoft.com/stream/license-overview). Доступ к службе Live Events можно получить с помощью Stream, Yammer или Microsoft Teams. Чтобы узнать больше о возможностях Live Events, ознакомьтесь со статьями [Live Events в microsoft 365 в Yammer, Microsoft Teams и Microsoft Stream](https://docs.microsoft.com/stream/live-event-m365).

Все поддерживаемые планы подписки подходят для доступа к веб-клиенту Microsoft Teams, настольным клиентам и мобильным приложениям.

Microsoft Teams недоступен в качестве автономной службы.

## <a name="feature-category-reference"></a>Справочник по категориям компонентов 

В этой таблице перечислены функции Microsoft Teams, доступные в планах лицензирования или облачных экземплярах. Применяются некоторые предостережения. Дополнительные сведения можно найти в сносках. Эта таблица может измениться без предварительного уведомления. Обратитесь к разделу Microsoft 365 Message Center Notifications об изменении основной службы и в [справочную документацию по лицензионным условиям корпорации Майкрософт](https://www.microsoft.com/licensing/product-licensing/products).

|||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <br/>|**Малый бизнес** <br/> |**Планы предприятия** <br/> |**GCC** <br/> |**GCC — High** <br/> |**ВЫЗОВ** <br/> |**Образование** <br/> |
|Чат  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Teams  <br/> |Да <br/> |Да <br/> |Да <br/> |Да<sup>1</sup>  <br/> |Да<sup>1</sup>  <br/> |Да  <br/> |
|Каналы — Standard  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Каналы — частные  <br/> |Да  <br/> |Да<sup>2</sup>  <br/> |Нет<sup>3</sup>  <br/> |Нет<sup>3</sup>  <br/> |Нет<sup>3</sup>  <br/> |Да  <br/> |
|Собрания  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Демонстрация экрана PowerPoint Audio/Video Desktop <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Голосовые вызовы  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Аудиоконференции  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |
|Приложения, Боты, соединители &  <br/> |Да  <br/> |Да  <br/> |Да<sup>4</sup>  <br/> |Да<sup>4</sup>  <br/> |Да<sup>4</sup>  <br/> |Да  <br/> |
|События Live  <br/> |Да  <br/> |Да  <br/> |Да  <br/> |Нет<sup>5</sup>  <br/> |Нет<sup>5</sup>  <br/> |Да  <br/> |

<sup>1</sup> в Microsoft Teams в GCC, а не в Microsoft Teams поддержка по требованию 2500 членов отдельной команды.<br/>
<sup>2</sup> планировщик Microsoft сейчас недоступен для доступа в частных каналах.<br/>
<sup>3</sup> частные каналы в настоящее время недоступны в облаках GCC. Дополнительные обновления сведений о доступности будут опубликованы в центре сообщений.<br/>
<sup>4</sup> Microsoft OneNote недоступно в облаках с DOD. В настоящее время приложения и публикация приложений недоступны в этих облаках.<br/>
<sup>5</sup> Live Events в настоящее время недоступно в GCC-High или с вызовом по требованию.<br/>

## <a name="next-steps"></a>Дальнейшие действия

Начните планировать развертывание Microsoft Teams, посетив [техническую документацию по Microsoft Teams](https://aka.ms/SuccessWithTeams). Оставайтесь в курсе функций и возможностей Teams, [присоединяясь к сообществу и посетив блог Microsoft Teams](https://aka.ms/TeamsBlog).