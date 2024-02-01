# Shapes

Shape is a term to describe the number and size of the dimensions of an N dimension (ND) array.

``MLXArray`` is an N dimensional array.  The number of dimensions is described by ``MLXArray/ndim``
and the size of each dimension can be examined with ``MLXArray/dim(_:)-8s2hf`` or ``MLXArray/shape``.

Some of these functions can manipulate the shape without changing the contents while others 
will moves rows and columns as they modify the shape.

## Topics

### MLXArray Shape Methods (Same Size)

Some methods allow you to manipulate the shape of the array.  These methods change the size
and ``MLXArray/shape`` of the dimensions without changing the number of elements or contents of the array:

- ``MLXArray/expandedDimensions(axis:stream:)``
- ``MLXArray/flattened(start:end:stream:)``
- ``MLXArray/reshaped(_:stream:)-19x5z``
- ``MLXArray/squeezed(axes:stream:)``
- ``expandedDimensions(_:axes:stream:)``
- ``asStrided(_:_:strides:offset:stream:)``

- ``flattened(_:start:end:stream:)``
- ``reshaped(_:_:stream:)-5x3y0``
- ``squeezed(_:axes:stream:)``

### MLXArray Shape Methods (Change Size)

These methods manipulate the shape and contents of the array:

- ``MLXArray/movedAxis(source:destination:stream:)``
- ``MLXArray/split(parts:axis:stream:)``
- ``MLXArray/split(indices:axis:stream:)``
- ``MLXArray/swappedAxes(_:_:stream:)``
- ``MLXArray/transposed(axes:stream:)``

### Free Functions To Manipulate Shapes

- ``asStrided(_:_:strides:offset:stream:)``
- ``concatenated(_:axis:stream:)``
- ``expandedDimensions(_:axes:stream:)``
- ``movedAxis(_:source:destination:stream:)``
- ``padded(_:width:value:stream:)``
- ``padded(_:widths:value:stream:)``
- ``split(_:indices:axis:stream:)``
- ``split(_:parts:axis:stream:)``
- ``stacked(_:axis:stream:)``
- ``swappedAxes(_:_:_:stream:)``
- ``transposed(_:axes:stream:)``