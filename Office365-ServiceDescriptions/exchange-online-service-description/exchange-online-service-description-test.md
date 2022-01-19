---
title: Описание службы Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ROBOTS: NOINDEX, NOFOLLOW
description: Узнайте о доступности Microsoft Exchange Online и функций в Microsoft 365 и Office 365 планах.
ms.openlocfilehash: e5ee41e61b5bbbcd2c1e28217437cceada038e3c
ms.sourcegitcommit: bee0e9c3474f9d0694a8648abff6ac1831fc9bd0
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/19/2022
ms.locfileid: "62083367"
---
# <a name="exchange-online-service-description"></a>Описание службы Exchange Online

Microsoft Exchange Online  это размещенное решение для обмена сообщениями с возможностями Microsoft Exchange Server в виде облачной службы. Оно предоставляет пользователям доступ к электронной почте, календарю, контактам и задачам с ПК, мобильных устройств и через Интернет. Оно полностью интегрируется с Active Directory, позволяя администраторам с помощью групповых политик и других средств администрирования управлять функциями Exchange Online в своей среде.
  
Организации, подписывающиеся на Exchange Online, сохраняют контроль над службами обмена сообщениями, которые они предлагают пользователям, но не имеют нагрузки на локальное серверное программное обеспечение. С учетом Exchange Online, описанных в описании этой службы, электронная почта передается на серверы, поддерживающий одновременно несколько клиентов. Эти серверы находятся в центрах обработки данных Майкрософт и доступны пользователям на широком диапазоне устройств внутри корпоративной сети или через Интернет.

В этом описании службы описаны основные различия между службами, предоставляемыми в различных облачных установках. Exchange Online основные функции не отличаются между подписками. Доступность возможностей соответствия требованиям зависит от уровня подписки.
  
## <a name="available-plans"></a>Доступные планы

Подробные сведения о планах подписки, которые позволяют пользователям Exchange Online, см. в таблице [сравнения решений Майкрософт.](https://go.microsoft.com/fwlink/?linkid=2139145)

Каждый пользователь, который Exchange Online службу, должен быть назначен в план подписки, и у каждого пользователя есть свой почтовый ящик. Папки и сообщения в этих почтовых ящиках находятся на компьютере, Exchange Server в центр обработки данных Майкрософт.
  
Для конференц-залов и общих почтовых ящиков подписки пользователей не требуются. У этих специальных почтовых ящиков нет учетных данных для входа. Вместо этого ими через делегирование управляют лицензированные пользователи с соответствующими разрешениями.

## <a name="feature-availability"></a>Доступность функций

В следующей таблице перечислены основные Exchange Online, доступные в планах. Некоторые оговорки применяются*. Эта таблица может измениться без уведомления. Полный список функций Exchange Online в планах см. в Exchange Online [compare Exchange Online.](https://www.microsoft.com/microsoft-365/exchange/compare-microsoft-exchange-online-plans)<br><br>
  
| Функция | Планы малого бизнеса | Enterprise планы | Планы образования | GCC | GCC High | DOD | 
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Планирование и развертывание](/exchange/plan-and-deploy/plan-and-deploy)|Да*|Да|Да|Да|Да|Да|
|[Разрешения](/exchange/permissions-exo/permissions-exo)|Да|Да|Да|Да|Да|Да|
|[Политика обработки сообщений и соответствие требованиям](/exchange/policy-and-compliance/policy-and-compliance)|Да*|Да*|Да|Да|Да|Да|
|[Защита от нежелательной почты и вредоносных программ](/exchange/antispam-and-antimalware/antispam-and-antimalware)|Да*|Да*|Да|Да|Да|Да|
|[Поток обработки почты](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)|Да*|Да|Да|Да|Да|Да|
|[Получатели](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)|Да*|Да*|Да|Да|Да*|Да*|
|[Функции создания отчетов и средства устранения неполадок](reporting-features-and-troubleshooting-tools.md)|Да*|Да*|Да|Да|Да*|Да*|
|[Общий доступ и совместная работа](/exchange/sharing/sharing)|Да|Да|Да|Да|Да|Да|
|[Клиенты и мобильные устройства](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)|Да*|Да|Да|Да*|Да*|Да*|
|[Службы голосовых сообщений](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)|Да*|Да*|Да|Нет*|Нет*|Нет*|
|[Высокая доступность и непрерывность бизнес-процессов](/exchange/high-availability/high-availability)|Да*|Да|Да|Да|Да|Да|
|[Взаимодействие, связь и совместимость](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)|Да|Да|Да|Да|Да|Да|
|[Установка и администрирование Exchange Online](/exchange/architecture/client-access/exchange-admin-center)|Да*|Да|Да|Да|Да|Да*|
|Расширение службы — настройка, надстройки и ресурсы|Да|Да|Да|Да|Да|Да|

## <a name="learn-more"></a>Подробнее

Дополнительные сведения о Exchange Online, ознакомьтесь со следующими ресурсами:

- [Exchange Online документации администратора](/exchange/exchange-online)
- [Exchange Online хранения и получателей](exchange-online-limits.md)
- [Новые возможности Центра администрирования Exchange](/exchange/whats-new)

### <a name="licensing-terms"></a>Условия лицензирования

Условия лицензирования продуктов и служб, приобретенных в рамках программ корпоративного лицензирования Майкрософт, см. на сайте [Условия использования продуктов Майкрософт](https://www.microsoft.com/licensing/terms/). 

### <a name="messaging"></a>Сообщения

Чтобы быть в курсе предстоящих изменений, в том числе новых и измененных функций, планового обслуживания или других важных объявлений, посетите Центр сообщений. Подробнее см. в [Центре сообщений](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Специальные возможности

Корпорация Майкрософт по-прежнему стремится к безопасности ваших данных и обеспечению специальных возможностей наших служб. Дополнительные сведения см. в [Центр управления безопасностью Майкрософт](https://www.microsoft.com/trust-center) и в [Центре специальных возможностей Office](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
