---
title: Взаимодействие, связь и совместимость
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 55cb63c948d6e5f98cea64f98d0ca9d3d8fcdc21
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244885"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Взаимодействие, связь и совместимость

## <a name="interoperability-with-other-microsoft-products"></a>Совместимость с другими продуктами корпорации Майкрософт

### <a name="skype-for-business-online"></a>Skype для бизнеса Online

Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.
  
Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:
  
- Обмен мгновенными сообщениями и взаимодействие с данными о присутствии в Outlook Web App
    
- Взаимодействие с голосовой почтой
    
Дополнительные сведения о настройке Skype для бизнеса Server 2015 для работы с Exchange Online см. в статье [Настройка интеграции между локальной системой Skype для бизнеса Server 2015 и Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). О гибридных конфигурациях можно узнать в статье [Поддерживаемые гибридные конфигурации Skype для бизнеса Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Для клиентов, у которых развернут сервер Microsoft SharePoint Server или SharePoint Online в составе плана подписки Office 365, SharePoint может подключаться к Exchange Online для интеграции служб.
  
Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Возможности внешнего подключения

Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:
  
- **Через протоколы обмена сообщениями, такие как MAPI через HTTP, SMTP, POP3, IMAP4 или веб-службы Exchange**. Внешние локальные приложения и приложения в Azure либо в других размещенных службах могут использовать данные в Exchange Online с помощью протоколов обмена сообщениями, таких как MAPI через HTTP, SMTP, POP3 и IMAPv4. Веб-службы Exchange или управляемый API веб-служб Exchange рекомендуется использовать для разработки приложений. 
    
- **Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. 
    
### <a name="exchange-web-services"></a>веб-службы Exchange

Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online. С использованием EWS или управляемого API веб-служб Exchange администраторы могут получить доступ к информации, хранящейся в Exchange через Интернет, из приложений, работающих локально, в Azure либо в других облачных службах. EWS позволяет администраторам выполнять специальные действия, например запрос содержимого почтового ящика, регистрация события календаря, создание задачи или вызов определенного действия на основе содержимого сообщения электронной почты. Exchange Online реализует функции EWS, предоставляя разрешения приложений учетным записям пользователей. Эти разрешения позволяют пользовательским приложениям использовать почтовый ящик приложения и добавлять контент. Олицетворение Exchange является одним из методов, используемых для предоставления разрешений приложения. Подробности использования веб-служб Exchange в Exchange Online см. в технических статьях в Центре разработки Exchange Online.
  
### <a name="smtp-relay"></a>Ретранслятор SMTP

Exchange Online можно использовать в качестве службы доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. Например, если бизнес-приложение отправляет оповещения пользователям по электронной почте, оно может быть настроено на использование Exchange Online как системы доставки почты. Приложение или служба должны пройти проверку подлинности по имени пользователя и паролю действительного лицензированного почтового ящика Exchange Online и подключиться с использованием протокола TLS.
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online](exchange-online-service-description.md).
  

