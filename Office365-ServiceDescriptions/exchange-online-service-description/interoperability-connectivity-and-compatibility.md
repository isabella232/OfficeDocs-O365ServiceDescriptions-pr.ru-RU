---
title: Взаимодействие, связь и совместимость
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 9e0ef704a1b43a81bffdd177aeef3f09c472103aa178c11867d1cc9db8b1aee2
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663782"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Взаимодействие, связь и совместимость

## <a name="interoperability-with-other-microsoft-products"></a>Совместимость с другими продуктами корпорации Майкрософт

### <a name="skype-for-business-online"></a>Skype для Бизнеса Онлайн

Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.
  
Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:
  
- Интероперабельность чата и присутствия в Outlook в Интернете
    
- Взаимодействие с голосовой почтой
    
Дополнительные сведения о настройке Skype для бизнеса Server 2015 для работы с Exchange Online см. в статье [Настройка интеграции между локальной системой Skype для бизнеса Server 2015 и Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). О гибридных конфигурациях можно узнать в статье [Поддерживаемые гибридные конфигурации Skype для бизнеса Server 2015](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Для клиентов, которые развернули Microsoft SharePoint Server или SharePoint Online в рамках плана подписки, SharePoint можно подключиться к Exchange Online для интегрированных служб.
  
Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Возможности внешнего подключения

Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:
  
- **Через протоколы обмена сообщениями, такие как MAPI через HTTP, SMTP, POP3, IMAP4 или веб-службы Exchange**. Внешние локальные приложения и приложения в Azure либо в других размещенных службах могут использовать данные в Exchange Online с помощью протоколов обмена сообщениями, таких как MAPI через HTTP, SMTP, POP3 и IMAPv4. Веб-службы Exchange или управляемый API веб-служб Exchange рекомендуется использовать для разработки приложений. 
    
- **Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. 
    
### <a name="exchange-web-services"></a>Веб-службы Exchange

Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online. С помощью EWS или управляемого API EWS администраторы могут получать доступ к данным, Exchange Online данным из приложений, работающих на локальной основе, в Azure или в других хостинг-службах. EWS позволяет администраторам выполнять специальные действия, такие как запрос содержимого почтового ящика, размещение события календаря, создание задачи или запуск определенного действия на основе содержимого сообщения электронной почты. Exchange Online ФУНКЦИОНАЛЬНОСТЬ EWS, выдав разрешения на приложения учетным записям клиентов. Эти разрешения позволяют приложению клиента получать доступ к почтовому ящику приложения и добавлять контент. Exchange Impersonation — это один из методов, используемых для предоставления разрешений приложения. Подробные сведения об использовании Exchange веб-Exchange Online с помощью Exchange Online обратитесь к техническим статьям центра Exchange Online разработчиков.
  
### <a name="smtp-relay"></a>Ретранслятор SMTP

Exchange Online можно использовать в качестве службы доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. Например, если бизнес-приложение отправляет оповещения пользователям по электронной почте, оно может быть настроено на использование Exchange Online как системы доставки почты. Приложение или служба должны пройти проверку подлинности по имени пользователя и паролю действительного лицензированного почтового ящика Exchange Online и подключиться с использованием протокола TLS.
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. Exchange Online [службы.](exchange-online-service-description.md)
