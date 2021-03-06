---
title: "IDebugProgramPublisher2::UnpublishProgramNode | Microsoft Docs"
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
  - "IDebugProgramPublisher2::UnpublishProgramNode"
helpviewer_keywords: 
  - "IDebugProgramPublisher2::UnpublishProgramNode"
ms.assetid: 57c7e6e1-b84e-4e14-ad83-cbbb64e2f526
caps.latest.revision: 9
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugProgramPublisher2::UnpublishProgramNode
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugProgramPublisher2::UnpublishProgramNode](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugprogrampublisher2-unpublishprogramnode).  
  
Removes a specified program node from availability to debug engines (DEs) and the session debug manager (SDM).  
  
## Syntax  
  
```cpp  
HRESULT UnpublishProgramNode(  
   IDebugProgramNode2* pProgramNode  
);  
```  
  
```csharp  
int UnpublishProgramNode(  
   IDebugProgramNode2 pProgramNode  
);  
```  
  
#### Parameters  
 `pProgramNode`  
 [in] An [IDebugProgramNode2](../../../extensibility/debugger/reference/idebugprogramnode2.md) object representing the program node being removed.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 Once removed, the program node is no longer available to be queried for program information.  
  
 To make a program node available, call the [PublishProgramNode](../../../extensibility/debugger/reference/idebugprogrampublisher2-publishprogramnode.md) method.  
  
## See Also  
 [IDebugProgramPublisher2](../../../extensibility/debugger/reference/idebugprogrampublisher2.md)   
 [IDebugProgramNode2](../../../extensibility/debugger/reference/idebugprogramnode2.md)   
 [PublishProgramNode](../../../extensibility/debugger/reference/idebugprogrampublisher2-publishprogramnode.md)

