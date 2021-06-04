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
description: Ознакомьтесь с этой статьей, чтобы узнать о следах отчетов и сообщений в Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653131"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Отчеты и трассировка сообщений в Exchange Online Protection

В Microsoft Exchange Online Protection (EOP) доступно множество различных отчетов, с помощью которых вы сможете определить общее состояние и работоспособность вашей организации. Некоторые отчеты доступны в центре администрирования Microsoft 365, другие — в центре администрирования Exchange (EAC).

Ищете сведения обо всех особенностях EOP? См. [Exchange Online Protection службы.](exchange-online-protection-service-description.md)

## <a name="microsoft-365-admin-center-reports"></a>Отчеты в Центре администрирования Microsoft 365

На странице Отчеты в центре администрирования Microsoft 365 содержится информация о трафике сообщений, обнаружениях нежелательной почты и вредоносных программ, а также сообщениях, затронутых правилами потока почты (также известными как правила транспорта) или политиками предотвращения потери данных (DLP). Администраторы EOP могут пользоваться улучшенными интерактивными отчетами для защиты, правил и политики предотвращения потери данных (DLP). Такие отчеты содержат краткое изложение данных и позволяют получать более подробные сведения по отдельным сообщениям.

Дополнительные сведения об этих отчетах см. в обзоре отчетов о защите почты для просмотра данных об обнаружении вредоносных программ, нежелательной почты [и правил.](/exchange/monitoring/use-mail-protection-reports)

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> В январе 2018 г. многие функции отчетов на основе REST и связанные с ними cmdlets были обесценились. Сведения о доступной замене отчетов Microsoft Graph отчетов в Office 365 см. в подтопии "Работа с отчетами об использовании" в [Microsoft Graph.](/graph/api/resources/report)

Недоступно для автономных клиентов EOP. Веб-службу отчетности клиентов REST/OData можно использовать для программного сбора сводок и подробных отчетов о данных обмена сообщениями, а данные можно отобразить на веб-странице на пользовательском портале управления веб-сайтом.

## <a name="message-trace"></a>Трассировка сообщений

Функция трассировки сообщений в EAC позволяет вам, как администратору, отслеживать сообщения электронной почты по мере их прохода через EOP. Эта функция помогает определить, было ли целевое сообщение электронной почты получено, отклонено, отложено или доставлено службой. Она также отображает те действия, которые произошли в отношении сообщения, прежде чем было достигнуто его окончательное состояние. Подробные сведения об определенном сообщении позволяют эффективно отвечать на вопросы пользователей, устранять неполадки потока сообщений и проверять изменения политики, а также снижают необходимость обращения за помощью в службу технической поддержки. Дополнительные сведения см. в сообщении [Run a message trace and view the results in the Exchange admin center.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)

## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. Exchange Online Protection [службы.](exchange-online-protection-service-description.md)