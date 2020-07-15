---
title: Планирование и развертывание
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132663"
---
# <a name="planning-and-deployment"></a>Планирование и развертывание

## <a name="planning-for-service-changes-and-growth"></a>Планирование с учетом изменения и роста службы

Организациям следует выбирать варианты миграции на основе исходной системы электронной почты, необходимого конечного результата (полного или частичного размещения в облаке), количество пользователей для переноса, а также того, как быстро нужно добиться результата.
  
## <a name="deployment-options"></a>Варианты развертывания

- **Развертывание только в облаке** Организация хранит все пользовательские почтовые ящики в Exchange Online. 
    
- **Гибридное развертывание Exchange** У организации будет определенное число пользовательских почтовых ящиков, размещенных в локальной организации Exchange, а некоторые почтовые ящики пользователей размещаются в Exchange Online. 
    
### <a name="cloud-only"></a>Только облако

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Гибридная среда

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Варианты миграции

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **Миграция через IMAP** Миграция почтовых ящиков из систем электронной почты на основе IMAP в Exchange Online. 
    
- **Прямая миграция Exchange** Перенос почтовых ящиков из Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 и облачных систем Exchange в Exchange Online в рамках единой прямой миграции. 
    
- **Поэтапная миграция Exchange** Поэтапная миграция почтовых ящиков из Exchange Server 2003 или 2007 с помощью веб-средств миграции с минимальными изменениями в локальной инфраструктуре. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Дополнительные сведения о переносе электронной почты и почтовых ящиков в Exchange Online см. в статье [Перенос электронной почты в Office 365  справка для администраторов](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Миграция IMAP

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Создание пустых почтовых ящиков в облаке для пользователей в организации (как правило, это делается путем загрузки CSV-файла или с помощью удаленной оболочки Windows PowerShell).
    
2. Ввод параметров подключения удаленного сервера.
    
3. Используйте CSV-файл для указания почтовых ящиков, данные из которых будут перенесены в почтовые ящики Exchange Online.
    
4. Когда информация введена, Exchange Online начинает переносить содержимое почтовых ящиков через IMAP (элементы календаря, контакты, задачи, и другие отличные от почтовых элементов данные не переносятся).
    
Дополнительные сведения об IMAP-миграции см. в статьях [Перенос почтовых ящиков IMAP в Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) и [Перенос других типов почтовых ящиков IMAP в Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Чтобы правильно использовать ресурсы удаленного сервера и полосу пропускания в процессе переноса, Exchange Online создает менее 10 подключений к IMAP-серверу. 
  
### <a name="cutover-exchange-migration"></a>Прямая миграция Exchange

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Используя адрес электронной почты и учетные данные локальной учетной записи администратора, Exchange Online подключается к локальной почтовой организации с помощью службы автообнаружения.
    
2. Exchange Online использует RPC/HTTP для чтения информации из каталога на удаленном сервере и создает почтовые ящики в Exchange Online.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. После завершения первоначальной миграции изменения будут синхронизироваться с облаком каждые 24 часа до тех пор, пока администратор не остановит и не удалит пакет миграции.
    
Чтобы переключить пользователей на облачные почтовые ящики, администраторы настраивают свои записи MX, чтобы они ссылались на корпорацию Майкрософт, и перенастройте профили пользователей в Outlook. Когда пользователи переходят на облачные почтовые ящики, их локальные автономные папки (OST-файлы) повторно синхронизируются, в результате чего почта загружается на клиентской рабочей станции. Пользователи могут отвечать на старые сообщения в своих почтовых ящиках после миграции.
  
Дополнительные сведения о прямой миграции Exchange см. в статье [Что необходимо знать о прямой миграции электронной почты в Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Поэтапная миграция Exchange

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Дополнительные сведения о поэтапной миграции Exchange см. в статье [Что необходимо знать о поэтапной миграции электронной почты в Office 365](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Средства миграции

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Сведения о пропущенных элементах** При прямой и поэтапной миграции, а также миграции IMAP, панель мониторинга миграции отображает сведения об элементах, которые были пропущены, включая причину пропуска и место расположения элемента в почтовом ящике пользователя. 
    
  - **Открытые отчеты миграции** Администраторы могут открыть статистику или отчет об ошибках миграции для пакета миграции непосредственно в панели. 
    
  - **Редактирование пакетов миграции** Если пакет миграции при поэтапной миграции Exchange или миграции IMAP находится в очереди, но в данный момент не выполняется, администраторы могут изменить его. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Дополнительные сведения о Средство синхронизации Azure Active Directory см. в разделе [Синхронизация каталогов: стратегия](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Мастер Центра администрирования Exchange (EAC), выполняющий сквозной процесс настройки гибридного развертывания.
    
  - Набор команд командной консоли Exchange, позволяющих организовать процесс настройки.
    
    Дополнительные сведения о мастере гибридной конфигурации см. в разделе [Мастер гибридной конфигурации](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Доступность функций

Чтобы просмотреть доступность функций в планах, отдельных параметрах и локальных решениях, ознакомьтесь со статьей [Описание службы Exchange Online](exchange-online-service-description.md).
  

