---
title: Работоспособность и непрерывная работа служб
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Администраторы Майкрософт могут просмотреть состояние служб и узнать, когда запланировано обслуживание. Работоспособность служб сведения доступны в любое время при входе в систему.
ms.openlocfilehash: 6b572af48f64e99cf4fc8cedb04a42476ec9e10a
ms.sourcegitcommit: e4bf187c926340f4afb68bfe51d38b303664ae00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65218165"
---
# <a name="service-health-and-continuity"></a>Работоспособность и непрерывная работа служб

Администраторы Майкрософт могут просмотреть состояние служб и узнать, когда запланировано обслуживание. Работоспособность служб сведения доступны в любое время при входе в систему.
  
> [!NOTE]
> Если вы используете план Office 365:, которым управляет 21Vianet, часть приведенной ниже информации может оказаться неприменимой. В этом случае см. [соглашение об уровне обслуживания 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Просмотр состояния служб

В Работоспособность служб показано текущее состояние службы и сведения о сбоях и сбоях службы. Сведения о плановом обслуживании доступны в Центре сообщений. Дополнительные сведения см [. в разделе "Просмотр состояния служб"](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Инциденты служб

Инцидент службы — это событие, которое влияет на предоставление службы. Инциденты службы могут быть вызваны сбоем оборудования или программного обеспечения в центре обработки данных Майкрософт, неисправным сетевым подключением из-за изменений, внесенных корпорацией Майкрософт, или серьезной проблемой центра обработки данных, такой как пожар, переполнение или региональная катастрофа. Прерывания, вызванные сторонними поставщиками услуг, или изменения, внесенные в среде, управляемой клиентом, не считаются инцидентами службы. Большинство инцидентов со службами может быть разрешено с помощью технологических решений Майкрософт и разрешается в течение короткого времени. Однако некоторые инциденты более серьезные и могут привести к длительным отказам.
  
Существует два типа уведомлений о времени, когда службы могут быть недоступны:
  
- **События планового обслуживания:** Плановое обслуживание — это регулярные обновления служб, инициированные корпорацией Майкрософт, для инфраструктуры и программных приложений. Уведомления о плановом обслуживании информируют клиентов о работе службы, которая может повлиять на функциональность службы Майкрософт. Клиенты получают уведомления не позднее чем за пять дней до планового обслуживания через Центр сообщений на Центр администрирования Microsoft 365. Корпорация Майкрософт обычно планирует обслуживание в периоды, когда использование службы исторически находится на самом низком уровне в зависимости от региональных часовых поясов.

- **Внеплановое время простоя:** Незапланированные инциденты службы происходят, когда одна из служб недоступна или не отвечает из-за сбоя в среде, управляемой Корпорацией Майкрософт. Клиенты получают уведомления об известных инцидентах службы Работоспособность служб на Центр администрирования Microsoft 365.

### <a name="recent-worldwide-uptimes"></a>Недавние время простоя по всему миру

Переход на облачную службу не должен означать потеря возможности узнать, что происходит. Если Microsoft 365, это не так. Мы стремимся быть прозрачными в наших операциях, чтобы вы могли отслеживать состояние службы, отслеживать проблемы и иметь исторические представления о доступности. В следующих таблицах показаны последние данные о времени простоя по всему миру.

**2022**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98%  | - | - | -|

<br>

**2021**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | 99.98% | 99.985% | 99.976%|

<br>

**2020**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98% | 99,99 % | 99.97% | 99.97% |

<br>

**2019**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% | 99.97% | 99.98% | 99.98% |

<br>

**2018**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99 % | 99.98% | 99.97% | 99.98% |

<br>

**2017**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99 % | 99.97% | 99.98% | 99,99 % |

## <a name="notification-policy"></a>Политика уведомлений

При возникновении инцидента службы, Майкрософт осознает, что для клиентов наиболее важна своевременная, целевая и точная информация. Корпорация Майкрософт уведомляет администраторов, напрямую взаимодействуя с затронутыми клиентами Работоспособность служб на Центр администрирования Microsoft 365. Обновления инцидентов службы предоставляются ежечасно или, если требуется другая частота, она будет указана в сообщении о связи SHD.
  
## <a name="service-health-communication-channels"></a>Работоспособность служб каналов связи

### <a name="admin-app"></a>Приложение администрирования

Приложение администрирования для администраторов организации позволяет подключаться к статусу службы Майкрософт вашей организации в пути. Администраторы Майкрософт смогут просматривать сведения о работоспособности службы и обновления состояния обслуживания с мобильных устройств. Дополнительные сведения см. в статье [Вопросы и ответы о приложении администрирования](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="microsoft-365-management-pack-for-microsoft-system-center-operations-manager"></a>Microsoft 365 управления для Microsoft System Center Operations Manager

Microsoft System Center Operations Manager (SCOM) — это интегрированная платформа управления, которая помогает управлять центром обработки данных, клиентскими устройствами и гибридными облачными ИТ-средами. Администраторы Майкрософт, использующие SCOM, могут импортировать пакет управления Microsoft 365, который позволяет им просматривать все коммуникации служб в Operations Manager в System Center. С помощью этого средства вы можете получить доступ к статусу подписанных служб, активным и разрешенным инцидентам службы и обмену данными в центре сообщений. Дополнительные сведения см. в пакете [System Center Microsoft Microsoft 365](https://www.microsoft.com/download/details.aspx?id=103379) в Центре загрузки Майкрософт.
  
### <a name="microsoft-365-service-communications-api-in-graph"></a>Microsoft 365 Service Communications API в Graph

API Microsoft 365 Service Communications позволяет получать доступ к обмену данными между службами нужным образом. С помощью этого API вы можете создавать средства и подключать их к обмену данными, что может упростить мониторинг среды. API service Communications позволяет отслеживать следующие элементы среды:

- Работоспособность службы в реальном времени

- Сообщения в Центре сообщений

Дополнительные сведения см. в справочнике [Microsoft 365 Service Communications](/graph/api/resources/service-communications-api-overview).

## <a name="post-incident-reviews"></a>Заключительный анализ инцидентов

Стремление Майкрософт к постоянному совершенствованию включает анализ затрагивающих клиентов внеплановых инцидентов служб, чтобы минимизировать их повторение в будущем.
  
Незапланированные инциденты службы определяются как перебои в работе служб с несколькими клиентами, которые влияют на использование службы, как определено в наших соглашениях об уровне обслуживания (SLA), и объявляются таким образом через Работоспособность служб в Центр администрирования Microsoft 365.
  
Для незапланированных инцидентов обслуживания, влияющих на клиентов, в которых было значительное и заметное влияние в большом количестве организаций, предварительная проверка после инцидента (PIR) будет доставлена через вашу службу Работоспособность служб в течение 48 часов после устранения инцидентов, а затем окончательный PIR в течение пяти рабочих дней. Подробный отчет PIR включает в себя:
  
- Влияние на работу пользователей и клиентов.

- Дата и время начала и окончания инцидента

- Подробная временная шкала мер влияния и разрешения

- Анализ основных причин и действия, предпринимаемые для постоянного улучшения

Для всех других инцидентов службы на странице Работоспособность служб на Центр администрирования Microsoft 365 содержится сводка по закрытию инцидента, включая окончательную сводку о событии, первопричине, времени начала и окончания, а также сведения о следующих шагах. Для этой категории инцидентов служб заключительный анализ инцидента не составляется.
  
## <a name="service-continuity"></a>Service continuity

Предложения Майкрософт предоставляются высокоустойчивыми системами, которые помогают поддерживать пиковую производительность служб. Обеспечение непрерывности служб является частью проектирования системы. Эти положения позволяют корпорации Майкрософт быстро восстанавливаться после непредвиденных событий, таких как сбой оборудования или приложения, повреждение данных или другие инциденты, влияющие на пользователей. Эти решения по обеспечению непрерывной работы также применяются при катастрофических отказах (например, во время стихийных бедствий или при инциденте в центре обработки данных Майкрософт, вызвавшем неработоспособность всего центра обработки данных).
  
Обратите внимание, что по завершении восстановления после критического сбоя потребуется некоторое время, чтобы полностью восстановилась избыточность центра обработки данных для службы. Например, при сбое в центре обработки данных 1 восстановление служб проводится в центре обработки данных 2. Однако непрерывность работы служб в центре обработки данных 2 за счет восстановленных ресурсов в центре обработки данных 1 или новых ресурсов в центре обработки данных 3 будет обеспечена не сразу. Соглашение об [уровне обслуживания](service-level-agreement.md) (SLA) Майкрософт применяется в течение этого времени. Office 365 21Vianet имеет другое соглашение об уровне обслуживания. Дополнительные сведения см. на [сайте 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Обеспечение доступности данных

Майкрософт обеспечивает доступность данных клиента, где бы они ни потребовались, с помощью следующих функциональных возможностей:
  
- **Хранение и резервирование данных:** Данные клиента хранятся в резервной среде с надежными возможностями защиты данных, позволяющими обеспечить доступность, непрерывность бизнес-процессов и быстрое восстановление. Реализуется несколько уровней избыточности данных, от избыточных дисков для защиты от сбоев локальных дисков, до постоянной, полной репликации данных в географически удаленном центре обработки данных. 

- **Мониторинг данных: службы Майкрософт** поддерживать высокий уровень производительности путем мониторинга: 

  - Databases

  - заблокированных процессов

  - потерь пакетов

  - процессов в очереди

  - задержек обработки запросов.

- **Выполнение профилактического обслуживания:** Профилактическое обслуживание включает проверки целостности баз данных, периодическое сжатие данных и просмотр журналов ошибок. 

## <a name="support"></a>Поддержка

Группы разработки и эксплуатации Майкрософт дополняются выделенной организацией поддержки, которая играет важную роль в обеспечении непрерывности бизнес-процессов для клиентов. Сотрудники поддержки имеют глубокие знания служб и связанных с ними приложений, а также прямой доступ к экспертам Майкрософт в области архитектуры, разработки и тестирования.
  
Организация поддержки тесно связана с операциями и разработкой продуктов, предлагает быстрые сроки разрешения инцидентов и обеспечивает канал, по которому можно услышать клиентов. Отзывы и предложения от клиентов предоставляют входные данные для процессов планирования, разработки и операций.
  
- **Отслеживание проблем по Интернету:** Клиентам необходимо знать, когда их проблемы будут разрешены, и им нужна возможность отслеживания актуального процесса разрешения. Этот Центр администрирования Microsoft 365 предоставляет единый веб-интерфейс для поддержки. Клиенты могут использовать портал для добавления запросов служб и их мониторинга, а также для получения отзывов от групп поддержки Майкрософт. 

- **Самообслуживка, поддерживаемая непрерывной поддержкой персонала:** Корпорация Майкрософт предлагает широкий спектр ресурсов и средств самообслуживания, которые помогут клиентам решить проблемы, связанные со службами, без поддержки Майкрософт. 

Перед вводом запроса служб клиенты могут обратиться к статьям базы знаний и разделам вопросов и ответов, которые обеспечивают немедленную помощь по большинству распространенных проблем. Эти ресурсы постоянно обновляются актуальной информацией, которая помогает избежать задержки, предоставляя решения для известных проблем. Однако при возникновении проблемы, при которой требуется помощь специалиста поддержки, немедленный доступ к штатным сотрудникам можно получить по телефону и на портале администрирования круглосуточно, 7 дней в неделю.
  
Дополнительные сведения о поддержке см. в статье [о поддержке](support.md) . 
  
## <a name="feature-availability"></a>Доступность функций

Сведения о доступности функций в планах см. в Microsoft 365 [и Office 365 службы платформы](office-365-platform-service-description.md).
