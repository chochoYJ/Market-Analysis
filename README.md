### Market-Entry-Analysis
* 2020년 5월 28일부터 6월 30일까지 진행된 프로젝트의 일부
* 모델링의 경우 사내 github에서 관리
  * GridSearchCV - DecisionTreeClassifier
      * Cross Validation : Test, Train 자동 분류 - 데이터 수가 적다는 한계를 보완 
      * GridSearch : 최적화된 파라미터를 찾아줌 → 해당 파라미터로 튜닝
  * 목적변수 데이터 량이 증가했을 경우 사용하면 좋을 모델
    - GridSearchCV >> RandomForestClassifier (모델링 & 시각화 완료)
    - LightGBM
