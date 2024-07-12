---
description: 
nms.assetid:
title: dot2add
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- dot2add
api_type:
- NA
---


# dot2add




## Syntax


```syntax
float dot2add(float16_t<2> a, float16_t<2> b, float c);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *a* | [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md) | [**half**](https://github.com/microsoft/DirectXShaderCompiler/wiki/16-Bit-Scalar-Types) | 2 |
| *b* | [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md) | [**half**](https://github.com/microsoft/DirectXShaderCompiler/wiki/16-Bit-Scalar-Types) | 2 |
| *c* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.4](../direct3dhlsl/hlsl-shader-model-6-4-features-for-direct3d-12.md) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [Single Precision Floating Point 2-Element Dot-Product and Accumulate](../direct3dhlsl/hlsl-shader-model-6-4-features-for-direct3d-12.md#signed-integer-dot-product-of-4-elements-and-accumulate)**