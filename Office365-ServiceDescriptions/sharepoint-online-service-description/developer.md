---
title: Разработчик
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-developer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 415c9536-ae70-4d4b-b481-5255cb03cc32
description: SharePoint Online это набор средств и технологий, основанных на веб-технологиях, которые помогают организациям хранить, совместно использовать цифровые данные и управлять ими. Эта размещенная служба, основанная на Microsoft SharePoint Server 2013, идеально подходит для работы с проектами, хранения данных и документов в централизованном расположении и обмена информацией с другими. Следующие функции подойдут разработчикам, которые хотят создавать приложения и решения для расширения функциональности SharePoint.
ms.openlocfilehash: 56ea1e5a083c4dd35eab8da537b77e802551ce32
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/26/2019
ms.locfileid: "39263120"
---
# <a name="developer"></a>Developer

SharePoint Online это набор средств и технологий, основанных на веб-технологиях, которые помогают организациям хранить, совместно использовать цифровые данные и управлять ими. Эта размещенная служба, основанная на Microsoft SharePoint Server 2013, идеально подходит для работы с проектами, хранения данных и документов в централизованном расположении и обмена информацией с другими. Следующие функции подойдут разработчикам, которые хотят создавать приложения и решения для расширения функциональности SharePoint.
  
## <a name="app-catalog-sharepoint"></a>Каталог приложений (SharePoint)

Публикуйте свои приложения во внутреннем корпоративном каталоге, размещенном на сервере, на котором выполнено развертывание SharePoint, для пользователей с доступом к SharePoint на этом сервере. Подробнее о [публикации приложений для Office и SharePoint](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store).
  
## <a name="app-deployment-cloud-hosted-apps"></a>Развертывание приложений: приложения, размещаемые в облаке

Приложения для SharePoint, размещаемые в облаке, содержат хотя бы один удаленный компонент, а также могут содержать компоненты, размещаемые в SharePoint. Подробнее о [вариантах размещения приложений для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in). 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>Развертывание приложений: приложения, размещаемые в SharePoint

Приложения, размещаемые в SharePoint, позволяют повторно использовать общие артефакты SharePoint, такие как списки и веб-части. Если выбрать такой подход, можно использовать только JavaScript, и невозможно использовать серверные коды. Подробнее о [вариантах размещения приложений для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in).
  
## <a name="app-management-service"></a>Служба управления приложениями

В базе данных службы управления приложениями хранятся сведения о лицензировании всех приложений для SharePoint. 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: внешние типы контента с областью действия приложений (ECT)

С добавлением новой модели приложений в SharePoint службы Business Connectivity Services (BCS) теперь могут заключать внешние типы контента на уровне приложения, а не на уровне фермы. Это обеспечивает большую гибкость для разработчиков приложений, позволяя им использовать внешние данные в своих приложениях. Узнайте больше о [типах внешних контента с областью действия приложений](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint).
  
## <a name="bcs-business-data-web-parts"></a>BCS: веб-части бизнес-данных

Веб-части бизнес-данных — это специальные веб-части, работающие с внешними данными. Они используются как стандартные веб-части SharePoint, но основаны на внешних типах контента, которые являются XML-описаниями подключений к внешним данным. 
  
## <a name="bcs-external-list"></a>BCS: внешний список

Внешний список  это особый вид списка SharePoint, в котором отображаются данные из внешнего источника данных. Он построен на внешнем типе контента, который описывает источник данных, и позволяет пользователям работать с данными в знакомом интерфейсе SharePoint. Узнайте больше о [внешних типах контента](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution). 
  
## <a name="bcs-odata-connector"></a>BCS: Соединитель OData

Соединитель OData — новый элемент SharePoint. Он позволяет службам Business Connectivity Services (BCS) использовать конечную точку для RESTFUL в качестве источника данных для внешних списков, веб-частей бизнес-данных и настраиваемых пользовательских интерфейсов.
  
## <a name="bcs-rich-client-integration"></a>BCS: Расширенная интеграция клиентов

Недоступно для клиентов SharePoint Online. Business Connectivity Services (BCS) использует бесплатный клиент и серверную архитектуру, которая позволяет клиентам Office, таким как Outlook и Excel, работать непосредственно с внешними данными, открытыми для SharePoint через внешние типы контента. Узнайте больше о [клиентской среде Business Connectivity Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14)).
  
## <a name="client-object-model-om"></a>Клиентская объектная модель (OM)

SharePoint 2013 имеет три клиентские объектные модели для управляемого кода: .NET, Silverlight и mobile. Кроме того, SharePoint содержит клиентскую объектную модель JavaScript. Узнайте больше о [том, как правильно выбрать набор API в SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint).
  
## <a name="custom-site-provisioning-page"></a>Страница подготовки настраиваемого сайта

Недоступно для пользователей SharePoint Online. Пользователи SharePoint Server 2013 получают быстрый и простой способ осуществления запросов сайта и могут начать пользоваться своими сайтами в короткий срок.
  
## <a name="developer-site"></a>Сайт разработчика

Используйте сайт разработчика Office 365 в качестве среды разработки и тестирования, чтобы сократить время настройки и начать создание, тестирование и развертывание приложений для SharePoint. Узнайте больше о [регистрации на сайте разработчика для Office 365](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription).
  
## <a name="forms-based-applications"></a>Приложения на основе форм

Представление формы  это, по существу, представление, которое содержит элементы управления. Приложение на основе форм позволяет пользователю создавать и использовать одну или несколько форм в приложении. Узнайте больше о [приложениях на основе форм](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60)).
  
## <a name="full-trust-solutions"></a>Решения с полным доверием

Не доступно для клиентов SharePoint Online. Пользователи SharePoint Server 2013 могут создавать решения с полным доверием (также называемые решениями фермы). В отличие от приложений для SharePoint, решения для фермы содержат код, который развертывается на серверах SharePoint и совершает вызовы объектной модели сервера SharePoint. Такие сборки всегда работают с полным доверием. Решения фермы нужно использовать для настройки административных функций SharePoint, таких как настраиваемые задания таймера, настраиваемые командлеты Windows PowerShell и расширения центра администрирования. Узнайте больше о [создании решений фермы в SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint).
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services

Служба форм предоставляет интерфейс веб-браузера в SharePoint, основанный на шаблонах форм, разработанных в InfoPath. Узнайте больше о [службах форм InfoPath Forms Services.](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))
  
## <a name="javascript-object-model"></a>Объектная модель JavaScript

SharePoint предоставляет объектную модель JavaScript для использования во встроенных сценариях или отдельных JS-файлах. Эта модель включает в себя те же функции, которые предоставляют клиентские объектные модели платформы .NET Framework и Silverlight. Объектная модель JavaScript представляет собой способ добавления настраиваемого кода SharePoint в приложение. Кроме того, он позволяет веб-разработчикам использовать свои собственные навыки JavaScript для создания приложений SharePoint с минимальной кривой обучения. Узнайте больше о [справке по API JavaScript для SharePoint 2013](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15)).
  
## <a name="remote-event-receiver"></a>Удаленный приемник событий

Для обработки событий в приложении для SharePoint разработчики могут создавать удаленные приемники событий и приемники событий приложения. Удаленные приемники событий обрабатывают события, происходящие с объектами приложения (например, списком, элементом списка или сайтом). Подробнее об [обработке событий в приложениях для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins). 
  
## <a name="rest-apis"></a>REST API

SharePoint 2013 обеспечивает выполнение веб-службы Representational State Transfer (REST), которая использует протокол OData для выполнения операций CRUD с данными списка SharePoint. Используется для доступа к данным SharePoint клиентских технологий, которые не используют JavaScript и не построены на платформах .NET Framework или Microsoft Silverlight. Узнайте больше о [программировании с использованием службы REST SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests).
  
## <a name="sharepoint-design-manager"></a>Дизайнер SharePoint

Дизайнер позволяет пошагово создавать проектные ресурсы, которые можно использовать для фирменного оформления сайтов. Загружайте проектные ресурсы  изображения, HTML, CSS и т. д.  и затем создавайте шаблонные страницы и макеты страниц. Узнайте больше о [разработке сайта SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development).
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013

С помощью SharePoint Designer опытные пользователи и разработчики могут быстро создавать решения SharePoint в соответствии с потребностями бизнеса. Узнайте больше о [SharePoint Designer для разработчиков](https://go.microsoft.com/fwlink/?LinkId=271294).
  
## <a name="sharepoint-framework"></a>SharePoint Framework

Платформа SharePoint Framework (SPFx) — это модель страниц и веб-частей, которая обеспечивает полную поддержку клиентской разработки SharePoint, простую интеграцию с данными SharePoint и поддержку инструментов с открытым кодом. Узнайте больше о [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview).
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>Рабочие процессы SharePoint 2010 (встроенные)

Используйте рабочие процессы из коробки, включенные в SharePoint, для моделирования общих бизнес-процессов.
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>Рабочие процессы SharePoint 2013 и SharePoint 2016

Рабочие процессы SharePoint 2013 и SharePoint 2016 на платформе Windows Workflow Foundation 4 (WF) были значительно переработаны в более ранних версиях. Возможно, наиболее заметной функцией новой инфраструктуры рабочих процессов является введение Azure в качестве узла выполнения рабочего процесса. Узнайте больше о [новых возможностях рабочих процессов для SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint).
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах Office 365, отдельных и локальных решениях, ознакомьтесь с [описанием службы SharePoint Online](sharepoint-online-service-description.md).
  

