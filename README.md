# Real-Time-Face-Mask-Detection

Created a real-time face mask detection system using OpenCV, Tensorflow, Streamlit, and DeepFace to detect whether a person is wearing a mask or not. Additionally, it also estimates the person's age and gender for better demographic analysis of the people who do or do not prefer to wear masks.

Used MobileNetV2 pre-trained model for detection, labels from imagenet dataset, and Haar Cascade classifier for classification.

Download the dataset from [here](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset).

> **_NOTE:_** Use Python version 3.11 only & this version is not compatible with linux. So use windows only.

# Installation

```
git clone https://github.com/adhokshaj-k/Real-Time-Face-Mask-Detection.git
pip install -r requirements.txt

streamlit run app.py
```


