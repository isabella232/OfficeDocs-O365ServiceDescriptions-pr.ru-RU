---
title: Службы голосовых сообщений
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036821"
---
# <a name="voice-message-services"></a><span data-ttu-id="dac7c-102">Службы голосовых сообщений</span><span class="sxs-lookup"><span data-stu-id="dac7c-102">Voice Message Services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="dac7c-103">Голосовая почта</span><span class="sxs-lookup"><span data-stu-id="dac7c-103">Voice mail</span></span>

<span data-ttu-id="dac7c-104">Microsoft Exchange Online предлагает услуги размещенной голосовой почты, которые включают в себя следующее.</span><span class="sxs-lookup"><span data-stu-id="dac7c-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="dac7c-105">Автоответчик (голосовая почта)</span><span class="sxs-lookup"><span data-stu-id="dac7c-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="dac7c-106">Удаленный доступ к Exchange (голосовой доступ к Outlook)</span><span class="sxs-lookup"><span data-stu-id="dac7c-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="dac7c-107">Удаленный доступ для вызывающих абонентов (автосекретарь)</span><span class="sxs-lookup"><span data-stu-id="dac7c-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="dac7c-p101">Службы обмена мгновенными сообщениями, размещенной голосовой позволяют компании для подключения его в локальной телефонной системы голосовой почты служб, предоставленных поставщиком Exchange Online. Сообщения голосовой почты записанные и сохраняются в Exchange Online инфраструктуры, позволяя пользователям получать доступ к своим голосовые сообщения из Outlook, Outlook на веб-сайте или мобильные телефоны. Все подключения к телефонной связи в Exchange Online требует протоколов передачу голоса по Протоколу (VoIP). Администраторы могут подключаться локальной IP-УАТС или УАТС телефонных систем с помощью шлюзов VoIP мультимедиа и пограничных контроллеров сеансов (SBC) для Exchange Online. Медиашлюз VoIP не требуется, если клиент развернут IP-УАТС или УАТС поддерживает VoIP напрямую и взаимодействует с Exchange голосовых сообщений служб. SBC развертываются в пограничной сети клиента для подключения локальной телефонной сетью и улучшения защиты от подслушивания и обнаружение вторжений communications (и сети клиента). Взаимодействие с возможностями голосовой связи Microsoft Lync Server 2010 и 2013 также поддерживается.</span><span class="sxs-lookup"><span data-stu-id="dac7c-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="dac7c-p102">Голосовой связи, недоступны в Exchange Online services функции обмена сообщениями, аналогичны предлагается в локальной Exchange Server 2016. К ним относятся:</span><span class="sxs-lookup"><span data-stu-id="dac7c-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="dac7c-117">Воспроизведение на телефоне из Outlook и Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="dac7c-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="dac7c-118">Уведомления о пропущенных вызовах.</span><span class="sxs-lookup"><span data-stu-id="dac7c-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="dac7c-119">Идентификатор звонящего (используется информация в глобальном списке адресов, личные контакты пользователя, пользовательские папки контактов и контакты из внешних социальных сетей).</span><span class="sxs-lookup"><span data-stu-id="dac7c-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="dac7c-120">Сообщение голосовой почты из Outlook на веб-серверы и Outlook (см. [Сброс ПИН-код голосовой почты](https://go.microsoft.com/fwlink/p/?LinkId=286328)) сброс ПИН-кода.</span><span class="sxs-lookup"><span data-stu-id="dac7c-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="dac7c-121">Индикатор ожидающего сообщения (дополнительные сведения см. в статье об [индикаторе ожидающих сообщений в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794)).</span><span class="sxs-lookup"><span data-stu-id="dac7c-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="dac7c-122">Правила автоответчика (дополнительные сведения см. в разделе [Включение переадресации вызовов для пользователей голосовой почты](https://go.microsoft.com/fwlink/p/?LinkId=271795)).</span><span class="sxs-lookup"><span data-stu-id="dac7c-122">Call Answering Rules (see [Allow Voice Mail Users to Forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span> 
    
- <span data-ttu-id="dac7c-123">Защищенная голосовая почта в Exchange Online (дополнительные сведения см. в статье [Защищенная голосовая почта в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796)).</span><span class="sxs-lookup"><span data-stu-id="dac7c-123">Protected Voice Mail in Exchange Online (see [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span> 
    
- <span data-ttu-id="dac7c-124">Просмотр голосовой почты (список поддерживаемых языков см. в разделе [Просмотр голосовой почты для конечных пользователей](https://go.microsoft.com/fwlink/p/?LinkId=271797)).</span><span class="sxs-lookup"><span data-stu-id="dac7c-124">Voice Mail Preview (see [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span> 
    
- <span data-ttu-id="dac7c-125">Голосовой доступ к электронной и голосовой почте, календарю, личным контактам и личным группам контактов.</span><span class="sxs-lookup"><span data-stu-id="dac7c-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="dac7c-126">Поиск по каталогу с помощью голосового доступа к Outlook или автосекретаря.</span><span class="sxs-lookup"><span data-stu-id="dac7c-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="dac7c-127">Администраторы настраивают и управляют совместимостью служб обмена голосовыми сообщениями с помощью Центра администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="dac7c-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="dac7c-128">Для получения дополнительной информации о функциях голосовой почты см. статью о [голосовой почте в Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="dac7c-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="dac7c-p103">Функция автоматического распознавания речи (ASR) недоступна во время навигации по меню или поиска по каталогу для пользователей голосового доступа к Outlook или пользователей автосекретаря, использующих голосовые команды. > Клиент должен предоставить телефонное соединение с коммутируемой телефонной сетью общего пользования (PSTN), используя шлюз VoIP и УАТС, IP-УАТС или Skype для бизнеса Server 2015. > Клиент должен предоставить локальные устройства пограничных контроллеров сеансов (SBC) и обеспечить правильную настройку SBC для подключения к службам голосовой почты в Интернете. Сюда входит настройка соответствующего уровня безопасности с использованием сертификатов, общедоступных и частных интерфейсов IP и подключением соответствующих портов TCP через их локальные брандмауэры. > Размещенная голосовая почта доступна только для подписчиков на Exchange Online (план 2) и Office 365 для предприятий E3.</span><span class="sxs-lookup"><span data-stu-id="dac7c-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="dac7c-134">Взаимодействие со сторонней голосовой почтой</span><span class="sxs-lookup"><span data-stu-id="dac7c-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="dac7c-p104">Локальные системы голосовой почты от сторонних провайдеров могут взаимодействовать с Exchange Online, если они способны пересылать голосовые сообщения через SMTP, или если они поддерживают службы Microsoft Exchange Web Services. Если система голосовой почты изначально не поддерживает переадресацию голосовых сообщений через SMTP, сервер электронной почты может быть размещен локально и может получать сообщения из системы голосовой почты, а затем направлять их на облако используя SMTP. Так как многие сторонние системы голосовой почты используют MAPI/CDO для взаимодействия с продвинутой единой системой обмена сообщениями Exchange Server, все возможности этих систем могут быть недоступны при использовании SMTP для совместимости с Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="dac7c-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="dac7c-p105">Поддержка Exchange Online единой системы обмена СООБЩЕНИЯМИ для сторонних производителей УАТС с помощью прямого подключения от клиентов, используемых SBC приведет к сбросу в 2018 июля. Для получения дополнительных сведений обратитесь к [прекращении поддержки для пограничных контроллеров сеансов в Exchange Online единой системы обмена сообщениями](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) .</span><span class="sxs-lookup"><span data-stu-id="dac7c-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="dac7c-140">Интеграция Skype для бизнеса</span><span class="sxs-lookup"><span data-stu-id="dac7c-140">Skype for Business integration</span></span>

<span data-ttu-id="dac7c-p106">Организации можно приобрести Скайп для бизнеса в Интернет, как автономную службу или как часть Microsoft Office 365. Скайп для бизнеса 2015 локальных также поддерживается. Чтобы узнать больше о Скайп для бизнеса в Интернет, видеть [Скайп для бизнеса Online описания службы](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="dac7c-p106">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365. Skype for Business 2015 on-premises is also supported. To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="dac7c-144">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="dac7c-144">Feature Availability</span></span>

<span data-ttu-id="dac7c-145">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="dac7c-145">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

