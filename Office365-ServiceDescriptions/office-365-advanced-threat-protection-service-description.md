---
title: Описание службы Office 365 Advanced Threat Protection
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 расширенного угроз защиты анализа — это облачная службу фильтрации электронной почты, которая помогает защитить организацию от неизвестного вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня и включает в себя компоненты по защите вашей организации от вредоносных ссылки в режиме реального времени. Пакет анализа содержит подробную отчетность и возможностей трассировки URL-адрес, которых администраторы могут понять виды атак, что происходит в вашей организации.
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036796"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="219ee-104">Описание службы Office 365 Advanced Threat Protection</span><span class="sxs-lookup"><span data-stu-id="219ee-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="219ee-p102">Microsoft Office 365 расширенного угроз защиты анализа — это облачная службу фильтрации электронной почты, которая помогает защитить организацию от неизвестного вредоносных программ и вирусов, обеспечивая надежную защиту нулевого дня и включает в себя компоненты по защите вашей организации от вредоносных ссылки в режиме реального времени. Пакет анализа содержит подробную отчетность и возможностей трассировки URL-адрес, которых администраторы могут понять виды атак, что происходит в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="219ee-p102">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>
  
<span data-ttu-id="219ee-107">Ниже приведены основные способы, с помощью которых можно использовать ATP для защиты сообщений.</span><span class="sxs-lookup"><span data-stu-id="219ee-107">The following are the primary ways you can use ATP for messaging protection:</span></span>
  
- <span data-ttu-id="219ee-108">В сценарии, предназначенном только для фильтра Office 365 ATP, ATP предоставляет облачную защиту электронной почты для вашей локальной среды Exchange Server 2013, устаревших версий Exchange Server или другого локального решения для почты SMTP.</span><span class="sxs-lookup"><span data-stu-id="219ee-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server 2013 environment, legacy Exchange Server versions, or any other on-premises SMTP email solution.</span></span>
    
- <span data-ttu-id="219ee-p103">Office 365 ATP можно включить для защиты почтовых ящиков Exchange Online, размещенных в облаке. Дополнительные сведения об Exchange Online см. в статье [Описание службы Exchange Online](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).</span><span class="sxs-lookup"><span data-stu-id="219ee-p103">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes. To learn more about Exchange Online, see the [Exchange Online Service Description](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).</span></span>
    
- <span data-ttu-id="219ee-111">Для защиты среды обмена сообщениями и управления маршрутизацией почты в гибридном развертывании можно настроить Advanced Threat Protection, если есть локальные и облачные почтовые ящики, а также используется Exchange Online Protection для фильтрации входящих писем.</span><span class="sxs-lookup"><span data-stu-id="219ee-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="219ee-112">Доступность Office 365 Advanced Threat Protection</span><span class="sxs-lookup"><span data-stu-id="219ee-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="219ee-113">ATP включен в Office 365 корпоративный E5, Office 365 Education A5 и Microsoft 365 для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="219ee-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="219ee-114">Функции анализа зависит от клиента в Microsoft 365 Business будут доступны 2018 лето.</span><span class="sxs-lookup"><span data-stu-id="219ee-114">Client-dependent ATP features in Microsoft 365 Business will be available Summer 2018.</span></span> 
  
<span data-ttu-id="219ee-115">Можно добавить Advanced Threat Protection в следующие планы подписки на Exchange и Office 365:</span><span class="sxs-lookup"><span data-stu-id="219ee-115">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span> 
  
- <span data-ttu-id="219ee-116">Exchange Online (план 1)</span><span class="sxs-lookup"><span data-stu-id="219ee-116">Exchange Online Plan 1</span></span>
    
- <span data-ttu-id="219ee-117">Exchange Online (план 2)</span><span class="sxs-lookup"><span data-stu-id="219ee-117">Exchange Online Plan 2</span></span>
    
- <span data-ttu-id="219ee-118">Базовая подписка на Exchange Online</span><span class="sxs-lookup"><span data-stu-id="219ee-118">Exchange Online Kiosk</span></span>
    
- <span data-ttu-id="219ee-119">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="219ee-119">Exchange Online Protection</span></span>
    
- <span data-ttu-id="219ee-120">Office 365 бизнес базовый</span><span class="sxs-lookup"><span data-stu-id="219ee-120">Office 365 Business Essentials</span></span>
    
- <span data-ttu-id="219ee-121">Office 365 бизнес премиум</span><span class="sxs-lookup"><span data-stu-id="219ee-121">Office 365 Business Premium</span></span>
    
- <span data-ttu-id="219ee-122">Office 365 для предприятий E1</span><span class="sxs-lookup"><span data-stu-id="219ee-122">Office 365 Enterprise E1</span></span>
    
- <span data-ttu-id="219ee-123">Office 365 для предприятий E3</span><span class="sxs-lookup"><span data-stu-id="219ee-123">Office 365 Enterprise E3</span></span>
    
- <span data-ttu-id="219ee-124">Office 365 корпоративный F1</span><span class="sxs-lookup"><span data-stu-id="219ee-124">Office 365 Enterprise F1</span></span>
    
- <span data-ttu-id="219ee-125">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="219ee-125">Office 365 A1</span></span>
    
- <span data-ttu-id="219ee-126">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="219ee-126">Office 365 A3</span></span>
    
<span data-ttu-id="219ee-127">Сведения о приобретении Office 365 Advanced Threat Protection см. на странице [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).</span><span class="sxs-lookup"><span data-stu-id="219ee-127">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).</span></span>
  
<span data-ttu-id="219ee-128">Сравнение функций в разных планах см. на странице [Сравнение планов Office 365 для бизнеса](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="219ee-128">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span></span>
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="219ee-129">Новые возможности Office 365 Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="219ee-129">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="219ee-130">Сведения о новых функциях в ATP см. в статье [Безопасные ссылки ATP в Office 365](https://go.microsoft.com/fwlink/?linkid=846016).</span><span class="sxs-lookup"><span data-stu-id="219ee-130">For information about new features in ATP, see [ATP safe links in Office 365](https://go.microsoft.com/fwlink/?linkid=846016).</span></span>
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="219ee-131">Требования для Office 365 Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="219ee-131">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="219ee-p104">ATP можно использовать с любым агентом передачи почты по протоколу SMTP, например Microsoft Exchange Server 2013. Сведения о поддерживаемых EOP операционных системах, веб-браузерах и языках см. в подразделах "Поддерживаемые браузеры" и "Поддерживаемые языки" статьи [Центр администрирования Exchange в Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span><span class="sxs-lookup"><span data-stu-id="219ee-p104">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server 2013. For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="219ee-134">Доступность функций в планах Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="219ee-134">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="219ee-p105">Каждая функция приведена ниже. Exchange Online обычно относят к семейству служб Office 365 корпоративный.</span><span class="sxs-lookup"><span data-stu-id="219ee-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>
  
|<span data-ttu-id="219ee-137">**Функция**</span><span class="sxs-lookup"><span data-stu-id="219ee-137">**Feature**</span></span>|<span data-ttu-id="219ee-138">**Отдельная служба ATP**</span><span class="sxs-lookup"><span data-stu-id="219ee-138">**ATP standalone**</span></span>|<span data-ttu-id="219ee-139">**Exchange Online Protection**</span><span class="sxs-lookup"><span data-stu-id="219ee-139">**Exchange Online Protection**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="219ee-140">Безопасные ссылки</span><span class="sxs-lookup"><span data-stu-id="219ee-140">Safe Links</span></span>  <br/> |<span data-ttu-id="219ee-141">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-141">Yes</span></span>  <br/> |<span data-ttu-id="219ee-142">Нет</span><span class="sxs-lookup"><span data-stu-id="219ee-142">No</span></span>  <br/> |
|<span data-ttu-id="219ee-143">Безопасные вложения</span><span class="sxs-lookup"><span data-stu-id="219ee-143">Safe Attachments</span></span>  <br/> |<span data-ttu-id="219ee-144">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-144">Yes</span></span>  <br/> |<span data-ttu-id="219ee-145">Нет</span><span class="sxs-lookup"><span data-stu-id="219ee-145">No</span></span>  <br/> |
|<span data-ttu-id="219ee-146">Аналитическая защита от подделок</span><span class="sxs-lookup"><span data-stu-id="219ee-146">Spoof intelligence</span></span>  <br/> |<span data-ttu-id="219ee-147">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-147">Yes</span></span>  <br/> |<span data-ttu-id="219ee-148">Нет</span><span class="sxs-lookup"><span data-stu-id="219ee-148">No</span></span>  <br/> |
|<span data-ttu-id="219ee-149">Карантин</span><span class="sxs-lookup"><span data-stu-id="219ee-149">Quarantine</span></span>  <br/> |<span data-ttu-id="219ee-150">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-150">Yes</span></span>  <br/> |<span data-ttu-id="219ee-151">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-151">Yes</span></span>  <br/> |
|<span data-ttu-id="219ee-152">Расширенные возможности защиты от фишинга</span><span class="sxs-lookup"><span data-stu-id="219ee-152">Advanced anti-phishing capabilities</span></span>  <br/> |<span data-ttu-id="219ee-153">Да</span><span class="sxs-lookup"><span data-stu-id="219ee-153">Yes</span></span>  <br/> |<span data-ttu-id="219ee-154">Нет</span><span class="sxs-lookup"><span data-stu-id="219ee-154">No</span></span>  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="219ee-155">Возможности Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="219ee-155">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-links"></a><span data-ttu-id="219ee-156">Безопасные ссылки</span><span class="sxs-lookup"><span data-stu-id="219ee-156">Safe Links</span></span>

<span data-ttu-id="219ee-p106">Компонент анализа безопасных ссылки проактивное пользователи будут защищены от опасных гиперссылок в сообщении. Защита остается каждый раз, когда они щелкните ссылку вредоносных ссылки динамически блокируются во время доступных хороший связи.</span><span class="sxs-lookup"><span data-stu-id="219ee-p106">The ATP Safe Links feature proactively protects your users from malicious hyperlinks in a message. The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>
  
### <a name="safe-attachments"></a><span data-ttu-id="219ee-159">Безопасные вложения</span><span class="sxs-lookup"><span data-stu-id="219ee-159">Safe Attachments</span></span>

<span data-ttu-id="219ee-p107">Функция безопасных вложений обеспечивает защиту от неизвестных вредоносных программ и вирусов, а также обеспечивает защиту системы обмена сообщениями от вирусов "нулевого дня". Все сообщения и вложения, не содержащие известную сигнатуру вируса или вредоносной программы, направляются в специальную среду, где ATP использует ряд методик машинного обучения и анализа для обнаружения преступных намерений. Если подозрительные действия не обнаружены, сообщение отправляется для доставки в почтовый ящик.</span><span class="sxs-lookup"><span data-stu-id="219ee-p107">Safe Attachments protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system. All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent. If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span> 
  
### <a name="spoof-intelligence"></a><span data-ttu-id="219ee-163">Аналитическая защита от подделок</span><span class="sxs-lookup"><span data-stu-id="219ee-163">Spoof intelligence</span></span>

<span data-ttu-id="219ee-p108">Подделка аналитики определяет, когда отправитель оказывается отправлять почту от имени одного или нескольких учетных записей пользователей в одном из доменов вашей организации. Она позволяет просмотрите всех отправителей, которые спуфинг вашего домена, а затем выберите Разрешить отправителю заблокировать отправителя. Подделка аналитики доступна в безопасности &amp; центре соответствия требованиям на странице параметров защиты от нежелательной почты.</span><span class="sxs-lookup"><span data-stu-id="219ee-p108">Spoof intelligence detects when a sender appears to be sending mail on behalf of one or more user accounts within one of your organization's domains. It enables you to review all senders who are spoofing your domain, and then choose to allow the sender to continue or block the sender. Spoof intelligence is available in the Security &amp; Compliance Center on the Anti-spam settings page.</span></span>
  
### <a name="quarantine"></a><span data-ttu-id="219ee-167">Карантин</span><span class="sxs-lookup"><span data-stu-id="219ee-167">Quarantine</span></span>

<span data-ttu-id="219ee-p109">Сообщения, идентифицированные службой Office 365 как спам, массовая рассылка, фишинг-почта, содержащая вредоносное ПО, или подпадающие под правило обработки почтового потока, могут быть отправлены в карантин. Фишинговые сообщения и сообщения, содержащие вредоносное ПО, по умолчанию отправляются непосредственно в карантин. Авторизованные пользователи могут просматривать, удалять сообщения электронной почты, отправленные в карантин, или управлять ими.</span><span class="sxs-lookup"><span data-stu-id="219ee-p109">Messages identified by the Office 365 service as spam, bulk mail, phishing mail, containing malware, or because they matched a mail flow rule can be sent to quarantine. By default, Office 365 sends phishing messages and messages containing malware directly to quarantine. Authorized users can review, delete, or manage email messages sent to quarantine.</span></span>
  
### <a name="advanced-anti-phishing-capabilities"></a><span data-ttu-id="219ee-171">Расширенные возможности защиты от фишинга</span><span class="sxs-lookup"><span data-stu-id="219ee-171">Advanced anti-phishing capabilities</span></span>

<span data-ttu-id="219ee-172">Эта функция использует модели машинного обучения для обнаружения фишинговых сообщений.</span><span class="sxs-lookup"><span data-stu-id="219ee-172">This feature uses machine learning models to detect phishing messages.</span></span> 
  
