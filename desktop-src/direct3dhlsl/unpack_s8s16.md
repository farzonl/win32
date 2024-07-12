---
description: 
nms.assetid:
title: unpack_s8s16
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- unpack_s8s16
api_type:
- NA
---


# unpack_s8s16




## Syntax


```syntax
int16_t<4> unpack_s8s16(p32i8 pk);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md) | [**int16_t**](https://github.com/microsoft/DirectXShaderCompiler/wiki/16-Bit-Scalar-Types) | 4 |
| *pk* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**int8_t4_packed**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.6](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_ShaderModel6_6) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [Unpack Intrinsics](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_SM_6_6_Pack_Unpack_Intrinsics#unpack-intrinsics)**