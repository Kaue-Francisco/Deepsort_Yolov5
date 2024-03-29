# Deep SORT with Yolov5

## Introduction
This repository contains simple tracking code with Deep Association Metric (Deep SORT).
The code loads the coco yolov5 model and uses it to detect cars on the highway, as shown in the example below:


## Example Results
![Detections](media/example.gif)

## Technologies
* Python3.9
* Opencv
* Pytorch
* Yolov5
* Jupyter Notebook

## Installation and Running the Tracker
First step: clone the repository:
``` bash
git clone https://github.com/Kaue-Francisco/Deepsort_Yolov5.git
```

Second step: Access the repository:
``` bash
cd Deepsort_Yolov5
```


Third step: Create venv and access venv
``` bash
python -m venv venv

.\venv\Scripts\activate # For Windows

source venv/bin/activate # For Linux
```

Fourth step: Install requirements
``` bash
pip install -r requirements.txt
```

**NOTE:** If you have trouble installing Torch in the requirements.txt file, I've left the pip command along with a link to install the library.

Fifth step: Run file Deepsort.ipynb ✨


## References
HowieMa: [DeepSORT_YOLOv5_Pytorch](https://github.com/HowieMa/DeepSORT_YOLOv5_Pytorch/tree/master)