# keras_james
tf.keras 유투브 강의의 내용을 그대로 따라해 본 것
[소스코드 위치] (https://github.com/jkh911208/tf.keras.git)

## 강의1. TensorFlow and Keras소개
## 강의2. TensorFlow 1.8설치

  우분투 터미널 환경에서, 다음과 같이 입력하여 우분투 package들을 최신 상태로 업데이트한다.
    $ sudo apt-get update && sudo apt-get upgrade
    
  우분투에 기본적으로 설치되어 있는 파이썬의 버전을 확인해본다. (rr의 경우 python 2.7.17, python3 3.6.9 버전이 설치되어 있음)
    $ python
    $ python3
  추가로, python3 package 관리자를 설치해 준다. (나는 의존성 문제가 발생) 
    $ sudo apt-get install python3-pip
    
  TensorFlow는 Python환경에 설치하는 것이기 때문에, pip으로 설치한다. 
  cpu버전의 tensorflow를 설치한다. numpy등의 Dependency들을 알아서 찾고 설치
    $ sudo pip3 install tensorflow
    
  TensorFlow가 정상설치되면, import tensorflow를 python3환경 내에서 했을 때, 
  
    $ sudo pip3 jupyter
    $ jupyter notebook 
    
  내 PC에 맞는 NVIDIA GPU Driver를 설치하고
  
  아래, 두 과정은 좀 복잡하여 스크립트를 만들어 설치하는 형태를 이야기한다.
  CUDA 설치한 다음
  cuDNN을 설치한다.
  
  이제 Tensorflow GPU버전을 설치 해야 하는데, 만일 위에서 CPU버전의 Tensorflow를 설치한 경우, CPU버전의 tf를 제거해야 GPU버전이 인스톨된다.
  
    $ sudo pip3 uninstall tensorflow
    $ sudo pip3 install tensorflow-gpu

## 강의3.
## 강의4.
## 강의5.
## 강의6.


딥러닝 개발 환경 잡기 - 드라이버부터 딥러닝 엔진까지
https://followers.tistory.com/15

http://jonghoonp.blogspot.com/2019/08/cuda-cudnn.html


CUDA, cuDNN 설치 버전 확인하기

https://crmn.tistory.com/31

설치기

https://jaeyung1001.tistory.com/19?category=727294

나중에 
https://followers.tistory.com/15

