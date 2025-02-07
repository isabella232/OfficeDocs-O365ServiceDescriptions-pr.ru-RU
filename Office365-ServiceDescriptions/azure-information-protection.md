---
title: Описание службы Azure Information Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Microsoft Azure защиты информации (AIP) помогает организациям обнаруживая, классифицировать, маркировать и защищать конфиденциальные документы и электронные письма.
ms.openlocfilehash: 5fb4d05ffdfaaa2ff3e4c3743f2837c9f54f8009
ms.sourcegitcommit: abe0415471c224a3d6a1d2f1317b08f67166ba11
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/24/2022
ms.locfileid: "64403959"
---
# <a name="azure-information-protection-service-description"></a>Описание службы Azure Information Protection

Microsoft Azure защиты информации (AIP) помогает организациям обнаруживая, классифицировать, маркировать и защищать конфиденциальные документы и электронные письма. Администраторы могут определять правила и условия автоматического применения меток, пользователи могут применять метки вручную или использовать сочетание этих двух меток, где пользователям даются рекомендации по использованию меток. Пользователи также могут использовать возможность вручную применять метки конфиденциальности к своему содержимому или автоматически классифицировать их содержимое. Дополнительные сведения см. [в видеоролике Что такое Azure Information Protection?](/azure/information-protection/what-is-information-protection)

## <a name="available-plans"></a>Доступные планы

Microsoft Azure защиты информации можно приобрести как в качестве автономных, так и через один из следующих пакетов лицензирования Майкрософт: Microsoft 365 корпоративный планов, Microsoft 365 плана соответствия требованиям (включая Azure Information Protection P2), Microsoft 365  Бизнес (включает Azure Information Protection P1), Enterprise Mobility + Security планы. Следующие планы защиты информации Azure предлагаются в качестве лицензии подписки на пользователя: Plan 1 (Microsoft 365 A3, Enterprise Mobility + Security A3 и Microsoft 365 бизнес-премиум) и Plan 2 (Microsoft 365 A5, Enterprise Mobility + Security A5) и AIP для Office 365 A3/A5. Подробные сведения о планах по подпискам, которые позволяют пользователям для Azure Information [Protection, см](https://aka.ms/M365BusinessPlans). в Microsoft 365 сравнения бизнес-Microsoft 365 корпоративный [и Microsoft 365 для образования](https://aka.ms/M365EnterprisePlans) планирования.[](https://aka.ms/EDU-Plan-Comparison)

## <a name="feature-availability"></a>Доступность функций

В таблице ниже перечислены функции защиты информации Azure, доступные в планах (применяются определенные оговорки , см. сноски для получения дополнительных сведений). Таблица может изменяться без уведомления. Перейдите в [полную таблицу сопоставления](https://go.microsoft.com/fwlink/?linkid=2139145)  подписок для основного списка функций Azure Information Protection в планах.

| Функция | Защита информации Azure для Office 365 | Azure Information Protection Premium P1 | Azure Information Protection Premium P2 |
|---------|---------|---------|---------|
| Потребление контента Azure Information Protection с помощью учетных записей для работы или школы из приложений и служб, учитывая политику AIP | Да | Да | Да |
| Bring Your Own Key (BYOK) для клиентского цикла обеспечения жизненного цикла ключа с управлением <sup>клиентом2</sup>     | Да | Да | Да |
| Настраиваемые шаблоны, в том числе ведомствальные. | Да | Да | Да |
| Защита локального контента Exchange и SharePoint через соединители управления правами | Да | Да | Да |
| Создание контента Azure Information Protection с помощью рабочих или школьных учетных записей | Да | Да | Да |
| Интеграция с шифрование сообщений Office 365 | Да | Да | Да |
| Административный <sup>контроль3</sup> | Да | Да | Да |
| Защита для форматов Microsoft Office файлов, включая PTXT, PJPG и PFILE (общая защита) | Нет | Да | Да |
| Ручная, по умолчанию и обязательная классификация документов | Нет | Да | Да |
| Сканер azure Information Protection для обнаружения контента для локального файла, совпадающий с любым из типов конфиденциальной информации | Нет | Да | Да |
| Сканер Azure Information Protection для применения метки для всех файлов локального файлового сервера или репозитория | Нет | Да | Да |
| Отслеживание и отзыв документов | Нет | Да | Да |
| Microsoft Information Protection набор разработчика программного обеспечения (SDK) для применения меток и защиты к электронным письмам и файлам для всех платформ — Windows, iOS, Mac OSX, Android и Linux | Нет | Да | Да |
| Настройка условий автоматической и рекомендуемой классификации | Нет | Нет | Да |
| Установите метки для автоматического применения предварительно настроенной защиты S/MIME в Outlook | Нет | Нет | Да |
| Управление oversharing информации при использовании Outlook (предупреждать, оправдывать или блокировать сообщения электронной почты) | Нет | Нет | Да |
| Удержание собственного ключа (HYOK), который охватывает Azure Information Protection и Active Directory (AD) Для строго регулируемых сценариев | Нет | Нет | Да |
| Шифрование с двойным ключом (DKE) | Нет | Нет | Да |
| Сканер Azure Information Protection для автоматической классификации, маркировки и защиты поддерживаемых локального файлов | Нет | Нет | Да |

> <sup>1</sup> Некоторые Office 365 также включают защиту данных с Microsoft Azure защиты информации. Сведения об этих Office 365 подписках и возможностях защиты данных, которые они включают, обратитесь к таблице данных лицензирования информационной  [защитыAzure](https://download.microsoft.com/download/E/C/F/ECF42E71-4EC0-48FF-AA00-577AC14D5B5C/Azure_Information_Protection_licensing_datasheet_EN-US.pdf).
<br/><sup>2 Подписка</sup> Azure, необходимая для использования настроенного ключа для Bring Your Own Key (BYOK).
<br/><sup>3</sup> Включает активацию или отключение службы, управление бортовой частью для поэтапного развертывания, ведение журнала использования, супер возможности пользователей для проверки электронных данных и восстановления данных, массовую защиту и незащищенность файлов.

## <a name="free"></a>Свободна

Единственной функцией, доступной для свободного плана, является потребление контента Azure Information Protection с помощью учетных записей для работы или школы из приложений и служб, учитывая политику AIP. Подписка на самообслужительство для пользователей в организации, которым были отправлены конфиденциальные файлы, защищенные службой Azure Information Protection, но не может быть аутентификацией, так как ИТ-отдел пользователей не управляет учетной записью в Azure, например, ИТ-отдел не имеет Office 365 или не использует службы Azure.

## <a name="learn-more"></a>Дополнительные сведения

### <a name="azure-information-protection-details"></a>Сведения о защите информации Azure

- **Azure RMS**. Служба [управления правами Azure (Azure RMS)](/azure/information-protection/what-is-azure-rms) предоставляет технологию защиты данных для Azure Information Protection. Azure RMS можно использовать с классификацией и маркировкой или самостоятельно.
- **Сканер AIP или** клиент: у вас должен быть план azure Information Protection для классификации, маркировки и защиты с помощью сканера или клиента Azure Information Protection. Дополнительные сведения см. в [Microsoft 365](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection) руководстве по лицензированию & [безопасности,](https://go.microsoft.com/fwlink/?linkid=2139145) современному сопоставлению планов работы (загрузка PDF), Azure Active Directory [ценообразованию | Microsoft Security](https://www.microsoft.com/security/business/identity-access-management/azure-ad-pricing).
- [**Калькулятор**](https://azure.microsoft.com/pricing/calculator/?service=information-protection). Оценка ежемесячных расходов на службы Azure.
- [**Документация**](/azure/information-protection/). Просмотрите технические учебники, видео и дополнительные ресурсы.
- **Azure Information Protection** не включает права на автоматическую классификацию на основе Машинное обучение (обучаемые классификаторы).
- **Шифрование** двойных ключей. Дополнительные сведения о шифровании с двойным ключом для Microsoft 365 перейдите в информационную защиту: двойное шифрование ключей [для Microsoft 365.](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-double-key-encryption-for-microsoft-365)
- **Power BI** включена в Microsoft 365 E5/A5/G5; во всех остальных планах Power BI лицензироваться отдельно.
- [**Сведения о продукте**](https://azure.microsoft.com/services/information-protection/). Дополнительные сведения о защите информации Azure.
- [**Часто задаваемые**](https://azure.microsoft.com/pricing/faq/) вопросы. Обзор цен Azure.
- **Scoping**. Кроме использования функции сканера AIP, политики могут быть распределены по определенным группам или пользователям и реестрам, чтобы предотвратить запуск функций классификации или маркировки нелицензионных пользователей.
- **Метка конфиденциальности**. Дополнительные сведения перейдите к информационной защите [:](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-sensitivity-labeling) маркировка чувствительности или проверьте [сравнение современного плана работы](https://go.microsoft.com/fwlink/?linkid=2139145).
- **Планы подписки**. Дополнительные сведения о том, как можно приобрести или оценить Azure Information Protection, а также различные функции, доступные для планов подписки, см. в сайте [Azure Information Protectionsite](https://www.microsoft.com/cloud-platform/azure-information-protection) .

### <a name="general-information"></a>Общие сведения

- **Доступность**. Корпорация Майкрософт по-прежнему привержена безопасности ваших данных и [доступности](https://www.microsoft.com/trust-center/compliance/accessibility)  наших служб. Дополнительные сведения см. в центре  [доверияMicrosoft](https://www.microsoft.com/trust-center)  и центре  [Office доступности](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
- Дополнительные **вопросы. Если** на ваш вопрос здесь не ответили, просмотрите часто задаваемые вопросы для [Azure Information Protection (AIP),](/azure/information-protection/faqs) которые связаны с классификацией и маркировкой, или специфические для защиты [данных (вопросы](/azure/information-protection/faqs-infoprotect) для классификации и маркировки [, вопросы](/azure/information-protection/faqs-rms) для защиты [данных, вопросы](/azure/information-protection/faqs-classic) ответы только для классического клиента) или см. ссылки и ресурсы, перечисленные вInformation и поддержку  [для Azure Information Protection](/azure/information-protection/information-support)  или обратитесь к руководителю учетной записи Майкрософт или [службе поддержки Майкрософт](/azure/information-protection/information-support#to-contact-microsoft-support).
- **Условия лицензирования**. Условия лицензирования продуктов и служб, приобретенных через программы лицензирования коммерческих объемов Корпорации Майкрософт, см. на сайте [Условия продукта](https://www.microsoft.com/licensing/terms/).
- **Обмен сообщениями**. Чтобы быть в курсе предстоящих изменений, включая новые и измененные функции, запланированное обслуживание или другие важные объявления, посетите Центр сообщений. Подробнее см. в [Центре сообщений](/microsoft-365/admin/manage/message-center).
- **Поддержка & SLA**: Если у вас есть какие-либо вопросы или требуется помощь, посетите службу поддержки  [visitAzure и](https://azure.microsoft.com/support/options)  выберите службу самопослужки или любой другой метод, чтобы связаться с нами для поддержки. Мы гарантируем, что конечные пользователи смогут создавать и потреблять IRM-документы и электронные письма в 99,9% случаев. Дополнительные новости можно узнать на  [страницеSLApage](/learn/modules/choose-azure-services-sla-lifecycle) . Для поддержки и SLA в суверенных облаках обратитесь к локальной учетной записи.
