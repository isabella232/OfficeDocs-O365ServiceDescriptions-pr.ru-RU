---
title: Почтовый потоки в Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: В этой статье рассказывается о движении почты в Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: c6b885abe6522c3f8d1b780c8c64c621c34011c2
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293675"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Почтовый потоки в Exchange Online Protection

Для большинства организаций, использующих Майкрософт, мы размещаем почтовые ящики и позаботитесь о движении почты. Это самая простая конфигурация, которая позволяет Майкрософт управлять всеми почтовыми ящиками и фильтрацией. Но для некоторых организаций требуется разместить почтовые ящики в локальной среде. Exchange Online Protection (EOP) позволяет сделать это и обеспечивает обработку антивирусных и нежелательной почты в облаке. Получить дополнительные сведения и приобрести EOP можно на сайте [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Ищете сведения об управлении доменом или пограничной блокировке на основе каталогов (DBEB)? Просмотр [получателей, доменов и управления организациями](recipient-domain-and-company-management.md). Чтобы узнать больше о всех возможностях EOP, ознакомьтесь с [описанием службы Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Маршрутизация электронной почты между корпорацией Майкрософт и вашими почтовыми серверами

Вы можете настроить соединитель для включения направления почты между корпорацией Майкрософт (включая Exchange Online или EOP) и SMTP-сервером электронной почты, например Exchange. Дополнительные сведения см. И [Настройте соединители для маршрутизации почты между корпорацией Майкрософт и вашими почтовыми серверами](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Как клиент EOP, вы можете настроить безопасный почтовый ящик с доверенным партнером с помощью соединителей Майкрософт. Корпорация Майкрософт поддерживает безопасное соединение через протокол TLS и позволяет создать соединитель для применения шифрования через TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) — это протокол шифрования, обеспечивающий безопасность связи через Интернет. С помощью соединителей можно настроить как принудительный входящий и исходящий TLS, используя сертификаты с собственной подписью или сертифицированным центром сертификации (CA). Кроме того, можно применить другие ограничения безопасности, такие как указание доменных имен или диапазонов IP-адресов, от которых Партнерская организация отправляет почту. 
  
Дополнительные сведения см. в статье [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Добавление IP-адреса партнера в список надежных отправителей

Вы можете добавить IP-адрес доверенного партнера в список надежных отправителей, чтобы к его письмам не применялись фильтры нежелательной почты. Для этого можно использовать список разрешенных IP-адресов фильтра подключений. Дополнительные сведения см. в статье [Настройка политики фильтров подключений](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Условная маршрутизация почты

Можно настроить соединитель с правилом транспорта для маршрутизации почты к определенному сайту на основании условий. Дополнительные сведения см. в статье [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Маршрутизация гибридной почты

"Гибридная организация" означает, что вы размещаете часть своих почтовых ящиков локально, а часть  в облаке (Exchange Online). Можно перейти с изолированного (локального) развертывания на гибридное развертывание.
  
В случае гибридного развертывания облачные и локальные почтовые ящики можно защитить с помощью EOP. Для локальных почтовых ящиков, когда они защищены с помощью EOP, требуются отдельные лицензии. Дополнительные сведения о маршрутизации почты в гибридном развертывании см. в статье [Маршрутизация транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
[Помощник по развертыванию Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) также приводит подробную инструкцию по обеспечению гибридного развертывания и гибридного транспорта сообщений. 
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, отдельных параметрах и локальных решениях, ознакомьтесь с [описанием службы Exchange Online Protection](exchange-online-protection-service-description.md).
