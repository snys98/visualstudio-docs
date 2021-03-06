---
title: "IDebugProgramNode2::DetachDebugger_V7 | Microsoft Docs"
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
  - "IDebugProgramNode2::DetachDebugger"
helpviewer_keywords: 
  - "IDebugProgramNode2::DetachDebugger"
  - "IDebugProgramNode2::DetachDebugger_V7"
ms.assetid: d2d4b78e-a2dd-4217-97a6-ab648fd2ee2f
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugProgramNode2::DetachDebugger_V7
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugProgramNode2::DetachDebugger_V7](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugprogramnode2-detachdebugger-v7).  
  
DEPRECATED. DO NOT USE.  
  
## Syntax  
  
```cpp#  
HRESULT DetachDebugger_V7 (   
   void   
);  
```  
  
```csharp  
int DetachDebugger_V7 ();  
```  
  
## Return Value  
 An implementation should always return `E_NOTIMPL`.  
  
## Remarks  
  
> [!WARNING]
>  As of [!INCLUDE[vsprvslong](../../../includes/vsprvslong-md.md)], this method is no longer used and should always return `E_NOTIMPL`.  
  
 This method is called when the debugger unexpectedly quits. When this method is called, the DE should resume the program as though the user detached from it. No more debug events should be sent. The program should be in a state where it is attachable from another instance of the debugger.  
  
## See Also  
 [IDebugProgramNode2](../../../extensibility/debugger/reference/idebugprogramnode2.md)

