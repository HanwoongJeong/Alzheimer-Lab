# 분별 : Alzheimer-Lab :post_office:

한국인공지능연구소에서 진행하는 [분별Lab](https://www.ai-lab.kr/labs/bunbyeol-raebjang-gimonggon)입니다 

### Purpose

딥러닝기법을 이용한 알츠하이머 아밀로이드 PET 이미지 분류

### Our Goals

- 문제: 기존의 알츠하이머진단의 경우는 MRI, CT 등으로 이루어집니다. 하지만 이러한 진단은 어느정도 장애가 진행되어야지(경도인지장애) 확인이 가능합니다.
하지만 Amyloid를 통한 진단의 경우 **조기진단은 가능**하지만 병의 진행이 **연속적**이기에 구분하기가 힘들고, 어느정도 전문성이 쌓여야 구분이 가능합니다. 

- 해결: 이러한 문제를 해결하기 위해 딥러닝을 통한 이미지분류로 알츠하이머의 여부를 구분하는 연구를 진행하려고 합니다. :ambulance:

|Input data :mag:|Train and validation results :chart_with_upwards_trend:|
|:---:|:---:|
|![](https://github.com/choco9966/Alzheimer-Lab/blob/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180714/image/picture.PNG)|![](https://github.com/choco9966/Alzheimer-Lab/blob/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180714/image/result.png)

### 랩소개 :man::woman:

저희 그룹은 최신 딥러닝 기법을 이용하여 이미지/영상 분류를 연구하는 모임입니다.연구에 주어진 자료들을 바탕으로 자료에 맞는 최적 분류모델을 도출하는 데 주안점을 두고 있습니다. 의학, IT, 통계 각 분야별 실무자 및 산업공학 재학생으로 구성돼 있는 만큼 서로 다른 도메인이 융합하여 강력한 시너지 효과를 내고자 합니다.

- `김웅곤/랩장` : 현재 통계청에서 근무하고 있는 3년차 직장인입니다. 대학 때 수학과 경영학을 전공하였으며 2014년에 정보경영학 수업에서 머신러닝을 처음 접한 후 머신러닝 이론을 틈틈이 공부해 왔습니다. 통계 실무와 부딪치면서 딥러닝의 가공할 만한 가능성을 느껴 주경야독으로 공부를 이어오던 중에 우연히 페이스북에서 한국인공지능연구소 모집문을 보고 지원하게 되었습니다. 이를 바탕으로 여러 사람들과 즐겁게 연구내용을 공유하고 토론을 나누고 싶습니다.

- `강도영/교수님` : 동아대학교 핵의학과 교수. 의료영상 분석 전문가로서 기존의 분석법과 비교하여 인공지능 기반 분석기법을 임상진료에 활용하고자 합니다.

- `양경성/부장님` : 개인적으로 자동차 번호판 자동인식 프로젝트를 수행하였습니다. 다양한 이미지 분석 연구를 수행하고 싶습니다.

- `이기선/치과의사(의공학 박사과정)` : 의료영상을 대상으로 한 인공지능 기반 분석 및 진단 분야 연구를 수행하고자 합니다.

- `김현우/연구원` : 현재 휴학중인 대학생입니다. 머신러닝 관련 프로젝터를 다수 수행하였으며 이번 기회를 통해 딥러닝 관련 프로젝트를 수행해보려 합니다.

## 연구일지 :page_facing_up:

| 미팅요일 | 간단한 설명 및 링크 ||
|:---:|:---:|:---|
|6월2일|[팀결성 및 주제선정](https://github.com/choco9966/Alzheimer-Lab/tree/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180602)| 알츠하이머 아밀로이드 PET 이미지 분류를 주제로 선정 |
|6월16일|[Resnet을 이용한 분류](https://github.com/choco9966/Alzheimer-Lab/tree/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180616)| unimbalanced 문제를 해결하기 위해 Augumentation 적용 논의 |
|6월30일|[VGG16을 이용한 분류](https://github.com/choco9966/Alzheimer-Lab/tree/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180630)| VGG16의 성능이 Resnet보다 뛰어난것을 확인 
|7월14일|[Idea 논의](https://github.com/choco9966/Alzheimer-Lab/tree/master/%ED%9A%8C%EC%9D%98%EB%82%B4%EC%9A%A9/20180714)| 앙생블 및 기존의 진행된 모델 결과  |
|7월27일|[Idea 논의]||

## 실험결과

| 실험 | Precision | Recall | F1-Score | 설명 및 코드 |
|:---:|:---:|:---:|:---:|:---|
|solution1||||Resnet을 적용|
|[solution2](https://github.com/choco9966/Alzheimer-Lab/tree/master/%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%EC%96%91%EA%B2%BD%EC%84%B1_%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%5B0624%5DResnet)||||Augumentation을 적용한 Resnet|
|[solution3](https://github.com/choco9966/Alzheimer-Lab/blob/master/%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%EA%B9%80%EC%9B%85%EA%B3%A4_%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/VGG16/VGG16%20-%20kimwoonggon)||||VGG16을 적용|
|[solution4](https://github.com/choco9966/Alzheimer-Lab/tree/master/%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%EC%96%91%EA%B2%BD%EC%84%B1_%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%5B0625%5Dvgg16)||||Augumentation을 적용한 VGG16|
|[solution5](https://github.com/choco9966/Alzheimer-Lab/tree/master/%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%EC%96%91%EA%B2%BD%EC%84%B1_%EC%8B%A4%ED%97%98%EA%B2%B0%EA%B3%BC/%5B0807%5D%EC%B6%94%EA%B0%80%EC%8B%A4%ED%97%98)||||1. data set 감소 2. augumentation 다르게 적용 3. test set 건드리지 않은 상태.|
