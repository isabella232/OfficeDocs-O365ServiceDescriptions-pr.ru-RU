---
title: Отчеты и трассировка сообщений в Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Ознакомьтесь с этой статьей, чтобы узнать о отчете и следе сообщений в Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653131"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a><span data-ttu-id="142d5-103">Отчеты и трассировка сообщений в Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="142d5-103">Reporting and message trace in Exchange Online Protection</span></span>

<span data-ttu-id="142d5-104">В Microsoft Exchange Online Protection (EOP) доступно множество различных отчетов, с помощью которых вы сможете определить общее состояние и работоспособность вашей организации.</span><span class="sxs-lookup"><span data-stu-id="142d5-104">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="142d5-105">Некоторые отчеты доступны в центре администрирования Microsoft 365, другие — в центре администрирования Exchange (EAC).</span><span class="sxs-lookup"><span data-stu-id="142d5-105">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="142d5-106">Ищете сведения обо всех особенностях EOP?</span><span class="sxs-lookup"><span data-stu-id="142d5-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="142d5-107">См. описание [службы онлайн-защиты Exchange.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="142d5-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="142d5-108">Отчеты центра администрирования Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="142d5-108">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="142d5-109">Страница Отчеты в центре администрирования Microsoft 365 содержит сведения о трафике сообщений, обнаружениях нежелательной почты и вредоносных программ, а также сообщениях, затронутых правилами потока почты (также известными как правила транспорта) или политиками предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="142d5-109">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="142d5-110">Администраторы EOP могут пользоваться улучшенными интерактивными отчетами для защиты, правил и политики предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="142d5-110">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="142d5-111">Такие отчеты содержат краткое изложение данных и позволяют получать более подробные сведения по отдельным сообщениям.</span><span class="sxs-lookup"><span data-stu-id="142d5-111">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="142d5-112">Дополнительные сведения об этих отчетах см. в обзоре отчетов о защите почты для просмотра данных об обнаружении вредоносных программ, нежелательной почты [и правил.](/exchange/monitoring/use-mail-protection-reports)</span><span class="sxs-lookup"><span data-stu-id="142d5-112">For more detailed information about these reports, see [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="142d5-113">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="142d5-113">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="142d5-114">В январе 2018 г. многие функции отчетов на основе REST и связанные с ними cmdlets были обесценились.</span><span class="sxs-lookup"><span data-stu-id="142d5-114">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="142d5-115">Сведения о доступной замене отчетов Microsoft Graph в Office 365 см. в подтопии "Работа с отчетами об использовании" [в Microsoft Graph.](/graph/api/resources/report)</span><span class="sxs-lookup"><span data-stu-id="142d5-115">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with usage reports in Microsoft Graph](/graph/api/resources/report).</span></span>

<span data-ttu-id="142d5-116">Недоступно для автономных клиентов EOP.</span><span class="sxs-lookup"><span data-stu-id="142d5-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="142d5-117">Веб-службу отчетности клиентов REST/OData можно использовать для программного сбора сводок и подробных отчетов о данных обмена сообщениями, а данные можно отобразить на веб-странице на пользовательском портале управления веб-сайтом.</span><span class="sxs-lookup"><span data-stu-id="142d5-117">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="142d5-118">Трассировка сообщений</span><span class="sxs-lookup"><span data-stu-id="142d5-118">Message trace</span></span>

<span data-ttu-id="142d5-119">Функция трассировки сообщений в EAC позволяет вам, как администратору, отслеживать сообщения электронной почты по мере их прохода через EOP.</span><span class="sxs-lookup"><span data-stu-id="142d5-119">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="142d5-120">Эта функция помогает определить, было ли целевое сообщение электронной почты получено, отклонено, отложено или доставлено службой.</span><span class="sxs-lookup"><span data-stu-id="142d5-120">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="142d5-121">Она также отображает те действия, которые произошли в отношении сообщения, прежде чем было достигнуто его окончательное состояние.</span><span class="sxs-lookup"><span data-stu-id="142d5-121">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="142d5-122">Подробные сведения об определенном сообщении позволяют эффективно отвечать на вопросы пользователей, устранять неполадки потока сообщений и проверять изменения политики, а также снижают необходимость обращения за помощью в службу технической поддержки.</span><span class="sxs-lookup"><span data-stu-id="142d5-122">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="142d5-123">Дополнительные сведения см. в обзоре Трассировка сообщений и просмотра результатов [в центре администрирования Exchange.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)</span><span class="sxs-lookup"><span data-stu-id="142d5-123">For more information, see [Run a message trace and view the results in the Exchange admin center](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="142d5-124">Доступность функций</span><span class="sxs-lookup"><span data-stu-id="142d5-124">Feature availability</span></span>

<span data-ttu-id="142d5-125">Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. в описании [службы Exchange Online Protection.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="142d5-125">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>