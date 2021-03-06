## 2018 Data Science

![Cover](https://github.com/bluebibi/data_science_2018/blob/master/cover.jpg)

- [원본 소스](https://github.com/link-kut/introduction_to_ml_with_python)
- [Study..(미세먼지를 이용한)](https://github.com/jungyj0211/data_science_2018/tree/master/scikit_study_workspace)

### CHAPTER 1 소개 
#### 1.1 왜 머신러닝인가? 
- 1.1.1 머신러닝으로 풀 수 있는 문제 
- 1.1.2 문제와 데이터 이해하기 
 
#### 1.2 왜 파이썬인가? 
#### 1.3 scikit-learn 
- 1.3.1 scikit-learn 설치 
#### 1.4 [필수 라이브러리와 도구들](https://nbviewer.jupyter.org/github/bluebibi/data_science_2018/blob/master/Chapter01/1.4.ipynb)
- 1.4.1 주피터 노트북
- 1.4.2 NumPy
- 1.4.3 SciPy 
- 1.4.4 matplotlib 
- 1.4.5 pandas 
- 1.4.6 mglearn 
#### 1.5 파이썬 2 vs. 파이썬 3 
#### 1.6 [소프트웨어 버전 확인](https://nbviewer.jupyter.org/github/bluebibi/data_science_2018/blob/master/Chapter01/1.6.ipynb) 
#### 1.7 [첫 번째 애플리케이션: 붓꽃의 품종 분류](https://nbviewer.jupyter.org/github/bluebibi/data_science_2018/blob/master/Chapter01/1.7.ipynb)
- 1.7.1 데이터 적재 
- 1.7.2 성과 측정: 훈련 데이터와 테스트 데이터 
- 1.7.3 가장 먼저 할 일: 데이터 살펴보기 
- 1.7.4 첫 번째 머신러닝 모델: k-최근접 이웃 알고리즘 
- 1.7.5 예측하기 
- 1.7.6 모델 평가하기 
#### 1.8 요약 

<br/>

### CHAPTER 2 지도 학습 
#### 2.1 분류와 회귀 
#### 2.2 일반화, 과대적합, 과소적합 
- 2.2.1 모델 복잡도와 데이터셋 크기의 관계 
#### 2.3 지도 학습 알고리즘 
- 2.3.1 [예제에 사용할 데이터셋](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.1.ipynb) 
- 2.3.2 [k-최근접 이웃](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.2.ipynb) 
- 2.3.3 [선형 모델](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.3.ipynb) 
- 2.3.4 [나이브 베이즈 분류기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.4.ipynb) (by 3/20)
- 2.3.5 [결정 트리](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.5.ipynb) 
- 2.3.6 [결정 트리의 앙상블](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.6.ipynb) 
- 2.3.7 [커널 서포트 벡터 머신](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.7.ipynb)
- 2.3.8 [신경망(딥러닝)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.3.8.ipynb) (by 3/27) 
#### 2.4 [분류 예측의 불확실성 추정](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.4.ipynb) 
- 2.4.1 [결정 함수](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.4.1.ipynb)
- 2.4.2 [예측 확률](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.4.2.ipynb)
- 2.4.3 [다중 분류에서의 불확실성](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.4.3.ipynb)
#### 2.5 [요약 및 정리 (by 4/3)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter02/2.5.ipynb)

<br/>

### CHAPTER 3 비지도 학습과 데이터 전처리 
#### 3.1 비지도 학습의 종류 
#### 3.2 비지도 학습의 도전 과제 
#### 3.3 데이터 전처리와 스케일 조정 
- 3.3.1 [여러 가지 전처리 방법](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.3.1.ipynb)
- 3.3.2 [데이터 변환 적용하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.3.2.ipynb)
- 3.3.3 [훈련 데이터와 테스트 데이터의 스케일을 같은 방법으로 조정하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.3.3.ipynb)
- 3.3.4 [지도 학습에서 데이터 전처리 효과 (by 4/10)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.3.4.ipynb)
#### 3.4 차원 축소, 특성 추출, 매니폴드 학습 
- 3.4.1 [주성분 분석(PCA)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.4.1.ipynb)
- 3.4.2 [비음수 행렬 분해(NMF)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.4.2.ipynb) 
- 3.4.3 [t-SNE를 이용한 매니폴드 학습](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.4.3.ipynb) (by 4/17)
#### 3.5 군집 
- 3.5.1 [k-평균 군집](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.5.1.ipynb) 
- 3.5.2 [병합 군집](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.5.2.ipynb) 
- 3.5.3 [DBSCAN](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.5.3.ipynb) 
- 3.5.4 [군집 알고리즘의 비교와 평가](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.5.4.ipynb) 
- 3.5.5 [군집 알고리즘 요약](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.5.5.ipynb) 
#### 3.6 [요약 및 정리 (by 4/24)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter03/3.6.ipynb) 

<br/>

### CHAPTER 4 데이터 표현과 특성 공학 
#### 4.1 범주형 변수
- 4.1.1 [원-핫-인코딩(가변수)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.1.1.ipynb)
- 4.1.2 [숫자로 표현된 범주형 특성](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.1.2.ipynb)
#### 4.2 [구간 분할, 이산화 그리고 선형 모델, 트리 모델](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.2.ipynb) (by 5/1)  
#### 4.3 [상호작용과 다항식](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.3.ipynb)  
#### 4.4 [일변량 비선형 변환](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.4.ipynb) (by 5/8) 
#### 4.5 특성 자동 선택
- 4.5.1 [일변량 통계](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.5.1.ipynb) 
- 4.5.2 [모델 기반 특성 선택](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.5.2.ipynb) 
- 4.5.3 [반복적 특성 선택](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.5.3.ipynb)  
#### 4.6 [전문가 지식 활용](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.6.ipynb)  
#### 4.7 [요약 및 정리 (by 5/15)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter04/4.7.ipynb) 

<br/>

### CHAPTER 5 모델 평가와 성능 향상 
#### 5.1 교차 검증
- 5.1.1 [scikit-learn의 교차 검증](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.1.1.ipynb) 
- 5.1.2 [교차 검증의 장점](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.1.2.ipynb) 
- 5.1.3 [계층별 k-겹 교차 검증과 그외 전략들](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.1.3.ipynb) 
#### 5.2 그리드 서치
- 5.2.1 [간단한 그리드 서치](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.2.1.ipynb) 
- 5.2.2 [매개변수 과대적합과 검증 세트](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.2.2.ipynb) 
- 5.2.3 [교차 검증을 사용한 그리드 서치 (by 5/22)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.2.3.ipynb) 
#### 5.3 평가 지표와 측정 
- 5.3.1 [최종 목표를 기억하라](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.3.1.ipynb) 
- 5.3.2 [이진 분류의 평가 지표](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.3.2.ipynb) 
- 5.3.3 [다중 분류의 평가 지표](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.3.3.ipynb) 
- 5.3.4 [회귀의 평가 지표](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.3.4.ipynb) 
- 5.3.5 [모델 선택에서 평가 지표 사용하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.3.5.ipynb) 
#### 5.4 [요약 및 정리 (by 5/29)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter05/5.4.ipynb) 

<br/>

### CHAPTER 6 알고리즘 체인과 파이프라인 
#### 6.1 [데이터 전처리와 매개변수 선택](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.1.ipynb) 
#### 6.2 [파이프라인 구축하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.2.ipynb) 
#### 6.3 [그리드 서치에 파이프라인 적용하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.3.ipynb) 
#### 6.4 파이프라인 인터페이스
- 6.4.1 [make- pipleline을 사용한 파이프라인 생성](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.4.1.ipynb) 
- 6.4.2 [단계 속성에 접근하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.4.2.ipynb) 
- 6.4.3 [그리드 서치 안의 파이프라인 속성에 접근하기](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.4.3.ipynb) 
#### 6.5 [전처리와 모델의 매개변수를 위한 그리드 서치](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.5.ipynb) 
#### 6.6 [모델 선택을 위한 그리드 서치](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.6.ipynb) 
#### 6.7 [요약 및 정리 (by 6/5)](https://nbviewer.jupyter.org/github/jungyj0211/data_science_2018/blob/master/Chapter06/6.7.ipynb) 

<br/>

