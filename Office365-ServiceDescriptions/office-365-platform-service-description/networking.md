---
title: сеть
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 поддерживает следующие сетевые функции.
ms.openlocfilehash: 8a9a8d8b5276f4f4578fec625849410268f855ad
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036702"
---
# <a name="networking"></a><span data-ttu-id="190e1-103">Организация сети</span><span class="sxs-lookup"><span data-stu-id="190e1-103">Networking</span></span>

<span data-ttu-id="190e1-104">Microsoft Office 365 поддерживает следующие сетевые функции.</span><span class="sxs-lookup"><span data-stu-id="190e1-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="190e1-105">Порты, протоколы и IP-адреса</span><span class="sxs-lookup"><span data-stu-id="190e1-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="190e1-p101">Office 365: использует IPv4- и IPv6-адреса. Использование IPv6-адресов не обязательное и не требуется для подключения к Office 365:. Не все возможности Office 365: поддерживаются в полной мере при использовании протокола IPv6. Дополнительные сведения о поддержке IPv6 в Office 365: см. в статье [Поддержка IPv6 в службах Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="190e1-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="190e1-p102">В справке Office 365: ведется список разрешенных IP-адресов для Office 365:. Дополнительные сведения см. в статье [URL-адреса и диапазоны IP-адресов Office 365](https://go.microsoft.com/fwlink/p/?LinkID=243567). Если вы используете план Office 365:, которым управляет 21Vianet, см. статью [URL- и IP-адреса для плана Office 365, которым управляет 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Об Office 365 Germany см. в статье [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="190e1-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="190e1-p103">Мы настоятельно рекомендуем обеспечить маршрутизацию в корневые домены, указанные в вышеупомянутых статьях (например, \*.Outlook.com, \*.MicrosoftOnline.com и \*.SharePoint.com), вместо маршрутизации в специальные подсети IP-адресов. Во втором случае при внесении изменений увеличивается риск перерывов в работе для пользователей.</span><span class="sxs-lookup"><span data-stu-id="190e1-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="190e1-116">Требования к пропускной способности</span><span class="sxs-lookup"><span data-stu-id="190e1-116">Bandwidth requirements</span></span>

<span data-ttu-id="190e1-117">Информацию о требованиях к пропускной способности см. в разделе [Планирование пропускной способности Интернета](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span><span class="sxs-lookup"><span data-stu-id="190e1-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="190e1-118">Подключение к Office 365</span><span class="sxs-lookup"><span data-stu-id="190e1-118">Connecting to Office 365</span></span>

<span data-ttu-id="190e1-p104">Все подключения к Office 365: выполняются по открытым интернет-каналам или с помощью частного подключения Azure ExpressRoute и защищены соответствующим SSL-шифрованием. Azure ExpressRoute позволяет напрямую подключаться к глобальной сети Microsoft в обход сети Интернет. Партнерская сеть Microsoft обеспечивает возможность подключения к глобальной сети Microsoft.</span><span class="sxs-lookup"><span data-stu-id="190e1-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="190e1-122">Дополнительные сведения об Azure ExpressRoute см. в статье [Azure ExpressRoute для Office 365](https://aka.ms/expressrouteoffice365).</span><span class="sxs-lookup"><span data-stu-id="190e1-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="190e1-123">Ускорители глобальной сети</span><span class="sxs-lookup"><span data-stu-id="190e1-123">WAN accelerators</span></span>

<span data-ttu-id="190e1-p105">Корпорация Майкрософт не предоставляет поддержку принадлежащим пользователям устройствам ускорения глобальной сети и кэширования в Office 365:. Если вы решите использовать контроллер оптимизации глобальной сети для улучшения производительности в условиях высокой задержки или низкой пропускной способности, вам необходимо будет отключать его во время устранения неполадок по запросам на обслуживание в корпорацию Майкрософт, а вопросы, связанные с поддержкой устройства,  решать с производителем устройства. Дополнительные сведения см. в разделе [Устройства ускорения глобальной сети и кэширования в Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span><span class="sxs-lookup"><span data-stu-id="190e1-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="190e1-127">Глобальная сеть Майкрософт</span><span class="sxs-lookup"><span data-stu-id="190e1-127">The global Microsoft network</span></span>

<span data-ttu-id="190e1-p106">Сетевая инфраструктура Office 365: состоит из обширного глобального портфеля центров обработки данных, серверов, сетей распределения содержимого, крайних вычислительных узлов и оптоволоконных сетей, с помощью которых обеспечивается всеобщее распределение служб. Сложно устроенный инструментарий службы и средства мониторинга глубоко интегрируются в работу каждого компонента, обеспечивая видимость на уровне центра обработки данных, сетевой магистрали, интернет-обменов и даже дальше, что помогает обнаружить, диагностировать и контролировать причины возникающих прерываний. Эта сеть обладает достаточной мощностью для сохранения нормального уровня производительности даже при больших объемах сетевых прерываний. Дополнительные сведения см. на странице [Подразделения Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span><span class="sxs-lookup"><span data-stu-id="190e1-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="190e1-p107">С целью сохранения конфиденциальности и целостности информации пользователей корпорация Майкрософт поддерживает сети потребительских служб отдельно от сетей Office 365:. Для контроля информационных потоков используется множество различных методов, включающих, среди прочего, следующие.</span><span class="sxs-lookup"><span data-stu-id="190e1-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="190e1-p108">Физическое разделение. Сегменты сети физически разделены маршрутизаторами, настроенными для предотвращения определенных схем связи.</span><span class="sxs-lookup"><span data-stu-id="190e1-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="190e1-p109">Логическое разделение. Для последующего разделения сообщений используется технология виртуальной локальной сети (VLAN).</span><span class="sxs-lookup"><span data-stu-id="190e1-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="190e1-p110">Брандмауэры. Брандмауэры и другие точки контроля сетевой безопасности используются для ограничения обмена данными в системах с доступом к Интернету, а также для изоляции систем от серверных систем, управляемых корпорацией Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="190e1-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="190e1-140">Ограничения протокола.</span><span class="sxs-lookup"><span data-stu-id="190e1-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="190e1-141">Дополнительные сведения см. в [Центре управления безопасностью Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span><span class="sxs-lookup"><span data-stu-id="190e1-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="190e1-142">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="190e1-142">Feature availability</span></span>

<span data-ttu-id="190e1-143">Сведения о доступности функций в планах Office 365 см. в статье [Описание служб платформы Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span><span class="sxs-lookup"><span data-stu-id="190e1-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

