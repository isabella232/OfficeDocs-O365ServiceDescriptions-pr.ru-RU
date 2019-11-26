---
title: Взаимодействие, связь и совместимость
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 2da88139da1d779c5fb72d3b8fe72a077c1f9e16
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262662"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Взаимодействие, связь и совместимость

## <a name="interoperability-with-other-microsoft-products"></a>Совместимость с другими продуктами корпорации Майкрософт

### <a name="skype-for-business-online"></a>Skype для бизнеса Online

Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.
  
Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:
  
- Взаимодействие с обменом мгновенными сообщениями и сведениями о присутствии в Outlook в Интернете
    
- Взаимодействие с голосовой почтой
    
Дополнительные сведения о настройке Skype для бизнеса Server 2015 для работы с Exchange Online см. в статье [Настройка интеграции между локальной системой Skype для бизнеса Server 2015 и Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). О гибридных конфигурациях можно узнать в статье [Поддерживаемые гибридные конфигурации Skype для бизнеса Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Для клиентов, у которых развернут сервер Microsoft SharePoint Server или SharePoint Online в составе плана подписки Office 365, SharePoint может подключаться к Exchange Online для интеграции служб.
  
Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Возможности внешнего подключения

Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:
  
- **Через протоколы обмена сообщениями, такие как MAPI через HTTP, SMTP, POP3, IMAP4 или веб-службы Exchange**. Внешние локальные приложения и приложения в Azure либо в других размещенных службах могут использовать данные в Exchange Online с помощью протоколов обмена сообщениями, таких как MAPI через HTTP, SMTP, POP3 и IMAPv4. Веб-службы Exchange или управляемый API веб-служб Exchange рекомендуется использовать для разработки приложений. 
    
- **Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. 
    
### <a name="exchange-web-services"></a>Веб-службы Exchange

Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online. С помощью EWS или управляемого API EWS администраторы могут получать доступ к данным, хранящимся в Exchange Online, из приложений, работающих в локальной среде, в Azure или других размещенных служб. С помощью служб EWS администраторы могут выполнять специальные действия, такие как запрос содержимого почтового ящика, публикация события календаря, создание задачи или запуск определенных действий на основе содержимого сообщения электронной почты. Exchange Online включает функции EWS, предоставляя разрешения приложений для учетных записей клиентов. Эти разрешения позволяют приложению клиента получить доступ к почтовому ящику приложения и добавить контент. Олицетворение Exchange — это один метод, который используется для предоставления разрешений приложения. Для получения дополнительных сведений об использовании веб-служб Exchange в Exchange Online обратитесь к техническим статьям в центре разработчиков Exchange Online.
  
### <a name="smtp-relay"></a>Ретранслятор SMTP

Exchange Online можно использовать в качестве службы доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. Например, если бизнес-приложение отправляет оповещения пользователям по электронной почте, оно может быть настроено на использование Exchange Online как системы доставки почты. Приложение или служба должны пройти проверку подлинности по имени пользователя и паролю действительного лицензированного почтового ящика Exchange Online и подключиться с использованием протокола TLS.
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах Office 365, отдельных и локальных решениях, ознакомьтесь с [описанием службы Exchange Online](exchange-online-service-description.md).
  

