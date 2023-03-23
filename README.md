<div align="center">
  <h1>BOND</h1>
  <h3>당신의 취미도 BOND로 시작하세요.</h3>
  <br>
<br>
</div>


# :pushpin: Bond
> **같은 관심사를 가진 사람들의 취미 모임 프로젝트 (네이버 밴드 클론코딩)**
> **[Bond 바로가기](http://146.56.191.169:8080)** <br>

### 프로젝트 개요

- Java와 Spring 프레임워크를 이용한 취미모임 프로젝트.
- 모임 정보, 회원 정보, 일정 기능 등을 관리하는 기능 제공

</br>

## 1. 제작 기간 & 참여 인원 & 구현 기능
- 2022년 10월 18일 ~ 2022년 12월 10일
- 4인 팀 프로젝트
- 구현 기능 및 기여
  - 로그인, 회원가입 기능
  - 내 정보 수정 및 모임 정보 수정
  - 모임 가입, 탈퇴 기능
  - 모임에 가입한 회원들 무한스크롤 비동기로 조회
  - 회원 정보 모달 

- 프로젝트 구조
![](https://user-images.githubusercontent.com/110797113/221120531-819fca85-1d0c-457e-a9b1-d46d717c21cb.png)



</br>

## 2. 사용 기술

<div align="center">
  
### **Back-end**
<img src="https://img.shields.io/badge/Java11-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/Spring5.3.14-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Oracle21C-F80000?style=for-the-badge&logo=oracle&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Apache Tomcat9.0-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
    <img src="https://img.shields.io/badge/Apache Maven-C71A36?style=for-the-badge&logo=ApacheMaven&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Sequrity-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white">

### **Front-end**
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 

</div>

</br></br>

<br><br>

## 3. ERD 설계
[FarmFarm ERD](https://www.erdcloud.com/d/rH52AGzEpuXjv7vir) 

<br>

![](https://user-images.githubusercontent.com/110797113/221129589-d3bbbf07-0888-4a18-b289-573cc86e827a.png)

<br><br>

## 4. 핵심 기능
회원가입 시 유효성 검사 및 무한스크롤
<details> 
<summary> 핵심 기능 설명 펼치기 </summary>

- 카테고리 별 게시판 목록이 나옴.
- 원하는 검색어를 원하는 조건별(제목, 내용, 제목+내용)로 검색 가능.
- 원하는 정렬 방식(최신순, 조회수, 좋아요)을 선택해 게시글 조회.
- 페이지네이션을 이용해 게시판 페이지를 이동.
- 코드 보러 가기
  - [Controller](https://github.com/Seo-de/FarmFarm/blob/main/FarmFarm/src/main/java/edu/kh/farmfarm/board/controller/BoardListController.java)
  - [Service](https://github.com/Seo-de/FarmFarm/blob/main/FarmFarm/src/main/java/edu/kh/farmfarm/board/model/service/BoardListServiceImpl.java)
  - [JS](https://github.com/Seo-de/FarmFarm/blob/main/FarmFarm/src/main/webapp/resources/js/board/boardList.js)
  <br>
  

</details>


</br>

## 5. 트러블 슈팅
**DB의 삭제**
학원 DB 서버를 업데이트 하는 과정에서 모든 DB가 날라갔던 경험
> 저희는 회원과 모임, 게시글에 관련된 다양한 샘플 데이터들을 생성해두었으나 학원 DB가 날라가 다시 생성해야했습니다.<br>
> 그러나 백업해둔 SQL문이 있어 수정한 부분까지 반영하여 데이터들을 다시 생성할 수 있었습니다.<br>
> 이 때 백업에 대한 중요성을 알게 되었던 값진 경험이었습니다.<br>


## 6. 프로젝트 결과

**프로젝트 결과**
- 취미 모임 SNS 프로토타입 완성
- 로그인, 회원가입, 유효성 검사 기능 구현

