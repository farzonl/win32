---
description: 
nms.assetid:
title: InterlockedCompareExchangeFloatBitwise
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- InterlockedCompareExchangeFloatBitwise
api_type:
- NA
---


# InterlockedCompareExchangeFloatBitwise




## Syntax


```syntax
void InterlockedCompareExchangeFloatBitwise(float32_only result, float compare, float value, float original);
```

```syntax
void InterlockedCompareExchangeFloatBitwise(uint byteOffest, float compare, float value, float original);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *result* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *compare* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *value* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *original* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | **void** | **void** | 0 |
| *byteOffest* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**uint**](../WinProg/windows-data-types) | 1 |
| *compare* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *value* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |
| *original* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|[Shader Model 6.3](https://github.com/microsoft/DirectXShaderCompiler/wiki/Shader-Model-6.3) and higher shader models | yes |

## Shader Stages



## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [InterlockedCompareStoreFloatBitwise](https://microsoft.github.io/DirectX-Specs/d3d/HLSL_SM_6_6_Int64_and_Float_Atomics.html#interlockedcompareexchange)**