# Hazy-CC
Dataset: [[BaiduNetdisk]][[https://pan.baidu.com/s/130D4wv-ulhwasS9OpHRWsA?pwd=213k]]

Samples in this Hazy-JHU dataset are selected from JHU-CROWD++，whose whose weather conditions label is fog/haze. This hazy-weather dataset belongs to the real-world one, and the train-validation-test is still following the original spilt of JHU-CROWD++.
There are 80 samples, 23 samples and 50 samples in training, validation and testing part of this dataset.


Samples in this Hazy-ShanghaiTechRGBD dataset are synthesized on ShanghaiTechRGBD dataset,accord-
ing to the haze simulation algorithm.This hazy-weather dataset belongs to the synthetic one,, and the train-test is still following ShanghaiTechRGBD dataset.
train_data contains images, train_depth and train_gt.
(1) images: *.jpg, 1920*1080 resolution.
(2) train_gt: *.mat, the position of a head is annotated in point (x, y), where
0 <= x < 1920 and 0 <= y <= 1080.
(43) train_bbox: pseudo box generated from point annotation and depth. 

test_data contains imagesand test_bbox_anno.
(1) The formats of images are similar to images in the train.
(2) test_bbox_anno: the position of a head is annotated in bounding box (x1, y1, x2, y2),
where (x1, y1) and (x2, y2) correspond to the coordinates of top-left corner and bottom-right corner.



If you find Hazy-ShanghaiTechRGBD and Hazy-JHU datasets useful, please consider cite our following work.
@article{Kong2023HazyCC,
title={Direction-aware attention aggregation for single-stage hazy-weather crowd counting},
author={Weihang Kong, Jienan Shen , He Li, Jiayu Liu, Junge Zhang},
journal={Expert Systems with Applications},
year={2023},
volume={225}
pages={120088}
}



