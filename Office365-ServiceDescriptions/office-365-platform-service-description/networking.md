---
title: сеть
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 поддерживает следующие сетевые функции.
ms.openlocfilehash: 915736e704f3d3995993100a82515ee71113be5b
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523427"
---
# <a name="networking"></a><span data-ttu-id="53f8a-103">Организация сети</span><span class="sxs-lookup"><span data-stu-id="53f8a-103">Networking</span></span>

<span data-ttu-id="53f8a-104">Microsoft Office 365 поддерживает следующие сетевые функции.</span><span class="sxs-lookup"><span data-stu-id="53f8a-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="53f8a-105">Порты, протоколы и IP-адреса</span><span class="sxs-lookup"><span data-stu-id="53f8a-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="53f8a-p101">Office 365: использует IPv4- и IPv6-адреса. Использование IPv6-адресов не обязательное и не требуется для подключения к Office 365:. Не все возможности Office 365: поддерживаются в полной мере при использовании протокола IPv6. Дополнительные сведения о поддержке IPv6 в Office 365: см. в статье [Поддержка IPv6 в службах Office 365](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span><span class="sxs-lookup"><span data-stu-id="53f8a-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="53f8a-p102">В справке Office 365: ведется список разрешенных IP-адресов для Office 365:. Дополнительные сведения см. в статье [URL-адреса и диапазоны IP-адресов Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Если вы используете план Office 365:, которым управляет 21Vianet, см. статью [URL- и IP-адреса для плана Office 365, которым управляет 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Об Office 365 Germany см. в статье [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="53f8a-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="53f8a-p103">Мы настоятельно рекомендуем обеспечить маршрутизацию в корневые домены, указанные в вышеупомянутых статьях (например, \*.Outlook.com, \*.MicrosoftOnline.com и \*.SharePoint.com), вместо маршрутизации в специальные подсети IP-адресов. Во втором случае при внесении изменений увеличивается риск перерывов в работе для пользователей.</span><span class="sxs-lookup"><span data-stu-id="53f8a-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="53f8a-116">Требования к пропускной способности</span><span class="sxs-lookup"><span data-stu-id="53f8a-116">Bandwidth requirements</span></span>

<span data-ttu-id="53f8a-117">Информацию о требованиях к пропускной способности см. в разделе [Планирование пропускной способности Интернета](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span><span class="sxs-lookup"><span data-stu-id="53f8a-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="53f8a-118">Подключение к Office 365</span><span class="sxs-lookup"><span data-stu-id="53f8a-118">Connecting to Office 365</span></span>

<span data-ttu-id="53f8a-119">Все подключения к Office 365 выполняются через общедоступный Интернет или по частному подключению Azure ExpressRoute и защищаются по протоколу SSL соответствующим образом.</span><span class="sxs-lookup"><span data-stu-id="53f8a-119">All Connections to Office 365 are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="53f8a-120">Azure ExpressRoute позволяет подключаться непосредственно к глобальной сети Microsoft, минуя Интернет.</span><span class="sxs-lookup"><span data-stu-id="53f8a-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="53f8a-121">Партнерская сеть Microsoft обеспечивает возможность подключения к глобальной сети Microsoft.</span><span class="sxs-lookup"><span data-stu-id="53f8a-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="53f8a-122">Дополнительные сведения об Azure ExpressRoute см. в статье [Azure ExpressRoute для Office 365](https://aka.ms/expressrouteoffice365).</span><span class="sxs-lookup"><span data-stu-id="53f8a-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="53f8a-123">Акселераторы глобальной сети</span><span class="sxs-lookup"><span data-stu-id="53f8a-123">WAN accelerators</span></span>

<span data-ttu-id="53f8a-p105">Корпорация Майкрософт не предоставляет поддержку принадлежащим пользователям устройствам ускорения глобальной сети и кэширования в Office 365:. Если вы решите использовать контроллер оптимизации глобальной сети для улучшения производительности в условиях высокой задержки или низкой пропускной способности, вам необходимо будет отключать его во время устранения неполадок по запросам на обслуживание в корпорацию Майкрософт, а вопросы, связанные с поддержкой устройства,  решать с производителем устройства. Дополнительные сведения см. в разделе [Устройства ускорения глобальной сети и кэширования в Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="53f8a-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="53f8a-127">Глобальная сеть Майкрософт</span><span class="sxs-lookup"><span data-stu-id="53f8a-127">The global Microsoft network</span></span>

<span data-ttu-id="53f8a-128">Сетевая инфраструктура Office 365 включает в себя большой Глобальный портфель центров обработки данных, серверов, сетей распространения контента, узлов пограничного вычисления и волоконно-оптических сетей для предоставления глобального распределения служб.</span><span class="sxs-lookup"><span data-stu-id="53f8a-128">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="53f8a-129">Усовершенствованные средства инструментирования и мониторинга служб интегрируются на глубоком уровне с каждым компонентом, что обеспечивает видимость для центра обработки данных, сетевой магистрали, Интернет Exchange и более поздних версий, чтобы помочь выявить и контролировать причины нарушений, которые никать.</span><span class="sxs-lookup"><span data-stu-id="53f8a-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="53f8a-130">Сеть разработана для поддержания достаточной емкости даже для крупномасштабных сетевых прерываний без снижения производительности.</span><span class="sxs-lookup"><span data-stu-id="53f8a-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="53f8a-131">Более подробную информацию можно узнать в [статье Глобальная сеть Майкрософт](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span><span class="sxs-lookup"><span data-stu-id="53f8a-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="53f8a-p107">С целью сохранения конфиденциальности и целостности информации пользователей корпорация Майкрософт поддерживает сети потребительских служб отдельно от сетей Office 365:. Для контроля информационных потоков используется множество различных методов, включающих, среди прочего, следующие.</span><span class="sxs-lookup"><span data-stu-id="53f8a-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="53f8a-p108">Физическое разделение. Сегменты сети физически разделены маршрутизаторами, настроенными для предотвращения определенных схем связи.</span><span class="sxs-lookup"><span data-stu-id="53f8a-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="53f8a-p109">Логическое разделение. Для последующего разделения сообщений используется технология виртуальной локальной сети (VLAN).</span><span class="sxs-lookup"><span data-stu-id="53f8a-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="53f8a-138">Брандмауэры.</span><span class="sxs-lookup"><span data-stu-id="53f8a-138">Firewalls.</span></span> <span data-ttu-id="53f8a-139">Брандмауэры и другие точки обеспечения безопасности сети используются для ограничения обмена данными с системами, доступными в Интернете, и для изоляции систем от серверных систем, управляемых корпорацией Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="53f8a-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="53f8a-140">Ограничения протокола.</span><span class="sxs-lookup"><span data-stu-id="53f8a-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="53f8a-141">Дополнительные сведения см. в [Центре управления безопасностью Office 365](https://www.microsoft.com/trust-center).</span><span class="sxs-lookup"><span data-stu-id="53f8a-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="53f8a-142">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="53f8a-142">Feature availability</span></span>

<span data-ttu-id="53f8a-143">Сведения о доступности функций в планах Office 365 см. в статье [Описание служб платформы Office 365](office-365-platform-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="53f8a-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](office-365-platform-service-description.md).</span></span>
  

