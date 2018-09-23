---
title: Поток почты[EOP]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Для большинства организаций, использующих Office 365 мы узла ваши почтовые ящики и взяла на себя поток почты. Он является простым конфигурации и означает, что Office 365 управляет всех почтовых ящиков и фильтрации. Тем не менее в некоторых организациях действуют необходима для хранения своих почтовых ящиков на локальном. Exchange Online Protection (EOP) позволяет выполнять и обеспечивает защиту от вирусов и нежелательной почты, обработки в облаке. Для получения дополнительных сведений и покупки EOP перейдите к Exchange Online Protection.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036711"
---
# <a name="mail-floweop"></a><span data-ttu-id="581a0-107">Поток почты[EOP]</span><span class="sxs-lookup"><span data-stu-id="581a0-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="581a0-p102">Для большинства организаций, использующих Office 365 мы узла ваши почтовые ящики и взяла на себя поток почты. Он является простым конфигурации и означает, что Office 365 управляет всех почтовых ящиков и фильтрации. Тем не менее в некоторых организациях действуют необходима для хранения своих почтовых ящиков на локальном. Exchange Online Protection (EOP) позволяет выполнять и обеспечивает защиту от вирусов и нежелательной почты, обработки в облаке. Для получения дополнительных сведений и покупки EOP перейдите к [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span><span class="sxs-lookup"><span data-stu-id="581a0-p102">For most organizations that use Office 365, we host your mailboxes and take care of mail flow. It's the simplest configuration and means that Office 365 manages all mailboxes and filtering. However, some organizations have a business need to keep all their mailboxes on premises. Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud. For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="581a0-p103">Ищете сведения об управлении доменами или пограничной блокировке на базе каталога (DBEB)? См. статью [Управление получателями, доменами и компаниями](recipient-domain-and-company-management.md). Дополнительные сведения о функциях EOP см. в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="581a0-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="581a0-116">Маршрутизация сообщений между Office 365 и почтовыми серверами пользователя</span><span class="sxs-lookup"><span data-stu-id="581a0-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="581a0-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-117"><a name="BKMK_outboundmailrouting"> </a></span></span>

<span data-ttu-id="581a0-p104">Вы можете настроить соединитель, чтобы обеспечить поток обработки почты между Office 365 (включая Exchange Online или EOP) и почтовым сервером, использующим SMTP, таким как сервер Exchange. Дополнительные сведения см. в статьях [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx) и [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span><span class="sxs-lookup"><span data-stu-id="581a0-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="581a0-121">Защищенный обмен сообщениями с доверенным партнером</span><span class="sxs-lookup"><span data-stu-id="581a0-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="581a0-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-122"></span></span>

<span data-ttu-id="581a0-p105">Пользователь EOP может настроить защищенный поток обработки почты, получаемой и отправляемой доверенным партнером, с помощью соединителей Office 365. Office 365 поддерживает протокол TLS. Вы можете создать соединитель, чтобы обеспечить шифрование согласно этому протоколу. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx)  это криптографический протокол, обеспечивающий защищенный обмен данными через Интернет. С помощью соединителей можно настроить принудительное использование протокола TLS для входящих и исходящих сообщений с применением самозаверяющего сертификата или сертификата, проверенного центром сертификации. Кроме того, можно задать другие ограничения в целях безопасности, такие как указание доменных имен или диапазонов IP-адресов, которые использует партнерская организация для отправки почты.</span><span class="sxs-lookup"><span data-stu-id="581a0-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="581a0-128">Дополнительные сведения см. в статье [Настройка соединителей для защиты потока обработки почты с партнерской организацией](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="581a0-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="581a0-129">Добавление IP-адреса партнера в список надежных отправителей</span><span class="sxs-lookup"><span data-stu-id="581a0-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="581a0-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span></span>

<span data-ttu-id="581a0-p106">Вы можете добавить IP-адрес доверенного партнера в список надежных отправителей, чтобы к его письмам не применялись фильтры нежелательной почты. Для этого можно использовать список разрешенных IP-адресов фильтра подключений. Дополнительные сведения см. в статье [Настройка политики фильтров подключений](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span><span class="sxs-lookup"><span data-stu-id="581a0-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="581a0-134">Условная маршрутизация почты</span><span class="sxs-lookup"><span data-stu-id="581a0-134">Conditional mail routing</span></span>
<span data-ttu-id="581a0-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-135"></span></span>

<span data-ttu-id="581a0-p107">Можно настроить соединитель с правилом транспорта для маршрутизации почты к определенному сайту на основании условий. Дополнительные сведения см. в статье [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span><span class="sxs-lookup"><span data-stu-id="581a0-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="581a0-138">Маршрутизация гибридной почты</span><span class="sxs-lookup"><span data-stu-id="581a0-138">Hybrid mail routing</span></span>
<span data-ttu-id="581a0-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-139"></span></span>

<span data-ttu-id="581a0-p108">"Гибридная организация" означает, что вы размещаете часть своих почтовых ящиков локально, а часть  в облаке (Exchange Online). Можно перейти с изолированного (локального) развертывания на гибридное развертывание.</span><span class="sxs-lookup"><span data-stu-id="581a0-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="581a0-p109">В случае гибридного развертывания облачные и локальные почтовые ящики можно защитить с помощью EOP. Для локальных почтовых ящиков, когда они защищены с помощью EOP, требуются отдельные лицензии. Дополнительные сведения о маршрутизации почты в гибридном развертывании см. в статье [Маршрутизация транспорта при гибридных развертываниях Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span><span class="sxs-lookup"><span data-stu-id="581a0-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="581a0-145">[Помощник по развертыванию Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) также приводит подробную инструкцию по обеспечению гибридного развертывания и гибридного транспорта сообщений.</span><span class="sxs-lookup"><span data-stu-id="581a0-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="581a0-146">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="581a0-146">Feature Availability</span></span>
<span data-ttu-id="581a0-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="581a0-147"></span></span>

<span data-ttu-id="581a0-148">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="581a0-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

