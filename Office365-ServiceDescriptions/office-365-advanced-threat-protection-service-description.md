---
title: Описание службы Office 365 Advanced Threat Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 02/20/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat protection (ATP) — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту от нерабочего дня, а также включает функции защиты Организация из нежелательных ссылок в режиме реального времени. ATP обладает богатыми возможностями создания отчетов и трассировки URL-адресов, которые сообщают администраторам о типах атак, происходящих в организации.
ms.openlocfilehash: 4bdd657ba517db072cf73a5e313d93ce2805b7b3
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468046"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Описание службы Office 365 Advanced Threat Protection

Microsoft Office 365 Advanced Threat protection (ATP) — это облачная служба фильтрации электронной почты, которая помогает защитить организацию от неизвестных вредоносных программ и вирусов, обеспечивая надежную защиту от нерабочего дня, а также включает функции защиты Организация из нежелательных ссылок в режиме реального времени. ATP обладает богатыми возможностями создания отчетов и трассировки URL-адресов, которые сообщают администраторам о типах атак, происходящих в организации.
  
Ниже приведены основные способы использования ATP для защиты сообщений.
  
- В сценариях, использующих только фильтрацию Office 365 ATP, ATP предоставляет облачную защиту электронной почты для локальной среды Exchange Server или любого другого локального решения электронной почты SMTP.
    
- Office 365 ATP можно включить для защиты почтовых ящиков Exchange Online, размещенных в облаке. Дополнительные сведения об Exchange Online см. в статье [Описание службы Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- Для защиты среды обмена сообщениями и управления маршрутизацией почты в гибридном развертывании можно настроить Advanced Threat Protection, если есть локальные и облачные почтовые ящики, а также используется Exchange Online Protection для фильтрации входящих писем.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Доступность Office 365 Advanced Threat Protection

ATP включена в Office 365 корпоративный, Office 365 для образования A5 и Microsoft 365 бизнес. 
  
Можно добавить Advanced Threat Protection в следующие планы подписки на Exchange и Office 365: 
  
- Exchange Online (план 1)
    
- Exchange Online (план 2)
    
- Базовая подписка на Exchange Online
    
- Exchange Online Protection
    
- Office 365 бизнес базовый
    
- Office 365 бизнес премиум
    
- Office 365 для предприятий E1
    
- Office 365 для предприятий E3
    
- Office 365 корпоративный F1
    
- Office 365 A1
    
- Office 365 A3
    
Сведения о приобретении Office 365 Advanced Threat Protection см. на странице [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).
  
Сравнение функций в разных планах см. на странице [Сравнение планов Office 365 для бизнеса](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Новые возможности Office 365 Advanced Threat Protection (ATP)

Мы продолжаем добавлять новые функции в Office 365 ATP. Ниже приведен список нескольких новых функций, некоторые из которых вызывают политику ATP для просмотра и обновления. Для получения дополнительных сведений о новых возможностях, поступающих в ATP (или Microsoft 365 в целом), посетите [план Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Обновления функций  |Элементы Action  |
|---------|---------|
|Начиная с 2019 февраля и выходящиеся в течение нескольких месяцев в течение нескольких месяцев, в ATP добавляются возможности [аналитики угроз](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) . <br>Если в вашей организации в настоящее время не существует ATP, то вы можете рассмотреть новые варианты, включая ATP Plan 1 и ATP Plan 2. <br>Чтобы узнать больше, ознакомьтесь со статьей [доступность функций в планАх расширенНой защиты от угроз (](#feature-availability-across-advanced-threat-protection-atp-plans) в этой статье) и [планах Office 365 Advanced Threat Protection и ценах](https://products.office.com/exchange/advance-threat-protection). |ИзУчите подписку Организации и при необходимости [купите или](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)изменяйте надстройку.  |
|Начиная с 2018 октября и выполнив эти несколько месяцев, когда люди используют Outlook или веб-приложение Outlook (OWA), [безопасные ссылки ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) отображают исходные URL-адреса, а не переписывают их. (Мы вызываем эту собственную визуализацию ссылок.)<br>Если для вашей организации доступна собственная визуализация ссылок, эта функция будет работать в Outlook 365 ("нажми и работай") и OWA.|Нет         |
|Начиная с сентября 2018, [страницы предупреждений Office 365 ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) — новая цветовая схема, дополнительные сведения и возможность перехода на сайт, несмотря на заданные предупреждения и рекомендации. |Нет         |
|Начиная со второй половины 2018, защита " [безопасные ссылки ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) " расширена для применения к URL-адресам в Office Online (Word Online, Excel Online, PowerPoint Online и OneNote Online) и Office 365 профессиональный плюс на компьютере Mac.   |[Просмотр и изменение политик безОпасных ссылок ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|Начиная с опоздания, Май 2018, функции карантина &amp; в центре безопасности соответствуют расширению [ATP для SharePoint Online, OneDrive для бизнеса и Microsoft Teams](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams). |[Просмотр и изменение политик безОпасных вложений ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|Начиная с 2018 марта Recovery [Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) Protection расширяется для применения к электронной почте, отправляемой между пользователями в Организации. |[Просмотр и изменение политик безОпасных ссылок ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|Начиная с октября 2017, защита [ссылок ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) расширена для применения к URL-адресам в сообщениях электронной почты, а также URL-адресам в документах Office 365 профессиональный плюс, таких как Word, Excel, PowerPoint и Visio в Windows, а также для приложений Office на устройствах с iOS и Android.  |Убедитесь, что используется [современная проверка подлинности для Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) . |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Требования для Office 365 Advanced Threat Protection (ATP)

ATP можно использовать с любым агентом передачи почты SMTP, например Microsoft Exchange Server. Сведения о операционных системах, веб-браузерах и языках, поддерживаемых пакетом ATP, можно найти в разделах "Поддерживаемые браузеры" и "Поддерживаемые языки" [центра администрирования Exchange в Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Доступность функций в планах Advanced Threat Protection (ATP)

Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.
  
|**Функция**|**План ATP 1**<br>(ранее в автономном режиме ATP)|**План ATP 2**<br>(ранее — аналитика угроз <br>Конфигурация | Office 365 корпоративный E5| 
|:-----|:-----|:-----|:-----|
| *Конфигурация, защита и обнаружение* | 
|Безопасные вложения |Да|Да |Да|
|Безопасные ссылки |Да|Да |Да | 
|Политики защиты от фишинга |Да |Да |Да |
|ATP для SharePoint, OneDrive и Microsoft Teams |Да |Да |Да|
|Безопасные ссылки в Teams |Да|Да |Да |
|Отчеты в режиме реального времени |Да |Да |Да|
|*Автоматизация, исследование, исправление и образование* |
|Журналы учета угроз |Нет |Да |Да |
|Проводник (Advanced Threat расследование) |Нет |Да |Да |
|Автоматическое исследование и ответ  |Нет |Да |Да |
|Симулятор атак |Нет |Да |Да |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Возможности Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Безопасные вложения

[Безопасное вложение ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) защищает от неизвестных вредоносных программ и вирусов и обеспечивает нулевую защиту для защиты системы обмена сообщениями. Все сообщения и вложения, не содержащие известную сигнатуру вируса или вредоносной программы, направляются в специальную среду, где ATP использует ряд методик машинного обучения и анализа для обнаружения преступных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик. 

### <a name="safe-links"></a>Безопасные ссылки

Функция [безопасных ссылок ATP](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) защищает пользователей от вредоносных URL-адресов в сообщении или в документе Office. Защита остается при каждом переходе по ссылке, поскольку вредоносные ссылки динамически блокируются, а безопасные ссылки остаются доступными.

### <a name="anti-phishing-policies"></a>Политики защиты от фишинга

[Защита от фишинга](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) проверяет входящие сообщения на наличие индикаторов, которые могут быть попыток фишинга. Когда пользователи охватываются политиками ATP (безопасные вложения, безопасные ссылки или защита от фишинга), входящие сообщения оцениваются с помощью нескольких моделей машинного обучения, которые анализируют сообщения и выполняют соответствующие действия на основе настроенных политик.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP для SharePoint, OneDrive и Microsoft Teams

[ATP для SharePoint, OneDrive и Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) помогает обнаруживать и блокировать файлы, которые определены как вредоносные на сайтах групп и библиотеках документов.

### <a name="real-time-reports"></a>Отчеты в режиме реального времени

Возможности мониторинга, доступные в центре безопасности Office 365 Security _Амп_, включают [отчеты в режиме реального времени и аналитические](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) сведения, которые позволяют администраторам системы безопасности и соответствия требованиям сосредоточиться на проблемах с высоким приоритетом, таких как атаки безопасности или Повышенная подозрительная активность. В дополнение к выделению проблемных областей, интеллектуальные отчеты и аналитические отчеты включают рекомендации и ссылки на просмотр и изучение данных, а также быстрое выполнение действий. 
  
### <a name="threat-trackers"></a>Журналы учета угроз

Средства [отслеживания угроз](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) представляют собой информативные элементы и представления, которые предоставляют авторизованным пользователям доступ к проблемам циберсекурити, которые могут повлиять на вашу организацию.

### <a name="explorer"></a>Explorer

[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (также называется обозревателем угроз) — это отчет в реальном времени, который позволяет авторизованным пользователям определять и анализировать последние угрозы. По умолчанию в этом отчете отображаются данные за прошедшие 7 дней; Однако представления можно изменить для отображения данных за прошедшие 30 дней. 

### <a name="attack-simulator"></a>Симулятор атак
  
[Имитатор атаки](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) позволяет авторизованным пользователям запускать сценарии с реалистичными атаками в Организации. Доступны различные виды атак, включая отображаемое имя спеар-фишинга, атаки с использованием пароля и атаки методом грубой силы пароля.