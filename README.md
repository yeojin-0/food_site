# Chinese_food

### app 생성 (중국집)
---
`Food`(name 속성 하나 있음)model을 만들어서 form으로 값을 입력하기 실습
Models.py Food 생성
name 속성
form을 구성해서 입력하기

---
Food(name 속성 하나 있음)라는 model을 만들어서 form으로 값을 입력하기 실습

Models.py Food 생성
name 속성
description 속성
기존에 description 옵션이 없어서 충돌 - defaut값을 넣거나, 아니면 sqlit3 파일 제거하고 재생성
form을 구성해서 입력하기
음식이름
음식설명
DB에 저장 확인

---
Dropdown 폼을 이용해서 실습
Category (ex : 면류, 식사류, 요리류)

name
Food 테이블

category (forienkey)
name
price
description
Form에서는 드롭다운으로 카테고리를 정하고

DB에 Food 항목 적용되도록

---
### 파일 업로드 실습
파일을 업로드하는데, 업로드된 파일이 프로젝트 폴더에 저장이 되버립니다

---
### 업로드한 사진 정보를 FOOD 테이블에 반영 어떻게 할까요?
Food에 이미지 경로 속성 추가
사진을 올리고 DB에 정보를 저장하고!

---
### Form을 이용하여 음식 등록 페이지를 만들어 봅시다!
음식 등록 페이지 구성
이름, 가격, 설명 란 추가
이미지 등록 추가
등록된 음식 삭제 기능 넣기
페이지 상속 기능을 이용하여 nav bar 적용

---
### 사이트 메인 페이지에 고객 페이지로 연결하는 버튼 생성
목적 : 고객페이지에 음식 리스트 나오고 누르면 세부 화면으로 이동하기
customer app 생성
그 버튼을 누리면 고객 index 페이지로 이동
함정 : index라는 이름을 여러개 넣었네? 등...

---
### 고객 제품 상세화면에서 장바구니 개발
추가, 삭제 버튼
기능 구현

---
### remove_cart에서 버그 수정
담는 정보가 음수가 나오는 문제 -> 0보다 작은 값은 처리 X

---
### 개발 방향을 잡고 개선하기!
장바구니에 다른 물품을 종합하지 못하고 있음
사용자별로 관리가 안되고 있음
장바구니 모든 물품을 확인하는 기능이 없음....

