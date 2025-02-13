---
title: сеть
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Корпорация Майкрософт поддерживает следующие сетевые функции.
ms.openlocfilehash: dfb53ec42745b57dfa88a86833d20b232d01e85a
ms.sourcegitcommit: 34dd2d202299d88b278490ef4fbea16aa1652fb2
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/30/2021
ms.locfileid: "61234890"
---
# <a name="networking"></a>Сеть

Корпорация Майкрософт поддерживает следующие сетевые функции.
  
## <a name="ports-protocols-and-ip-addresses"></a>Порты, протоколы и IP-адреса

Корпорация Майкрософт использует адреса IPv4 и IPv6. Использование адресов IPv6 является необязательным и не требуется для подключения к Office 365. Не все Microsoft 365 полностью включены с помощью IPv6. Дополнительные сведения о поддержке Ipv6 см. в [службы Майкрософт.](/office365/enterprise/ipv6-support)
  
Корпорация Майкрософт поддерживает список разрешенных IP-адресов в справке Майкрософт. Дополнительные сведения см. в [различных диапазонах URL-адресов и IP-адресов.](/office365/enterprise/urls-and-ip-address-ranges) Для Office 365 21Vianet см. URL-адреса и IP-адреса для Office 365 [21Vianet.](/office365/enterprise/managing-office-365-endpoints)
  
> [!IMPORTANT]
> Мы настоятельно рекомендуем обеспечить маршрутизацию в корневые домены, указанные в вышеупомянутых статьях (например, \*.Outlook.com, \*.MicrosoftOnline.com и \*.SharePoint.com), вместо маршрутизации в специальные подсети IP-адресов. Во втором случае при внесении изменений увеличивается риск перерывов в работе для пользователей. 
  
## <a name="bandwidth-requirements"></a>Требования к пропускной способности

Информацию о требованиях к пропускной способности см. в разделе [Планирование пропускной способности Интернета](/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Подключение к Microsoft

Все подключения к Microsoft делаются через общедоступный Интернет или через частное подключение Azure ExpressRoute и при необходимости защищены службой SSL. Azure ExpressRoute позволяет подключаться непосредственно к глобальной сети Майкрософт, минуя Интернет. Партнерская сеть Microsoft обеспечивает возможность подключения к глобальной сети Microsoft.
  
Дополнительные сведения об Azure ExpressRoute см. в статье [Azure ExpressRoute для Office 365](/microsoft-365/enterprise/azure-expressroute).
  
### <a name="wan-accelerators"></a>Акселераторы глобальной сети

Корпорация Майкрософт не предоставляет поддержку принадлежащим пользователям устройствам ускорения глобальной сети и кэширования в Office 365:. Если вы решите использовать контроллер оптимизации глобальной сети для улучшения производительности в условиях высокой задержки или низкой пропускной способности, вам необходимо будет отключать его во время устранения неполадок по запросам на обслуживание в корпорацию Майкрософт, а вопросы, связанные с поддержкой устройства,  решать с производителем устройства. Дополнительные сведения см. в разделе [Устройства ускорения глобальной сети и кэширования в Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Глобальная сеть Майкрософт

Инфраструктура сети Майкрософт состоит из большого глобального портфеля центров обработки данных, серверов, сетей распространения контента, краев вычислительных узлов и оптоволоконных сетей для обеспечения глобального распространения услуг. Сложные инструменты и мониторинг служб интегрируются на самых глубоких уровнях с каждым компонентом, предоставляя видимость в центре обработки данных, магистрали сети, интернет-биржах и за его пределами, чтобы помочь определить, диагностировать и управлять причиной возникающих сбоев. Сеть построена для поддержания достаточной емкости даже для крупномасштабных перерывов в работе сети без ухудшения производительности. Дополнительные сведения см. в [веб-сайте Microsoft Global Network.](/azure/networking/microsoft-global-network) 
  
Чтобы сохранить конфиденциальность и целостность данных клиентов, Корпорация Майкрософт сохраняет сети потребительских служб отдельно от сетей Майкрософт. Для контроля информационных потоков используется множество различных методов, включающих, среди прочего, следующие.
  
- Физическое разделение. Сегменты сети физически разделены маршрутизаторами, настроенными для предотвращения определенных схем связи.
    
- Логическое разделение. Для последующего разделения сообщений используется технология виртуальной локальной сети (VLAN).
    
- Брандмауэры. Брандмауэры и другие точки обеспечения безопасности сети используются для ограничения обмена данными с системами, которые находятся в интернете, а также для изоляции систем из удаленных систем, управляемых Корпорацией Майкрософт. 
    
- Ограничения протокола.
    
Дополнительные сведения см. в [Центре управления безопасностью Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, см. Microsoft 365 [и Office 365 описание службы платформы.](office-365-platform-service-description.md)
