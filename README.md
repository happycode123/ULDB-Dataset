# <div align="center"> ULDB Dataset</div>
The ULDB dataset is **the first light source image dataset** in the field of underwater wireless optical communication.<br>

## Introduction
The camera-assisted active alignment system is an important solution for achieving link alignment between underwater wireless optical communication **(UWOC)** terminals. 
Our work aims to enhance the capability of such alignment systems to cope with misalignment. 
Therefore, deep learning techniques are introduced to detect light sources from images captured by the camera.
To train and evaluate the deep learning model, we construct the **UWOC Light Source Detection Benchmark (ULDB)** dataset, 
which is the first light source image dataset in the UWOC field.
We sincerely hope that the ULDB dataset can facilitate future research.

## Paper (coming soon)
<br>

## Details of the ULDB dataset 
The ULDB dataset consists of 2200 representative images with corresponding position annotations.
These images were all captured using a camera with a large FOV of 87 degrees in a standard swimming pool. 
They cover a wide range of misalignment scenarios, incorporating diverse variations in distance, angle, and external interference factors.
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

## Download (coming soon)
<br>

<div align="right"> [Updated on 2023-11-22] </div>

