# Python project to detect the use of masks

! [Alt Text] (https://i1.wp.com/www.marktechpost.com/wp-content/uploads/2019/10/1_QAAGYDHreoRm4vEArNzTTQ.png?resize=372%2C238&ssl=1)

## Installation

you need to install some libraries.

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
It contains images of the faces of people with masks and without masks.

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