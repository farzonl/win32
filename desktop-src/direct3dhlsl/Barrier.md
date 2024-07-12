---
description: 
nms.assetid:
title: Barrier
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- Barrier
api_type:
- NA
---


# Barrier




## Syntax


```syntax
void Barrier(uint MemoryTypeFlags, uint SemanticFlags);
```

```syntax
void Barrier(NodeRecordOrUAV o, uint SemanticFlags);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *MemoryTypeFlags* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *SemanticFlags* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *o* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) |  | 1 |
| *SemanticFlags* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.8](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_ShaderModel6_8) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [Work Graphs Barrier Types](https://microsoft.github.io/DirectX-Specs/d3d/WorkGraphs.html#barrier)**