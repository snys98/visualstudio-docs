---
title: "IEnumDebugPropertyInfo2::GetCount | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IEnumDebugPropertyInfo2::GetCount"
helpviewer_keywords: 
  - "IEnumDebugPropertyInfo2::GetCount"
ms.assetid: 9b0b3ce6-08cb-46fd-a6d9-92b36e60da19
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# IEnumDebugPropertyInfo2::GetCount
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IEnumDebugPropertyInfo2::GetCount](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/ienumdebugpropertyinfo2-getcount).  
  
Returns the number of elements in the enumeration.  
  
## Syntax  
  
```cpp#  
HRESULT GetCount(  
   ULONG* pcelt  
);  
```  
  
```csharp  
int GetCount(  
   out uint pcelt  
);  
```  
  
#### Parameters  
 `pcelt`  
 [out] Returns the number of elements in the enumeration.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 This method is not part of the customary COM enumeration interface which specifies that only the `Next`, `Clone`, `Skip`, and `Reset` methods need to be implemented.  
  
## See Also  
 [IEnumDebugPropertyInfo2](../../../extensibility/debugger/reference/ienumdebugpropertyinfo2.md)

