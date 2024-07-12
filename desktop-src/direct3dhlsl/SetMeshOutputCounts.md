---
description: 
nms.assetid:
title: SetMeshOutputCounts
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- SetMeshOutputCounts
api_type:
- NA
---


# SetMeshOutputCounts




## Syntax


```syntax
void SetMeshOutputCounts(uint numVertices, uint numPrimitives);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *numVertices* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *numPrimitives* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.5](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_ShaderModel6_5) and higher shader models | yes |

## Shader Stages

* [**Mesh Shader**](https://microsoft.github.io/DirectX-Specs/d3d/MeshShader.html)


## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [SetMeshOutputCounts](https://microsoft.github.io/DirectX-Specs/d3d/MeshShader.html#setmeshoutputcounts)**