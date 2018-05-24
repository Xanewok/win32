﻿---
Description: 'Builds a left-handed orthographic projection matrix.'
ms.assetid: '67bec4a3-2126-4f5a-9301-97faa6dc6e84'
title: D3DXMatrixOrthoLH function
---

# D3DXMatrixOrthoLH function

Builds a left-handed orthographic projection matrix.

## Syntax


```C++
D3DXMATRIX* D3DXMatrixOrthoLH(
  _Inout_ D3DXMATRIX *pOut,
  _In_    FLOAT      w,
  _In_    FLOAT      h,
  _In_    FLOAT      zn,
  _In_    FLOAT      zf
);
```



## Parameters

<dl> <dt>

*pOut* \[in, out\]
</dt> <dd>

Type: **[**D3DXMATRIX**](direct3d9.d3dxmatrix)\***

Pointer to the resulting [**D3DXMATRIX**](d3d10-d3dxmatrix.md).

</dd> <dt>

*w* \[in\]
</dt> <dd>

Type: **[**FLOAT**](winprog.windows_data_types)**

Width of the view volume.

</dd> <dt>

*h* \[in\]
</dt> <dd>

Type: **[**FLOAT**](winprog.windows_data_types)**

Height of the view volume.

</dd> <dt>

*zn* \[in\]
</dt> <dd>

Type: **[**FLOAT**](winprog.windows_data_types)**

Minimum z-value of the view volume which is referred to as z-near.

</dd> <dt>

*zf* \[in\]
</dt> <dd>

Type: **[**FLOAT**](winprog.windows_data_types)**

Maximum z-value of the view volume which is referred to as z-far.

</dd> </dl>

## Return value

Type: **[**D3DXMATRIX**](direct3d9.d3dxmatrix)\***

Pointer to the resulting [**D3DXMATRIX**](d3d10-d3dxmatrix.md).

## Remarks

All the parameters of the D3DXMatrixOrthoLH function are distances in camera space. The parameters describe the dimensions of the view volume.

The return value for this function is the same value returned in the pOut parameter. In this way, the D3DXMatrixOrthoLH function can be used as a parameter for another function.

This function uses the following formula to compute the returned matrix.


```
2/w  0    0           0
0    2/h  0           0
0    0    1/(zf-zn)   0
0    0    zn/(zn-zf)  1
```



## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3DX10Math.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3DX10.lib</dt> </dl>   |



## See also

<dl> <dt>

[Math Functions](d3d10-graphics-reference-d3dx10-functions-math.md)
</dt> </dl>

 

 



