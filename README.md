# <div align="center"> ULDB Dataset </div>
The ULDB dataset is **the first image dataset** specifically designed for the link alignment task in the field of underwater wireless optical communication **(UWOC)**. <br>

## Introduction
The camera-assisted active alignment system is an important solution for achieving link alignment between UWOC terminals. 
Our work aims to enhance the alignment capability of such systems. 
Therefore, the object detection and keypoint detection techniques are introduced to detect the light source from the captured image.
To train and evaluate the deep learning model, we construct the **UWOC Light Source Detection Benchmark (ULDB)** dataset.
We sincerely hope that the ULDB dataset can facilitate future research.

## Paper
Bowen Jia, Wenmin Ge, Jingxuan Cheng, Zihao Du, Renming Wang, Guangbin Song, Yufan Zhang, Chengye Cai, Sitong Qin, and Jing Xu, 
**"Deep Learning-based Cascaded Light Source Detection for Link Alignment in Underwater Wireless Optical Communication"**
<a href="https://doi.org/10.1109/JPHOT.2024.3453116"> [official version] </a>


## Details of the ULDB dataset 
The ULDB dataset consists of 2200 representative images.
We annotated the light spot regions (in the form of bounding boxes) and the light sources (in the form of keypoints) in these images.
These images were all captured using a camera with a large field-of-view (FOV) of 87 degrees in a standard swimming pool. 
They cover a wide range of misalignment scenarios, including diverse variations in distance, angle, and external interference factors.
<br>

Some examples of images in ULDB dataset are shown below:
<div align="center">
<img width="100%" src="https://github.com/happycode123/ULDB-Dataset/blob/main/Examples_in_ULDB.jpg?raw=true">
</div>
<br>

Some details about the ULDB dataset are as follows:

|Type			|Number	|
|---------------|-------|
|Total images	|2200	|
|Background images	|300	|
|Images in<br>training/validation/test set	|1540/330/330	|
|Light spot region annotations	|1900	|
|Light source annotations	|1849	|

The annotations of the ULDB dataset follow the COCO format. 
The directory tree looks like as follows:
```
${DATASET_ROOT}/ULDB_dataset
├── images
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── ... (all images)
│   └── n.jpg
├── test.json
├── train.json
└── val.json
````

## Download
**The ULDB dataset is for academic use only. If this dataset is helpful to you, please cite our paper. Thanks!** ❤️

- [BaiduYun Link](https://pan.baidu.com/s/1nSqr7cgE4PASBxnG4a24_Q) | Key : ftvx
- [Google Drive Link](https://drive.google.com/file/d/1_l1ld9XiYncsjT62LibhrW_7YMWK-_iV/view?usp=sharing)

**Password: uldb123456**

<br>
<div align="right"> [Created on 2023-11-22, Updated on 2024-09-15] </div>
