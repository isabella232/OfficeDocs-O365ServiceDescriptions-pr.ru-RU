---
title: Получатель, домен и управление компанией в Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Ознакомьтесь с этой статьей, чтобы узнать об управлении получателем, доменом и компанией в Microsoft Exchange Online защиты (EOP).
ms.openlocfilehash: fc2b9f6fbd797e8e765758c11c486ce6afaba5a5855602e79f5418c1e80bb1ea
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664062"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Получатель, домен и управление компанией в Exchange Online Protection

Microsoft Exchange Online Защита (EOP) предоставляет несколько способов управления данными получателя, домена и компании. Как администратор вы можете выполнять определенные задачи управления в центре администрирования Exchange (EAC) и проверять другие задачи управления, выполняемые в Центр администрирования Microsoft 365.
  
Ищете сведения обо всех особенностях EOP? См. [Exchange Online Protection службы.](exchange-online-protection-service-description.md)
  
## <a name="mail-recipients"></a>Mail recipients

Получатели почты классифицируются как пользователи почты или группы и могут управляться с помощью синхронизации каталогов, непосредственно в EAC или с помощью удаленных Windows PowerShell. Если вы управляете локально получателями, необходимо выполнить синхронизацию каталогов для отражения получателей почты в EAC. Пользователи, управляемые исключительно в Центр администрирования Microsoft 365, не просматриваются в EAC, но их можно добавить или удалить из членства в группе ролей администратора в EAC. Дополнительные сведения о получателях в EOP см. в [нем Recipients in EOP.](/microsoft-365/security/office-365-security/manage-recipients-in-eop)
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

В службе Exchange Online Protection можно настраивать только роли администраторов. Пользователей можно добавить в группы ролей администраторов по умолчанию и удалить из них непосредственно в Центре администрирования Exchange. Настройка RBAC недоступна. Дополнительные сведения см. в статье, посвященной [управлению разрешениями группы ролей администраторов в EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Управление доменами

Управляемые домены — это домены, защищенные EOP. Управляемые домены можно просматривать, а типы доменов можно изменять в Центре администрирования Exchange. Подготовка и управление доменом происходят в Центр администрирования Microsoft 365 и изменения отражаются в EAC. Дополнительные сведения см. в [статью Просмотр или изменение управляемых доменов в EOP.](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
  
## <a name="match-subdomains"></a>Соответствующие поддомены

В службе EOP можно включить поток почты к поддоменам управляемого домена. Дополнительные сведения см. в статье [Включение потока почты к поддоменам в службе EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Пограничная блокировка на основе каталогов

Функция пограничной блокировки на основе каталогов позволяет отклонять сообщения для недопустимых получателей в сети периметра службы. DBEB позволяет администраторам добавлять получателей с поддержкой почты в Microsoft и блокировать все сообщения, отправленные на адреса электронной почты, которые не присутствуют в Microsoft. Если сообщение отправляется на допустимый адрес электронной почты, присутствующий в Microsoft, сообщение продолжается через остальные уровни фильтрации служб (анти-вредоносные программы, анти-спам, правила транспорта). Если адрес отсутствует, служба блокирует сообщение еще до фильтрации, а отправителю отправляется отчет о недоставке сообщения. 
  
Включение функции пограничной блокировки на основе каталогов требует настройки доменов и учетных записей пользователей. Дополнительные сведения см. в статье, посвященной [применению пограничной блокировки на основе каталогов для отклонения сообщений, отправленных недопустимым получателям](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, автономных вариантах и локальном решении, см. Exchange Online Protection [службы.](exchange-online-protection-service-description.md)