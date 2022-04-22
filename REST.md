# REST API 공부 내용

웹 직무부트캠프 2주차 REST API에 관한 내용을 정리한 파일입니다.

---

## REST API
REST는 Representational State Transfer로, 리소스를 이름으로 구분하여 해당 리소스의 상태를 주고 받는 것을 의미합니다.
<br>
<br>
REST API는 HTTP URI를 통해 리소스를 명시하고, HTTP Method를 통해 해당 자원에 대한 CRUD(Create, Read, Update, Delete)를 적용합니다.

---

## 규칙
1. / 는 계층 관계를 나타낼 때 사용합니다.
2. URI의 마지막에 / 를 붙이지 않습니다.
3. \- 은 가독성을 높이는 데 사용됩니다.
4. _ 은 URI에 사용하지 않습니다.
5. 파일의 확장자는 URI에 포함하지 않습니다.
6. URI에는 소문자를 사용합니다.

---

## 역할에 따른 HTTP Method
|행위|HTTP Method|
|--|--|
|조회|GET|
|생성|POST|
|수정|PUT|
|삭제|DELETE|

--- 

