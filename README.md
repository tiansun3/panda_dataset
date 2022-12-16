# Panda Dataset

This is a dataset we collect from [ILSVRC 2017](https://www.kaggle.com/c/imagenet-object-localization-challenge) proposed by [ImageNet](https://image-net.org/challenges/LSVRC/index.php).

We select a specific animal we want to detect, **panda**(wnid = n02510455) as our dataset.

The original data has 1300 image in ".JPEG" file with 501 corresponding bounding box in ".xml" file.

Some of the image as no given ".xml" file so we delet these images and keep only 501 images with 501 bounding box files.

We also make a "panda_label.csv" file based on the ".xml" files to help bounding.

## Folder Structure:

* anotations: contains the xml files in PASCAL VOC format
* data: contains  the label files (csv)
* images: contains the image data in JPEG format
