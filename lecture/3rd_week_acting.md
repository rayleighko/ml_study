# 실습을 통한 딥러닝 학습!  

#### 지금까지 학습한 내용을 실습을 통해 구현해보자!  

## 아나콘다 기초 사용법

우선 [아나콘다 설치 페이지][conda-install]에 접속해 각 OS에 맞는 Anaconda 설치 파일을 다운로드 하자. Python 3.6을 기준으로 anaconda3를 설치하면 본 문서와 같은 환경에서 실습을 진행할 수 있다.  

[conda-install]: https://www.anaconda.com/download/

```Ubuntu LTS 18.04
# Ubuntu LTS 18.04

# install anaconda
> bash ./Anaconda3-5.1.0-Linux-x86_64.sh 

Welcome to Anaconda3 5.1.0

In order to continue the installation process, please review the license
agreement.
Please, press ENTER to continue
>>> 
...
# anaconda 설치 후 변경사항 적용
> source ~/.bashrc

# version check anaconda  
> conda --version  

# update anaconda
> conda update conda  

# create anaconda virtual environemnt 
> conda create --name(-n) 가상환경명 설치할패키지  

# ex) installed Python 3.6 version & create virtual environment. name is 'test'  
> conda create --name test python=3.6  

# or> 
> conda create -n test python=3.6  

# check installed virtual environment
> conda info --envs  

# virtual environment activation  
# ex) activate test  
> activate 가상환경명  

# virtual environment deactivation
# ex) deactivate test   
> deactivate 가상환경명  

# install package
# ex) conda install 패키지명  
> conda install simplejson  

# chekc install package 
> conda list  

# remove all package to virtual environment  
# ex) conda remove --name test --all  
> conda remove --name 가상환경명 --all  

# or>  
> conda remove -n 가상환경명 --all  

# clean anaconda cache  
> conda clean --all  

# or>  
> conda clean -a  
```
  
```Windows
# Windows  

```

```MAC
# MAC  

```

## Anaconda?  

Python 기반 데이터 분석에 필요한 opensource library를 모아놓은 development platform을 말한다.  

또한, Virtual envionment Manager, Package Manager을 제공한다.  

## Anaconda로 TensorFlow 설치

``` Ubuntu LTS 18.04
# Ubuntu LTS 18.04

# using anaconda install Tensorflow to python 3.6
> conda create --name tensorflow python=3.6 tensorflow
```

## Anaconda로 Jupyter Notebook 설치

``` Ubuntu LTS 18.04
# Ubuntu LTS 18.04

# using anaconda install jupyter to pyrhon 3
> pip3 install jupyter
```

## Anacaonda 가상환경을 활성화 후 jupyter notebook 실행

``` Ubuntu LTS 18.04
# Ubuntu LTS 18.04

> jupyter notebook
```

