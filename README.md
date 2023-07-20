# mahjong_detect_AI
## 0. 개요 (프로젝트 소개)
### 일본 리치마작을 오프라인에서 진행할 때 마작 초보들은 제대로 점수를 계산하지 못한다. 따라서 초보들을 위해 화료이후 사진을 찍으면 그 사진을 인식하여 점수를 계산해주는 프로그램이다.
### 프로젝트 구성 시작 - 2023-05-21

## 1. 시작 가이드
### 개발 기술
### <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">

## 2. 멤버
### 동명대학교 배교성 / 김동현 / 안준현 / 이민재

## 3. YOLO V5를 이용한 학습 (만수 대상)
### 마작패 만수를 밝기를 조절하여 1만 - 11장, 2만 - 11장, ... , 9만 - 11장, 적5만 - 11장, 총 110장의 이미지 준비.
### YOLO V5 중 YOLO V5X 모델 및 GOOGLE COLAB을 이용하여 학습 시작.
### COLAB에서 학습 시키기 : <https://hemon.tistory.com/m/59>


### 학습 후 최고 정확도 결과
### ![Alt test](https://github.com/bae7491/mahjong_detect_AI/assets/44579627/147f354e-9a04-4df9-af5d-fa7b5bd9711c)   


### 학습 후 정확도가 낮은 결과
### ![Alt test](https://github.com/bae7491/mahjong_detect_AI/assets/44579627/4a9784ec-86d3-4d26-8191-75a3fa16d387)


## 4. YOLO V5를 이용한 학습 (전체 패 대상)

### 3에서 만수패를 대상으로 YOLO V5를 돌렸던 방식을 이용하여 1만, 2만, ... , 발, 중 까지 적도라를 포함한 37개의 패를 밝기를 조절하여 각 11장씩, 총 407장의 이미지를 준비.
### YOLO V5를 GOOGLE COLAB에서 돌리던 중 런타임 에러가 발생하여 PC에서 재학습 시작.
### 커스텀 이미지를 이용하여 학습 시키기 : <https://dohyeon.tistory.com/38>
