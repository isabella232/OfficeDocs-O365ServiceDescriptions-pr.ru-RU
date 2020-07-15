---
title: Установка и администрирование Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: В этой статье описываются административные элементы управления и поддержка, доступные для настройки параметров Exchange Online и поддержания среды Exchange Online в Организации, ее выполнения и текущей. Он включает сведения о средствах самостоятельного администрирования и возможностях, доступных для организаций; административные обязанности корпорации Майкрософт и обязательства производительности; а также обслуживание и обновления для продукта.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133004"
---
# <a name="exchange-online-setup-and-administration"></a>Установка и администрирование Exchange Online

В этой статье описываются административные элементы управления и поддержка, доступные для настройки параметров Exchange Online и поддержания среды Exchange Online в Организации, ее выполнения и текущей. Он включает сведения о средствах самостоятельного администрирования и возможностях, доступных для организаций; административные обязанности корпорации Майкрософт и обязательства производительности; а также обслуживание и обновления для продукта.
  
## <a name="self-service-administration-tools"></a>Средства самостоятельного администрирования

Несмотря на то, что Microsoft напрямую контролирует все центры обработки данных Exchange Online и отвечает за общую производительность системы, он может управлять только частью элементов, объединяемых для предоставления общего интерфейса для пользователей. Сами организации отвечают за сетевые соединения с центрами обработки данных, глобальную сеть (WAN) и локальные сети (LAN) пользователей. Кроме того, они отвечают за устройства пользователей и их конфигурацию.Они также обеспечивают необходимое лицензирование для каждого пользователя относительно любой требующейся функции, включая возможность управления этими функциями, пока пользователю нужен доступ к этой функции.
  
Следовательно, Exchange Online предоставляет пользователям-администраторам инструменты, описанные ниже, для управления различными задачами, связанными с обменом сообщениями.
  
- [Портал Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Центр администрирования Microsoft 365](#microsoft-365-admin-center)
    
- [Центр администрирования Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Удаленная оболочка Windows PowerShell для Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Портал Microsoft Office 365

Портал Microsoft Office 365, расположенный по адресу [https://portal.office.com](https://portal.office.com), представляет из себя веб-сайт, на котором администраторы и партнеры могут приобретать службы Office 365 и управлять ими, а пользователи могут получать доступ к средствам Office 365 для совместной работы и использовать их.
  
### <a name="microsoft-365-admin-center"></a>Центр администрирования Microsoft 365

Центр администрирования Microsoft 365 — это веб-портал, с которого администратор службы каждой компании может управлять учетными записями и параметрами пользователей для каждой из служб Майкрософт, на которые они подписаны. В центре администрирования Microsoft 365 администраторы могут перейти по ссылкам в центр администрирования Exchange, где они могут управлять параметрами Exchange Online. Дополнительные сведения о том, как приступить к работе с помощью центра администрирования Microsoft 365, можно найти в следующем видео: [Введение в Office 365 корпоративный](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Центр администрирования Exchange

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Дополнительные сведения об управлении Exchange Online с помощью Центра администрирования Exchange см. в разделе [Центр администрирования Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Удаленная оболочка Windows PowerShell для Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Для предотвращения атак типа "отказ в обслуживании" (DoS) можно открыть не более трех подключений оболочки Windows PowerShell к организации Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Возможности самообслуживания для Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Политики безопасности мобильных устройств для Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Отслеживание сообщений для Exchange Online

Отслеживание сообщений с помощью функции "отчеты о доставке" описывается в следующем разделе: [функции отчетов и средства устранения неполадок](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Использование отчетов для Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Размер почтового ящика для каждого пользователя в организации.
    
- Настраиваемые разрешения, заданные для почтовых ящиков, такие как передача прав доступа.
    
- Данные о подключении мобильных устройств, например, подключенных с помощью Exchange ActiveSync, об используемых устройствах и дате их последнего подключения.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Дополнительные сведения о командлетах Windows PowerShell, которые используются в Exchange Online, см. в разделе [Командлеты Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Аудит для Exchange Online

Функция ведения журнала аудита описана в следующем разделе: [функции отчетов и средства устранения неполадок](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Обновления служб и продуктов для Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
После выпуска корпорацией Майкрософт основной версии Exchange клиенты могут обновить службы до новой версии в течение 12 месяцев.
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  