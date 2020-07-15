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
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="c6bc8-102">Взаимодействие, связь и совместимость</span><span class="sxs-lookup"><span data-stu-id="c6bc8-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="c6bc8-103">Совместимость с другими продуктами корпорации Майкрософт</span><span class="sxs-lookup"><span data-stu-id="c6bc8-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="c6bc8-104">Skype для бизнеса Online</span><span class="sxs-lookup"><span data-stu-id="c6bc8-104">Skype for Business Online</span></span>

<span data-ttu-id="c6bc8-105">Для клиентов, у которых локально развернут Microsoft Lync Server 2010, Lync Server 2013 или Microsoft Office Communications Server 2007 R2, Microsoft Office Communicator обеспечивает подключение к Microsoft Exchange через Интернет с помощью веб-служб Exchange, чтобы получить доступ к сообщениям об отсутствии и данным календаря.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="c6bc8-106">Локальные Lync Server 2010 и Lync Server 2013 поддерживают взаимодействие с Exchange Online двумя дополнительными способами:</span><span class="sxs-lookup"><span data-stu-id="c6bc8-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="c6bc8-107">Взаимодействие с обменом мгновенными сообщениями и сведениями о присутствии в Outlook в Интернете</span><span class="sxs-lookup"><span data-stu-id="c6bc8-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="c6bc8-108">Взаимодействие с голосовой почтой</span><span class="sxs-lookup"><span data-stu-id="c6bc8-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="c6bc8-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span><span class="sxs-lookup"><span data-stu-id="c6bc8-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span></span> <span data-ttu-id="c6bc8-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="c6bc8-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="c6bc8-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="c6bc8-111">Microsoft SharePoint</span></span>

<span data-ttu-id="c6bc8-112">Для клиентов, которые развернули Microsoft SharePoint Server или SharePoint Online в составе плана подписки, SharePoint может подключиться к Exchange Online для интегрированных служб.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="c6bc8-113">Дополнительные сведения о подключении SharePoint к Exchange Online см. в статье [Использование SharePoint Online в личном домене вместе с другими службами](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="c6bc8-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="c6bc8-114">Возможности внешнего подключения</span><span class="sxs-lookup"><span data-stu-id="c6bc8-114">Features for external connectivity</span></span>

<span data-ttu-id="c6bc8-115">Exchange Online предоставляет следующие возможности по подключению внешних устройств и приложений:</span><span class="sxs-lookup"><span data-stu-id="c6bc8-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="c6bc8-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span></span> <span data-ttu-id="c6bc8-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="c6bc8-118">**Как ретранслятор SMTP**. Exchange Online можно настроить как службу доставки SMTP для ретрансляции сообщений электронной почты, отправляемых с факсовых шлюзов, сетевых устройств, а также пользовательских приложений.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="c6bc8-119">Веб-службы Exchange</span><span class="sxs-lookup"><span data-stu-id="c6bc8-119">Exchange Web Services</span></span>

<span data-ttu-id="c6bc8-120">Веб-службы Exchange являются предпочтительным API для разработки в Exchange Server и Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="c6bc8-121">С помощью EWS или управляемого API EWS администраторы могут получать доступ к данным, хранящимся в Exchange Online, из приложений, работающих в локальной среде, в Azure или других размещенных служб.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="c6bc8-122">С помощью служб EWS администраторы могут выполнять специальные действия, такие как запрос содержимого почтового ящика, публикация события календаря, создание задачи или запуск определенных действий на основе содержимого сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="c6bc8-123">Exchange Online включает функции EWS, предоставляя разрешения приложений для учетных записей клиентов.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="c6bc8-124">Эти разрешения позволяют приложению клиента получить доступ к почтовому ящику приложения и добавить контент.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="c6bc8-125">Олицетворение Exchange — это один метод, который используется для предоставления разрешений приложения.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="c6bc8-126">Для получения дополнительных сведений об использовании веб-служб Exchange в Exchange Online обратитесь к техническим статьям в центре разработчиков Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="c6bc8-127">Ретранслятор SMTP</span><span class="sxs-lookup"><span data-stu-id="c6bc8-127">SMTP relay</span></span>

<span data-ttu-id="c6bc8-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> <span data-ttu-id="c6bc8-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span><span class="sxs-lookup"><span data-stu-id="c6bc8-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span></span> <span data-ttu-id="c6bc8-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="c6bc8-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="c6bc8-131">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="c6bc8-131">Feature availability</span></span>

<span data-ttu-id="c6bc8-132">Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="c6bc8-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

