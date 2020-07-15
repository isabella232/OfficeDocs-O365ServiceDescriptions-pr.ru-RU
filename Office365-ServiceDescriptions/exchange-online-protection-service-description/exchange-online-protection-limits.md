---
title: Ограничения Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: В настоящее время существуют следующие ограничения для Exchange Online Protection. Эти пределы нельзя настраивать, если не указано иное.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133013"
---
# <a name="exchange-online-protection-limits"></a>Ограничения Exchange Online Protection

В настоящее время существуют следующие ограничения для Exchange Online Protection. Эти пределы нельзя настраивать, если не указано иное. 
  
> [!TIP]
> Дополнительные сведения об ограничении в Exchange Online приведены в статье [Exchange Online Limits](../exchange-online-service-description/exchange-online-limits.md). Ограничения правил транспорта также применимы в случае пользователей отдельных выпусков EOP. Частота получателей и пределы скорости сообщений для Exchange Online неприменимы для отдельных клиентов EOP. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Ограничение на размер сообщения** Максимальный размер сообщения для пользователей отдельного выпуска EOP, включая вложения, составляет 150 МБ. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Ограничение на списки разрешенных или заблокированных IP-адресов** При настройке списков разрешенных или заблокированных IP-адресов в фильтре соединений можно указать максимум 1273 записи, где запись может быть одним IP-адресом или диапазоном CIDR, включающим от 24 до 32 IP-адресов. 
    
- **Лимит расхода для сообщений** Сообщения в РБП останутся в очередях в течение 24 часов. Попытки повторной отправки сообщений зависят от типа ошибки, полученной от почтовой системы получателя. Повторные попытки выполняются каждые 15 минут. 
    
- **Период хранения для карантина нежелательной почты** По умолчанию сообщения, отправляемые на карантин, хранятся в течение 30 дней. Администраторы снизить это значение с помощью политик фильтрации содержимого. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Пределы отслеживания отчетов и сообщений** Сведения об ограничении отчетов и трассировке сообщений можно найти в разделе "отчеты и сведения об отслеживании сообщений и задержка" в [отчетах и трассировке сообщений в Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Ограничения на параметры EOP

|**Функция**|****Отдельный выпуск EOP****|****Функции EOP в Exchange Online****|****Клиентская лицензия Exchange Enterprise CAL со службами****|
|:-----|:-----|:-----|:-----|
|Ограничения домена  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Ограничение на размер сообщений (учитывая вложения)  <br/> |150 МБ  <br/> |150 МБ  <br/> |150 МБ  <br/> |
|Ограничение числа получателей  <br/> |См. раздел "Максимальное число получателей" выше  <br/> |500 получателей при отправке с размещенного почтового ящика. Другие сценарии см. в разделе "Максимальное число получателей" выше  <br/> |См. раздел "Максимальное число получателей" выше  <br/> |
|Максимальное количество надежных отправителей  <br/> |1024 записи  <br/> |1024 записи  <br/> ||
|Предельное количество заблокированных отправителей для каждой политики  <br/> |1024 записи  <br/> |1024 записи  <br/> ||
|Ограничение на списки разрешенных или заблокированных IP-адресов  <br/> |1273 записи  <br/> |1273 записи  <br/> |1273 записи  <br/> |
|Ограничение на отложенные сообщения  <br/> |1 день, повторная попытка каждые 15 минут  <br/> |1 день, повторная попытка каждые 15 минут  <br/> |1 день, повторная попытка каждые 15 минут  <br/> |
|Период хранения нежелательных сообщений, отправленных в карантин  <br/> |30 дней по умолчанию, но их можно опустить  <br/> |30 дней по умолчанию, но их можно опустить  <br/> |30 дней по умолчанию, но их можно опустить  <br/> |
|Уведомления пользователей о нежелательных сообщениях, помещенных в карантин  <br/> |3 дня по умолчанию, можно указать от 1 до 15 дней  <br/> |3 дня по умолчанию, можно указать от 1 до 15 дней  <br/> |3 дня по умолчанию, можно указать от 1 до 15 дней  <br/> |
   

