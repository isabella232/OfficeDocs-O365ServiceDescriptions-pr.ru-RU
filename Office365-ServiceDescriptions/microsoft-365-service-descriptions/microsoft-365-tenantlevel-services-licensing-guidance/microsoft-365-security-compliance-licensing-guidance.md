---
title: Руководство по лицензированию Microsoft 365 для обеспечения соответствия & безопасности
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: В этой статье содержится руководство по лицензированию для обеспечения соответствия требованиям Microsoft 365, чтобы избежать потенциальных сбоев в обслуживании из-за нелицензирования доступа.
ms.openlocfilehash: 04ff448cd45ed81b17ed230547462c80d8c47669
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/07/2021
ms.locfileid: "49779993"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Руководство по лицензированию Microsoft 365 для обеспечения соответствия & безопасности

В рамках этой статьи служба на уровне клиента — это веб-служба, которая при покупке для любого пользователя в клиенте (в составе планов &mdash; Office 365 или Microsoft 365) активируется частично или полностью для всех пользователей в клиенте. &mdash; Хотя некоторые пользователи без лицензий могут получить доступ к службе технически, лицензия необходима для любого пользователя, который будет пользоваться этой службой.

> [!NOTE]
> Некоторые службы клиента в настоящее время не могут ограничивать преимущества определенными пользователями. Следует принять меры, чтобы ограничить преимущества службы лицензированными пользователями. Это позволит избежать потенциального нарушения работы службы в организации после того, как станут доступны целевые возможности.

Чтобы увидеть варианты лицензирования пользователей для получения преимуществ от функций соответствия требованиям Microsoft 365 с 1 апреля 2020 г., скачайте подробное сравнение лицензирования соответствия требованиям Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Защита идентификации Azure Active Directory

Защита идентификации Azure Active Directory — это функция плана Azure Active Directory Premium P2, которая позволяет обнаруживать потенциальные уязвимости, влияющие на удостоверения организации, настраивать автоматические ответы на обнаруженные подозрительные действия, связанные с удостоверениями вашей организации, а также исследовать подозрительные инциденты и принять соответствующие меры для их устранения.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Аналитики SecOps и специалисты по безопасности получают преимущества от объединения представлений помеченных пользователей и событий риска на основе алгоритмов машинного обучения. Конечные пользователи получают преимущества от автоматической защиты, предоставляемой условным доступом на основе рисков, и повышенной безопасности, предоставляемой с помощью уязвимостей.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Клиенты с лицензиями E1 и E3 смогут получить доступ только к базовой оценке защиты данных по умолчанию. Клиенты с лицензиями Office 365 E5/A5 и Microsoft 365 E5/A5 (включены в них для обеспечения соответствия требованиям, управления информационной защитой, а также для EDiscovery и аудита) смогут получить доступ к оценке базовых параметров защиты &amp; данных, GDPR, NIST 800-53 и ISO 27001. Настраиваемая функция оценки и аттестации уровня премиум зарезервированы для клиентов Office 365 E5/A5 и Microsoft 365 E5/A5. Premium assessments will be available for purchase during the first half of 2021 through VL, CSP, and WebDirect.  

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции защиты идентификации Azure AD включены на уровне клиента для всех пользователей в клиенте. Сведения о защите идентификации Azure AD см. в этой [теме.](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут определять область защиты идентификации Azure AD, назначая политики риска, определяющие уровень сброса паролей, и разрешая доступ только лицензированным пользователям. Инструкции по области развертывания Azure AD Identity Protection см. в инструкциях по настройке и [встроению политик риска.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Управление удостоверением Azure Active Directory

Управление удостоверениями Azure Active Directory позволяет сбалансировать потребности организации в безопасности и производительности сотрудников с правильными процессами и видимостью. Он использует управление правами, проверки доступа, привилегированное управление удостоверениями и политики использования, чтобы гарантировать, что нужные люди имеют правильный доступ к нужным ресурсам.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Управление удостоверениями Azure Active Directory повышает производительность пользователей, упрощая запрос доступа к приложениям, группам и Microsoft Teams в одном пакете доступа. Пользователи также могут быть настроены в качестве администраторов без участия администраторов. Для проверки доступа пользователи могут просмотреть членство в группах с интеллектуальными рекомендациями для регулярных действий.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security и Azure Active Directory Premium (план 2) предоставляют пользователям права на управление удостоверением Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Функции управления удостоверением Azure AD включены на уровне клиента, но реализуются для каждого пользователя. Сведения об управлении удостоверением Azure AD см. в сведениях об управлении [удостоверением Azure AD?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут назначать области управления удостоверениями Azure AD, назначая пакеты доступа, проверки доступа или привилегированное управление удостоверениями только лицензированным пользователям. Инструкции по области развертывания управления удостоверениями Azure AD см. в:

- [Требования к лицензиям на управление правами Azure AD](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Требования к лицензиям на проверку доступа Azure AD](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Требования к лицензиям для использования privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender для удостоверений

Microsoft Defender for Identity (прежнее имя Azure Advanced Threat Protection) — это облачная служба, которая помогает защитить корпоративные гибридные среды от различных типов сложных целевых кибератак и угроз внутри организации.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Аналитики SecOp и специалисты по безопасности получают преимущества от возможности Microsoft Defender для удостоверений обнаруживать и исследовать сложные угрозы, скомпрометировать удостоверения и вредоносные действия внутри компании. Конечные пользователи получают преимущества, отслеживая свои данные с помощью Microsoft Defender для удостоверений.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security и Microsoft Defender for Identity для пользователей предоставляют пользователям права на доступ к удостоверениям в Microsoft Defender.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции Microsoft Defender для удостоверений включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке Azure ATP см. в записи ["Создание экземпляра Microsoft Defender для удостоверений".](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

В настоящее время Microsoft Defender для служб идентификации не может ограничить возможности определенными пользователями. Необходимо лицензировать всех пользователей, которые вы собираетесь использовать.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender для Office 365

Microsoft Defender для Office 365 (прежнее — Office 365 Advanced Threat Protection) помогает защитить организации от сложных атак, таких как фишинг и вредоносное ПО нулевого дня. Microsoft Defender для Office 365 также предоставляет сведения о действиях, сопоставляет сигналы из широкого диапазона данных, помогая определять, определять приоритеты и предоставлять рекомендации по устранению потенциальных угроз.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Microsoft Defender для Office 365 защищает пользователей от сложных атак, таких как фишинг и вредоносные программы нулевого дня. Полный список служб, предоставляемых в планах 1 и 2, см. в [Microsoft Defender для Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы? 

Microsoft Defender для Office 365 планов 1 и 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5 и Microsoft 365 бизнес премиум предоставляют пользователю права на преимущества Microsoft Defender для Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции Microsoft Defender для Office 365 включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке политик Microsoft Defender для Office 365 для лицензированных пользователей см. в microsoft [Defender для Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Чтобы расширить область действия Microsoft Defender для Office 365, следуйте политикам развертывания безопасных ссылок и безопасных вложений:

- Сведения о настройке безопасных ссылок для лицензированных пользователей см. в подсети ["Безопасные ссылки" в Microsoft Defender для Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Сведения о настройке безопасных вложений для лицензированных пользователей см. в подсети "Безопасные вложения" в [Microsoft Defender для Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) — это подмножество Microsoft Cloud App Security с функциями, которые ограничены Office 365 и не имеют дополнительной безопасности для сторонних облачных приложений и служб IaaS.

OCAS позволяет организациям получить доступ к своим облачным приложениям и службам для повышения производительности, предоставляет сложную аналитику для выявления и борьбы с киберугрозами, а также позволяет контролировать передачу данных в &mdash; Office 365.

Сравнение функций см. в различиях [между Microsoft Cloud App Security и Office 365 Cloud App Security.](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

OCAS обнаруживает теневые ИТ-службы, обеспечивает защиту от угроз в Office 365 и может контролировать, какие приложения имеют разрешение на доступ к данным.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Office 365 E5/A3/A5/G5 предоставляет пользователю права на преимущества OCAS.
Дополнительные сведения см. в таблице [лицензирования Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции OCAS включены на уровне клиента для всех пользователей в клиенте.

Сведения о настройке службы см. в базовой настройке [Cloud App Security.](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут ограничить развертывания OCAS, чтобы обеспечить доступ к определенным приложениям и ограничить группы пользователей, отслеживаемую Office 365 Cloud App Security. Дополнительные сведения см. в [области развертывания.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) — это решение брокера безопасности облачного доступа (CASB), которое позволяет организациям получать доступ к своим облачным приложениям и службам, предоставляет сложную аналитику для выявления и борьбы с киберугрозами, а также позволяет контролировать передачу данных между любым облачным &mdash; приложением.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

MCAS обнаруживает и оценивает теневые ИТ-технологии, обеспечивает защиту от угроз в облачных приложениях от первого и третьего поставщиков, а также защищает информацию в облачных приложениях от первого и третьего поставщиков.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

McAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5 Compliance, and Microsoft 365 Information Protection and Governance предоставляют пользователям права на преимущества MCAS.

Azure AD P1 предоставляет пользователям права на использование возможностей обнаружения в MCAS.

Чтобы воспользоваться возможностями управления приложениями условного доступа в MCAS, пользователям также необходимо иметь лицензию на Azure Active Directory P1, которая входит в состав Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/ G3, Microsoft 365 E5/A5/G5 и Microsoft 365 E5/A5/G5 Security.

Чтобы воспользоваться преимуществами автоматического маркировки, пользователям необходимо иметь лицензию на Azure Information Protection P2, которая входит в состав Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5 Compliance и Microsoft 365 Information Protection and Governance.

Дополнительные сведения см. в таблице [лицензирования Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции MCAS включены на уровне клиента для всех пользователей в клиенте.

Сведения о настройке политик Microsoft Cloud App Security для лицензированных пользователей см. в обзоре [Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут область развертывания MCAS для лицензированных пользователей с помощью возможностей развертывания в области, доступных в службе. Дополнительные сведения см. в [области развертывания.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Диспетчер соответствия требованиям

Упрощение соответствия требованиям и снижение риска с помощью диспетчера соответствия требованиям. Диспетчер соответствия требованиям помогает организациям соответствовать требованиям нормативных требований, стандартов, политик компании или других необходимых структур контроля.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Ниже следующую пользу для пользователей из службы диспетчера соответствия требованиям:

- Перевод сложных нормативов, стандартов, политик компании или других нужных структур контроля на простой язык
- Предоставляет доступ к большой библиотеке заметивных оценок и пользовательских оценок для удовлетворения уникальных потребностей в соответствии с соответствием требованиям
- Сопопока нормативных мер с рекомендуемой деятельностью по улучшению
- Предоставляет пошаговую инструкцию по реализации решений для удовлетворения нормативных требований
- Помогает пользователям определить приоритеты действий, которые будут иметь наивысшее влияние на их соответствие организации, связывая оценку с каждым действием

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Клиенты с лицензиями office 365 E5/A5 и Microsoft 365 E5/A5 смогут получить доступ к оценке базовых параметров защиты данных, GDPR, NIST 800-53 и ISO 27001, а также использовать настраиваемую функцию оценки. Премиум-оценки будут доступны для приобретения пользователям Office 365 E5/A5 и Microsoft 365 E5/A5 в первой половине 2021 г. Они будут доступны для покупки через VL, CSP и WebDirect.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Диспетчер соответствия требованиям по умолчанию предусмотрен для вашего клиента. Администраторы устанавливают разрешения пользователей и назначают роли, чтобы пользователи, не в том числе администраторы в организации, могли приступить к использованию диспетчера соответствия требованиям. Дополнительные сведения см. в [подстройки "Начало работы с](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)диспетчером соответствия требованиям": настройка разрешений пользователей и назначение ролей.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Доступ к диспетчеру соответствия требованиям управляется путем настройки разрешений пользователя и назначения ролей. Дополнительные сведения см. в [подстройки "Начало работы с](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)диспетчером соответствия требованиям": настройка разрешений пользователей и назначение ролей.

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender для конечной точки

Microsoft Defender для конечной точки (ранее ATP в Microsoft Defender) — это решение для обеспечения безопасности конечных точек, которое включает управление и оценку уязвимостей на основе рисков; возможности уменьшения поверхности атаки; защита нового поколения на основе поведения и на основе облака; обнаружение конечных точек и реагирование на них (EDR); автоматическое исследование и исправление; и службы управляемой охоты. Дополнительные узнать см. на странице "Microsoft Defender for [Endpoint".](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Какие пользователи получают преимущества от службы?

Лицензированные пользователи Windows 10 Корпоративная E5, Windows 10 для образовательных служб A5, Microsoft 365 E5 (M365 E5), в том числе Windows 10 Корпоративная E5, Microsoft 365 E5 Security, Microsoft 365 A5 (M365 A5), могут воспользоваться преимуществами Microsoft Defender для конечной точки.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Аналитики SecOps и специалисты по безопасности получают преимущества от возможностей защиты конечных точек в Microsoft Defender для конечной точки для профилактической защиты, обнаружения после нарушения безопасности, автоматического расследования и реагирования на сложные угрозы. Конечные пользователи получают преимущества от отслеживания вредоносных событий в Microsoft Defender для конечной точки.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции Microsoft Defender для конечных точек включены на уровне клиента для всех пользователей в клиенте. Сведения о развертывании [см. в подупоке "Этапы развертывания".](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Microsoft Defender for Endpoint administrators can use role-based access control (RBAC) to create roles and groups within the security operations team to grant appropriate access to the Microsoft Defender Security Center. Дополнительные сведения см. в под [управлением доступом на портале с помощью управления доступом на основе ролей.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="information-protection"></a>Защита информации

Защита информации помогает организациям обнаруживировать, классифицировать, пометить и защитить конфиденциальные документы и сообщения электронной почты. Администраторы могут определять правила и условия для автоматического применения меток, пользователи могут применять метки вручную или использовать сочетание этих двух меток, где пользователям даются рекомендации по их использованию.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователям полезно иметь возможность вручную применять метки конфиденциальности к своему содержимому или автоматически классифицировать их содержимое.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP (план 1) и план 2 AIP предоставляют пользователю права на ручное маркировку конфиденциальности.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP (план 1) и AIP (план 2) предоставляют пользователю права на применение и просмотр меток конфиденциальности в Power BI и защиту данных при экспорте из Power BI в Excel, PowerPoint или PDF. 

> [!NOTE]
> Power BI входит в состав Microsoft 365 E5/A5/G5; Во всех остальных планах power BI должна лицензироваться отдельно.

Microsoft 365 E5/A5/G5, соответствие требованиям Microsoft 365 E5/A5/G5, Защита информации Microsoft 365 и управление, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 и AIP (план 2) предоставляют пользователям права на автоматическое маркировку конфиденциальности.

Конкретные права по лицензии см. в подробном сравнении лицензирования соответствия требованиям Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Не включает права на автоматическую классификацию на основе машинного обучения (обучаемые классификаторы).

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции защиты информации включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке политик для лицензированных пользователей см. в подсети "Активация службы управления правами Azure".

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

За исключением случаев, когда используется функция сканера AIP, политики могут быть отредактированы для определенных групп или пользователей и реестров, чтобы запретить пользователям без лицензий запускать функции классификации или маркировки. Инструкции по области развертывания AIP см. в настройке политики [Azure Information Protection.](https://docs.microsoft.com/azure/information-protection/configure-policy)

Для функции сканера AIP корпорация Майкрософт не обязуется предоставлять возможности классификации файлов, маркировки и защиты пользователям, у которых нет лицензии.

## <a name="information-governance"></a>Управление информацией

Управление информацией помогает организациям управлять рисками путем обнаружения, классификации, маркировки и управления их данными. Управление информацией позволяет организациям соответствовать бизнес-требованиям и нормативным требованиям, а также уменьшить риск атаки, предоставляя возможности хранения и удаления данных Microsoft 365 и сторонних организаций.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи могут классифицировать данные в целях хранения, чтобы подкрепить определенные политики и нормативы.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 и автономные планы Exchange предоставляют пользователю права на ручное применение меток хранения без записей к данным почтовых ящиков.

Планы Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 и автономные планы SharePoint предоставляют пользователю права на ручное применение меток хранения без записей к файлам в SharePoint или OneDrive. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange (план 2) и архивация на базе Exchange Online предоставляют пользователю права на получение преимуществ базовой политики хранения почтовых ящиков на всей организации или в масштабе расположения и(или) ручное применение меток хранения к данным почтовых ящиков.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3 и SharePoint (план 2) предоставляют пользователю права на получение преимуществ базовой политики хранения SharePoint или OneDrive и(или) ручное применение метки хранения без записи к файлам в SharePoint или OneDrive.

Microsoft 365 E5/A5/E3/A3 и Office 365 E5/A5/E3/A3 предоставляют пользователю права на преимущества политики хранения Teams.

Microsoft 365 E5/A5, соответствие требованиям Microsoft 365 E5/A5, Защита информации и управление Microsoft 365, Office 365 E5/A5, и Office 365 Advanced Compliance предоставляет пользователю права на автоматическое применение меток или политик хранения, применение меток или политик хранения по умолчанию, начало периода хранения метки хранения на основе настраиваемого события, запуск проверки выровненности вручную в конце срока хранения метки, импорт сторонних данных через собственные соединители данных, объявление файла записи, обнаружение помеченного содержимого и отслеживание действий с меткой.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection и Управление предоставляют пользователю права на автоматическое применение меток хранения на основе обучаемых классификаторов.

Конкретные права по лицензии см. в подробном сравнении лицензирования соответствия требованиям Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции управления сведениями включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке управления сведениями для применения автоматической настройки и политик для лицензированных пользователей см. в подсети [Microsoft Information Governance в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Функции управления сведениями могут применяться к лицензированным пользователям в определенных расположениях (сайтах групп, сайтах групп и т. д.). Сведения о настройке управления сведениями для применения автоматической настройки и политик для лицензированных пользователей см. в подсети [Microsoft Information Governance в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>Управление записями

Управление записями помогает организациям выполнять свои бизнес-и нормативные обязательства по хранению записей путем обнаружения, классификации, маркировки, хранения и defensible удаления в своих данных Microsoft 365 и сторонних данных.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5, соответствие требованиям Microsoft 365 E5/A5, Защита информации и управление Microsoft 365, Office 365 E5/A5, Office 365 Advanced Compliance предоставляют пользователю права на управление записями, включая объявление элементов как записей, автоматическое применение меток хранения или записей и выполнение процессов проверки перед удалением (за исключением автоматического применения меток хранения на основе обучаемых классификаторов).

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection и Управление предоставляют пользователю права на автоматическое применение меток хранения или записей на основе обучаемых классификаторов.

Конкретные права по лицензии см. в подробном сравнении лицензирования соответствия требованиям Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи могут объявлять контент как запись и управлять полным процессом записей из определения и объявления политики посредством допустимого удаления.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции управления записями включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке управления записями для применения к лицензированным пользователям см. в сведениях об управлении записями [в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Функции управления записями можно применять к лицензированным пользователям в определенных расположениях (сайтах групп, сайтах групп и т. д.). Сведения о настройке управления записями для применения к лицензированным пользователям см. в сведениях об управлении записями [в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Соединители данных 

Корпорация Майкрософт предоставляет сторонние соединители данных, которые можно настроить в Центре соответствия требованиям Microsoft 365. Список соединитений данных, предоставляемых корпорацией Майкрософт, см. в таблице [сторонних соединитений данных.](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) В этой таблице также скомплены решения для обеспечения соответствия требованиям, которые можно применить к сторонним данным после импорта и архива данных в Microsoft 365, а также ссылки на пошаговых инструкций для каждого соединитела.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Основное преимущество использования соединители данных для импорта и архива сторонних данных в Microsoft 365 — возможность применения различных решений для обеспечения соответствия требованиям Microsoft 365 к данным после их импорта. Это гарантирует, что данные вашей организации, не относясь к Майкрософт, будут обеспечивать соответствие нормативным требованиям и стандартам, влияющим на вашу организацию.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Следующие лицензии предоставляют пользователю права на преимущества соединители данных:

- Microsoft 365 E5/A5
- Защита информации и управление данными в Microsoft 365 E5 или A5
- Соответствие требованиям Microsoft 365 E5 или A5
- Управление рисками для программы внутренней оценки Microsoft 365 E5/A5
- Microsoft 365 E5/A5 eDiscovery и аудит
- Office 365 E5/A5
- Office 365 Advanced Compliance

Для соединители данных в Центре безопасности и & соответствия требованиям M365, предоставляемые партнером Майкрософт, вашей организации потребуется деловые отношения с партнером, прежде чем вы сможете развернуть эти соединители.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Соединители настраиваются с помощью Центра безопасности & соответствия требованиям и каталога соединитеев.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Службы соединители данных — это значение на уровне клиента. Каждый пользователь, который должен воспользоваться преимуществами этой службы, должен иметь лицензию.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API Microsoft Graph для защиты от потери данных Teams (DLP)

Ранее в этом году мы объявили об общедоступных предварительных версиях API уведомлений об изменениях [Microsoft Graph для сообщений в Teams.](https://go.microsoft.com/fwlink/?linkid=2143888) Этот API позволяет разработчикам создавать приложения, которые могут прослушивать сообщения Microsoft Teams практически в режиме реального времени, и включить реализации сценариев DLP как для клиентов, так и для программных продуктов. Кроме того, API исправлений Microsoft Graph позволяет применять действия DLP к сообщениям Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

[Возможности защиты от потери данных (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) широко используются в Microsoft Teams, особенно по мере перехода организаций на удаленную работу. Если в вашей организации имеется политика DLP, вы можете определить политики, которые препятствуют обмену конфиденциальной информацией в канале Microsoft Teams или сеансе чата.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Чтобы получить поддержку защиты от lp в чате Teams, вам потребуется одна из следующих лицензий E5:

- Microsoft 365 E5/A5
- Соответствие требованиям Microsoft 365 E5 или A5
- Защита информации и управление Microsoft 365 E5/A5
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Доступ к API настраивается на уровне клиента.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

API Microsoft Graph для DLP Teams — это значение на уровне клиента. Каждый пользователь, который должен воспользоваться преимуществами этой службы, должен иметь лицензию.

## <a name="ediscovery"></a>Обнаружение электронных данных

EDiscovery предоставляет решения по анализу и обнаружению электронных данных для ИТ-отделов и юридических отделов корпораций для выявления, сбора, сохранения, сокращения и просмотра контента, связанного с расследованием или судебным процессом, перед экспортом из системы Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Advanced eDiscovery дает пользователю преимущества, когда он выбирается в качестве хранителя данных (лицо, у которого есть административный контроль над документом или электронным файлом) для дела.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 и Office 365 Advanced Compliance предоставляют пользователям права на основные функции eDiscovery.

Microsoft 365 E5/A5/G5, Соответствие требованиям Microsoft 365 E5/A5/G5, eDiscovery и аудит Microsoft 365 E5/A5, Office 365 E5/A5/G5 и Office 365 Advanced Compliance предоставляют пользователям права на расширенные eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции Advanced eDiscovery включены на уровне клиента для всех пользователей в клиенте, когда администраторы назначают разрешения на eDiscovery в Центре безопасности & соответствия требованиям.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы eDiscovery могут выбирать определенных пользователей в качестве хранителей данных для дела с помощью встроенного средства управления хранителями в Advanced eDiscovery, как описано в описании добавления хранителей в дело [Advanced eDiscovery.](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)

## <a name="office-365-customer-key"></a>Ключ клиента Office 365

С помощью ключа клиента вы управляете ключами шифрования вашей организации и настраивает Office 365 так, чтобы они использовались для шифрования неавтовых данных в центрах обработки данных Майкрософт. Другими словами, ключ клиента позволяет добавить уровень шифрования, принадлежащий вам, используя собственные ключи. Неавтомтные данные включают данные из Exchange Online и Skype для бизнеса, которые хранятся в почтовых ящиках и файлах в SharePoint Online и OneDrive для бизнеса.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи получают преимущества ключа клиента, шифруя свои неавтные данные на уровне приложения с помощью ключей шифрования, предоставляемых, контролируемых и управляемых собственной организацией.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 и Office 365 Advanced Compliance предоставляют пользователю права на преимущества ключа клиента. Чтобы получить все преимущества ключа клиента, необходимо также иметь подписку на Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Ключи шифрования ключа клиента Office 365 можно включить для всех данных, хранимых в почтовых ящиках Exchange Online и Skype для бизнеса, а также в файлах SharePoint Online, OneDrive для бизнеса и Teams. Дополнительные сведения о ключе клиента Office 365, в том числе о том, как начать работу, см. в сообщении о шифровании [службы с помощью ключа клиента.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

В Exchange Online и Skype для бизнеса почтовые ящики можно шифровать с помощью ключа клиента. Прежде чем использовать ключ клиента для Office 365, необходимо настроить Azure. Действия [по созданию](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) и настройке необходимых ресурсов Azure, а также по настройке ключа клиента в Office 365 см. в подстройке ключа клиента. После завершения настройки Azure определите, какую политику и, следовательно, какие ключи следует назначить почтовым ящикам и файлам в организации. Почтовые ящики и файлы, для которых вы не назначите политику, будут использовать политики шифрования, контролируемые и управляемые корпорацией Майкрософт. Дополнительные сведения о ключе клиента или общие сведения см. в сообщении о шифровании [службы с помощью ключа клиента.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Защищенное хранилище пользователя в Office 365

Блокировка клиентов обеспечивает дополнительный уровень контроля, предлагая клиентам возможность явной авторизации доступа для операций службы. Демонстрация того, что для явной авторизации доступа к данным имеются процедуры, служба блокировки клиентов также может помочь организациям выполнить определенные обязательства по обеспечению соответствия требованиям, такие как HIPAA и FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Блокировка клиентов гарантирует, что никто в корпорации Майкрософт не сможет получить доступ к содержимому клиента для выполнения операции обслуживания без явного утверждения клиента. Клиентский блокировок позволяет клиенту в процесс утверждения запросов на доступ к его содержимому. Иногда инженеры Майкрософт участвуют в процессе поддержки для устранения неполадок и устранения проблем, о проблемах, о которые сообщили клиенты. В большинстве случаев проблемы устранены с помощью обширных средств телеметрии и отладки, которые корпорация Майкрософт установила для своих служб. Однако в некоторых случаях инженеру майкрософт может потребоваться доступ к содержимому клиента для определения основной причины и устранения проблемы. Служба блокировки клиентов требует, чтобы инженер запрашивал доступ у клиента в качестве последнего шага в рабочий процесс утверждения. Это дает организациям возможность утверждать или отоать эти запросы, что дает им прямой контроль над тем, может ли инженер корпорации Майкрософт получать доступ к данным конечных пользователей организации.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, соответствие требованиям Microsoft 365 E5/A5/G5, Управление рисками для предварительной оценки Microsoft 365 и Office 365 Advanced Compliance предоставляют пользователям права на преимущества пользовательского фикса.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Администраторы могут включить блокировку клиентов в Центре администрирования Microsoft 365. Дополнительные сведения [см. в подзагоке "Блокировка клиента" в Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Если блок-блокировка клиента включена, корпорация Майкрософт должна получить утверждение организации перед доступом к контенту.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

В настоящее время служба клиентского почтового ящика не может быть ограничена определенными пользователями. Необходимо лицензировать всех пользователей, которые вы собираетесь использовать.

## <a name="privileged-access-management-in-office-365"></a>Управление привилегированным доступом в Office 365

[Управление привилегированным доступом (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) обеспечивает детальное управление доступом к привилегированным задачам администратора в Office 365. После включения PAM для выполнения задач с повышенными привилегиями пользователям потребуется запросить доступ в срок через рабочий процесс утверждения с высокой областью действия и временем.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Включение PAM позволяет организациям работать без постоянных привилегий. Пользователи получают преимущества от дополнительного уровня защиты от уязвимостей, возникающих из-за постоянного административного доступа, который обеспечивает неподтвержденный доступ к своим данным.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы? 

Office 365 E5/A5, Microsoft 365 E5/A5, Соответствие требованиям Microsoft 365 E5/A5 и Защита информации Microsoft 365 E5/A5 предоставляют пользователю права на преимущества PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции PAM включены на уровне клиента для всех пользователей в клиенте. Сведения о настройке политик PAM см. в руководстве ["Начало работы с управлением привилегированным доступом".](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Клиенты могут управлять PAM для каждого пользователя с помощью групп утверждения и политик доступа, которые могут применяться к лицензированным пользователям. Дополнительные сведения см. в [руководстве по управлению привилегированным доступом в Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="double-key-encryption-for-microsoft-365"></a>Шифрование с двойным ключом для Microsoft 365 

Шифрование с помощью двойного ключа для Microsoft 365 позволяет защитить высококонфиденциальную информацию в удовлетворении специальных требований и обеспечить полный контроль над ключом шифрования. В службе двойного шифрования ключей используются два ключа для защиты данных: один ключ в вашем элементе управления и второй ключ надежно хранится в Microsoft Azure. Для просмотра данных необходимо иметь доступ к обоим ключам. Так как корпорация Майкрософт может получить доступ только к одному ключу, ваш ключ и ваши данные недоступны корпорации Майкрософт, обеспечивая полный контроль над конфиденциальностью и безопасностью ваших данных.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи получают преимущества шифрования с помощью двойного ключа, так как могут перенести свои зашифрованные данные в облако, что препятствует доступу сторонних поставщиков, если ключ остается под контролем пользователей. Пользователи могут защищать и использовать содержимое, зашифрованное с помощью двойного ключа, аналогично любому другому защищенному содержимому с меткой конфиденциальности.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 и Office 365 Advanced Compliance предоставляют пользователям права на шифрование с двойным ключом.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Двойное шифрование ключей поддерживает классические версии Microsoft Office для Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Чтобы назначить ключи шифрования данным в организации Office 365 и(или) Microsoft 365 для лицензированных пользователей, следуйте инструкциям по развертыванию шифрования с двойным ключом.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Предотвращение потери данных в Office 365 для Exchange Online, SharePoint Online и OneDrive для бизнеса

Благодаря office 365 data loss prevention (DLP) для Exchange Online, SharePoint Online и OneDrive для бизнеса организации могут идентифицировать, отслеживать и автоматически защищать конфиденциальную информацию в электронных письмах и файлах (включая файлы, хранимые в хранилищах файлов Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи получают преимущества DLP для Exchange Online, SharePoint Online и OneDrive для бизнеса, когда их сообщения электронной почты и файлы проверяются на конфиденциальные сведения, настроенные в политике DLP организации.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 A1/E3/A3/Business, Office 365 E3/A3 и Office 365 Data Loss Prevention предоставляют пользователю права на защиту от потери данных Office 365 для Exchange Online, SharePoint Online и OneDrive для бизнеса.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию сообщения электронной почты Exchange Online, сайты SharePoint и учетные записи OneDrive включены в расположения *(рабочие нагрузки)* для этих функций DLP для всех пользователей в клиенте. Дополнительные сведения об использовании политик защиты от потери данных см. в обзоре защиты [от потери данных.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут настраивать расположения (рабочие нагрузки), включенных пользователей и исключенных пользователей в Центре безопасности & соответствия требованиям, в расположениях для защиты от **потери**  >  **данных.**

## <a name="communication-data-loss-prevention-for-teams"></a>Предотвращение потери данных для Teams

С помощью защиты от личных данных для Teams организации могут блокировать чаты и сообщения каналов, содержащие конфиденциальную информацию, например финансовые сведения, личные сведения, сведения о здоровье и другую конфиденциальную информацию.

### <a name="which-users-benefit-from-the-service"></a>Какие пользователи получают преимущества от службы?

Лицензированные пользователи Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 Information Protection и управления, а также Office 365 Advanced Compliance могут воспользоваться преимуществами защиты от lp для связи для Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Преимущество отправителей— наличие конфиденциальной информации в исходях чатах и сообщениях каналов проверяется на наличие конфиденциальной информации, настроенной в политике DLP организации.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию сообщения чата и канала Teams являются включенным *расположением (рабочей нагрузкой)* для этих функций DLP для всех пользователей в клиенте. Дополнительные сведения об использовании политик защиты от потери данных см. в обзоре защиты [от потери данных.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут настраивать расположения (рабочие нагрузки), включенных пользователей и исключенных пользователей в Центре безопасности & соответствия требованиям, в расположениях для защиты от **потери**  >  **данных.**

## <a name="information-barriers"></a>Информационные барьеры

Информационные барьеры — это политики, которые администратор может настроить, чтобы запретить отдельным лицам или группам общаться друг с другом. Это полезно, если, например, один отдел занимается сведениями, которые не должны быть общими для других отделов, или если группе необходимо запретить общение с внешними контактами. Политики информационных барьеров также препятствуют подыском и обнаружению. Это означает, что если вы попытаетесь связаться с кем-то, с кем не следует взаимодействовать, вы не найдете этого пользователя в средстве "Выбор людей".

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи получают преимущества расширенных возможностей соответствия требованиям информационных барьеров, когда им запрещено общаться с другими пользователями. Например:<br><br>

| Сценарий | Кому требуется лицензия? |
|:------|:------|:------|
| Две группы (группа 1 и группа 2) не могут взаимодействовать друг с другом (то есть пользователям группы 1 запрещено взаимодействовать с пользователями группы 2, а пользователям группы 2 запрещено взаимодействовать с пользователями группы &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1). | Пользователи в группах &nbsp; 1 и &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Insider Risk Management, Office 365 E5/A5 и Office 365 Advanced Compliance предоставляют пользователям права на преимущества информационных барьеров.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Администраторы создают политики информационных барьеров и управляют ими с помощью рабочихлетов PowerShell в Центре безопасности & соответствия требованиям. Чтобы создать политику информационных барьеров, администраторы должны быть назначены глобальному администратору Microsoft 365 корпоративный, глобальному администратору Office 365 или администратору соответствия требованиям. По умолчанию эти политики применяются к всем пользователям в клиенте. Дополнительные сведения о информационных барьерах см. в информационных [барьерах в Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы могут настраивать расположения (рабочие нагрузки), включенных пользователей и исключенных пользователей в Центре безопасности & соответствия требованиям. Например, если у всех пользователей есть лицензия на Office 365 E3 и ни у одного из них нет лицензий на Office 365 Advanced Compliance/E5, им не потребуется создавать политики информационных барьеров для организации. Дополнительные сведения [см. в информационных барьерах в Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Шифрование сообщений Office 365

Шифрование сообщений Office 365 (OME) — это служба, основанная на службе Azure RMS, которая позволяет отправлять шифрованные письма пользователям внутри или за пределами организации независимо от того конечного электронного адреса (Gmail, Yahoo! Mail, Outlook.com и т. д.).

Для просмотра зашифрованных сообщений получатели могут получить одноразовый пароль, войти с учетной записью Майкрософт либо войти с помощью рабочей или учебной учетной записи, связанной с Office 365. Получатели также могут отправлять зашифрованные ответы. Им не нужна подписка для просмотра зашифрованных сообщений или отправки зашифрованных ответов.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Отправителю сообщений предоставляется дополнительный контроль над конфиденциальными сообщениями, предоставляемыми службой шифрования сообщений Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E3/A3, Office 365 E3/A3 и Azure Information Protection (план 1) предоставляют пользователю права на использование шифрования сообщений Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Администраторы создают политики шифрования сообщений Office 365 и управляют ими в Центре администрирования Exchange в соответствии с **правилами потока обработки**  >  **почты.** По умолчанию эти правила применяются к всем пользователям в клиенте. Дополнительные сведения о настройке новых возможностей шифрования сообщений Office 365 см. в подстройки "Настройка новых возможностей [шифрования сообщений".](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы должны применять правила потока почты для шифрования сообщений Office 365 только к лицензированным пользователям. Дополнительные сведения об определении правил потока почты см. в подпишитесь на определение правил потока почты [для шифрования сообщений электронной почты.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Расширенное шифрование сообщений Office 365

Office 365 Advanced Message Encryption помогает клиентам выполнять обязательства по обеспечению соответствия требованиям, которые требуют более гибкого контроля над внешними получателями и их доступа к зашифрованным электронным письмам. С помощью расширенного шифрования сообщений администраторы могут управлять конфиденциальными сообщениями электронной почты, общими за пределами организации, с помощью автоматических политик, которые могут обнаруживать типы конфиденциальной информации (например, персональные данные, финансовые или медицинские коды) или использовать ключевые слова для повышения защиты путем применения пользовательских шаблонов электронной почты и истечения срока доступа к зашифрованным электронным письмам через безопасный веб-портал. Кроме того, администраторы могут дополнительно контролировать зашифрованные сообщения электронной почты, к которых был доступ через безопасный веб-портал, отменив доступ в любое время.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Отправителю сообщений предоставляется дополнительный контроль над конфиденциальными сообщениями электронной почты, предоставляемый расширенным шифрованием сообщений.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Office 365 E5/A5, Microsoft 365 E5/A5, соответствие требованиям Microsoft 365 E5/A5, Защита информации и управление Microsoft 365, а также office 365 Advanced Compliance предоставляют пользователям права на расширенные шифрования сообщений.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Администраторы создают политики advanced Message Encryption и управляют ими в Центре администрирования Exchange в соответствии **с правилами потока обработки**  >  **почты.** По умолчанию эти правила применяются к всем пользователям в клиенте. Дополнительные сведения о настройке новых возможностей шифрования сообщений см. в дополнительных сведениях о настройке новых возможностей шифрования [сообщений Office 365.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы должны применять правила потока почты для advanced Message Encryption только к лицензированным пользователям. Дополнительные сведения об определении правил потока почты см. в подпишитесь на определение правил потока почты для шифрования сообщений электронной почты [в Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Соответствие требованиям к обмену данными

Соответствие коммуникации в Microsoft 365 помогает свести к минимуму риски для связи, помогая обнаруживать, захватывать и принимать меры по исправлению недопустимых сообщений в организации. Вы можете определить определенные политики, которые захватывают внутреннюю и внешнюю электронную почту, Microsoft Teams или сторонние коммуникации в вашей организации. Проверяющие могут принять соответствующие меры по исправлению, чтобы убедиться, что они соответствуют стандартам сообщений вашей организации.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Специалисты по обеспечению соответствия требованиям получают преимущества от этой службы, отслеживая коммуникации организации с помощью политик соответствия требованиям к коммуникациям.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance и Microsoft 365 Insider Risk Management предоставляют пользователю права на соответствие требованиям к данным.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

Администраторы и специалисты по обеспечению соответствия требованиям создают политики соответствия требованиям в Центре соответствия требованиям Microsoft 365. Эти политики определяют, какие сообщения и пользователи подлежат проверке в организации, определяют настраиваемые условия, которые должны соответствовать коммуникациям, и указывают, кто должен выполнять проверки.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Администраторы выбирают определенных пользователей или группы, которые необходимо включить в политику соответствия требованиям к коммуникациям. При выборе группы они также могут выбрать определенных пользователей в группе, которые будут исключены из политики соответствия требованиям к коммуникациям. Дополнительные сведения о политиках соответствия требованиям к коммуникациям см. в сведениях о том, как начать работу с соответствием требованиям в Отношении связи [в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Управление внутренними рисками

Управление внутренними рисками — это решение в Microsoft 365, которое помогает свести к минимуму внутренние риски, позволяя обнаруживать, исследовать и принимать меры в отношении рискованных действий в организации.

Настраиваемые политики позволяют обнаруживать вредоносные и непреднамеренные рискованные действия в организации, в том числе при необходимости переадружать дела в службу Microsoft Advanced eDiscovery. Аналитики рисков в организации могут быстро принять соответствующие меры, чтобы убедиться, что пользователи соответствуют стандартам соответствия вашей организации.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Пользователи получают преимущества, отслеживая свою деятельность на наличие риска.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Какие лицензии предоставляют пользователю права на преимущества службы?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance и Microsoft 365 Insider Risk Management предоставляют пользователю права на преимущества управления рисками для программы оценки.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

В Центре соответствия требованиям Microsoft 365 должны быть созданы и назначены пользователям политики управления рисками для участников программы.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

При создании политики в Центре соответствия требованиям Microsoft 365 на  странице "Выбор пользователей и групп" выберите "Выбрать пользователей или группы", чтобы  выбрать только лицензированных пользователей, или, если у всех пользователей есть лицензия, можно выбрать "Все пользователи и группы с включенной поддержкой почты".  Дополнительные сведения см. в руководстве ["Начало работы с управлением рисками внутри организации".](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Политики условного доступа

Условный доступ — это средство, используемое Azure Active Directory для совместной работы сигналов, принятия решений и применения политик организации. Условный доступ находится в основе управления на основе удостоверений. Политики условного доступа — это, по крайней мере, простые, утверждения if-then. Если пользователь хочет получить доступ к ресурсу, ему необходимо выполнить действие. Пример: менеджер по зарплате хочет получить доступ к приложению для ведомости и должен выполнить многофакторную проверку подлинности для доступа к нему.

### <a name="which-users-benefit-from-the-service"></a>Какие пользователи получают преимущества от службы?

Лицензированные пользователи Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium и Azure Active Directory Premium (план 1) могут воспользоваться политиками условного доступа. Лицензированные пользователи Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security и Azure Active Directory Premium (план 2) могут воспользоваться преимуществами защиты идентификации (политики условного доступа на основе рисков).

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Аналитики операций безопасности и специалисты по безопасности получают преимущество, имея возможность применять политики организации к пользователям, требуя от них выполнения определенных критериев перед предоставлением доступа к корпоративному контенту. Конечные пользователи получают доступ к своей работе везде и по своему выбору, защищая ресурсы организации.

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию функции условного доступа включены на уровне клиента для всех пользователей в клиенте.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

В частности, для защиты идентификации и условного доступа пользователь должен быть включен в группу или добавлен в политику условного доступа. Условие пользователей и групп является обязательным в политике условного доступа. В политике можно выбрать либо всех пользователей, **либо** определенных пользователей и группы. Следует выбирать только соответствующих лицензированных пользователей и группы. Дополнительные сведения см. в [под вопросе "Условный доступ: условия".](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)

## <a name="advanced-audit"></a>Расширенный аудит

Расширенный аудит в Microsoft 365 обеспечивает однолетний срок хранения журналов аудита для действий пользователей и администраторов и позволяет создавать настраиваемые политики хранения журнала аудита для управления хранением журнала аудита для других служб Microsoft 365. Кроме того, он предоставляет доступ к важным событиям для расследований и доступ к API действий управления Office 365 с высокой пропускной способностью. Дополнительные сведения см. в [дополнительных сведениях об аудите в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

Вы также можете включить срок хранения в 10 лет с помощью SKU надстройки. SKU надстройки потребуется с начала 2021 г.

### <a name="which-users-benefit-from-the-service"></a>Какие пользователи получают преимущества от службы?

Лицензированные пользователи Office 365 E5, Microsoft 365 E5, соответствия требованиям Microsoft 365 E5 и службы eDiscovery и аудита Microsoft 365 могут воспользоваться расширенным аудитом.

Лицензированные пользователи с расширенным аудитом и 10-летней надстройой хранения журнала аудита могут воспользоваться преимуществами 10-летнего хранения журнала аудита.

### <a name="how-do-users-benefit-from-the-service"></a>Преимущества службы для пользователей

Расширенный аудит дает пользователям преимущества, так как записи аудита, связанные с действиями пользователей в службах Microsoft 365, могут храниться в течение одного года. Кроме того, занося в журнал события аудита с высоким значением, такие как доступ или чтение элементов в почтовом ящике пользователя. Дополнительные сведения см. в [дополнительных сведениях об аудите в Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Как служба была размещена или развернута?

По умолчанию расширенный аудит включен на уровне клиента для всех организаций с подпиской на Office 365 или Microsoft 365 E5 и автоматически предоставляет однолетний срок хранения журналов аудита для действий (выполняемых пользователями с соответствующей лицензией) в Azure Active Directory, Exchange и SharePoint. Кроме того, организации могут использовать политики хранения журнала аудита для управления периодом хранения записей аудита, созданных действиями в других службах Microsoft 365. 10-летнее хранение журнала аудита также включено с помощью тех же политик хранения. Дополнительные сведения см. в статье [Управление политиками хранения журнала аудита](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Как служба может применяться только к пользователям клиента, у которых есть лицензия на службу?

Однолетний срок хранения журналов аудита и аудит важных событий применяется только к пользователям с соответствующей лицензией. Кроме того, администраторы могут использовать политики хранения журнала аудита, чтобы указать более короткие сроки хранения для журналов аудита определенных пользователей.

10-летнее хранение журналов аудита применяется только к пользователям с соответствующей лицензией на надстройки. SKU надстройки потребуется с начала 2021 г.
