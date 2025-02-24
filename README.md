# OVIS data loading and evaluation
## Introduction

This package provides data loading and evaluation functionalities for video instance segmentation on [OVIS](http://songbai.site/ovis/). It is built based on [COCO API](https://github.com/cocodataset/cocoapi) designed for [MSCOCO](http://cocodataset.org/) and [COCO API (YouTube-VIS)](https://github.com/youtubevos/cocoapi) designed for [YouTube-VIS](https://youtube-vos.org/dataset/vis/). For evaluation metrics, please refer to the [YouTube-VIS](https://youtube-vos.org/dataset/vis/) and [OVIS challenge paper](https://openreview.net/pdf?id=IfzTefIU_3j) for details.

We have only implemented Python API for OVIS. API in other languages are not available for now.

## Installation
To install:
```
cd PythonAPI

# To compile and install locally 
python setup.py build_ext --inplace

# To install library to Python site-packages 
python setup.py build_ext install
```

## Contact
If you have any questions regarding the repo, please create an issue.
