# Python project to detect the use of masks

![Example](https://github.com/LuizAlencar17/face-mask-detector/blob/main/GIFs/example.gif?raw=true)

Python project that uses a MobileNetV2 deep learning model to detect the use of the user's mask through the webcam.

## Installation

You need to install some libraries.

```bash
pip install tensorflow
pip install keras
pip install matplotlib
pip install Pillow
pip install imutils
pip install numpy
pip install random
pip install cv2
```

## Files

The repository is organized as follows:

#### 1. Dataset
It contains images of the faces of people with masks and without masks. This dataset has few examples, but you can download the full dataset from the link: https://drive.google.com/file/d/1PIxc4l7l5BEy7EYT6_3O-mKF9r5fugV_/view?usp=sharing

```bash
/dataset
-------- /with_mask
-------- /without_mask
```

#### 2. Face detector
This folder contains the files for the face detector model.

```bash
/face_detector
-------- /deploy.prototxt
-------- /res10_300x300_ssd_iter_140000.caffemodel
```

#### 3. File to train and evaluate models
In this file, training and evaluation of the deep learning model is carried out.

```bash
Train-and-Evaluation_Face-Mask-Detector.ipynb
```

#### 4. File to test pre-trained models
If you wanted to test the model on your webcam, you can !!! when executing the file below. This file to run on the webcam was based with the great help of Balajisrinivas. You saw his github https://github.com/balajisrinivas.

```bash
Webcam_Face-Mask-Detector.ipynb
```



   ## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
