# **睡意检测**

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/jackaduma/drowsiness-detection)


本项目实现了**一种计算机视觉系统，该系统可以自动检测实时视频流中的驾驶员睡意状况，然后在驾驶员感到困倦时发出警报**

这项技术将对行业有所帮助，并且理想情况下可以减少与疲劳相关的事故。

------

## **使用OpenCV进行睡意检测**


------

**This repository contains:** 

1. [detect code](detect.py) which can detect drowsiness by opencv.
2. [face landmarks model](model/shape_predictor_68_face_landmarks.dat) you can use face landmarks detection by opencv.

------

## **内容列表**

- [**睡意检测**](#睡意检测)
  - [**使用OpenCV进行睡意检测**](#使用opencv进行睡意检测)
  - [**内容列表**](#内容列表)
  - [**依赖**](#依赖)
  - [**用法**](#用法)
    - [**检测**](#检测)
  - [**Demo**](#demo)
  - [**引用**](#引用)
  - [**License**](#license)
  
------


## **依赖** 

```bash
pip install -r requirements.txt
```
## **用法**

### **检测**

```python
python detect.py
```


------


## **Demo**

Samples:


------

## **引用**

------

## **License**

[Apache 2.0](LICENSE) © Kun