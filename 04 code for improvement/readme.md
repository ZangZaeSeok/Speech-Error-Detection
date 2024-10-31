# 데이터 개선을 위한 코드
- 학습된 모델 중 가장 성능이 좋은 Validation CER metric을 사용한 모델에 error class에 대한 Threshold를 0.5로 하여 데이터 개선을 진행하였다.
- 본 코드들은 데이터 개선을 위해 오디오 파일을 전처리하고 모델에 입력하는 과정과, 각 파일명에 오류를 태깅하는 코드를 담는다.

#
#
- 01 PreProcessing
  - 데이터 전처리 과정 코드
- 02 Dataloader Generator
  - 모델의 입력데이터 생성 코드
- 03 Data Improvement
  - 데이터 개선용 코드
