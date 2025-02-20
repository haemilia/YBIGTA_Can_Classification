# iCANSee: 시각장애인을 위한 캔음료 분류 어플리케이션

## 프로젝트 목표


❓ **Problem:** 대부분의 캔 음료에 적절한 점자 표기가 되어 있지 않아서 시각장애인이 어떤 음료인지 구분하기 매우 어려움

✅ **Solution:** 캔 음료를 촬영하면 어떤 음료인지 음성으로 출력해주는 어플리케이션 ‘iCANsee’ 개발


## 프로젝트 관련 개념

### Object Detection

딥러닝과 컴퓨터 비전 기술을 활용하여, 이미지 혹은 비디오에서 특정 객체(object)를 식별하고 위치를 찾는 작업. 

객체가 포함된 이미지/비디오 입력 데이터로부터 딥러닝 모델이 객체를 식별할 수 있는 특징을 학습하여 객체를 식별하고 위치를 추정. 객체 식별 이후에는 bounding box를 생성하여 상자의 좌표와 크기로 객체의 위치를 표시하고, 객체가 어떤 종류인지 클래스 분류를 수행하는 방식으로 진행됨.

### Image Classification

컴퓨터 비전 분야에서 사용되는 기술로, 입력 이미지를 클래스 라벨 중 하나로 분류하는 작업.

주어진 이미지에 대해 CNN(Convolutional Neural Network) 등의 모델을 이용해 입력 이미지의 공간적인 특징을 추출하여 이미지의 핵심적인 구조와 패턴을 파악한 후, 추출된 특징을 기반으로 이미지를 주어진 클래스 라벨 중 하나로 예측하는 방식으로 진행됨.

### YOLO

YOLO(You Only Look Once)는 Object Detection, Image Classification, Image Segmentation 등의 task들을 수행하는 딥러닝 기반의 모델로, 특히 실시간 Object Detection 분야에 특화되어 있다고 알려져 있는 모델. 

이미지를 한 번에 전체 그리드로 나누고, 각 그리드 셀에서 객체의 bounding box와 클래스 라벨을 예측함으로써 실시간으로 객체를 탐지할 수 있다는 특징이 있음.

### React Native

JavaScript와 React를 기반으로 하는 모바일 어플리케이션 개발 도구. iOS 및 안드로이드 운영 체제에서 네이티브 앱과 유사한 사용자 인터페이스를 만들 수 있으며, 코드의 재사용성과 개발 생산성을 높여준다는 장점이 있음.

### Expo

React Native 기반의 오픈 소스 플랫폼으로 React Native 프로젝트를 생성하고 관리하는 데 사용되며, 다양한 도구와 라이브러리가 제공되며 테스트 및 배포를 간편하게 할 수 있다는 장점이 있음.

### gRPC

구글이 개발한 Open Source Remote Procedure Call 프레임워크. gRPC에서 클라이언트 애플리케이션은 다른 머신의 서버 애플리케이션에 있는 메소드를 로컬 객체처럼 직접 호출할 수 있어 분산 애플리케이션 및 서비스를 더 쉽게 만들 수 있다는 특징이 있음.

Stream request/Stream response 가능하며 속도가 빠르고 다양한 request를 동시에 처리하고 돌려줄 수 있다는 장점이 있음.
