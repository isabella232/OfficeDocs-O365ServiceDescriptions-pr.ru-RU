---
title: Разработчик
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 05/20/2019
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
ms.openlocfilehash: c1b9bd6e86b14d8328edabc0ebf1d81fb592fb21
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342518"
---
# <a name="developer"></a>Для разработчиков

SharePoint Online это набор средств и технологий, основанных на веб-технологиях, которые помогают организациям хранить, совместно использовать цифровые данные и управлять ими. Эта размещенная служба, основанная на Microsoft SharePoint Server 2013, идеально подходит для работы с проектами, хранения данных и документов в централизованном расположении и обмена информацией с другими. Следующие функции подойдут разработчикам, которые хотят создавать приложения и решения для расширения функциональности SharePoint.
  
## <a name="app-catalog-sharepoint"></a>Каталог приложений (SharePoint)
<a name="bkmk_AppCatalogSharePoint"> </a>

Публикуйте свои приложения во внутреннем корпоративном каталоге, размещенном на сервере, на котором выполнено развертывание SharePoint, для пользователей с доступом к SharePoint на этом сервере. Подробнее о [публикации приложений для Office и SharePoint](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store).
  
## <a name="app-deployment-cloud-hosted-apps"></a>Развертывание приложений: приложения, размещаемые в облаке
<a name="bkmk_AppDeploymentCloudHostedApps"> </a>

Приложения для SharePoint, размещаемые в облаке, содержат хотя бы один удаленный компонент, а также могут содержать компоненты, размещаемые в SharePoint. Подробнее о [вариантах размещения приложений для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in). 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>Развертывание приложений: приложения, размещаемые в SharePoint
<a name="bkmk_AppDeploymentSharePointHostedApps"> </a>

Приложения, размещаемые в SharePoint, позволяют повторно использовать общие артефакты SharePoint, такие как списки и веб-части. Если выбрать такой подход, можно использовать только JavaScript, и невозможно использовать серверные коды. Подробнее о [вариантах размещения приложений для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in).
  
## <a name="app-management-services"></a>Службы управления приложениями
<a name="bkmk_AppManagementServices"> </a>

В базе данных службы управления приложениями хранятся сведения о лицензировании всех приложений для SharePoint. 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: Внешние типы контента (ECT) из области приложений
<a name="bkmk_AppScopedExternalContentTypes"> </a>

С добавлением новой модели приложений в SharePoint службы Business Connectivity Services (BCS) теперь могут заключать внешние типы контента на уровне приложения, а не на уровне фермы. Это обеспечивает большую гибкость для разработчиков приложений, позволяя им использовать внешние данные в своих приложениях. Подробнее о [внешних типах контента из области приложений](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint).
  
## <a name="bcs-business-data-web-parts"></a>BCS: веб-части бизнес-данных
<a name="bkmk_BCSBusinessDataWebparts"> </a>

Веб-части бизнес-данных — это специальные веб-части, работающие с внешними данными. Они используются как стандартные веб-части SharePoint, но основаны на внешних типах контента, которые являются XML-описаниями подключений к внешним данным. 
  
## <a name="bcs-external-list"></a>BCS: Внешний список
<a name="bkmk_BCSExternalList"> </a>

Внешний список  это особый вид списка SharePoint, в котором отображаются данные из внешнего источника данных. Он построен на внешнем типе контента, который описывает источник данных, и позволяет пользователям работать с данными в знакомом интерфейсе SharePoint. Узнайте больше о [внешних типах контента](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution). 
  
## <a name="bcs-odata-connector"></a>BCS: Соединитель OData
<a name="bkmk_OdataConnector"> </a>

Соединитель OData  новый элемент SharePoint. Он позволяет Business Connectivity Services (BCS) использовать конечную точку RESTful OData как источник данных для внешних списков, веб-частей бизнес-данных и настраиваемых интерфейсов пользователей.
  
## <a name="bcs-rich-client-integration"></a>BCS: Расширенная интеграция клиента
<a name="bkmk_BCSRichClientIntegration"> </a>

Недоступно для клиентов SharePoint Online. Business Connectivity Services (BCS) использует бесплатный клиент и серверную архитектуру, которая позволяет клиентам Office, таким как Outlook и Excel, работать непосредственно с внешними данными, открытыми для SharePoint через внешние типы контента. Узнайте больше о [клиентской среде Business Connectivity Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14)).
  
## <a name="client-object-model-om"></a>Клиентская объектная модель (OM)
<a name="bkmk_ClientObjectModel"> </a>

SharePoint 2013 имеет три клиентские объектные модели для управляемого кода: .NET, Silverlight и mobile. Кроме того, SharePoint содержит клиентскую объектную модель JavaScript. Узнайте больше о [том, как правильно выбрать набор API в SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint).
  
## <a name="custom-site-provisioning-page"></a>Страница подготовки настраиваемого сайта
<a name="bkmk_CustomSiteProvisioning"> </a>

Недоступно для пользователей SharePoint Online. Пользователи SharePoint Server 2013 получают быстрый и простой способ осуществления запросов сайта и могут начать пользоваться своими сайтами в короткий срок.
  
## <a name="developer-site"></a>Сайт разработчика
<a name="bkmk_DeveloperSite"> </a>

Используйте Сайт разработчика Office 365 как среду разработки и тестирования, чтобы сократить время настройки и начать создавать, тестировать и развертывать свои приложения для SharePoint. Узнайте больше о [регистрации на сайте разработчика Office 365](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription).
  
## <a name="forms-based-applications"></a>Приложения на основе форм
<a name="bkmk_FormsBasedApplications"> </a>

Представление формы  это, по существу, представление, которое содержит элементы управления. Приложение на основе форм позволяет пользователю создавать и использовать одну или больше форм в рамках приложения. Узнайте больше о [приложениях на основе форм](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60)).
  
## <a name="full-trust-solutions"></a>Решения с полным доверием
<a name="bkmk_FullTrustSolutions"> </a>

Недоступно для пользователей SharePoint Online. Пользователи SharePoint Server 2013 могут создавать решения с полным доверием. Такие решения также называются решениями фермы. В отличие от приложений для SharePoint, решения для фермы содержат код, который развертывается на серверах SharePoint и совершает вызовы объектной модели сервера SharePoint. Такие сборки всегда работают с полным доверием. Решения фермы нужно использовать для настройки административных функций SharePoint, таких как настраиваемые задания таймера, настраиваемые командлеты Windows PowerShell и расширения центра администрирования. Узнайте больше о [создании решений фермы в SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint).
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services
<a name="bkmk_InfoPathFormsServices"> </a>

Служба форм обеспечивает возможность заполнения форм веб-браузера в SharePoint на основании шаблонов форм, разработанных в InfoPath. Узнайте больше о [службах форм InfoPath Forms Services.](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))
  
## <a name="javascript-object-model"></a>Объектная модель JavaScript
<a name="bkmk_JavaScriptObjectModel"> </a>

SharePoint предоставляет объектную модель JavaScript для использования во встроенных сценариях или отдельных JS-файлах. Эта модель включает в себя те же функции, которые предоставляют клиентские объектные модели платформы .NET Framework и Silverlight. Объектная модель JavaScript представляет собой способ добавления настраиваемого кода SharePoint в приложение. Она также позволяет веб-разработчикам использовать имеющиеся навыки в JavaScript для создания приложений SharePoint с минимальной кривой обучения. Узнайте больше о [справке по API JavaScript для SharePoint 2013](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15)).
  
## <a name="remote-event-receiver"></a>Удаленный приемник событий
<a name="bkmk_RemoteEventReceiver"> </a>

Для обработки событий в приложении для SharePoint разработчики могут создавать удаленные приемники событий и приемники событий приложения. Удаленные приемники событий обрабатывают события, происходящие с объектами приложения (например, списком, элементом списка или сайтом). Подробнее об [обработке событий в приложениях для SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins). 
  
## <a name="rest-apis"></a>REST API
<a name="bkmk_RESTAPI"> </a>

SharePoint 2013 обеспечивает выполнение веб-службы Representational State Transfer (REST), которая использует протокол OData для выполнения операций CRUD с данными списка SharePoint. Используется для доступа к данным SharePoint клиентских технологий, которые не используют JavaScript и не построены на платформах .NET Framework или Microsoft Silverlight. Узнайте больше о [программировании с использованием службы REST SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests).
  
## <a name="sharepoint-design-manager"></a>Дизайнер SharePoint
<a name="bkmk_SharePointDesignerManager"> </a>

Дизайнер позволяет пошагово создавать проектные ресурсы, которые можно использовать для фирменного оформления сайтов. Загружайте проектные ресурсы  изображения, HTML, CSS и т. д.  и затем создавайте шаблонные страницы и макеты страниц. Узнайте больше о [разработке сайта SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development).
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013
<a name="bkmk_SharePointDesigner"> </a>

При помощи SharePoint Designer продвинутые пользователи и разработчики могут быстро создавать решения SharePoint в соответствии с потребностями бизнеса. Узнайте больше о [SharePoint Designer для разработчиков](https://go.microsoft.com/fwlink/?LinkId=271294).
  
## <a name="sharepoint-framework"></a>SharePoint Framework
<a name="bkmk_SharePointFramework"> </a>

Платформа SharePoint Framework (SPFx) — это модель страниц и веб-частей, которая обеспечивает полную поддержку клиентской разработки SharePoint, простую интеграцию с данными SharePoint и поддержку инструментов с открытым кодом. Узнайте больше о [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview).
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>Рабочие процессы SharePoint 2010 (встроенные)
<a name="bkmk_Worflow2010outofthebox"> </a>

Используйте рабочие процессы из коробки, включенные в SharePoint, для моделирования общих бизнес-процессов.
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>Рабочие процессы SharePoint 2013 и SharePoint 2016
<a name="bkmk_Workflow2013"> </a>

Рабочие процессы SharePoint 2013 и SharePoint 2016 на платформе Windows Workflow Foundation 4 (WF) были значительно переработаны в более ранних версиях. Возможно, наиболее заметной функцией новой инфраструктуры рабочих процессов является введение Azure в качестве узла выполнения рабочего процесса. Узнайте больше о [новых возможностях рабочих процессов для SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint).
  
## <a name="feature-availability"></a>Доступность функций
<a name="bkmk_Workflow2013"> </a>

Просмотреть функции, доступные в планах Office 365, отдельных и локальных решениях, можно в статье [Описание службы SharePoint Online](sharepoint-online-service-description.md).
  

