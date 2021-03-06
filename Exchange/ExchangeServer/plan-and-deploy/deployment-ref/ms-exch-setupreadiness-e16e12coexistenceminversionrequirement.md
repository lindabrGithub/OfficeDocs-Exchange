---
title: "Can't install Exchange 2016 in a forest that contains Exchange 2007 servers [E16E12CoexistenceMinVersionRequirement]"
ms.author: dstrome
author: dstrome
manager: serdars
ms.date: 4/19/2018
ms.audience: Developer
ms.topic: reference
f1_keywords:
- 'ms.exch.setupreadiness.E16E12CoexistenceMinVersionRequirement'
ms.prod: exchange-server-itpro
localization_priority: Normal
ms.assetid: 4e1b9510-3188-43eb-9252-7c64cb2bc0e3
description: "Microsoft Exchange Server 2016 can't continue because one or more computers are running Exchange 2007 or older were found in the Active Directory forest. Before you can install Exchange 2016, all computers running Exchange 2007 or older must be removed from the forest. Mailboxes, public folders, and all other Exchange objects or components must be upgraded to the latest release of Exchange Server 2010."
---

# Can't install Exchange 2016 in a forest that contains Exchange 2007 servers [E16E12CoexistenceMinVersionRequirement]

Microsoft Exchange Server 2016 can't continue because one or more computers are running Exchange 2007 or older were found in the Active Directory forest. Before you can install Exchange 2016, all computers running Exchange 2007 or older must be removed from the forest. Mailboxes, public folders, and all other Exchange objects or components must be upgraded to the latest release of Exchange Server 2010.
  
The path you need to follow to install Exchange 2016 in your organization depends on the version of Exchange you currently have installed in your forest. See the following table for more information.
  
|**If you have the following installed in your organization**|**You must take this path to upgrade to Exchange 2016**|
|:-----|:-----|
|Exchange 2000  <br/> |1. Install Exchange 2007 into your Exchange 2000 organization.  <br/> 2. Configure Exchange 2007 and Exchange 2000 coexistence.  <br/> 3. Migrate Exchange 2000 mailboxes, public folders, and other components to Exchange 2007.  <br/> 4. Decommission and remove all Exchange 2000 servers.  <br/> 5. Install Exchange 2013 into your Exchange 2007 organization.  <br/> 6. Configure Exchange 2013 and Exchange 2007 coexistence.  <br/> 7. Migrate Exchange 2007 mailboxes, public folders, and other components to Exchange 2013.  <br/> 8. Decommission and remove all Exchange 2007 servers.  <br/> 9. Install Exchange 2016 into your Exchange 2013 organization.  <br/> 10. Configure Exchange 2016 and Exchange 2013 coexistence.  <br/> 11. Migrate Exchange 2013 mailboxes, public folders, and other components to Exchange 2016.  <br/> 12. Decommission and remove all Exchange 2013 servers.  <br/> |
|Exchange 2003  <br/> |1. Install Exchange 2010 into your Exchange 2003 organization.  <br/> 2. Configure Exchange 2010 and Exchange 2003 coexistence.  <br/> 3. Migrate Exchange 2003 mailboxes, public folders, and other components to Exchange 2010.  <br/> 4. Decommission and remove all Exchange 2003 servers.  <br/> 5. Install Exchange 2016 into your Exchange 2010 organization.  <br/> 6. Configure Exchange 2016 and Exchange 2010 coexistence.  <br/> 7. Migrate Exchange 2010 mailboxes, public folders, and other components to Exchange 2016.  <br/> 8. Decommission and remove all Exchange 2010 servers.  <br/> |
|Exchange 2007  <br/> |1. Install Exchange 2013 into your Exchange 2007 organization.  <br/> 2. Configure Exchange 2013 and Exchange 2007 coexistence.  <br/> 3. Migrate Exchange 2007 mailboxes, public folders, and other components to Exchange 2013.  <br/> 4. Decommission and remove all Exchange 2007 servers.  <br/> 5. Install Exchange 2016 into your Exchange 2013 organization.  <br/> 6. Configure Exchange 2016 and Exchange 2013 coexistence.  <br/> 7. Migrate Exchange 2013 mailboxes, public folders, and other components to Exchange 2016.  <br/> 8. Decommission and remove all Exchange 2013 servers.  <br/> |
   
When upgrading to Exchange 2010 or later, you can use the Exchange Deployment Assistant to help you complete your deployment. For more information, see the following links:
  
- [Exchange 2010 Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=171086)
    
- [Exchange 2013 Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=277105)
    
Having problems? Ask for help in the Exchange forums. Visit the forums at: [Exchange Server](https://go.microsoft.com/fwlink/p/?linkId=60612), [Exchange Online](https://go.microsoft.com/fwlink/p/?linkId=267542), or [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?linkId=285351).
  
Did you find what you're looking for? Please take a minute to [send us feedback](mailto:ExchangeHelpFeedback@microsoft.com&subject=Exchange%202016%20help%20feedback&Body=Thanks%20for%20taking%20the%20time%20to%20send%20us%20feedback!%20We%20strive%20to%20respond%20to%20every%20message%20we%20receive,%20even%20though%20it%20might%20take%20us%20a%20while.%20Let%20us%20know%20what%20you%20think%20about%20Exchange%20content:%20What%20are%20we%20doing%20right%3F%20How%20can%20we%20make%20help%20better%3F%0APlease%20note%20that%20we're%20unable%20to%20respond%20to%20requests%20for%20support%20submitted%20via%20this%20email%20address.%20If%20you%20need%20help,%20please%20contact%20Exchange%20Server%20support%20at%20http://go.microsoft.com/fwlink/p/%3FLinkId=402506.%0AThanks!%0AThe%20Exchange%20Server%20Content%20Publishing%20team) about the information you were hoping to find.
  

