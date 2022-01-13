---
title: Описание службы защиты информации Azure
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Microsoft Azure защиты информации (AIP) помогает организациям открывать, классифицировать, маркировать и защищать конфиденциальные документы и электронные письма.
ms.openlocfilehash: b5c5848b6cb7fc44dd744c5aed0a320c0809aa60
ms.sourcegitcommit: 7b178adab989723e535f18fb8509e2c9eb9ea607
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/13/2022
ms.locfileid: "62028771"
---
# <a name="azure-information-protection-service-description"></a>Описание службы защиты информации Azure

Microsoft Azure защиты информации (AIP) помогает организациям открывать, классифицировать, маркировать и защищать конфиденциальные документы и электронные письма. Администраторы могут определять правила и условия автоматического применения меток, пользователи могут применять метки вручную или использовать сочетание этих двух меток, где пользователям даются рекомендации по использованию меток. Пользователи также могут использовать возможность вручную применять метки конфиденциальности к своему содержимому или автоматически классифицировать их содержимое. Дополнительные сведения см. [в видеоролике Что такое Azure Information Protection?](/azure/information-protection/what-is-information-protection)

## <a name="available-plans"></a>Доступные планы

Microsoft Azure защиты информации можно приобрести как в качестве автономных, так и через один из следующих пакетов лицензирования Майкрософт: Microsoft 365 корпоративный планы, Microsoft 365 план соответствия требованиям (включает Azure Information Protection P2), Microsoft 365  Бизнес (включает Azure Information Protection P1), Enterprise Mobility + Security планы. Следующие планы защиты информации Azure предлагаются в качестве лицензии подписки на пользователя: Plan 1 (M365 A3, Enterprise Mobility + Security A3 и M365 бизнес-премиум) и Plan 2 (M365 A5, Enterprise Mobility + Security A5) и AIP для O365 (O365 A3/A5). Подробные сведения о планах по подпискам, которые позволяют пользователям для Azure Information Protection, см. сравнение бизнес-плана [M365,](https://aka.ms/M365BusinessPlans)сравнение [плана M365 Enterprise m365](https://aka.ms/M365EnterprisePlans) и сравнение плана [M365.](https://aka.ms/EDU-Plan-Comparison)

## <a name="feature-availability"></a>Доступность функций

В таблице ниже перечислены функции защиты информации Azure, доступные в планах (применяются определенные оговорки , см. сноски для получения дополнительных сведений). Таблица может изменяться без уведомления. Перейдите в [полную таблицу сопоставления](https://go.microsoft.com/fwlink/?linkid=2139145)  подписок для основного списка функций Azure Information Protection в планах.

| Компонент | Azure Information Protection for Office 365 | Azure Information Protection Premium P1 | Azure Information Protection Premium P2 |
|---------|---------|---------|---------|
| Потребление контента Azure Information Protection с помощью учетных записей для работы или школы из приложений и служб, учитывая политику AIP | Да | Да | Да |
| Bring Your Own Key (BYOK) для управляемого клиента жизненного цикла обеспечения ключа<sup>2</sup>     | Да | Да | Да |
| Настраиваемые шаблоны, в том числе ведомствальные. | Да | Да | Да |
| Защита локального контента Exchange и SharePoint через соединители управления правами | Да | Да | Да |
| Создание контента Azure Information Protection с помощью рабочих или школьных учетных записей | Да | Да | Да |
| Интеграция с шифрование сообщений Office 365 | Да | Да | Да |
| Административный<sup>контроль 3</sup> | Да | Да | Да |
| Защита для форматов Microsoft Office файлов, включая PTXT, PJPG и PFILE (общая защита) | Нет | Да | Да |
| Ручная, по умолчанию и обязательная классификация документов | Нет | Да | Да |
| Сканер azure Information Protection для обнаружения контента для локального файла, совпадающий с любым из типов конфиденциальной информации | Нет | Да | Да |
| Сканер Azure Information Protection для применения метки для всех файлов локального файлового сервера или репозитория | Нет | Да | Да |
| Отслеживание и отзыв документов | Нет | Да | Да |
| Microsoft Information Protection программного обеспечения (SDK) для применения меток и защиты к электронным письмам и файлам для всех платформ — Windows, iOS, Mac OSX, Android и Linux | Нет | Да | Да |
| Настройка условий автоматической и рекомендуемой классификации | Нет | Нет | Да |
| Установите метки для автоматического применения предварительно настроенной защиты S/MIME в Outlook | Нет | Нет | Да |
| Управление oversharing информации при использовании Outlook (предупреждать, оправдывать или блокировать сообщения электронной почты) | Нет | Нет | Да |
| Удержание собственного ключа (HYOK), который охватывает Azure Information Protection и Active Directory (AD) Для строго регулируемых сценариев | Нет | Нет | Да |
| Шифрование с двойным ключом (DKE) | Нет | Нет | Да |
| Сканер Azure Information Protection для автоматической классификации, маркировки и защиты поддерживаемых локального файлов | Нет | Нет | Да |

> <sup>1</sup> Некоторые Office 365 также включают защиту данных с помощью Microsoft Azure защиты информации. Сведения об этих Office 365 подписках и возможностях защиты данных, которые они включают, обратитесь к таблице лицензий [Azure Information Protection.](https://download.microsoft.com/download/E/C/F/ECF42E71-4EC0-48FF-AA00-577AC14D5B5C/Azure_Information_Protection_licensing_datasheet_EN-US.pdf)
<br/><sup>2 Подписка</sup> Azure, необходимая для использования настроенного ключа для Bring Your Own Key (BYOK).
<br/><sup>3</sup> Включает активацию или отключение службы, управление бортовой частью для поэтапного развертывания, ведение журнала использования, супер возможности пользователей для проверки электронных данных и восстановления данных, массовую защиту и незащищенность файлов.

## <a name="free"></a>Свободна

Единственной функцией, доступной для свободного плана, является потребление контента Azure Information Protection с помощью учетных записей для работы или школы из приложений и служб, учитывая политику AIP. Подписка на самообслужительство для пользователей в организации, которым были отправлены конфиденциальные файлы, защищенные azure Information Protection, но не может быть аутентификацией, так как ИТ-отдел пользователей не управляет учетной записью в Azure, например, ИТ-отдел не имеет Office 365 или использует службы Azure.

## <a name="learn-more"></a>Подробнее

### <a name="azure-information-protection-details"></a>Сведения о защите информации Azure

- **Служба управления правами** [Azure (Azure RMS)](/azure/information-protection/what-is-azure-rms) предоставляет технологию защиты данных для Azure Information Protection. Azure RMS можно использовать с классификацией и маркировкой или самостоятельно.
- **Сканер AIP или клиент.** Вы должны иметь план Azure Information Protection для классификации, маркировки и защиты с помощью сканера или клиента Azure Information Protection. Дополнительные сведения см. в [Microsoft 365](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection)руководства по лицензированию & [безопасности,](https://go.microsoft.com/fwlink/?linkid=2139145) сравнение современного плана работы (загрузка PDF), Azure Active Directory [цены | Microsoft Security](https://www.microsoft.com/security/business/identity-access-management/azure-ad-pricing).
- [**Калькулятор.**](https://azure.microsoft.com/pricing/calculator/?service=information-protection)Оценка ежемесячных расходов на службы Azure.
- [**Документация.**](/azure/information-protection/)Просмотрите технические учебники, видео и дополнительные ресурсы.
- **Azure Information Protection** не включает права на автоматическую классификацию на основе Машинное обучение (обучаемые классификаторы).
- **Шифрование** с двойным ключом. Дополнительные сведения о шифровании двойных ключей для Microsoft 365 перейдите в информационную [защиту: двойное](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-double-key-encryption-for-microsoft-365) шифрование ключей для Microsoft 365.
- **Power BI** включен в Microsoft 365 E5/A5/G5; во всех остальных планах Power BI лицензироваться отдельно.
- [**Сведения о продукте.**](https://azure.microsoft.com/services/information-protection/)Дополнительные сведения о azure Information Protection.
- [**Часто задаваемые**](https://azure.microsoft.com/pricing/faq/)вопросы. Обзор цен Azure.
- **Scoping.** Кроме использования функции сканера AIP, политики могут быть распределены по определенным группам или пользователям, а реестры могут быть изменены, чтобы предотвратить запуск функций классификации или маркировки нелицензионных пользователей.
- **Метка конфиденциальности:** Дополнительные сведения перейдите в информационную [защиту:](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-sensitivity-labeling) маркировка конфиденциальности или проверьте сравнение современного плана [работы.](https://go.microsoft.com/fwlink/?linkid=2139145)
- **Планы подписки.** Дополнительные сведения о том, как можно приобрести или оценить azure Information Protection, а также различные функции, доступные для планов подписки, см. на сайте [Azure Information Protection.](https://www.microsoft.com/cloud-platform/azure-information-protection)  

### <a name="general-information"></a>Общие сведения

- **Доступность.** Корпорация Майкрософт по-прежнему привержена безопасности [](https://www.microsoft.com/trust-center/compliance/accessibility)ваших данных и   доступности наших служб. Дополнительные сведения см. в [центре доверия Майкрософт](https://www.microsoft.com/trust-center)и центре Office    [доступности.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
- Для **вопросов.** Если на ваш вопрос здесь не ответили, просмотрите часто задаваемые вопросы для [Azure Information Protection (AIP),](/azure/information-protection/faqs) которые специфи перечислены в классификации и маркировке, или специфические для защиты данных [(вопросы](/azure/information-protection/faqs-infoprotect)для классификации и [метки,](/azure/information-protection/faqs-rms)вопросы для защиты данных [,](/azure/information-protection/faqs-classic)вопросы часто задаваемого для классического клиента) или см. ссылки и ресурсы, перечисленные в сведениях и поддержке для Azure Information  [Information Protection](/azure/information-protection/information-support)  или обратитесь к руководителю учетной записи Майкрософт или [службе поддержки Майкрософт.](/azure/information-protection/information-support#to-contact-microsoft-support)
- **Условия лицензирования.** Условия лицензирования продуктов и служб, приобретенных через программы лицензирования коммерческих объемов Корпорации Майкрософт, см. на сайте [Условия продукта.](https://www.microsoft.com/licensing/terms/)
- **Сообщения.** Чтобы быть в курсе предстоящих изменений, в том числе новых и измененных функций, планового обслуживания или других важных объявлений, посетите Центр сообщений. Подробнее см. в [Центре сообщений](/microsoft-365/admin/manage/message-center).
- **Поддержка & SLA.** Если у вас есть какие-либо вопросы или требуется помощь, посетите  [службу поддержки Azure](https://azure.microsoft.com/support/options)и выберите службу самопослужки или любой другой метод, чтобы связаться с   нами для поддержки. Мы гарантируем, что конечные пользователи смогут создавать и потреблять IRM-документы и электронные письма в 99,9% случаев. Чтобы узнать больше, посетите [страницу SLA.](/learn/modules/choose-azure-services-sla-lifecycle)   Для поддержки и SLA в суверенных облаках обратитесь к локальной учетной записи.
