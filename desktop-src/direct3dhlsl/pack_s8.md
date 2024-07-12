---
description: 
nms.assetid:
title: pack_s8
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- pack_s8
api_type:
- NA
---


# pack_s8




## Syntax


```syntax
p32i8 pack_s8(any_int16or32<4> v);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**int8_t4_packed**](../WinProg/windows-data-types) | 1 |
| *v* | [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md) | [**int**](../WinProg/windows-data-types), [**int16_t**](https://github.com/microsoft/DirectXShaderCompiler/wiki/16-Bit-Scalar-Types), [**uint**](../WinProg/windows-data-types), or [**uint16_t**](https://github.com/microsoft/DirectXShaderCompiler/wiki/16-Bit-Scalar-Types) | 4 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.6](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_ShaderModel6_6) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [Pack Intrinsics](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_SM_6_6_Pack_Unpack_Intrinsics#pack-intrinsics)**