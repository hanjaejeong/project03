# 딥러닝을 활용한 유실/유기동물 등록 및 찾기 서비스

### 프로젝트 소개
- 개발 기간 : 2022. 11. 02 ~ 2022. 12. 13

- 개발 인원 : 5명

- 기술 및 환경 : Java, Phtyon, Html, JS, Spring, JBDC, Eclipse, MySql

- 개발 목표 : 하나의 사이트에서 유실동물이나 반려동물 관련 정보를 찾아볼 수 없다. 이를 해결하기 위해 여러 사이트에 흩어져있는 정보를 크롤링하여 하나의 사이트에서 보여주고 반려동물 등록 및 유실동물 찾기를 하기 위함이다.

- 개발 내용
  - 로그인 및 회원가입 : 로그인을 통해 커뮤니티에 글을 작성할 수 있음
  - 마이페이지 : 사용자 정보를 확인 및 수정할 수 있음
  - 유실동물 공고 : 등록된 유실동물의 정보를 모아볼 수 있고, 검색을 통해 원하는 동물의 정보만 조회할 수 있음
  - 유실동물 등록 : 유실동물을 등록할 수 있음
  - 커뮤니티 : 반려동물 정보, 입양 정보, 입양 및 재회 후기, 봉사활동 정보를 공유할 수 있음
  - 반려생활 길잡이 : 반려동물을 키울 때 필요한 기본정보 및 상식을 확인할 수 있음

- 기대효과 및 활용방안
  - 딥러닝을 통한 반려동물 이미지 매칭이 가능함
  - 반려인 커뮤니티를 통해 반려 생활 정보 공유 및 봉사활동 정보 등을 공유할 수 있음 
  - 유실동물이 지역 경계를 벗어날 경우, 찾기 힘든 점을 축종 및 특성 검색 등으로 보호자가 빠르게 찾을 수 있음
  - 이미지를 기반으로 검색하는 기능을 이용하면 실종 신고자를 빠르게 찾을 수 있음

- 산출문서
  - WBS
  - 프로젝트기획서
  - 요구사항정의서
  - 빅데이터분석정의서
  - 화면설계서
  - 데이터베이스요구사항분석서
  - 테이블명세서

---

### 사용기술
<img src="https://user-images.githubusercontent.com/107980523/209783103-8b015160-54c8-4138-a0ce-e1166fe86422.png" width="500" height="200"/>

### 유스케이스
<img src="https://user-images.githubusercontent.com/107980523/210202986-1ef8b5af-7e57-4d61-8f7b-1c478c9a5f5b.png" width="500"/>

### 서비스 흐름도
<img src="https://user-images.githubusercontent.com/107980523/210202997-408b5cae-81c9-4be0-b3be-81aa49ec8d86.png" width="550"/>

### E-R Diagram

---

### 나의 역할
1. 프로젝트 총괄
2. 웹 기능구현 : JDBC를 활용하여 데이터를 등록, 수정 및 조회할 수 있도록 함
3. 데이터 수집 및 전처리 : 파이썬을 활용하여 데이터를 크롤링하고 전처리하여 데이터베이스에 
