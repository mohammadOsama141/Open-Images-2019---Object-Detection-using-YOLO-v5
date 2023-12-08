# Open-Images-2019---Object-Detection-using-YOLO-v5

## Introduction

This project implements an object detection challenge using a subset of the Open Images 2019 dataset. The Open Images Challenge 2019, hosted by Google AI in partnership with Kaggle, featured three tracks: Object Detection, Visual Relationship Detection, and Instance Segmentation. The challenge focuses on detecting objects from a large set of diverse images.

### Dataset

The project uses a subset of the Open Images 2019 dataset, which is part of the Open Images V5 dataset. The dataset is known for its variety and complexity, containing several objects in different scenes. It includes annotations for image classification, object detection, visual relationship detection, and instance segmentation.

- **Total Images**: 30,000 (subset)
- **Original Dataset Source**: [Open Images 2019 - Object Detection | Kaggle](https://www.kaggle.com/c/open-images-2019-object-detection)
- **Subset Dataset Source**: [Google 2019 30k Train Data | Kaggle](https://www.kaggle.com/datasets/mindtrinket/google-2019-30k-train/data)
- **Labels and Annotations Source**: [Open Images Challenge Downloads](https://storage.googleapis.com/openimages/web/challenge2019_downloads.html)

### Notebooks Overview

1. **CV assign3_part1.ipynb**: This notebook focuses on preliminary data processing, including loading and filtering the bounding box annotations from the dataset.
2. **CV_assign3_part2.ipynb**: Further data handling and preparation steps are implemented, including train-test splitting and data transformation suitable for model training.
3. **cvAssign3_yolo.ipynb**: This notebook contains the implementation of the object detection model, using the YOLO (You Only Look Once) framework.

### Object Detection Task

The object detection track of the Open Images Challenge 2019 involves predicting tight bounding boxes around object instances in images. The dataset covers 500 classes out of 600, with annotations including both positive and negative image-level labels to indicate the presence or absence of object classes.

### Evaluation

The primary evaluation metric for the object detection task is the mean Average Precision (mAP) over the 500 classes. The challenge set is used for reporting results, with a focus on accurately measuring recall and enabling a fair comparison of false positives and false negatives.
