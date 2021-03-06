---
title: "Max degree of parallelism & Policy-Based Management"
description: Describes configuring a policy to verify the value of max degree of parallelism for Policy-Based Management for SQL Server. 
ms.custom: seo-lt-2019
ms.date: "07/18/2019"
ms.prod: sql
ms.prod_service: "database-engine"
ms.reviewer: ""
ms.technology: security
ms.topic: conceptual
helpviewer_keywords: 
  - "Best Practices [Database Engine]"
ms.assetid: ec908006-67ae-4674-9a61-25ea741d6197
author: VanMSFT
ms.author: vanto
---
# Set the Max Degree of Parallelism Option for Optimal Performance
[!INCLUDE[appliesto-ss-xxxx-xxxx-xxx-md](../../includes/appliesto-ss-xxxx-xxxx-xxx-md.md)]
  This rule determines whether the max degree of parallelism (MAXDOP) option for a value greater than 8. Setting this option to a larger value often causes unwanted resource consumption and performance degradation.  
  
## Best Practices Recommendations  
 Set the max degree of parallelism option to 8 or less by using sp_configure.  
  
## For More Information  
 [Recommendations and guidelines for the max degree of parallelism configuration option in SQL Server](https://go.microsoft.com/fwlink/?linkid=117786)  
  
 [Configure the max degree of parallelism Server Configuration Option](../../database-engine/configure-windows/configure-the-max-degree-of-parallelism-server-configuration-option.md)  
  
 [sp_configure &#40;Transact-SQL&#41;](../../relational-databases/system-stored-procedures/sp-configure-transact-sql.md)  
  
  
