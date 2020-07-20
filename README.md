# **Drowsiness-Detection**

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/jackaduma/CycleGAN-VC2)

[**中文说明**](./README.zh-CN.md) | [**English**](./README.md)


This code is **a computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy**.

- [x] Face Landmarks
- [x] Usage
  - [x] Detect
- [ ] Demo

------

## **Drowsiness detection with OpenCV**


------

**This repository contains:** 

1. [detect code](detect.py) which can detect drowsiness by opencv.
2. [face landmarks model](model/shape_predictor_68_face_landmarks.dat) you can use face landmarks detection by opencv.

------

## **Table of Contents**

- [**Drowsiness-Detection**](#drowsiness-detection)
  - [**Drowsiness detection with OpenCV**](#drowsiness-detection-with-opencv)
  - [**Table of Contents**](#table-of-contents)
  - [**Requirement**](#requirement)
  - [**Usage**](#usage)
    - [**detect**](#detect)
  - [**Demo**](#demo)
  - [**Reference**](#reference)
  - [**License**](#license)
  
------



## **Requirement** 

```bash
pip install -r requirements.txt
```
## **Usage**

### **detect**

```python
python detect.py
```


------


## **Demo**

Samples:


------

## **Reference**

------

## **License**

[Apache 2.0](LICENSE) © Kun