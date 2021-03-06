---
UID: NN:dbgmodel.IDebugHostExtensibility
title: IDebugHostExtensibility (dbgmodel.h)
description: The extensibility interface to the underlying debugger.
ms.assetid: ca0b53b7-9e3a-4dca-ab84-0e147006ac32
ms.date: 07/13/2018
ms.topic: interface
req.header: dbgmodel.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.umdf-ver:
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
- apiref
api_type: 
- COM
api_location: 
- dbgmodel.h
api_name: 
- IDebugHostExtensibility
product:
- Windows
targetos: Windows
tech.root: debugger
ms.custom: RS5
---

# IDebugHostExtensibility interface

## -description

The extensibility interface to the underlying debugger.


## -inheritance
IDebugHostExtensibility interits from IUnknown. 
## -members

<p>IDebugHostExtensibility has these methods.</p>
<table>
	<tr>
		<td>Method</td>
		<td>Description</td>
	</tr>
	<tr>
		<td>QueryInterface</td>
		<td>TBD</td>
	</tr>
	<tr>
		<td>AddRef</td>
		<td>TBD</td>
	</tr>
	<tr>
		<td>Release</td>
		<td>TBD</td>
	</tr>
	<tr>
		<td>CreateFunctionAlias</td>
		<td>TBD</td>
	</tr>
	<tr>
		<td>DestroyFunctionAlias</td>
		<td>TBD</td>
	</tr>
</table>

## -remarks

Certain functionality of the debug host is optionally subject to extensibility. This may, for instance, include the expression evaluator. The IDebugHostExtensibility interface is the means by which these extensibility points are accessed. 

## -see-also

[Debugger Data Model C++ Overview](https://docs.microsoft.com/windows-hardware/drivers/debugger/data-model-cpp-overview)
