## Use Case UC-21: ViewPredictionReports
**1) Related Requirements** : REQ-4, REQ-28, REQ-29, REQ-30

**2) Initiating Actors** : Any of: 창고관리자, 점주

**3) Actor's Goal** : 근처 창고의 차후 재고 예측 리포트 확인, 창고의 재고 예측 리포트 확인

**4) Participating Actors** : 분석모듈

**5) Preconditions** : 판매 예측 리포트가 수치화되어 있어야한다.

**6) Postconditions** :  판매 예측 리포트를 화면에 출력한다.

**7) Flow of Events for Main Success Scenario**

| Direction | n    | Actor Action                                                 |
| --------- | ---- | ------------------------------------------------------------ |
|           | 1    | include WriteReport(UC-#)                                    |
| →         | 2    | 사용자가 판매 예측 리포트 출력 버튼을 누른다.                |
| ←         | 3    | 분석모듈은 판매 예측 리포트를 작성한다.                      |
| ←         | 4    | 분석모듈은 데이터베이스에 저장된 판매 예측 리포트르 화면에 출력한다. |

**8) Flow of Events for Extensions (Alternate Scenarios)**

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |