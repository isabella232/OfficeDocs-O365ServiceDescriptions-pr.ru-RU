---
title: Поток почты[EOP]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Для большинства организаций, использующих Office 365 мы узла ваши почтовые ящики и взяла на себя поток почты. Он является простым конфигурации и означает, что Office 365 управляет всех почтовых ящиков и фильтрации. Тем не менее в некоторых организациях действуют необходима для хранения своих почтовых ящиков на локальном. Exchange Online Protection (EOP) позволяет выполнять и обеспечивает защиту от вирусов и нежелательной почты, обработки в облаке. Для получения дополнительных сведений и покупки EOP перейдите к Exchange Online Protection.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036711"
---
# <a name="mail-floweop"></a>Поток почты[EOP]

Для большинства организаций, использующих Office 365 мы узла ваши почтовые ящики и взяла на себя поток почты. Он является простым конфигурации и означает, что Office 365 управляет всех почтовых ящиков и фильтрации. Тем не менее в некоторых организациях действуют необходима для хранения своих почтовых ящиков на локальном. Exchange Online Protection (EOP) позволяет выполнять и обеспечивает защиту от вирусов и нежелательной почты, обработки в облаке. Для получения дополнительных сведений и покупки EOP перейдите к [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Ищете сведения об управлении доменами или пограничной блокировке на базе каталога (DBEB)? См. статью [Управление получателями, доменами и компаниями](recipient-domain-and-company-management.md). Дополнительные сведения о функциях EOP см. в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Маршрутизация сообщений между Office 365 и почтовыми серверами пользователя
<a name="BKMK_outboundmailrouting"> </a>

Вы можете настроить соединитель, чтобы обеспечить поток обработки почты между Office 365 (включая Exchange Online или EOP) и почтовым сервером, использующим SMTP, таким как сервер Exchange. Дополнительные сведения см. в статьях [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx) и [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Защищенный обмен сообщениями с доверенным партнером
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

Пользователь EOP может настроить защищенный поток обработки почты, получаемой и отправляемой доверенным партнером, с помощью соединителей Office 365. Office 365 поддерживает протокол TLS. Вы можете создать соединитель, чтобы обеспечить шифрование согласно этому протоколу. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx)  это криптографический протокол, обеспечивающий защищенный обмен данными через Интернет. С помощью соединителей можно настроить принудительное использование протокола TLS для входящих и исходящих сообщений с применением самозаверяющего сертификата или сертификата, проверенного центром сертификации. Кроме того, можно задать другие ограничения в целях безопасности, такие как указание доменных имен или диапазонов IP-адресов, которые использует партнерская организация для отправки почты. 
  
Дополнительные сведения см. в статье [Настройка соединителей для защиты потока обработки почты с партнерской организацией](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).
  
## <a name="safe-listing-a-partners-ip-address"></a>Добавление IP-адреса партнера в список надежных отправителей
<a name="BKMK_safelistingapartnersipaddress"> </a>

Вы можете добавить IP-адрес доверенного партнера в список надежных отправителей, чтобы к его письмам не применялись фильтры нежелательной почты. Для этого можно использовать список разрешенных IP-адресов фильтра подключений. Дополнительные сведения см. в статье [Настройка политики фильтров подключений](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Условная маршрутизация почты
<a name="BKMK_conditionalmailrouting"> </a>

Можно настроить соединитель с правилом транспорта для маршрутизации почты к определенному сайту на основании условий. Дополнительные сведения см. в статье [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Маршрутизация гибридной почты
<a name="BKMK_hybridmailrouting"> </a>

"Гибридная организация" означает, что вы размещаете часть своих почтовых ящиков локально, а часть  в облаке (Exchange Online). Можно перейти с изолированного (локального) развертывания на гибридное развертывание.
  
В случае гибридного развертывания облачные и локальные почтовые ящики можно защитить с помощью EOP. Для локальных почтовых ящиков, когда они защищены с помощью EOP, требуются отдельные лицензии. Дополнительные сведения о маршрутизации почты в гибридном развертывании см. в статье [Маршрутизация транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
[Помощник по развертыванию Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) также приводит подробную инструкцию по обеспечению гибридного развертывания и гибридного транспорта сообщений. 
  
## <a name="feature-availability"></a>Доступность функций
<a name="BKMK_hybridmailrouting"> </a>

Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).
  

