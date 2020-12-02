# create-art

[![GitHub issues](https://img.shields.io/github/issues/PraveenKumarSridhar/create-art?style=for-the-badge)](https://github.com/PraveenKumarSridhar/create-art/issues)
[![GitHub forks](https://img.shields.io/github/forks/PraveenKumarSridhar/create-art?style=for-the-badge)](https://github.com/PraveenKumarSridhar/create-art/network)
[![GitHub stars](https://img.shields.io/github/stars/PraveenKumarSridhar/create-art?style=for-the-badge)](https://github.com/PraveenKumarSridhar/create-art/stargazers)
[![GitHub license](https://img.shields.io/github/license/PraveenKumarSridhar/create-art?style=for-the-badge)](https://github.com/PraveenKumarSridhar/create-art/blob/main/LICENSE)

Train a model using TensorFlow to create art.

Link to the notebook  [here](https://github.com/PraveenKumarSridhar/create-art/blob/main/Art_Generation_with_Neural_Style_Transfer_v3a.ipynb)

## DATA:
<hr/>

You can choose any content and style images. But the restriction on height and width is  (WIDTH = 300, HEIGHT = 225).


## MODEL:
<hr/>

The model used here is VGG-19. You can download it from [here](https://s3.amazonaws.com/cadl/models/vgg16.tfmodel)

## Environment and tools Used:
<hr/>

```
1. Jupyter Notebook
2. Numpy
3. Matplotlib
4. Tensorflow
5. imageio
```

## Required package installation:
<hr/>

```
pip install tensorflow==1.14
pip install numpy
pip install imageio
```

## Results
<hr/>
<img align="center" alt="Training loss vs epochs "  src="https://raw.githubusercontent.com/PraveenKumarSridhar/create-art/main/output/generated_image.jpg" />
