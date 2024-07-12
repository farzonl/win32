---
description: 
nms.assetid:
title: or
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- or
api_type:
- NA
---


# or




## Syntax


```syntax
bool<> or(any<> x, any<> y);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool** | any |
| *x* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |
| *y* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|HLSL 2021 and higher shader models | yes |

## Shader Stages


## Remarks

In HLSL 2021 `or(X, Y);` is a replacement for
```hlsl
int3 X = {1, 1, 1};
int3 Y = {0, 0, 0};
bool3 Cond = X || Y;
```

## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [HLSL 2021 Logical operation short-circuiting for scalars](https://github.com/microsoft/DirectXShaderCompiler/wiki/HLSL-2021#logical-operation-short-circuiting-for-scalars)**