#  Object_detecting ( YOLO v4, YOLO v7, Android Studio )
## [디지털스마트부산아카데미 1기] 주차장 DataSet을 활용해 CCTV 어플 구현
<br/>

***

<br/>

<div><h1>📚 Development Environment</h1></div>
<div>
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white">
<img src="https://img.shields.io/badge/Android%20Studio-3DDC84.svg?&style=for-the-badge&logo=Android%20Studio&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00.svg?&style=for-the-badge&logo=TensorFlow&logoColor=white">
<img src="https://img.shields.io/badge/YOLO-00FFFF.svg?&style=for-the-badge&logo=YOLO&logoColor=white">
<img src="https://img.shields.io/badge/Google Colab-F9AB00.svg?&style=for-the-badge&logo=Google Colab&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</div>

<br/>

## 프로젝트 목표
:heavy_check_mark:  주차장 DataSet을 학습시켜 주차여부 탐지가 가능한 CCTV 프로그램 <br/>
:heavy_check_mark:  구현한 CCTV 프로그램의 성능 측정 <br/>
:heavy_check_mark:  수업시간에 배운 Yolov4 이외에 다른 버전의 Yolo를 사용하고 성능 비교 <br/>
:heavy_check_mark:  CCTV 탐지 프로그램을 Android 어플로 제작

<br/>

* <h2>Dataset</h2>
  * https://public.roboflow.com/object-detection/pklot  

![스크린샷(2)](https://user-images.githubusercontent.com/90381800/194216063-077b4b34-0cc5-4576-a6c1-3114052d9a11.png)

<br/>

* <h2>Data detail</h2> 
 * image 
  
  
![2012-09-11_15_16_58_jpg rf f7c3a6a0a496da10a770916a11b6252c](https://user-images.githubusercontent.com/90381800/194216709-8976c6a7-2338-4d30-9bf4-f5e703ffe71f.jpg)


  * Bounding Box Data  


|class_id|center_x|center_y|width|height|
|:-:|:--:|:--:|:--:|:--:|
|1|0.23557692307692307|0.28846153846153844|0.036057692307692304|0.0625|
|0|0.25961538461538464|0.29086538461538464|0.03485576923076923|0.06610576923076923|
|1|0.2860576923076923|0.29086538461538464|0.03365384615384615|0.06610576923076923|
|0|0.3112980769230769|0.28846153846153844|0.036057692307692304|0.06610576923076923|
|1|0.33653846153846156|0.29086538461538464|0.03365384615384615|0.0625|

## Reuslt

![results](https://user-images.githubusercontent.com/90381800/194973838-b7bf158c-d59a-4813-ad4c-b834a77ece7c.png)
<br/>
![image](https://user-images.githubusercontent.com/90381800/194973702-4c9cd6dc-53a6-4c03-b16b-fe9545c871d3.png)

## 참고

* YOLO v4  https://github.com/AlexeyAB/darknet  
* YOLO v7  https://github.com/WongKinYiu/yolov7  
* Android  
