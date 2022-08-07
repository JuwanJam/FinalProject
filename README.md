# FinalProject
FinalProject by 세나개

<p align="center">
 <img src="https://user-images.githubusercontent.com/110036792/181253203-6ca9a1ca-21b7-42c3-b380-4319e9cdc50e.png"> 
</p>


## [SketchDay 접속 링크](http://58.236.95.130:9999/)를 통해서 저희의 서비스 이용이 가능합니다!!


# :blue_book:SketchDay : 내 일기의 감정을 통하여 노래를 추천 받고 그림일기로 볼 수 있는 서비스
> 2021.05.19 ~ 2021.07.26 Spring FinalProject
* 반려동물을 기르는 가구가 늘며 바쁜 현대 사회에서 사용자의 거주지를 중심으로 사용자의 원하는 지역, 시간대를 고려하여 사용자와 돌봄 매니저를 빠르게 매칭 시켜주는 기능으로 사용자와 반려동물의 삶의 질을 높이는 반려동물 돌봄 서비스입니다.
# 목차
[1. 조원 소개](#1-조원-소개)

[2. 배경 및 목적](#2-배경-및-목적)

[3. 주요 서비스 화면](#3-주요-서비스-화면)

[4. Service Flow](#4-service-flow)

[5. Architecture](#5-architecture)

[6. ERD](#6-erd)

[7. 실행 방법](#7-실행-방법)


# 1. 조원 소개
#### 세나개(세상에 나쁜 개발자는 없다.)
>  박주완, 김준혁, 노승민, 이예선, 최재윤

# 2. 배경 및 목적
* -	바쁜 현대 사회의 1인 가구와 반려동물을 키우는 사람들이 많아짐으로서 빠르고 쉽게 반려동물 돌봄 서비스를 제공하는 웹 사이트를 기획하였습니다.
#### :bulb: 즉, 일기 분석을 통한 사용자의 감정변화를 보여주고 내 일기와 비슷한 다른 사용자의 일기, 노래 추천 및 그림일기 생성 서비스를 통해 사용자들의 추억을 저장하고 특별한 소통 공간을 만들고자 했습니다.
&nbsp;
* **타켓층**
  * 반려동물을 키우는 1인 가구
  * 반려동물에게 친구를 만들어주고 싶은 사용자


&nbsp;

* **주요 기능**
  * 누구나 돌봄요청을 할 수 있고, 누구나 돌봄매니저가 될 수 있는 양방향 서비스
  * 원하는 지역, 날짜, 기간을 확인, 검색하여 원하는 사용자 간의 매칭
  * 리뷰와 별점 기능으로 돌봄 매니저의 정보를 확인 후 선택 가능
  * 포인트 충전을 통한 개인 거래
  * 회원가입(email 인증), 로그인, 회원정보수정, 비밀번호/아이디 찾기

  
&nbsp;

![AI 5조 포스터](https://user-images.githubusercontent.com/90138160/167758253-69d4e3f3-6b39-4930-8aea-15feef5c145e.jpg)

# 3. 주요 서비스 화면
> 토글 클릭하시면 이미지 확인이 가능합니다.
<details>
    <summary>메인 달력화면</summary>
 
![image](https://user-images.githubusercontent.com/90138160/167751290-e1fe1f35-2cc1-47b4-99b4-f7062553dde0.png)
 
 <summary>이번 달 워드클라우드 및 감정선</summary>
 
 ![image](https://user-images.githubusercontent.com/90138160/167753532-4a80d045-79a1-40b5-83d5-eff6424eb57a.png)
 
</details>
<details>
    <summary>결과창</summary>
 
![InkedKakaoTalk_20220510_131857649_LI](https://user-images.githubusercontent.com/90138160/167750556-8a1a5de2-7f67-4162-a6dc-3ac767bdf6ff.jpg)
 
</details>

<details>
    <summary>공유 일기 리스트</summary>
 
![image](https://user-images.githubusercontent.com/90138160/167752496-7146bf10-3e1a-42ee-ab63-b34f6107ed1b.png)
 
</details>

<details>
    <summary>내 프로필</summary>
 
![image](https://user-images.githubusercontent.com/90138160/167753541-03f101ad-23b5-48b2-bdf1-c20b8f86eb6c.png)
 
</details>


# 4. Service Flow
<p align="center">
 <img src="https://user-images.githubusercontent.com/90138160/165701902-97f4d696-584c-4155-8116-7c38d8e43640.png"> 
</p>


# 5. Architecture
![아키텍처 정의서](https://user-images.githubusercontent.com/45118610/167749427-fdfed6e1-6316-4c36-94a0-27e96ad70f84.PNG)
![architecture](https://user-images.githubusercontent.com/29485153/167747788-55849e07-8379-4d9a-9a93-e36383704e56.png)

# 6. ERD
![에이블스쿨 AI 빅프로젝트_ERD_05조 (1) (1)](https://user-images.githubusercontent.com/66732995/167747338-8f355dcc-b2aa-48c0-a31e-b95080965fb0.png)

# 7. 실행 방법
### 1. 파이썬 설치(v3.x)

### 2. 파이썬 가상환경 생성 및 실행

### 3. 원하는 위치에서 SketchDay 프로젝트 clone 진행 및 프로젝트 폴더 최상단으로 위치 이동

### 4. pip install -r requirements.txt 실행

### 5. [구글 드라이브](https://drive.google.com/file/d/153Cqkgfj_U7C0oEaAAjgtezDVEl3YmqZ/view?usp=sharing) 클릭해서 압축파일(용량이 큰 모델 및 디폴트 이미지 파일) 다운로드 후 압축 해제

### 6. 압축 해제후 
#### - 다운로드 파일의 media 파일은 프로젝트 최상단에 복사
#### - 다운로드 파일의 diary/ml_models 내의 모델 파일도 프로젝트파일 내의 같은 위치에 복사

#### - 다운로드 파일의 task/ml 내의 models 폴더를 프로젝트파일 내의 같은 위치에 복사

### 7. python manage.py makemigrations 실행

### 8. python manage.py migrate 실행

### 9. 각 환경에 맞는 [redis-server](https://redis.io/docs/getting-started/) 공식문서 링크에서 설치 후 실행

### 10. python manage.py runworker background_tasks 실행

### 11. python manage.py runserver
