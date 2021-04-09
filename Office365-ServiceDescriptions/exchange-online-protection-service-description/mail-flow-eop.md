---
title: Поток почты в Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Ознакомьтесь с этой статьей, чтобы узнать о потоке почты в Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653141"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Поток почты в Exchange Online Protection

Для большинства организаций, которые используют Корпорацию Майкрософт, мы разобираем почтовые ящики и заботимся о потоке почты. Это простейшая конфигурация, которая означает, что Корпорация Майкрософт управляет всеми почтовыми ящиками и фильтрацией. Но для некоторых организаций требуется разместить почтовые ящики в локальной среде. Exchange Online Protection (EOP) позволяет вам это сделать и предоставляет обработку антивирусной и анти-нежелательной почты в облаке. Получить дополнительные сведения и приобрести EOP можно на сайте [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Поиск сведений об управлении доменом или блокировке на основе каталогов (DBEB)? См. [в этой ленте "Получатель", "Управление доменом" и "Управление компанией".](recipient-domain-and-company-management.md) Дополнительные возможности EOP см. в описании [службы exchange Online Protection.](exchange-online-protection-service-description.md)
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Маршрутивка электронной почты между Корпорацией Майкрософт и собственными серверами электронной почты

Можно настроить соединитель, чтобы включить поток почты между Microsoft (включая Exchange Online или EOP) и сервером электронной почты на основе SMTP, например Exchange. Дополнительные сведения см. И [настройка соединители для маршрутной почты между Microsoft и вашими собственными серверами электронной почты](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Как клиент EOP можно настроить безопасный поток почты с доверенным партнером с помощью соединители Microsoft. Корпорация Майкрософт поддерживает защищенную связь с помощью службы безопасности транспортных слоев (TLS), и вы можете создать соединитель для обеспечения шифрования с помощью TLS. [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) — это криптографический протокол, который обеспечивает безопасность для связи через Интернет. С помощью соединителов можно настроить как принудительно входящие, так и исходяющие TLS с помощью самозаверяемых или сертифицированных сертификатов. Вы также можете применять другие ограничения безопасности, такие как указание доменных имен или IP-адресов, из которых ваша организация-партнер отправляет почту. 
  
Дополнительные сведения см. в статье [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Добавление IP-адреса партнера в список надежных отправителей

Вы можете добавить IP-адрес доверенного партнера в список надежных отправителей, чтобы к его письмам не применялись фильтры нежелательной почты. Для этого можно использовать список разрешенных IP-адресов фильтра подключений. Дополнительные сведения см. в статье [Настройка политики фильтров подключений](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Условная маршрутизация почты

Можно настроить соединитель с правилом транспорта для маршрутизации почты к определенному сайту на основании условий. Дополнительные сведения см. в статье [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Маршрутизация гибридной почты

"Гибридная организация" означает, что вы размещаете часть своих почтовых ящиков локально, а часть  в облаке (Exchange Online). Можно перейти с изолированного (локального) развертывания на гибридное развертывание.
  
В случае гибридного развертывания облачные и локальные почтовые ящики можно защитить с помощью EOP. Для локальных почтовых ящиков, когда они защищены с помощью EOP, требуются отдельные лицензии. Дополнительные сведения о маршрутизации почты в гибридном развертывании см. в статье [Маршрутизация транспорта при гибридных развертываниях Exchange](/exchange/transport-routing).
  
[Помощник по развертыванию Microsoft Exchange Server](/exchange/exchange-deployment-assistant) также приводит подробную инструкцию по обеспечению гибридного развертывания и гибридного транспорта сообщений. 
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. в описании [службы Exchange Online Protection.](exchange-online-protection-service-description.md)