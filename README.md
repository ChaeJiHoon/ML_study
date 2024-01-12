- ML을 이용하여 꽃의 개화여부를 판별하고자 함
- 토마토꽃 데이터 셋을 이용
  
    
- 2024.01.12 : 토마토 꽃을 3가지 경우로 분류하는 코드 작성 (tomato_data)
  - 미개화, 1개 꽃 개화, 2개 꽃 개화의 경우로 분류
  - 각 200개의 데이터를 좌우반전 시켜 2배로 데이터 증가
  - 각 400개의 데이터를 가지고 CNN 학습을 통해 코드 구현
  - 아직 매우 안좋은 손실률과 높은 오차를 가지고있음
  - 컴퓨팅파워가 부족하여 매우 느린 학습 속도를 가지고있음
  - 이번주 주말 목표
    - 3개의 꽃 개화까지 분류하는 코드를 작성
    - 개당 500개씩의 데이터인 총 2000개의 데이테를 통한 CNN 학습 코드를 작성
    - 이미지 데이터를 전처리하여 val_loss: 1 이하, val_accuracy: 0.5 이상의 코드를 작성
    - 에포크 횟수와, 신경층 갯수를 적절히 설정하는 하이퍼 파라미터 설정    

<!---
ChaeJiHoon/ChaeJiHoon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
