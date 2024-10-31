# :jack_o_lantern: Korean Pronunciation Error Detection (한국어 발음 오류 탐지)
> 본 연구는  [AI 데이터 품질 개선 오픈랩 프로그램 우수상(상위 3팀) 수상](https://www.datanet.co.kr/news/articleView.html?idxno=179709)한 '외국인과 아동 한국어 음성 데이터의 오류 구간 탐지모델'에 대한 연구자료이자, 
[아동 및 외국인 음성 데이터의 발음 오류 구간 검출을 위한 멀티모달 학습 모델](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11495814) 논문에서 구현한 실험을 재현할 수 있게 하는 코드입니다.

## :apple: 기대 효과
**1. 오류 음성 데이터 식별**
> 오류가 발생된 데이터를 식별하여 학습에서 배제 또는 예측 난이도 조정이 가능하게 할 수 있습니다.
 
**2. 음성 오류 구간 라벨링:**
> 오류가 발생된 음성의 구간 라벨링을 통해, 데이터 개선을 수행할 수 있습니다.

## 🗃️Dataset
* 오류 구간이 라벨링된 음성 데이터셋: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=123
* 아동 음성 데이터셋: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=540
* 외국인 음성 데이터셋: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=505

## 🌲Working Enviornment
* pickle5
* operators
* typing
* pandas
* ipython
* torch
* matplotlib
* torchaudio
* scikit-learn


## 🗂️각 디렉토리별 설명
**00 Data:**
> 발음 오류 탐지 모델을 위한 학습 데이터 (용량 관계상 한국어 음성 데이터는 제외)

**01 Code:**
> 발음 오류 탐지 모델을 위한 학습 데이터 전처리 및 모델 학습과 관련된 코드

**03 Models**
> 학습된 발음 오류 탐지 모델

**04 code for improvement**
> AI 데이터 성능 개선을 위한 코드

**05 Error Tagging Data**
> 성능 개선을 통해, 발음 오류 구간이 태깅된 데이터(csv, Pandas DataFrame Pickle)



