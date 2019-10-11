---
title: Поток почты[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Для большинства организаций, в которых используется Office 365, мы размещаем почтовые ящики на своих серверах и обслуживаем поток обработки почты. Такая конфигурация самая простая, согласно ей Office 365 управляет всеми почтовыми ящиками и фильтрацией. Но для некоторых организаций требуется разместить почтовые ящики в локальной среде. Exchange Online Protection (EOP) позволяет это сделать и обеспечивает обработку почты, предназначенную для защиты от вирусов и нежелательной почты, в облаке. Получить дополнительные сведения и приобрести EOP можно на сайте Exchange Online Protection.
ms.openlocfilehash: 5a581c8004bcdc001160a2499cd623c6eee772f2
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442734"
---
# <a name="mail-floweop"></a>Поток почты[EOP]

Для большинства организаций, в которых используется Office 365, мы размещаем почтовые ящики на своих серверах и обслуживаем поток обработки почты. Такая конфигурация самая простая, согласно ей Office 365 управляет всеми почтовыми ящиками и фильтрацией. Но для некоторых организаций требуется разместить почтовые ящики в локальной среде. Exchange Online Protection (EOP) позволяет это сделать и обеспечивает обработку почты, предназначенную для защиты от вирусов и нежелательной почты, в облаке. Получить дополнительные сведения и приобрести EOP можно на сайте [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Ищете сведения об управлении доменами или пограничной блокировке на базе каталога (DBEB)? См. статью [Управление получателями, доменами и компаниями](recipient-domain-and-company-management.md). Дополнительные сведения о функциях EOP см. в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Маршрутизация сообщений между Office 365 и почтовыми серверами пользователя

Вы можете настроить соединитель, чтобы обеспечить поток обработки почты между Office 365 (включая Exchange Online или EOP) и почтовым сервером, использующим SMTP, таким как сервер Exchange. Дополнительные сведения см. в статьях [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector) и [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Защищенный обмен сообщениями с доверенным партнером

Как клиент EOP, вы можете настроить безопасный процесс обработки почты с помощью доверенного партнера с помощью соединителей Office 365. Office 365 поддерживает безопасное соединение через протокол TLS и позволяет создать соединитель для применения шифрования через TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) — это протокол шифрования, обеспечивающий безопасность связи через Интернет. С помощью соединителей можно настроить как принудительный входящий и исходящий TLS, используя сертификаты с собственной подписью или сертифицированным центром сертификации (CA). Кроме того, можно применить другие ограничения безопасности, такие как указание доменных имен или диапазонов IP-адресов, от которых Партнерская организация отправляет почту. 
  
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

Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).
