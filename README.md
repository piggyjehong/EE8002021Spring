# EE800 2021 Spring
## 0. Dataset description and data pre-processing
The original dataset link: <https://www.kaggle.com/andrewmvd/face-mask-detection>
This dataset contains 853 images belonging to the 3 classes, as well as their bounding boxes in the PASCAL VOC format.
The classes are:

- With mask
- Without mask
- Mask worn incorrectly

This dataset has the following structure:
```
  - archive
       - annotations (bouding box information in xml format)
       - images (pictures in png format)
```


## References
1. png2jpg.ipynb: <https://blog.csdn.net/weixin_40446557/article/details/104059660>
