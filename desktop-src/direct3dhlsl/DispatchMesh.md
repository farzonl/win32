---
description: 
nms.assetid:
title: DispatchMesh
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- DispatchMesh
api_type:
- NA
---


# DispatchMesh




## Syntax


```syntax
void DispatchMesh(uint threadGroupCountX, uint threadGroupCountY, uint threadGroupCountZ, udt meshPayload);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *threadGroupCountX* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *threadGroupCountY* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *threadGroupCountZ* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *meshPayload* | [**RayPayload**](../direct3d12/ray-payload.md) [**Struct**](../direct3dhlsl/dx-graphics-hlsl-struct.md) | **RayPayload** | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.5](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_ShaderModel6_5) and higher shader models | yes |

## Shader Stages

* [**Amplification Shader**](https://microsoft.github.io/DirectX-Specs/d3d/MeshShader.html#amplification-shader-and-mesh-shader)


## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [DispatchMesh - intrinsic](https://microsoft.github.io/DirectX-Specs/d3d/MeshShader.html#dispatchmesh-intrinsic)**