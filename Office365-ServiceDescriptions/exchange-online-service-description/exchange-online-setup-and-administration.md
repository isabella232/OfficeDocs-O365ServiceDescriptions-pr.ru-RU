---
title: Установка и администрирование Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
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
description: В этом разделе описываются элементы управления и поддержка администрирования, доступные для настройки параметров Exchange Online и поддержания среды Exchange Online в Организации, ее выполнения и текущей. Он включает сведения о средствах самостоятельного администрирования и возможностях, доступных для организаций; административные обязанности корпорации Майкрософт и обязательства производительности; а также обслуживание и обновления для продукта.
ms.openlocfilehash: 93eb996df011a83658aa953521a469d7822f9118
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342788"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="a421a-104">Установка и администрирование Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="a421a-105">В этом разделе описываются элементы управления и поддержка администрирования, доступные для настройки параметров Exchange Online и поддержания среды Exchange Online в Организации, ее выполнения и текущей.</span><span class="sxs-lookup"><span data-stu-id="a421a-105">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="a421a-106">Он включает сведения о средствах самостоятельного администрирования и возможностях, доступных для организаций; административные обязанности корпорации Майкрософт и обязательства производительности; а также обслуживание и обновления для продукта.</span><span class="sxs-lookup"><span data-stu-id="a421a-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="a421a-107">Средства самостоятельного администрирования</span><span class="sxs-lookup"><span data-stu-id="a421a-107">Self-service administration tools</span></span>

<span data-ttu-id="a421a-p103">Несмотря на то что корпорация Майкрософт непосредственно контролирует все центры обработки данных Exchange Online и отвечает за общую производительность системы, она может контролировать только часть элементов, которые в сочетании составляют совокупный опыт пользователей Office 365. Сами организации отвечают за сетевые соединения с центрами обработки данных, глобальную сеть (WAN) и локальные сети (LAN) пользователей. Кроме того, они отвечают за устройства пользователей и их конфигурацию. Они также обеспечивают необходимое лицензирование для каждого пользователя относительно любой требующейся функции, включая возможность управления этими функциями, пока пользователю нужен доступ к этой функции.</span><span class="sxs-lookup"><span data-stu-id="a421a-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="a421a-112">Следовательно, Exchange Online предоставляет пользователям-администраторам инструменты, описанные ниже, для управления различными задачами, связанными с обменом сообщениями.</span><span class="sxs-lookup"><span data-stu-id="a421a-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="a421a-113">Портал Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="a421a-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="a421a-114">Центр администрирования Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="a421a-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="a421a-115">Центр администрирования Exchange</span><span class="sxs-lookup"><span data-stu-id="a421a-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="a421a-116">Удаленная оболочка Windows PowerShell для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="a421a-117">Портал Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="a421a-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="a421a-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="a421a-118"></span></span>

<span data-ttu-id="a421a-119">Портал Microsoft Office 365, расположенный по адресу [https://portal.office.com](https://portal.office.com), представляет из себя веб-сайт, на котором администраторы и партнеры могут приобретать службы Office 365 и управлять ими, а пользователи могут получать доступ к средствам Office 365 для совместной работы и использовать их.</span><span class="sxs-lookup"><span data-stu-id="a421a-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="a421a-120">Центр администрирования Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="a421a-120">Microsoft 365 admin center</span></span>
<span data-ttu-id="a421a-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="a421a-121"></span></span>

<span data-ttu-id="a421a-122">Центр администрирования Microsoft 365 — это веб-портал, с которого администратор службы каждой компании может управлять учетными записями и параметрами пользователей для каждой службы Office 365, на которую они подписаны.</span><span class="sxs-lookup"><span data-stu-id="a421a-122">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="a421a-123">В центре администрирования Microsoft 365 администраторы могут перейти по ссылкам в центр администрирования Exchange, где они могут управлять параметрами Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a421a-123">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="a421a-124">Дополнительные сведения о том, как приступить к работе с помощью центра администрирования Microsoft 365, можно найти в следующем видео: [Введение в Office 365 корпоративный](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="a421a-124">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="a421a-125">Центр администрирования Exchange</span><span class="sxs-lookup"><span data-stu-id="a421a-125">Exchange admin center</span></span>
<span data-ttu-id="a421a-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="a421a-126"></span></span>

<span data-ttu-id="a421a-p105">Exchange Online предоставляет единую консоль управления, которая упрощает работу и оптимизирована для управления локальными, гибридными и веб-развертываниями. В Центре администрирования Exchange администраторы могут управлять специальными параметрами Exchange.</span><span class="sxs-lookup"><span data-stu-id="a421a-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="a421a-129">Дополнительные сведения об управлении Exchange Online с помощью Центра администрирования Exchange см. в разделе [Центр администрирования Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="a421a-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="a421a-130">Удаленная оболочка Windows PowerShell для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="a421a-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="a421a-131"></span></span>

<span data-ttu-id="a421a-p106">С помощью удаленной оболочки Windows PowerShell администраторы могут подключаться к Exchange Online для выполнения задач управления, недоступных или нецелесообразных при использовании Центра администрирования Exchange. Такие задачи включают автоматизацию повторяющихся задач, извлечение данных из пользовательских отчетов, настройку политик и подключение Exchange Online к существующим процессам и инфраструктуре. Дополнительные сведения см. в статье [Подключение к Exchange Online с помощью удаленной оболочки PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="a421a-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="a421a-p107">Exchange Online использует те же командлеты оболочки Windows PowerShell, что и Exchange Server 2013, но некоторые команды и параметры недоступны, поскольку эти функции не применяются в Exchange Online. Список командлетов, которые используются с Exchange Online, см. в разделе [Командлеты Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="a421a-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="a421a-p108">Для использования удаленной оболочки Windows PowerShell администраторам не нужно устанавливать какое-либо средство управления или миграции Exchange Server. Однако компьютеры администраторов должны работать под управлением Windows Management Framework 3.0, включающей в себя Windows PowerShell версии 3 и WinRM 3.0; а также Windows .NET Framework 4.5. Эти компоненты уже установлены на компьютере под управлением ОС Windows 8 или Windows Server 2012. Администраторы могут загружать эти компоненты на компьютеры под управлением ОС Windows 7 или Windows Server 2008 R2 вручную.</span><span class="sxs-lookup"><span data-stu-id="a421a-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a421a-141">Для предотвращения атак типа "отказ в обслуживании" (DoS) можно открыть не более трех подключений оболочки Windows PowerShell к организации Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a421a-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="a421a-142">Возможности самообслуживания для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="a421a-p109">Ниже приводятся важные функции, доступные для управления Exchange Online с помощью Центра администрирования Exchange, удаленной оболочки Windows PowerShell и других инструментов. С помощью этих инструментов можно контролировать и многие другие параметры, как описано в этом документе.</span><span class="sxs-lookup"><span data-stu-id="a421a-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="a421a-145">Политики безопасности мобильных устройств для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="a421a-p110">Exchange Online поддерживает те же политики ActiveSync для мобильных устройств, что и Exchange Server 2013. Администраторы могут применять и настраивать эти политики для отдельных пользователей и групп с помощью Центра администрирования Exchange или удаленной оболочки Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a421a-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="a421a-148">Отслеживание сообщений для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="a421a-149">Отслеживание сообщений с помощью отчетов о доставке описывается в следующем разделе. [Функции создания отчетов и средства устранения неполадок](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="a421a-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="a421a-150">Использование отчетов для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="a421a-p111">Администраторы могут использовать удаленную оболочку Windows PowerShell для получения информации об использовании служб Exchange Online сотрудниками организации. К такой информации относятся следующие сведения.</span><span class="sxs-lookup"><span data-stu-id="a421a-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="a421a-153">Размер почтового ящика для каждого пользователя в организации.</span><span class="sxs-lookup"><span data-stu-id="a421a-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="a421a-154">Настраиваемые разрешения, заданные для почтовых ящиков, такие как передача прав доступа.</span><span class="sxs-lookup"><span data-stu-id="a421a-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="a421a-155">Данные о подключении мобильных устройств, например, подключенных с помощью Exchange ActiveSync, об используемых устройствах и дате их последнего подключения.</span><span class="sxs-lookup"><span data-stu-id="a421a-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="a421a-p112">Командлеты удаленной оболочки Windows PowerShell, которые начинаются с префикса "get-", могут получать данные от системы Exchange Online. Администраторы могут экспортировать эту информацию с Windows PowerShell в формате CSV для расширенного анализа или создания отчета.</span><span class="sxs-lookup"><span data-stu-id="a421a-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="a421a-158">Дополнительные сведения о командлетах Windows PowerShell, которые используются в Exchange Online, см. в разделе [Командлеты Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="a421a-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="a421a-159">Аудит для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="a421a-160">Функция ведения журнала аудита описана в следующем разделе. [Функции создания отчетов и средства устранения неполадок](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="a421a-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="a421a-161">Обновления служб и продуктов для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a421a-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="a421a-p113">Клиенты Exchange Online пользуются преимуществом периодических обновлений Exchange до новейших технологий, в том числе до новых выпусков Exchange Server. Эти обновления доступны бесплатно и гарантируют, что клиенты всегда используют новейшее программное обеспечение Exchange.</span><span class="sxs-lookup"><span data-stu-id="a421a-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="a421a-164">После выпуска корпорацией Майкрософт основной версии Exchange клиенты могут обновить службы до новой версии в течение 12 месяцев.</span><span class="sxs-lookup"><span data-stu-id="a421a-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a421a-165">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="a421a-165">Feature Availability</span></span>

<span data-ttu-id="a421a-166">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="a421a-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

