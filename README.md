# 人臉辨識 (face-recognition)
Face recognition using MTCNN and FaceNet

這個專案主要是用來幫助學習如何使用mtcnn與Google's facenet來設計一個簡單易用的人臉辨識系統。

## 參考
* [OpenFace](https://github.com/cmusatyalab/openface)
* Facenet 專案 [davidsandberg](https://github.com/davidsandberg/facenet)
* [bearsprogrammer](https://github.com/bearsprogrammer/real-time-deep-face-recognition)
* [shanren7](https://github.com/shanren7/real_time_face_recognition)

## 依賴函數庫
* Tensorflow 1.2.1
* Python 3.5
* 以及在[davidsandberg](https://github.com/davidsandberg/facenet)專案的[requirement.txt](https://github.com/davidsandberg/facenet/blob/master/requirements.txt)要求

## 預先訓練的模型
* Inception_ResNet_v1 CASIA-WebFace-> [20170511-185253](https://drive.google.com/file/d/0B5MzpY9kBtDVOTVnU3NIaUdySFE/edit)

## 使用MTCNN進行人臉對齊
* 你需要從[davidsandberg](https://github.com/davidsandberg/facenet)的專案中下載[det1.npy, det2.npy, and det3.npy](https://github.com/davidsandberg/facenet/tree/master/src/align) 
