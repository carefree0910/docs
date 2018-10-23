

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.argmax

### `tf.argmax`

``` python
argmax(
    input,
    axis=None,
    name=None,
    dimension=None
)
```



Defined in [`tensorflow/python/ops/math_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.1/tensorflow/python/ops/math_ops.py).

See the guide: [Math > Sequence Comparison and Indexing](../../../api_guides/python/math_ops#Sequence_Comparison_and_Indexing)

Returns the index with the largest value across axes of a tensor.

#### Args:

* <b>`input`</b>: A `Tensor`. Must be one of the following types: `float32`, `float64`, `int64`, `int32`, `uint8`, `uint16`, `int16`, `int8`, `complex64`, `complex128`, `qint8`, `quint8`, `qint32`, `half`.
* <b>`axis`</b>: A `Tensor`. Must be one of the following types: `int32`, `int64`.
    int32, 0 <= axis < rank(input).  Describes which axis
    of the input Tensor to reduce across. For vectors, use axis = 0.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

  A `Tensor` of type `int64`.