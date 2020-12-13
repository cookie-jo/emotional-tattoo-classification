# JSP&Servlet MVC(model2) 웹 프로젝트 + 머신러닝 + 딥러닝

## Introduction
감성타투 도안추천 서비스
<br>
타투용품 판매 + 타투추천 + 예약 & 결제 + 리뷰게시판
<br><br>


## Technical Specification
![3차팀프로젝트 기술스택1](https://user-images.githubusercontent.com/67885590/102000474-424a8480-3d2b-11eb-9e98-9f2f62bc48b1.PNG)
<br>
![3차팀프로젝트 기술스택2](https://user-images.githubusercontent.com/67885590/102000481-50000a00-3d2b-11eb-9c2d-29ffc5e3c81f.PNG)
<br>

## Required Library
- mysql-connector-java-8.0.22
- cos.library
<br>


## Requirements Specification
- 회원 가입(개인회원, 사업자회원)

- 로그인, 로그아웃, 마이페이지

- 상품목록, 상품상세, 장바구니, 결제

- 디자인별 타투, 예약, 결제

- 타투샵, 예약, 결제

- 타투 그림그리기로 추천, 타투 설문조사로 추천

## Database Modeling
![3차ERD](https://user-images.githubusercontent.com/67885590/102000485-5a220880-3d2b-11eb-91c0-203dec6ac684.PNG)

<br>

## 주요 기능 설명
### ***사이트 메인화면***
<br>

![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/67885590/102000511-905f8800-3d2b-11eb-8c20-6032a574c8d6.gif)

<br>

> 메인화면에서는 가장 최근에 등록된 상품과 가장 판매량이 높은 상품을 확인할 수 있습니다.

<br>


### ***챗봇 기능***
<br>

![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/67885590/102000535-c13fbd00-3d2b-11eb-92e5-fa80054c8a4e.gif)

<br>

> 챗봇기능은 정해진 형식으로 입력을 해야 답변을 하는 기능으로 간단하게 넣어봤습니다.

<br>

### ***회원가입***
<br>

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/67885590/102000521-ad945680-3d2b-11eb-952f-949d96b181f7.gif)

<br>

> 회원가입은 우편번호 api를 사용해 주소를 입력받을 수 있게 하였습니다.

<br>


### ***로그인***
<br>

![ezgif com-gif-maker (7)](https://user-images.githubusercontent.com/67885590/102000525-b71dbe80-3d2b-11eb-9623-2765dfe8a440.gif)

<br>

> 로그인은 개인회원과 사업자 회원으로 나누었고 개인회원으로 먼저 소개해드리겠습니다.

<br>



### ***상품 목록 조회***

<br>
image

<br>
> 한 페이지에 상품을 8개씩 보여주게 하였고 상품이미지, 상품명, 상품가격을 보여주며



### ***상품 상세 조회***
image

> 제품 상세조회 페이지에서는 제품에 대한 이미지와 해당 제품에 달린 리뷰를 확인할 수 있습니다.



### ***장바구니를 통한 구매***
image

> 장바구니 페이지에서는 상품의 수량을 변경하거나 장바구니에서 아이템을 삭제할 수 있습니다.



### ***리뷰게시판 CRUD***
<br>

![ezgif com-gif-maker (15)](https://user-images.githubusercontent.com/67885590/102000569-1380de00-3d2c-11eb-9cbf-db54241b0a38.gif)

<br>

> 리뷰게시판은 글을 작성, 수정, 삭제할 수 있고 cos.library를 사용하여 파일 업로드를 할 수 있습니다.

<br>
