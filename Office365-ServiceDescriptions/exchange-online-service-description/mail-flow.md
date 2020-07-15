---
title: Поток обработки почты
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Для большинства организаций мы разместите свои почтовые ящики и позаботитесь о движении почты. Это самая простая конфигурация, которая позволяет Майкрософт управлять всеми почтовыми ящиками и фильтрацией. Но некоторым организациям нужны более сложные схемы доставки почты для соответствия определенным нормативным и корпоративным требованиям. Такие варианты конфигурации описаны в этой статье.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132723"
---
# <a name="mail-flow"></a>Поток обработки почты

Для большинства организаций мы разместите свои почтовые ящики и позаботитесь о движении почты. Это самая простая конфигурация, которая позволяет Майкрософт управлять всеми почтовыми ящиками и фильтрацией. Но некоторым организациям нужны более сложные схемы доставки почты для соответствия определенным нормативным и корпоративным требованиям. Такие варианты конфигурации описаны в этой статье. 
  
## <a name="custom-routing-of-outbound-email"></a>Пользовательская маршрутизация исходящих сообщений электронной почты

Microsoft Exchange Online может маршрутизировать почту, исходящую из вашей организации, через локальный сервер или размещенную службу (иногда называется "промежуточным узлом"). Это позволяет Организации использовать устройства защиты от потери данных, выполнять пользовательскую пост-обработку исходящей электронной почты и доставлять электронную почту бизнес-партнерам через частные сети. Exchange Online также поддерживает переопределение адресов, при котором исходящая электронная почта маршрутизируется через локальный шлюз, который изменяет адреса. Эта функция позволяет скрывать дочерние домены, делать сообщения электронной почты из нескольких доменов в виде одного домена или сделать сообщение, ретранслируемое партнером, таким, как если бы оно было отправлено из вашей организации. Администраторы настраивают специальную маршрутизацию в Центре администрирования Exchange (EAC).
  
Дополнительные сведения см. [в разделе Настройка соединителей для маршрутизации почты между корпорацией Майкрософт и своими почтовыми серверами](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online может обеспечивать доставку входящей и исходящей почты для вашей организации. Если ваш домен получателя размещен в Exchange Online с записями MX DNS, указывающими на Exchange Online Protection, почтовые потоки из клиента для получателя не будут перемещаться по Интернету.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

В качестве клиента Exchange Online можно настроить безопасный почтовый ящик с доверенным партнером с помощью соединителей Майкрософт. Корпорация Майкрософт поддерживает безопасное соединение через протокол TLS и позволяет создать соединитель для применения шифрования через TLS. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) — это протокол шифрования, обеспечивающий безопасность связи через Интернет. С помощью соединителей можно настроить как принудительный входящий и исходящий TLS, используя сертификаты с собственной подписью или сертифицированным центром сертификации (CA). Кроме того, можно применить другие ограничения безопасности, такие как указание доменных имен или диапазонов IP-адресов, от которых Партнерская организация отправляет почту. 
  
Дополнительные сведения см. в статье [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Может потребоваться сертификат, проверенный центром сертификации. 
  
## <a name="conditional-mail-routing"></a>Условная маршрутизация почты

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
Дополнительные сведения см. в статье [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Список надежных отправителей входящей почты

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
Дополнительные сведения см. в статье [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Маршрутизация почты в гибридной конфигурации

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
Дополнительные сведения о маршрутизации почты в гибридном развертывании приведены в статье [Маршрутизация транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
[Помощник по развертыванию Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) также приводит подробную инструкцию по обеспечению гибридного развертывания и гибридного транспорта сообщений. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Общее адресное пространство с локальным управлением маршрутизацией (запись MX указывает на локальную организацию)

Общее адресное пространство с локальным управлением маршрутизацией (MX указывает на локальную систему) — это сценарий для маршрутизации почты в гибридном развертывании, в котором почтовые ящики размещаются частично в Exchange Online и в локальной среде, а входящий и исходящий входящий и исходящий потоки Интернета направляются через локальную организацию Exchange. Этот сценарий также называется централизованным почтовым транспортом. В этом сценарии Exchange Online подготавливается к работе с EOP, а входящая почта Интернета направляется на локальный почтовый сервер, прежде чем направлять их в EOP, а затем в почтовые ящики, размещенные в Exchange Online. Кроме того, исходящая почта, отправленная внешним получателям из почтовых ящиков Exchange Online, маршрутизируется через локальную организацию Exchange. При такой конфигурации можно использовать одно пространство имен домена SMTP для всех почтовых ящиков в локальной организации Exchange и организации Exchange Online. 
  
Дополнительные сведения о транспорте в гибридном развертывании см. в статье [Параметры транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Общее адресное пространство без локального управления маршрутизацией (запись MX указывает на EOP)

Общее адресное пространство без локального управления маршрутизацией (запись MX указывает на EOP) представляет собой сценарий маршрутизации почты в гибридном развертывании, согласно которому одна часть почтовых ящиков размещается в Exchange Online, другая  в локальной организации, а запись MX указывает на Exchange Online Protection (EOP). Этот сценарий подходит, если вы используете Майкрософт для размещения некоторых почтовых ящиков вашей организации и хотите, чтобы EOP защищать как локальные, так и облачные почтовые ящики. В этом сценарии почта, отправленная внутренним получателям, сначала проходит через EOP, где происходит фильтрация нежелательной почты и применяются соответствующие политики, а затем попадает в локальные и облачные почтовые ящики. 
  
Дополнительные сведения о транспорте в гибридном развертывании см. в статье [Параметры транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Устранение неполадок развертывания с помощью мастера гибридной конфигурации

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
Дополнительные сведения об устранении неполадок развертывания с помощью мастера гибридной конфигурации см. в статье [Устранение неполадок в гибридном развертывании](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Управление гибридной конфигурацией

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
Дополнительные сведения об управлении конфигурацией гибридного развертывания см. в статье [Управление гибридным развертыванием](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Требования к гибридному развертыванию

Дополнительные сведения о требованиях для гибридного развертывания см. в статье [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> В некоторых гибридных конфигурациях, возможно, потребуется приобрести лицензии Exchange Online Protection для локальных почтовых ящиков. 
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, отдельных параметрах и локальных решениях, ознакомьтесь с [описанием службы Exchange Online](exchange-online-service-description.md).
  