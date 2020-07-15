---
title: Разрешения
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132693"
---
# <a name="permissions"></a>Разрешения

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Дополнительные сведения о модели разрешений RBAC, используемой в Exchange Online, содержатся в разделе [Разрешения](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Разрешения на основе ролей

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Существует два типа ролей  административные роли и роли конечных пользователей.
  
- **Административные роли** Эти роли предусматривают разрешения, которые можно назначить администраторам или опытным пользователям при помощи групп ролей, управляющих частью организации Exchange Online, например получателями, серверами или базами данных. 
    
- **Роли конечных пользователей** Эти роли, назначенные с помощью политик назначения ролей, позволяют пользователям управлять аспектами собственных почтовых ящиков и групп рассылки, которыми они владеют. Роли конечных пользователей начинаются с префикса  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Некоторые роли, доступные в локальной версии Microsoft Exchange Server 2013, могут быть недоступны в Exchange Online. 
  
Дополнительные сведения о разрешениях в Exchange Online см. в разделе [Разрешения на основе ролей](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Группы ролей

Группы ролей управления связывают роли управления с группами администраторов или пользователей-специалистов. Администраторы отвечают за управление общей конфигурацией организации или получателей в Exchange Online. Опытные пользователи управляют определенными функциями Exchange Online, такими как соблюдение требований, или эти пользователи могут иметь ограниченные возможности управления, такие как у членов службы поддержки, но без широких прав администратора. Группы ролей обычно связывают административные роли управления, которые позволяют администраторам и пользователям специалистов управлять настройкой Организации и получателей. Например, именно с помощью групп ролей администраторам может предоставляться возможность управления получателями или использования функций обнаружения почтовых ящиков. 
  
> [!IMPORTANT]
> Некоторые группы ролей, доступные в локальной версии Microsoft Exchange Server 2013, могут быть недоступны в Exchange Online. 
  
Дополнительные сведения о группах ролей см. в разделе [Группы ролей и политики назначения роли](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Политики назначения роли

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Некоторые политики назначения ролей, доступные в локальной версии Microsoft Exchange Server 2013, могут быть недоступны в Exchange Online. 
  
Дополнительные сведения о политиках назначения ролей см. в разделе [Группы ролей и политики назначения ролей](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Доступность функций

Просмотреть сведения о доступности функций в планах, отдельных и локальных решениях можно в статье [Exchange Online Service Description](exchange-online-service-description.md).
  

