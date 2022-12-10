# Project_Non_Spending
# 🥶 얼어죽어도 코딩(팀명: 얼죽코)
![image](https://user-images.githubusercontent.com/101463273/190317107-76a99a4d-1867-4f7e-b09c-082a66407dcb.png)


## 👽 서비스 소개
* 서비스명:  MZ세대를 중심으로 유행중인 무지출챌린지 통합 지원 웹사이트 구현
* 개발 목표: 사용자의 무지출챌린지를 효과적으로 달성할 수 있도록 도와준다. 나와 챌린지 목표 금액이 비슷한 사람들과 매칭되어 챌린지 달성이 가능하도록 한다.
정부 지원금이나 절약 정보, 단체에서 진행하는 무료 이벤트를 사용자 간 공유할 수 있도록 한다. 사용자가 주로 어디에 돈을 쓰는지 지출 항목을 분류하고 차트로 시각화하여 지출 관리를 도운다.
<br>

## 📅 프로젝트 기간
2022.08.16 ~ 2022.09.07 (3주)
<br>

## UI설계도 : 피그마
![피그마](https://user-images.githubusercontent.com/108074336/189464650-29e9035b-4efe-4939-ab41-2d59db4cb26c.png)

## ⭐ 주요 기능
* <b>지출 입력</b>
  * 챌린지 기간 중 지출 발생 내역입력  
<br>![지출반성](https://user-images.githubusercontent.com/108074336/189464195-39227081-06f4-4d89-951e-3202f9ac4f76.png)

* <b>챌린지 진행 상황 관리</b>
<br>![레벨게시판](https://user-images.githubusercontent.com/108074336/189463412-0943d186-6a19-40f6-9936-e53dd9c17a73.png)
  * 지출 입력자료를 토대로 사용자의 챌린지 달성도확인
  * 등급 간 전체 달성도 현황확인
  * 챌린지 기간 중 TOP 5 순위확인
 
* <b>소비 분석</b>
<br>![3주소비차트](https://user-images.githubusercontent.com/108074336/189464267-72eb3c3d-9650-4020-b5c5-9f351ca2e428.png)
  * 챌린지 진행 기간 중 지출금 차트 확인
  
<br>![소비항목차트](https://user-images.githubusercontent.com/108074336/189464301-483c753b-3122-4d96-923d-158caa40c565.png)
  * 챌린지 진행 기간 중 지출이 많은 항목에 대한 차트확인
  * 쇼핑, 식비, 교통, 여가, 기타 총 5가지 항목에 따른 소비분석
  * 1년 소비차트를 통한 1년간의 소비 항목분석 
  
<br>![카드추천](https://user-images.githubusercontent.com/108074336/189464103-de6c996b-490b-4bba-b519-4914366b91fc.png)
  * 차트에서 많은 비율을 차지하는 항목에 대한 카드 추천
  
<br>![무지출달력](https://user-images.githubusercontent.com/108074336/189464337-b7d92062-dacb-48f1-9d1c-62901e0b4f0c.png)
  * 무지출에 성공한 날을 달력에 표시

* <b>등급 게시판</b>
  * '챌린지 목표금액'에 따른 사용자 등급분류
  <br> (본 개발에서의 등급분류는 아래와 같음)
<br>![등급분류표](https://user-images.githubusercontent.com/108074336/189463205-f90be6c5-f2e5-447c-97c1-ade4af176df1.png)
  * 등급 간 프라이빗 커뮤니티 존재
  
* <b>절약정보 게시판</b>
<br>![보조금](https://user-images.githubusercontent.com/108074336/189464067-79e591c9-3285-4a03-b6c5-cbc73373d28e.png)
  * 정부 보조금 정보 확인 
  * 기업이나 단체에서 진행하는 무료 이벤트 정보 확인

* <b>절약정보 게시판</b>
  * 전체 이용자간 커뮤니티를 통한 소통 가능 
<br>

## ⛏ 기술스택
<table>
    <tr>
        <th>구분</th>
        <th>내용</th>
    </tr>
    <tr>
        <td>사용언어</td>
        <td>
            <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"/>
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"/>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>라이브러리</td>
        <td>
            <img src="https://img.shields.io/badge/BootStrap-7952B3?style=for-the-badge&logo=BootStrap&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>개발도구</td>
        <td>
            <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"/>
            <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>서버환경</td>
        <td>
            <img src="https://img.shields.io/badge/Apache Tomcat-D22128?style=for-the-badge&logo=Apache Tomcat&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>데이터베이스</td>
        <td>
            <img src="https://img.shields.io/badge/Oracle 11g-F80000?style=for-the-badge&logo=Oracle&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>협업도구</td>
        <td>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>
        </td>
    </tr>
</table>


<br>

## 📌 SW유스케이스
![us케이스](https://user-images.githubusercontent.com/101463273/189058538-62776cb8-1eb9-4088-b21d-f89a68cc2c04.png)

<br>

## 📌 서비스 흐름도
![서비스흐름도](https://user-images.githubusercontent.com/101463273/189019753-1cbc1489-5b71-4980-9c90-6fbec84b6923.png)
<br>

## 📌 ER다이어그램
![db](https://user-images.githubusercontent.com/101463273/189014345-19668b19-1a6e-43bb-8f2b-97d5075e86d5.png)
<br>
<br>

## 🖥 화면 구성

### 메인화면/지출입력
![로그인후_메인](https://user-images.githubusercontent.com/101463273/189025954-c0e38b77-22ef-4a1f-acc4-673b246c407d.png)
![메인_지출입력](https://user-images.githubusercontent.com/101463273/189026408-de883063-86b4-439b-a881-ccbd9862c963.png)
<br>
<br>

### 회원가입/로그인/회원수정/회원탈퇴
![회원가입](https://user-images.githubusercontent.com/101463273/189025967-c122cfad-e733-4d50-9028-cc0752a82e0e.png)
![로그인](https://user-images.githubusercontent.com/101463273/189025958-98788b95-7220-4b76-a1e8-6902de36515e.png)
![마이페이지1](https://user-images.githubusercontent.com/101463273/189025986-299441f3-0baa-4832-ae57-76a00d685f3e.png)
![마이페이지2](https://user-images.githubusercontent.com/101463273/189025991-5f127c44-b21a-4834-bfb6-554949c81649.png)
<br>
<br>

### 마이챌린지
![마이챌린지](https://user-images.githubusercontent.com/101463273/189026466-9c941f79-3d8b-4f68-9207-625b977a304d.png)
<br>

### 게시판
![자유게시판](https://user-images.githubusercontent.com/101463273/189026511-749c0978-cc67-4da1-8d51-be34f43cc1b1.png)
![Uploading 게시글.png…]()
![게시글](https://user-images.githubusercontent.com/101463273/189026760-37616a6e-4342-4d48-b13d-e1cf886f3b9a.png)
![게시글작성](https://user-images.githubusercontent.com/101463273/189026529-806cdb5a-2b51-40c2-973e-c21b6fc95531.png)
![게시글수정](https://user-images.githubusercontent.com/101463273/189026523-0ed330f0-b4f8-4b1f-b6f4-5f8155c26c00.png)
<br>
<br>

### 레벨 게시판/세이브 포인트 게시판
![레벨게시판](https://user-images.githubusercontent.com/101463273/189026596-79295e41-40df-4b86-ac24-fea832ab2dcc.png)
![절약정보게시판](https://user-images.githubusercontent.com/101463273/189026622-39ea74db-5ee4-444d-8e53-cf24964c4a0e.png)
<br>
<br>

## 시연 영상
https://youtu.be/or-fU9-e654
## 👨‍👩‍👦‍👦 팀원 역할
<table>
  <tr>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4439/4439959.png" height="100"/></td>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4439/4439968.png" width="100" height="100"/></td>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4440/4440873.png" width="100" height="100"/></td>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4440/4440953.png" width="100" height="100"/></td>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4440/4440876.png" width="100" height="100"/></td>
    <td align="center"><img src="https://cdn-icons-png.flaticon.com/512/4439/4439947.png" width="100" height="100"/></td>

  </tr>
  <tr>
    <td align="center"><strong>김유리</strong></td>
    <td align="center"><strong>이윤호</strong></td>
    <td align="center"><strong>백근만</strong></td>
    <td align="center"><strong>김재강</strong></td>
    <td align="center"><strong>박혜민</strong></td>
    <td align="center"><strong>김민우</strong></td>

  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Backend</b></td>

  </tr>
    <tr>
    <td align="center"><b>팀장<br>게시판 서비스 구현<br>레벨 화면 구현<br>DB 설계</b></td>
    <td align="center"><b>게시판 서비스 구현<br>달성도 차트 구현<br>DB 설계</b></td>
    <td align="center"><b>회원 관리<br>마이챌린지<br>메인화면 구현<br>DB 설계</b></td>
    <td align="center"><b>회원 관리<br>마이챌린지<br>메인화면 구현<br>DB 설계</b></td>
    <td align="center"><b>회원 관리<br>마이챌린지<br>메인화면 구현<br>DB 설계</b></td>
    <td align="center"><b>게시판 서비스<br>레벨 화면 구현<br>DB 설계</b></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/kimpizza" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/uno719" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/100geun10000" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/jaegangkim" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/bingomangsoo" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/Tiel0043" target='_blank'>github</a></td>

  </tr>
</table>

## 🤾‍♂️ 트러블슈팅
  
* DB 설계 문제<br>
 DB 테이블 설계가 막막했다.
 
* 프로젝트 통합 문제<br>
 git lab을 이용하여 프로젝트를 통합하였는데 git lab 사용이 처음이어서 익숙하지 않았고, merge 이후에는 충돌 문제가 발생하였다.
