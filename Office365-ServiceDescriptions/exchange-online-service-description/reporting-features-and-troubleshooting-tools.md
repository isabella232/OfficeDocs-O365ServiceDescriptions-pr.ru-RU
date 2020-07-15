---
title: Функции создания отчетов и средства устранения неполадок
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online предоставляет разнообразные функции для создания отчетов в центре администрирования Exchange.
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132603"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Функции создания отчетов и средства устранения неполадок

Microsoft Exchange Online предоставляет разнообразные функции для создания отчетов в центре администрирования Exchange.
  
## <a name="reporting-features"></a>Функции создания отчетов

Пользователи Exchange Online могут получить доступ к отчетам в центре администрирования Microsoft 365, загрузив книгу отчетов Excel или используя веб-службы.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Создание отчетов в центре администрирования Microsoft 365

На странице Отчеты в центре администрирования Microsoft 365 есть отчеты, содержащие сводные сведения о почтовых ящиках и группах. Например, в одном отчете приводятся группы, перечисленные по дням, неделям и годам создания и удаления. Также имеются сводные отчеты для новых и удаленных, активных и неактивных почтовых ящиков. 
  
Кроме того, на странице Отчеты в центре администрирования Microsoft 365 содержатся отчеты о сообщениях, которые предоставляют сведения о трафике сообщений, обнаружении нежелательной почты и вредоносных программ, а также о сообщениях, затрагиваемых правилами транспорта Exchange или политиками защиты от потери данных (DLP). Администраторы Exchange Online могут пользоваться улучшенными интерактивными отчетами для защиты, правил и политики предотвращения потери данных (DLP). Такие отчеты содержат краткое изложение данных и дают возможность получения более подробных сведений по отдельным сообщениям.
  
Дополнительные сведения о том, какие отчеты доступны в каждой подписке, можно найти в разделе [отчеты](../office-365-platform-service-description/reports.md). Более подробные сведения о странице "отчеты" центра администрирования Microsoft 365 приведены в статье [Просмотр и скачивание отчетов об использовании служб в Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) и [Использование отчетов о защите почты для просмотра данных о вредоносных и нежелательных сообщениях, а также об обнаруженных правилах](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Создание отчетов с помощью рабочей книги отчетов Excel

Кроме того, книгу отчетов Excel 2013 можно использовать для просмотра сводных отчетов с возможностями детализации. Тем не менее, рекомендуется использовать расширенные отчеты центра администрирования Microsoft 365. Со временем планируется прекращение поддержки рабочей книги отчетов Excel 2013. Чтобы получить дополнительные сведения и ссылки для загрузки и установки книги, посетите следующую [страницу загрузки](https://go.microsoft.com/fwlink/p/?LinkId=271776). Дополнительные сведения об использовании рабочей книги см. в разделе [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).     
  
### <a name="reporting-using-web-services"></a>Reporting using web services

Доступ к сводным и подробным отчетам о почтовых ящиках, группах и данных сообщений можно получить с помощью веб-службы отчетов клиента REST/OData, которая представляет собой программный интерфейс, позволяющий создавать настраиваемые отчеты. Дополнительные сведения см. в статье [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Функции создания отчетов и средства устранения неполадок в Центре администрирования Exchange

В Центре администрирования Exchange доступны следующие функции создания отчетов и средства устранения неполадок.
  
### <a name="trace-an-email-message"></a>Отслеживание электронных сообщений

Функция трассировки сообщений позволяет администратору следить за сообщениями электронной почты по мере их прохождения через службу Exchange Online. Эта функция помогает определить, было ли целевое сообщение электронной почты получено, отклонено, отложено или доставлено службой. Это дает возможность оперативно отвечать на вопросы пользователей и устранять неполадки потока сообщений, а также снижает необходимость обращения за помощью в службу технической поддержки.
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
Дополнительные сведения о функции отслеживания сообщений см. в статье [Отслеживание электронных сообщений](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Отчеты аудита

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
Дополнительные сведения о ведении журнала аудита см. в разделе [Отчеты аудита](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Отчеты единой системы обмена сообщениями

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  

