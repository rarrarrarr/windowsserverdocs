---
title: ftp: lcd
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 60a25808-6abb-408b-8373-0bbdcd0994b4 vhorne
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# ftp: lcd

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

changes the working directory on the local computer. By default, the working directory is the directory in which **ftp** was started.   
## Syntax  
```  
lcd [<directory>]  
```  
### Parameters  
|Parameter|Description|  
|-------|--------|  
|[<directory>]|Specifies the directory on the local computer to which to change. if *directory* is not specified, the current working directory is changed to the default directory.|  
## <a name="BKMK_Examples"></a>Examples  
change the working directory on the local computer to **C:\dir1**  
```  
lcd C:\dir1  
```  
## additional references  
-   [Command-Line Syntax Key](command-line-syntax-key.md)  