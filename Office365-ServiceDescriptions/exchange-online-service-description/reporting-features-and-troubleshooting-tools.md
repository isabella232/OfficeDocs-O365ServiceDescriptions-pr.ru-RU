---
title: Функции создания отчетов и средства устранения неполадок
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online предоставляет разнообразные функции для создания отчетов в центре администрирования Exchange.
ms.openlocfilehash: 16bcea7f90115ca3238e502e5b57d756d24025ba
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210222"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="1e1d9-103">Функции создания отчетов и средства устранения неполадок</span><span class="sxs-lookup"><span data-stu-id="1e1d9-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="1e1d9-104">Microsoft Exchange Online предоставляет разнообразные функции для создания отчетов в центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="1e1d9-105">Функции создания отчетов</span><span class="sxs-lookup"><span data-stu-id="1e1d9-105">Reporting features</span></span>

<span data-ttu-id="1e1d9-106">Пользователи Exchange Online могут получить доступ к отчетам в центре администрирования Microsoft 365, загрузив книгу отчетов Excel или используя веб-службы.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="1e1d9-107">Создание отчетов в центре администрирования Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="1e1d9-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="1e1d9-p101">На странице Отчеты в центре администрирования Microsoft 365 есть отчеты, содержащие сводные сведения о почтовых ящиках и группах. Например, в одном отчете указывается количество групп, созданных и удаленных по дням, неделям, месяцам или годам. Также имеются сводные отчеты для новых и удаленных почтовых ящиков, а также для активных и неактивных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p101">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups. For example, one report lists the number of groups created and deleted by day, week, month, or year. There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="1e1d9-p102">Кроме того, на странице Отчеты в центре администрирования Microsoft 365 содержатся отчеты об обмене сообщениями, содержащие сведения о трафике сообщений, обнаружении нежелательной почты и вредоносных программ, а также о сообщениях, на которые влияют правила транспорта Exchange или защита от потери данных (DLP). правила. Расширенные отчеты для защиты, правил и DLP предоставляют Интерактивные отчеты для администраторов Exchange Online. Эти отчеты предоставляют сводную информацию и возможность детальной детализации сведений об отдельных сообщениях.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p102">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="1e1d9-p103">Дополнительные сведения о том, какие отчеты доступны для каждой подписки на Office 365, можно найти в разделе [отчеты](../office-365-platform-service-description/reports.md). Более подробные сведения о странице "отчеты" центра администрирования Microsoft 365 приведены в статье [Просмотр и скачивание отчетов об использовании служб в office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) и [Использование отчетов о защите почты в Office 365 для просмотра данных о вредоносных и нежелательных сообщениях, а также об обнаружении правил ](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p103">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md). For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="1e1d9-116">Создание отчетов с помощью рабочей книги отчетов Excel</span><span class="sxs-lookup"><span data-stu-id="1e1d9-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="1e1d9-p104">Кроме того, книгу отчетов Excel 2013 можно использовать для просмотра сводных отчетов с возможностями детализации. Тем не менее, рекомендуется использовать расширенные отчеты центра администрирования Microsoft 365. Книга отчетов Excel 2013 планируется использовать в будущем. Чтобы получить дополнительные сведения и ссылки для загрузки и установки книги, посетите следующую [страницу загрузки](https://go.microsoft.com/fwlink/p/?LinkId=271776). Сведения о том, как использовать книгу, можно найти в разделе [отчеты о защите почты с помощью книги отчетов Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p104">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities. However, we recommend using the enhanced Microsoft 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future. For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="1e1d9-122">Создание отчетов с помощью веб-служб</span><span class="sxs-lookup"><span data-stu-id="1e1d9-122">Reporting using Web services</span></span>

<span data-ttu-id="1e1d9-p105">Как сводные, так и подробные отчеты о почтовых ящиках, группах и данных сообщений доступны через веб-службы для создания отчетов REST или OData, которые являются программным интерфейсом, позволяющим создавать настраиваемые отчеты. Дополнительные сведения см. в статье [Веб-службы отчетности в Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="1e1d9-125">Функции создания отчетов и средства устранения неполадок в Центре администрирования Exchange</span><span class="sxs-lookup"><span data-stu-id="1e1d9-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="1e1d9-126">В Центре администрирования Exchange доступны следующие функции создания отчетов и средства устранения неполадок.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="1e1d9-127">Отслеживание электронных сообщений</span><span class="sxs-lookup"><span data-stu-id="1e1d9-127">Trace an email message</span></span>

<span data-ttu-id="1e1d9-p106">Функция отслеживания сообщений позволяет пользователям в качестве администратора отслеживать электронные сообщения, проходящие через службу Exchange Online. Эта функция помогает определить, было ли целевое сообщение электронной почты получено, отклонено, отложено или доставлено службой. Это дает возможность оперативно отвечать на вопросы пользователей и устранять неполадки потока сообщений, а также снижает необходимость обращения за помощью в службу технической поддержки.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="1e1d9-p107">Для получения информации по общим вопросам и тенденциям устранения неполадок используйте средства создания отчетов. Для одиночных случаев, в которых требуются сведения о сообщении, используйте средство отслеживания сообщений.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="1e1d9-133">Дополнительные сведения о функции отслеживания сообщений см. в статье [Отслеживание электронных сообщений](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="1e1d9-134">Отчеты аудита</span><span class="sxs-lookup"><span data-stu-id="1e1d9-134">Auditing reports</span></span>

<span data-ttu-id="1e1d9-p108">Журнал аудита можно использовать для устранения проблем с конфигурацией и обеспечения соблюдения нормативных и законодательных требований путем отслеживания отдельных изменений, вносимых администраторами. В Exchange Online доступно два способа ведения журнала аудита:</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="1e1d9-p109">Ведение журнала аудита действий администратора записывает любые действия, выполняемые администратором. Это позволяет устранять неполадки конфигурации или выявлять причины проблем безопасности или соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="1e1d9-p110">В журнале аудита почтовых ящиков записываются все обращения к почтовым ящикам от пользователей, не являющихся их владельцами. Таким образом, можно определить, кто обращался к почтовому ящику, и какие действия были произведены.</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="1e1d9-141">Дополнительные сведения о ведении журнала аудита см. в разделе [Отчеты аудита](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="1e1d9-142">Отчеты единой системы обмена сообщениями</span><span class="sxs-lookup"><span data-stu-id="1e1d9-142">Unified Messaging reports</span></span>

<span data-ttu-id="1e1d9-p111">Такие отчеты можно использовать для мониторинга и устранения неполадок единой системы обмена сообщениями в организации Exchange Online. Дополнительные сведения см. в разделе [Запуск отчетов для вызовов голосовой почты](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="1e1d9-145">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="1e1d9-145">Feature Availability</span></span>

<span data-ttu-id="1e1d9-146">Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="1e1d9-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

