---
title: Взаимодействие, связь и совместимость
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 80d4248da8fd9d3600789df35085c24e6e436433
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342688"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="c92e7-102">Взаимодействие, связь и совместимость</span><span class="sxs-lookup"><span data-stu-id="c92e7-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="c92e7-103">Совместимость с другими продуктами корпорации Майкрософт</span><span class="sxs-lookup"><span data-stu-id="c92e7-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="c92e7-104">Skype для бизнеса Online</span><span class="sxs-lookup"><span data-stu-id="c92e7-104">Skype for Business Online</span></span>

<span data-ttu-id="c92e7-105">Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.</span><span class="sxs-lookup"><span data-stu-id="c92e7-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="c92e7-106">Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:</span><span class="sxs-lookup"><span data-stu-id="c92e7-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="c92e7-107">Обмен мгновенными сообщениями и взаимодействие с данными о присутствии в Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="c92e7-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="c92e7-108">Взаимодействие с голосовой почтой</span><span class="sxs-lookup"><span data-stu-id="c92e7-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="c92e7-p101">Дополнительные сведения о настройке Skype для бизнеса Server 2015 для работы с Exchange Online см. в статье [Настройка интеграции между локальной системой Skype для бизнеса Server 2015 и Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). О гибридных конфигурациях можно узнать в статье [Поддерживаемые гибридные конфигурации Skype для бизнеса Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="c92e7-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="c92e7-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="c92e7-111">Microsoft SharePoint</span></span>

<span data-ttu-id="c92e7-112">Для клиентов, у которых развернут сервер Microsoft SharePoint Server или SharePoint Online в составе плана подписки Office 365, SharePoint может подключаться к Exchange Online для интеграции служб.</span><span class="sxs-lookup"><span data-stu-id="c92e7-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="c92e7-113">Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="c92e7-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="c92e7-114">Возможности внешнего подключения</span><span class="sxs-lookup"><span data-stu-id="c92e7-114">Features for external connectivity</span></span>

<span data-ttu-id="c92e7-115">Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:</span><span class="sxs-lookup"><span data-stu-id="c92e7-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="c92e7-p102">**Через протоколы обмена сообщениями, такие как MAPI через HTTP, SMTP, POP3, IMAP4 или веб-службы Exchange**. Внешние локальные приложения и приложения в Azure либо в других размещенных службах могут использовать данные в Exchange Online с помощью протоколов обмена сообщениями, таких как MAPI через HTTP, SMTP, POP3 и IMAPv4. Веб-службы Exchange или управляемый API веб-служб Exchange рекомендуется использовать для разработки приложений.</span><span class="sxs-lookup"><span data-stu-id="c92e7-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="c92e7-118">**Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений.</span><span class="sxs-lookup"><span data-stu-id="c92e7-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="c92e7-119">веб-службы Exchange</span><span class="sxs-lookup"><span data-stu-id="c92e7-119">Exchange Web Services</span></span>

<span data-ttu-id="c92e7-p103">Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online. С использованием EWS или управляемого API веб-служб Exchange администраторы могут получить доступ к информации, хранящейся в Exchange через Интернет, из приложений, работающих локально, в Azure либо в других облачных службах. EWS позволяет администраторам выполнять специальные действия, например запрос содержимого почтового ящика, регистрация события календаря, создание задачи или вызов определенного действия на основе содержимого сообщения электронной почты. Exchange Online реализует функции EWS, предоставляя разрешения приложений учетным записям пользователей. Эти разрешения позволяют пользовательским приложениям использовать почтовый ящик приложения и добавлять контент. Олицетворение Exchange является одним из методов, используемых для предоставления разрешений приложения. Подробности использования веб-служб Exchange в Exchange Online см. в технических статьях в Центре разработки Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c92e7-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="c92e7-127">Ретранслятор SMTP</span><span class="sxs-lookup"><span data-stu-id="c92e7-127">SMTP relay</span></span>

<span data-ttu-id="c92e7-p104">Exchange Online можно использовать в качестве службы доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений. Например, если бизнес-приложение отправляет оповещения пользователям по электронной почте, оно может быть настроено на использование Exchange Online как системы доставки почты. Приложение или служба должны пройти проверку подлинности по имени пользователя и паролю действительного лицензированного почтового ящика Exchange Online и подключиться с использованием протокола TLS.</span><span class="sxs-lookup"><span data-stu-id="c92e7-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="c92e7-131">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="c92e7-131">Feature Availability</span></span>

<span data-ttu-id="c92e7-132">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="c92e7-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

