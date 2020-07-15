---
title: сеть
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Корпорация Майкрософт поддерживает следующие сетевые функции.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132333"
---
# <a name="networking"></a>Сеть

Корпорация Майкрософт поддерживает следующие сетевые функции.
  
## <a name="ports-protocols-and-ip-addresses"></a>Порты, протоколы и IP-адреса

Корпорация Майкрософт использует IPv4-и IPv6-адреса. Использование IPv6-адресов является необязательным и не является обязательным для подключения к Office 365. Не все функции Microsoft 365 полностью включены с помощью IPv6. Дополнительные сведения о поддержке протокола IPv6 см [в разделе Поддержка IPv6 в службах Майкрософт](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Корпорация Майкрософт поддерживает список разрешенных IP-адресов в справке Майкрософт. Дополнительные сведения см. в разделе [URL-адреса и диапазоны IP-адресов](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Для Office 365 под управлением 21Vianet обратитесь к разделам [URL-адресов и IP-адресов для Office 365](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)под управлением 21vianet. В Office 365 для Германии вы найдете [конечные точки office 365 для Германии](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>Требования к пропускной способности

Информацию о требованиях к пропускной способности см. в разделе [Планирование пропускной способности Интернета](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Подключение к Microsoft

Все подключения к корпорации Майкрософт выполняются через общедоступный Интернет или по частному подключению Azure ExpressRoute и защищаются по протоколу SSL соответствующим образом. Azure ExpressRoute позволяет подключаться непосредственно к глобальной сети Microsoft, минуя Интернет. Партнерская сеть Microsoft обеспечивает возможность подключения к глобальной сети Microsoft.
  
Дополнительные сведения об Azure ExpressRoute см. в статье [Azure ExpressRoute для Office 365](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>Акселераторы глобальной сети

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Глобальная сеть Майкрософт

Сетевая инфраструктура Майкрософт включает в себя большой Глобальный портфель центров обработки данных, серверов, сетей распространения контента, узлов пограничных вычислений и волоконно-оптических сетей для предоставления глобального распределения служб. Усовершенствованные средства обслуживания и мониторинга служб интегрируются на самых глубоком уровне с каждым компонентом, что обеспечивает видимость центра обработки данных, сетевой магистрали, Интернет Exchange и более поздних версий для выявления причин неисправностей и управления ею. Сеть разработана для поддержания достаточной емкости даже для крупномасштабных сетевых прерываний без снижения производительности. Более подробную информацию можно узнать в [статье Глобальная сеть Майкрософт](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Чтобы обеспечить конфиденциальность и целостность данных о клиентах, корпорация Майкрософт следит за сетями служб пользователей, отделенными от сетей Майкрософт. Для контроля информационных потоков используется множество различных методов, включающих, среди прочего, следующие.
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- Брандмауэры. Брандмауэры и другие точки обеспечения безопасности сети используются для ограничения обмена данными с системами, доступными в Интернете, и для изоляции систем от серверных систем, управляемых корпорацией Майкрософт. 
    
- Ограничения протокола.
    
Дополнительные сведения см. в [Центре управления безопасностью Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть сведения о доступности функций в планах, ознакомьтесь со статьей [Microsoft 365 и Office 365 Platform Service Description](office-365-platform-service-description.md).
  

