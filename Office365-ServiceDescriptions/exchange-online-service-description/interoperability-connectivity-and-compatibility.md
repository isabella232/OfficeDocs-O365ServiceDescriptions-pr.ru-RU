---
title: Взаимодействие, связь и совместимость
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132753"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Взаимодействие, связь и совместимость

## <a name="interoperability-with-other-microsoft-products"></a>Совместимость с другими продуктами корпорации Майкрософт

### <a name="skype-for-business-online"></a>Skype для бизнеса Online

Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.
  
Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:
  
- Взаимодействие с обменом мгновенными сообщениями и сведениями о присутствии в Outlook в Интернете
    
- Взаимодействие с голосовой почтой
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Для клиентов, которые развернули Microsoft SharePoint Server или SharePoint Online в составе плана подписки, SharePoint может подключиться к Exchange Online для интегрированных служб.
  
Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Возможности внешнего подключения

Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. 
    
### <a name="exchange-web-services"></a>Веб-службы Exchange

Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online. С помощью EWS или управляемого API EWS администраторы могут получать доступ к данным, хранящимся в Exchange Online, из приложений, работающих в локальной среде, в Azure или других размещенных служб. С помощью служб EWS администраторы могут выполнять специальные действия, такие как запрос содержимого почтового ящика, публикация события календаря, создание задачи или запуск определенных действий на основе содержимого сообщения электронной почты. Exchange Online включает функции EWS, предоставляя разрешения приложений для учетных записей клиентов. Эти разрешения позволяют приложению клиента получить доступ к почтовому ящику приложения и добавить контент. Олицетворение Exchange — это один метод, который используется для предоставления разрешений приложения. Для получения дополнительных сведений об использовании веб-служб Exchange в Exchange Online обратитесь к техническим статьям в центре разработчиков Exchange Online.
  
### <a name="smtp-relay"></a>Ретранслятор SMTP

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  

