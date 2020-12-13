# JSP/Servlet MVC 웹 프로젝트 + 머신러닝 + 딥러닝

## Introduction
감성타투 도안추천 서비스
<br>
웹 쇼핑몰 + 게시판 + 머신러닝(잠재요인 기반 협업필터링) + 딥러닝(CNN, 전이학습모델(VGG19))
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

- 챗봇

- 타투 그림판

- 타투 설문조사

- 디자인별 타투, 예약, 결제

- 타투샵, 예약, 결제

- 상품목록, 상품상세, 장바구니, 결제

- 리뷰 게시판(CRUD)

<br>

## Database Modeling
![3차ERD](https://user-images.githubusercontent.com/67885590/102000485-5a220880-3d2b-11eb-91c0-203dec6ac684.PNG)

<br>

## 주요 기능 설명
### ***사이트 메인화면***
<br>

![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/67885590/102000511-905f8800-3d2b-11eb-8c20-6032a574c8d6.gif)

<br>

> 메인화면에서는 타투 도안 추천서비스, 타투 종류, 타투샵, 타투 용품, 리뷰게시판, 챗봇을 볼 수 있습니다.

<br>


### ***챗봇 기능***
<br>

![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/67885590/102000535-c13fbd00-3d2b-11eb-92e5-fa80054c8a4e.gif)

<br>

> 챗봇기능은 액셀파일에 답을 미리 넣어두어서 정해진 형식으로 입력 ex)타투가격,  타투종류  하면 답변을 하는 형식으로 간단하게 넣어봤습니다.

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

> 로그인은 개인회원과 사업자 회원으로 나누었습니다.

<br>



### ***그림판***
<br>

![ezgif com-gif-maker (10)](https://user-images.githubusercontent.com/67885590/102000543-d288c980-3d2b-11eb-8817-a6b98551ebe7.gif)

<br>

> 그림판은 자바스크립트를 사용하였고 그림을 그린 후 jpg형식의 파일로 다운 받은 후 업로드하면 서버에 저장되고, 전송하기 버튼을 누르면 파이썬으로 넘어 가서 동작 후 결과를 보여줍니다.

<br>


### ***설문조사***
<br>

![ezgif com-gif-maker (11)](https://user-images.githubusercontent.com/67885590/102000551-e03e4f00-3d2b-11eb-920c-ff3c698895d0.gif)

<br>

> 설문조사는800여개 타투 중 쿼리문으로 랜덤으로 25개를 불러오고 5개씩 5번 랜덤으로 보여주고 선택한 값 5개를 파이썬으로 넘기게 되고 동작 후 결과를 보여줍니다.

<br>


### ***디자인별 타투***
<br>

![ezgif com-gif-maker (12)](https://user-images.githubusercontent.com/67885590/102000552-eaf8e400-3d2b-11eb-8dd9-4524424f480c.gif)

<br>

> 디자인별 타투에서는 5가지 카테고리가 있고, 카테고리 클릭 시 타투를 보여주고 사진을 클릭하면 팝업창이 뜨며 예약을 할 수 있습니다.

<

### ***타투샵***

<br>

![ezgif com-gif-maker (13)](https://user-images.githubusercontent.com/67885590/102000556-f9470000-3d2b-11eb-91ed-c264bb426b2d.gif)

<br>

> 타투샵은 지역별 카테고리가 있고, 카테고리 클릭 시 타투를 보여주고 사진을 클릭하면 팝업창이 뜨며 예약할 수 있습니다. 

<br>


### ***타투관리용품***

<br>

![ezgif com-gif-maker (14)](https://user-images.githubusercontent.com/67885590/102000561-0532c200-3d2c-11eb-87e1-dd62e9f23028.gif)

<br>

> 타투관리용품 종류를 볼 수 있고 클릭시 상세페이지로 이동하며 개수를 선택하여 장바구니에 담아 결제 할 수 있습니다.

<br>


### ***리뷰게시판 CRUD***
<br>

![ezgif com-gif-maker (15)](https://user-images.githubusercontent.com/67885590/102000569-1380de00-3d2c-11eb-9cbf-db54241b0a38.gif)

<br>

> 리뷰게시판은 글을 작성, 수정, 삭제할 수 있고 cos.library를 사용하여 파일 업로드를 할 수 있습니다.

<br>
