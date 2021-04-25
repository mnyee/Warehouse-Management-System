# Domain Model for UC-16 : RequestData

## Extracting the Responsibilities

| Responsibility Description                                   | Type | Concept Name |
| ------------------------------------------------------------ | ---- | ------------ |
| 창고관리자, 점주가 입력한 데이터는 데이터베이스에 저장된다. | D | 데이터 모듈 |
| 저장된 데이터는 권한을 갖는 계정만 접근이 가능하다. | K | authority |





## Extracting the Associations

| Concept pair | Association Description | Association Name |
| ------------------ | ----------------------- | ---------------- |
| authority <-> 데이터 모듈  | 데이터베이스에 입력하기 위해 권한을 가진 사용자인지 확인한다. | 데이터 전달 |


## Extracting the Attributes

| Concept | Attributes | Attribute Description |
| ------- | ---------- | --------------------- |
|  authority | 접근가능성 | 시스템에 접근 가능한지 확인  |
