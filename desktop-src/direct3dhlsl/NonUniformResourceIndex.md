---
description: 
nms.assetid:
title: NonUniformResourceIndex
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- NonUniformResourceIndex
api_type:
- NA
---


# NonUniformResourceIndex




## Syntax


```syntax
any<> NonUniformResourceIndex(any<> index);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |
| *index* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6](../direct3dhlsl/shader-model-6-0.md) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [NonUniformResourceIndex semantics](https://microsoft.github.io/DirectX-Specs/d3d/WorkGraphs#nonuniformresourceindex-semantics)**
 - [**Resource Binding**](../direct3d12/resource-binding-in-hlsl.md).