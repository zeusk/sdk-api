---
UID: NE:wpcevent.tagWPC_ARGS_EMAILRECEIEVEDEVENT
title: WPC_ARGS_EMAILRECEIEVEDEVENT (wpcevent.h)
description: Indicates information about an email message that has been received.
old-location: parcon\wpc_args_emailreceivedevent.htm
tech.root: parcon
ms.assetid: 6d3076cb-445b-463a-8f04-264438304c37
ms.date: 12/05/2018
ms.keywords: WPC_ARGS_EMAILRECEIEVEDEVENT, WPC_ARGS_EMAILRECEIEVEDEVENT enumeration, WPC_ARGS_EMAILRECEIEVEDEVENT_APPNAME, WPC_ARGS_EMAILRECEIEVEDEVENT_APPVERSION, WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHCOUNT, WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHMENTNAME, WPC_ARGS_EMAILRECEIEVEDEVENT_CARGS, WPC_ARGS_EMAILRECEIEVEDEVENT_EMAILACCOUNT, WPC_ARGS_EMAILRECEIEVEDEVENT_REASON, WPC_ARGS_EMAILRECEIEVEDEVENT_RECEIVEDTIME, WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPCOUNT, WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPIENT, WPC_ARGS_EMAILRECEIEVEDEVENT_SENDER, WPC_ARGS_EMAILRECEIEVEDEVENT_SUBJECT, WPC_ARGS_EMAILRECEIVEDEVENT, parcon.wpc_args_emailreceivedevent, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_APPNAME, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_APPVERSION, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHCOUNT, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHMENTNAME, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_CARGS, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_EMAILACCOUNT, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_REASON, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_RECEIVEDTIME, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPCOUNT, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPIENT, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_SENDER, wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT_SUBJECT
ms.topic: enum
f1_keywords:
- wpcevent/WPC_ARGS_EMAILRECEIEVEDEVENT
dev_langs:
- c++
req.header: wpcevent.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Wpcevent.h
api_name:
- WPC_ARGS_EMAILRECEIEVEDEVENT
targetos: Windows
req.typenames: WPC_ARGS_EMAILRECEIEVEDEVENT
req.redist: 
ms.custom: 19H1
---

# WPC_ARGS_EMAILRECEIEVEDEVENT enumeration


## -description


Indicates information about an email message that has been received.


## -enum-fields




### -field WPC_ARGS_EMAILRECEIEVEDEVENT_SENDER

The sender who sent the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_APPNAME

The name of the application that sent the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_APPVERSION

The version of the application that sent the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_SUBJECT

The subject line of the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_REASON

The reason given for the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPCOUNT

The number of accounts that received the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_RECIPIENT

The recipient account that received the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHCOUNT

The number of attachments in the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_ATTACHMENTNAME

The name of the attachment in the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_RECEIVEDTIME

The time that the email message was received.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_EMAILACCOUNT

The email account that sent the email message.


### -field WPC_ARGS_EMAILRECEIEVEDEVENT_CARGS

The arguments for the email message.

