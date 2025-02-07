---
title: SharePoint для правительственных сред США
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Узнайте о доступности SharePoint для государственных облачных клиентов США.
ms.openlocfilehash: 762c6a097a8a150d80ce224b27da75146c8862f9
ms.sourcegitcommit: 1de205ecf7df78abe558d71f1c225087501382b4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/10/2022
ms.locfileid: "62523154"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint для правительственных сред США

В этой статье представлен обзор различий функций между облаком правительства США и коммерческим облаком, указанным в описании SharePoint [службы](../../sharepoint-online-service-description/sharepoint-online-service-description.md). SharePoint доступно для сред облако сообщества для государственных организаций (GCC), GCC High и DoD. 

Дополнительные сведения о правительственном облаке, в том числе о праве на покупку, см. в Microsoft 365 [government — как покупать](./microsoft-365-government-how-to-buy.md). Чтобы сравнить Office 365 для государственных организаций, см. Office 365 для государственных организаций [планы](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Чтобы узнать о необходимых конечных точках при управлении сетевыми подключениями, [](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) см. в Office 365 правительственных GCC высоких конечных точек или Office 365 конечных точек [doD правительства](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business) США.

Помимо возможностей и возможностей Office 365, организации могут воспользоваться следующими функциями, уникальными для облачной среды правительства США:

-   Содержимое клиентов организации логически изолировано от контента клиента в коммерческих Office 365 от Microsoft.
-   Контент клиентов вашей организации хранится в США.
-   Доступ к контенту клиентов вашей организации ограничен защищенным персоналом корпорации Майкрософт.
-   Правительственные облачные среды соответствуют сертификатам и аккредитациям, которые необходимы для клиентов государственного сектора США.

Наша цель — предоставить все SharePoint и функциональные возможности в правительственных облачных средах. Некоторые функции недоступны из-за требований клиентов правительственных облаков. Другие функции приходят в правительственные среды, но пока недоступны. В следующих разделах вы узнаете о доступности функций в облачных средах правительства.

## <a name="developer-features"></a>Возможности для разработчиков

Не существует известных различий между функциями разработчика для коммерческих клиентов и функциями разработчика для государственных облачных клиентов.

- Подключение к внешним приложениям, таким как источники данных для надстройок, ограничено источниками, расположенными в границах системной безопасности, поддерживаемых правительственной средой.
- Business Connectivity Services (BCS) поддерживается для сценариев подключения, в которых источники данных остаются недоступными в пределах границы безопасности облачной службы.

Если вы используете сторонние приложения на сайтах, просмотрите заявления о конфиденциальности и соответствии требованиям, предоставленные третьими сторонами при оценке надлежащего использования этих служб для вашей организации. Сторонние приложения и службы могут включать хранение, передачу и обработку данных клиентов вашей организации в сторонних системах, которые находятся вне государственного облака и поэтому не покрываются обязательствами по обеспечению соответствия требованиям и защите данных. 

## <a name="it-admin-features"></a>Функции ИТ-администрирования

Ниже представлены различия между функциями ИТ-администратора для коммерческих клиентов и функциями ИТ-администратора для государственных облачных клиентов.

- Изменение адреса сайта не доступно для клиентов GCC high.
- Средство SharePoint и диспетчер миграции требуют изменения конфигурации. Дополнительные сведения см. в [правительственной облачной поддержке SPMT](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io еще не поддерживается.
- Multi-geo не доступен для всех клиентов правительственных облаков.
- На домашней странице центра администрирования SharePoint для клиентов GCC High и DoD недоступны следующие карточки: SharePoint, использование SharePoint сайта, использование OneDrive, SharePoint активности файлов и OneDrive файлов.
- [Отслеживаемая карта просмотра](/sharepoint/manage-sites-in-new-admin-center#track-a-view) недоступна в центре администрирования SharePoint для всех клиентов правительственных облаков.

Дополнительные сведения о миграции FastTrack см. в [описании Office 365 службы правительства США](./office-365-us-government.md#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Функции безопасности и соответствия требованиям

Не существует известных различий между функциями безопасности и соответствия требованиям для коммерческих клиентов и функциями безопасности и соответствия требованиям для государственных облачных клиентов.

Сведения об особенностях безопасности и соответствия требованиям см. в Microsoft 365 [инструкции по обеспечению соответствия требованиям &amp; безопасности](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance).

Сведения о Azure Active Directory правительственных функций см. в документации [Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Сведения о правительственных службах Azure Information Protection см. в описании [службы Azure information protection Premium.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

Сведения о SharePoint Syntex см. в SharePoint Syntex [service Description](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features).

## <a name="sites-and-content"></a>Сайты и контент

Ниже представлены различия между сайтами и функциями контента для коммерческих клиентов и веб-сайтами и функциями контента для государственных облачных клиентов:

- Веб-части, которые зависят от подключений к интернет-службам, таким как Amazon Kindle, Карты Bing, Twitter и YouTube, не будут работать так, как ожидалось
- Библиотека активов организации недоступна
- Graph функциональность SharePoint Online для GCC High в настоящее время отключена. Любая служба, которая опирается на microsoft Graph в настоящее время может быть недоступна
- Функции, которые зависят от подключений к интернет-службам, например вкладке образы акций, будут работать не так, как ожидалось.
- Уведомления для действий на файле и сайте недоступны
- Веб-часть новостей будет извлекать новости только с текущего сайта. Новости от выбранных сайтов или откатов новостей концентратора с связанных сайтов недоступны для GCC клиентов High и DoD

## <a name="search-features"></a>Функции поиска

Сведения о доступности определенных компонентов Поиск (Майкрософт) в GCC, GCC high и DoD можно найти в [следующей таблице](/MicrosoftSearch/microsoft-search-us-government-environments#microsoft-search-features).

## <a name="sharing-and-sync"></a>Совместное использование и синхронизация

Различия между коммерческим облаком и облачной средой правительства см. в разделе [Общий доступ к файлам](./gcc-high-and-dod.md#file-sharing).

## <a name="plan-for-governance"></a>Планирование управления

Переход в облако обеспечивает преобразующее впечатление со встроенными средствами управления администрированием. Определение требований к управлению и их удовлетворения. Перейдите [к плану управления для преобразования командной работы с Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) дополнительными сведениями. Вы найдете рекомендации по Office 365, SharePoint, Teams и других.

## <a name="deploy-sharepoint-for-collaboration"></a>Развертывание SharePoint для совместной работы

После развертывания организации в облаке правительства Microsoft США следуйте рекомендуемой схеме развертывания, описанной в центре ресурсов SharePoint [внедрения.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Обязательно вступать в диалог с чемпионами по управлению усыновлением и изменением.
Вы также можете работать с [FastTrack](https://www.microsoft.com/fasttrack) или выбранным партнером, чтобы выкатить службу для пользователей.
Посетите Центр [доверия Майкрософт](https://www.microsoft.com/trust-center) , чтобы узнать больше о том, как Корпорация Майкрософт подходит к обеспечению безопасности, конфиденциальности и соответствия требованиям, а также основных принципов, которые мы уполномочиваем организации обслуживать своих клиентов.

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>Настройка SharePoint службы поддержки мастера гибридной конфигурации для всех клиентов правительственных облаков

Мастер SharePoint конфигурации содержит поддержку гибридных SharePoint с помощью специальных сред SPO.

Чтобы сделать гибридные SharePoint доступными для этой среды, необходимо изменить значение **** параметра, связанного с.configсреды. См [. файл конфигурации редактирования](#editing-configuration-file).

> [!NOTE]
> Сведения о специальных средах SPO, для которых SharePoint гибридные функции, см. в [сайте Supported Environments](#supported-environments).

## <a name="editing-configuration-file"></a>Файл конфигурации редактирования

1. Установка или обновление мастера SharePoint конфигурации.
2. Перейдите к папке, в которой установлен мастер SharePoint конфигурации. Пример: `%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. Запустите **microsoft.online.cse.hybridsp.common.dll.config** в текстовом редакторе, например Блокнот.
Содержимое этого файла изображено на следующем скриншоте:

:::image type="content" source="../../media/content.png" alt-text="Содержимое в файле конфигурации":::

4. Изменение значения параметра `SPOEnvironmentType` .
5. Сохраните изменения в **microsoft.online.cse.hybridsp.common.dll.config** файле.
6. Повторно запустите мастер SharePoint конфигурации.
   Параметры применяются, и SharePoint гибридные функции доступны в настроенной среде SPO.

## <a name="supported-environments"></a>Поддерживаемые среды

SharePoint гибридные функции поддерживают следующие среды SPO:

- Public
- PPE
- GCC
- GccHigh
- DoD
- Пользовательские

Если клиент задает значение `SPOEnvironmentType` **Custom**, `AuthorityEndPoint``AADGraphEndPoint``MSGraphEndPoint` для этих конечных точек для пользовательской среды SPO используются клавиши и клавиши.

Если значение `SPOEnvironmentType` задано любому значению, кроме **Custom**, `AuthorityEndPoint``AADGraphEndPoint``MSGraphEndPoint` то клавиши и клавиши игнорируются, а мастер гибридной конфигурации SharePoint использует жесткие кодированные значения, соответствующие этим типам среды SPO.
