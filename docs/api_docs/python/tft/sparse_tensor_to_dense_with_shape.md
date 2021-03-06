<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tft.sparse_tensor_to_dense_with_shape" />
<meta itemprop="path" content="Stable" />
</div>

# tft.sparse_tensor_to_dense_with_shape

``` python
tft.sparse_tensor_to_dense_with_shape(
    x,
    shape,
    default_value=0
)
```

Converts a `SparseTensor` into a dense tensor and sets its shape.

#### Args:

* <b>`x`</b>: A `SparseTensor`.
* <b>`shape`</b>: The desired shape of the densified `Tensor`.
* <b>`default_value`</b>: (Optional) Value to set for indices not specified. Defaults
    to zero.


#### Returns:

A `Tensor` with the desired shape.


#### Raises:

* <b>`ValueError`</b>: If input is not a `SparseTensor`.