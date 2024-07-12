---
description: 
nms.assetid:
title: select
ms.topic: reference
ms.date: 07/12/2024
topic_type:
- APIRef
- kbSyntax
api_name:
- select
api_type:
- NA
---


# select




## Syntax


```syntax
any<> select(bool<> cond, any<> t, any<> f);
```

```syntax
any_sampler select(bool cond, any_sampler t, any_sampler f);
```


## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |
| *cond* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool** | any |
| *t* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |
| *f* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md), [**vector**](../direct3dhlsl/dx-graphics-hlsl-vector.md), or [**matrix**](../direct3dhlsl/dx-graphics-hlsl-matrix.md) | **bool**, [**float**](../WinProg/windows-data-types), or [**int**](../WinProg/windows-data-types) | any |
## Type Description

| Name  | [**Template Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md)| [**Component Type**](../direct3dhlsl/dx-graphics-hlsl-data-types.md) | Size |
|-------|--------------------------------------------------------------------|----------------------------------------------------------------------|------|
| *ret* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types), [**int**](../WinProg/windows-data-types), or [**uint**](../WinProg/windows-data-types) | 1 |
| *cond* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | **bool** | 1 |
| *t* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types), [**int**](../WinProg/windows-data-types), or [**uint**](../WinProg/windows-data-types) | 1 |
| *f* | [**scalar**](../direct3dhlsl/dx-graphics-hlsl-scalar.md) | [**float**](../WinProg/windows-data-types), [**int**](../WinProg/windows-data-types), or [**uint**](../WinProg/windows-data-types) | 1 |

## Minimum Shader Model

This function is supported in the following shader models.
|Shader Model |	Supported|
|-------------|----------|
|HLSL 2021 and higher shader models | yes |

## Shader Stages


## Remarks

In HLSL 2021 `int3 Z = select(X, 1, 0);` is a replacement for
```hlsl
int3 X = {1, 1, 1};
int3 Z = X ? 1 : 0;
```

## See also


- [**Intrinsic Functions (DirectX HLSL)**](../direct3dhlsl/dx-graphics-hlsl-intrinsic-functions.md)
- **See [HLSL 2021 Logical operation short-circuiting for scalars](https://github.com/microsoft/DirectXShaderCompiler/wiki/HLSL-2021#logical-operation-short-circuiting-for-scalars)**