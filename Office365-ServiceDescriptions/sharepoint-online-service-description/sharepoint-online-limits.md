---
title: Ограничения SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Узнайте об ограничениях SharePoint для Microsoft 365 и отдельных планов.
ms.openlocfilehash: 5da27b4b889be7890946787d56618fcc007fd10b
ms.sourcegitcommit: 172963e811598f2b94d3b65150cec1d0487af197
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/10/2022
ms.locfileid: "63419457"
---
# <a name="sharepoint-limits"></a>Ограничения SharePoint

Сведения об ограничениях служб в SharePoint для Microsoft 365.
  
## <a name="limits-by-plan"></a>Ограничения плана 

| Функция | Microsoft 365 бизнес базовый, бизнес стандарт или бизнес премиум | Microsoft 365 A3, E3, G3 & A5, E5, G5</br>Office 365 A3, E3, G3 & A5, E5, G5</br>Office 365 A1, E1, G1</br>SharePoint 1 или 2 | Microsoft 365 F1 или F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Общее хранилище для <sup>организации1, 2, 5</sup> <br/> |1 ТБ плюс 10 ГБ на приобретенную лицензию<sup>3</sup>  <br/> |1 ТБ плюс 10 ГБ на приобретенную лицензию<sup>3</sup> <br/> |1 ТБ<sup>3</sup> <br/> |
|Максимальный объем хранилища для каждого сайта (семейства веб-сайтов)<sup>4</sup><br/> |25 ТБ <br/> |25 ТБ <br/> |25 ТБ <br/> |
|Сайты (семейства веб-сайтов) на организацию  <br/> |2 <sup>миллиона5</sup> <br/> |2 <sup>миллиона5</sup> <br/> |2 миллиона<br/> |
|Количество пользователей  <br/> |До 300  <br/> |1-500 000<sup>6</sup> <br/> |1-500 000<sup>6</sup> <br/> |
   
<sup>1</sup> [Узнайте, как найти общее и доступное место в хранилище для вашей организации](/sharepoint/manage-site-collection-storage-limits). Вы можете приобрести неограниченный дополнительный объем хранилища SharePoint. См. статью [Добавление места в хранилище для подписки](/office365/admin/subscriptions-and-billing/add-storage-space) 
<br/><sup>2</sup> Рекомендуем следить за корзиной и регулярно ее очищать. Она занимает часть общее место в хранилище организации. 
<br/> <sup>3</sup> Если у вас есть подписка на Microsoft 365 и надстройка Office 365 с дополнительным хранилищем, место в хранилище добавляется. 
<br/> <sup>4</sup> Это *ограничение* хранилища для одного сайта (ранее называлось "семейство веб-сайтов"), а не объем хранилища, *предоставленный* для каждого сайта. Это ограничение применяется ко всем типам сайтов, включая сайты групп, подключенные к Office 365 и OneDrive. Администраторы SharePoint могут [вручную устанавливать более низкие ограничения хранилища](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Не включая OneDrive для каждого лицензированного пользователя. 
<br/> <sup>6</sup> Если у вас более 500 000 пользователей, обратитесь к представителю Майкрософт. 
  
## <a name="service-limits-for-all-plans"></a>Ограничения на обслуживание для всех планов

### <a name="file-size-and-file-path-length"></a>Размер файла и длина пути к файлу

- **250 ГБ — ограничение на отправку файлов.** Применяется к каждому отдельному файлу, отправленному на вкладку "Файлы Microsoft Teams", в библиотеки документов SharePoint, папки OneDrive и беседы Yammer.

- **250 МБ — файл, вложенный в элемент списка.** Применяется к Microsoft Спискам и спискам SharePoint на основе одной платформы списков.

- Весь путь декодирования файла, включая имя файла, не может содержать более 400 символов для OneDrive, OneDrive для работы или учебного заведения и SharePoint в Microsoft 365. Ограничение применяется к комбинации пути папки и имени файла после декодирования. Дополнительные сведения см. в  [файле имя и длина пути](https://support.microsoft.com/office/restrictions-and-limitations-in-onedrive-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa#filenamepathlengths).

Дополнительные сведения об ограничениях при использовании нового приложения синхронизации OneDrive (OneDrive.exe) см. в статье [Недопустимые имена файлов и типы файлов](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="items-in-lists-and-libraries"></a>Элементы в списках и библиотеках

Список может содержать до 30 миллионов элементов, а библиотека — до 30 миллионов файлов и папок. Если список, библиотека или папка содержат более 100 000 элементов, вы не сможете нарушить наследование разрешений для списка, библиотеки или папки. Вы также не можете повторно наследовать разрешения на него. Однако вы по-прежнему можете прекратить наследование отдельных элементов в списке, библиотеке или папке до максимального числа уникальных разрешений в списке или библиотеке (см. следующий раздел). Дополнительные сведения о других ограничениях, действующих при просмотре больших списков, см. в статье [Управление крупными списками и библиотеками в Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="lists-and-libraries"></a>Списки и библиотеки

2000 списков и библиотек, объединенных в коллекцию веб-сайтов (включая основной сайт и все подвиды).

### <a name="subsites"></a>Дочерние сайты

2 000 на сайт (семейство веб-сайтов). Рекомендуется создавать сайты и организовывать их в концентраторы, а не создавать дополнительные сайты. При использовании подсайтов рекомендуется ограничить их количество (особенно на сайтах с высокой посещаемостью).

> [!NOTE]
> В вашей организации может быть не более 2 000 центральных сайтов. Возможно, для каждой функции может не потребоваться веб-узел концентратора, и перед созданием концентраторов необходимо некоторое планирование. Дополнительные сведения см. в [SharePoint веб SharePoint узлов](/sharepoint/planning-hub-sites).

### <a name="users"></a>Пользователи

2 миллиона для каждого семейства веб-сайтов.

> [!NOTE]
> Количество гостей, которых можно пригласить на сайты SharePoint, не ограничивается. Дополнительные сведения о внешнем общем доступе см. в статье [Обзор внешнего общего доступа](/sharepoint/external-sharing-overview).

### <a name="sharepoint-groups"></a>Группы SharePoint

Пользователь может быть участником 5 000 групп на сайт (семейство веб-сайтов), а каждая группа может содержать не более 5 000 пользователей. Для одного сайта (семейства веб-сайтов) можно использовать до 10 000 групп.

> [!NOTE]
> Что касается ограничений групп Azure AD, см. статью [Ограничения службы Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions), так как такие ограничения могут повлиять на управление членством на сайтах общедоступных и частных групп.

### <a name="unique-security-scopes-per-list-or-library"></a>Уникальные области безопасности для каждого списка или библиотеки

Для больших списков необходимо иметь как можно меньше уникальных разрешений и не более 5 000.

### <a name="versions"></a>Версии

50 000 основных и 511 промежуточных версий.

### <a name="sharepoint-hosted-applications"></a>Приложения, размещенные в SharePoint

20 000 экземпляров на организацию.

### <a name="sharepoint-workflow"></a>Рабочий процесс SharePoint

SharePoint 2013 г. процессы могут работать по проекту навеки, если нет конечных условий или явного действия остановки.

### <a name="managed-metadata"></a>Управляемые метаданные

Всего 1 миллион терминов с 2 миллионами меток терминов и 1 миллионом свойств терминов (эти ограничения указаны для общих терминов и терминов на уровне сайта). 1 000 глобальных наборов терминов и 1 000 глобальных групп.

### <a name="overall-site-metadata"></a>Общие метаданные сайта

1 000 ГБ на сайт (метаданные редко достигают этого размера).

### <a name="hold-limits"></a>Ограничения удержания

Удержания включают в себя удержание случае eDiscovery и Microsoft 365 политики хранения для SharePoint и OneDrive. Они учитываются в максимальном значении 10 000 на клиента для политик совместимости, которые также включают политики DLP, информационные барьеры и метки конфиденциальности.

Максимальное число поддерживаемых удерживает:

- SharePoint или OneDrive (все сайты автоматически включены): 13
- SharePoint или OneDrive (определенные расположения включаются или исключаются): 2 600

### <a name="sync"></a>Синхронизация

Для оптимальной производительности рекомендуется хранить не более 300 000 файлов в одной библиотеке OneDrive или библиотеке сайта группы. Несмотря на то что SharePoint Online позволяет хранить до 30 миллионов документов в одной библиотеке, для оптимальной производительности мы рекомендуем синхронизировать не более 300 000 файлов во всех библиотеках документов. Кроме того, проблемы с производительностью могут возникнуть, если во всех библиотеках, которые вы синхронизируете, хранится 300 000 и более элементов, даже если вы не синхронизируете все из них. Если вы используете предыдущий клиент синхронизации OneDrive для бизнеса (Groove.exe), ограничение количества синхронизируемых файлов для одной библиотеки составит 20 000 элементов (включая 5 000 элементов для каждого сайта группы).

### <a name="moving-and-copying-across-sites"></a>Перемещение и копирование между сайтами

Для копирования или перемещения нескольких файлов за одну операцию необходимо три требования:

- Общий размер файла не превышает 100 ГБ
- Не более 30 000 файлов
- Размер каждого файла не должен превышать 15 ГБ

## <a name="see-also"></a>См. также

[Ограничения поиска в SharePoint](/sharepoint/search-limits)
