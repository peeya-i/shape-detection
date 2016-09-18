# shape-recognition

This is an example of object detection with neural networks (implemented with Python + keras). The training images contain abstract geometric shapes and can be easily bootstraped. 

The code is split up into several Jupyter notebooks. They increase in complexity and roughly follow the structure in the blog post:

* Detection of rectangles in numpy arrays: [single-rectangle](single-rectangle.ipynb), [two-rectangles](two-rectangles.ipynb), [multiple-rectangles](multiple-rectangles.ipynb)
* Additional classification between rectangles and triangles: [two-rectangles-or-triangles](two-rectangles-or-triangles.ipynb), [multiple-rectangles-or-triangles](multiple-rectangles-or-triangles.ipynb)
* Application to more complex images (using convnets): [color-multiple-shapes](color-multiple-shapes.ipynb)


![](plots/bw-single-rectangle_prediction.png)


## Requirements

* Python 2.7 (with numpy, matplotlib, jupyter)
* keras
* Theano or Tensorflow
* pycairo (for color-multiple-shapes)
