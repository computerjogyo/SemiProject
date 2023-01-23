# PigPick
<p align="center"><img width="200" alt="logo" src="https://user-images.githubusercontent.com/74584001/213995960-27c60097-d2c8-416a-99fd-df847c153d7c.gif"></p>

> 사용자의 취향을 고려하여 메뉴를 추천해주는 웹사이트

### Feature
* 사용자가 원하는 카테고리를 선택시 메뉴 랜덤 추천하기
* 사용자 위치 기반으로 반경 1km 이내의 식당 리스트 출력하기
* 식당에 관한 리뷰 작성 및 리뷰 확인하기
* 식당 찜하기(식당 좋아요 기능)
* 사용자가 가장 많이 먹은 음식 메뉴 ,작성한 리뷰, 찜한 식당  확인하기

### Skills & Tools
![Java](https://img.shields.io/badge/Java-007396.svg?&style=for-the-badge&logo=Java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F.svg?&style=for-the-badge&logo=Spring&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white)
![ApacheMaven](https://img.shields.io/badge/ApacheMaven-c71A36.svg?&style=for-the-badge&logo=ApacheMaven&logoColor=white)

![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white)
![Eclipse IDE](https://img.shields.io/badge/Eclipse%20IDE-2C2255.svg?&style=for-the-badge&logo=Eclipse%20IDE&logoColor=white)
![AmazonAWS](https://img.shields.io/badge/AmazonAWS-232F3E.svg?&style=for-the-badge&logo=AmazonAWS&logoColor=white)

### Contributor
* 단시연 (Front-end , 아이디어 기획) : 전체적인 퍼블리싱 및 프론트엔드
* 김현지 (Back-end) : 전체 백엔드 및 데이터베이스 관리
* 김서윤 (Front-end) : 전체적 웹 디자인 및 퍼블리싱

## 메뉴 랜덤 추천
<p align="center"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/213997316-161714a0-c289-421c-a781-9fe9a9a2787f.gif"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/213997810-2aa41a2f-9c68-4a24-99ec-f78d108462b1.gif"></p>

* 메뉴 추천 페이지에서 사용자가 원하는 카테고리 선택 ( ex. 일식 / 밥 / 맵기 x )
* 추천 받기 클릭 시 선택한 카테고리 기반으로 DB에서 메뉴 랜덤 추천
* 메뉴를 다시 추천 받고 싶을 시엔 다시 찾기 클릭하면 선택한 카테고리 내에 다른 메뉴 추천

* 추천 받은 메뉴로 식당 찾기 클릭 시 해당 메뉴를 판매하는 식당을 Kakao Map에 출력
* 내 위치를 기반으로 반경 1km 내에 해당하는 식당만 출력
* 내 위치에서 가까운 식당을 마커에 순번으로 표시


## 회원가입 & 로그인
<p align="center"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/213998616-62399c3d-a346-4ed5-aa39-8edfe224965a.gif"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/213998639-9a52fc20-283b-4373-be50-846186a4a52c.gif"></p>

* 추천 받은 메뉴로 식당 찾기 클릭 시 해당 메뉴를 판매하는 식당을 Kakao Map에 출력
* 내 위치를 기반으로 반경 1km 내에 해당하는 식당만 출력
* 내 위치에서 가까운 식당을 마커에 순번으로 표시

* 로그인 페이지에서 카카오 로그인 클릭
* 카카오 로그인 API에서 토큰 및 카카오에 가입된 사용자 정보 받아옴
* 카카오 계정으로 로그인 완료 시 사용자 정보 DB에 입력 및 카카오 계정으로 로그인


## 리뷰목록
<p align="center"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/214000198-ee131c2c-324d-47cf-a7ff-5050a13e3ace.gif"><img width="50%" alt="" src="https://user-images.githubusercontent.com/74584001/214000277-a4963f44-ac28-4b51-be3a-0469e9205515.gif"></p>

* 식당에 대한 리뷰 목록 및 리뷰 목록 페이징 처리
* 리뷰 내용 클릭 시. 리뷰 상세보기로 이동


## 리뷰작성 & 리뷰수정 & 리뷰삭제
<p align="center"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214000660-0bf26205-e6b1-4f88-b8d6-5bfd8313783b.gif"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214000692-a1ce7370-a6af-4bfb-968c-f126389c9610.gif"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214000712-56771bfc-9830-4527-a575-5e6093f9da89.gif"></p>

* 글쓰기 클릭 시 리뷰 작성 페이지로 이동 ( 로그인 상태에서만 가능 )
* 식당 키워드 검색 시 식당 리스트 출력 후 식당 선택
* 별점 , 리뷰 작성

* 사용자가 작성한 리뷰에서만 Edit 활성
* 클릭시 수정 페이지로 이동
* 별점 , 리뷰 수정

* 사용자가 작성한 리뷰에서만 Delete 활성
* 클릭시 리뷰 삭제


## 식당 상세보기 & 좋아요
<p align="center"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214004797-ae72a5bc-e6de-4fb0-84c4-991e8967dfb6.gif"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214004873-743d2841-db55-4b54-b314-5b9354c34e6e.gif
"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214004954-56650e7a-e565-4a71-8e67-34110e03e9e5.gif"></p>

* 리뷰 페이지에서 식당 이름 클릭 시 식당 상세정보 페이지로 이동
* 식당 위치, 상세정보, 작성된 리뷰 확인

* 리뷰 페이지에서 식당 이름 클릭 시 식당 상세정보 페이지로 이동
* 식당 위치, 상세정보, 작성된 리뷰 확인

* 리뷰 페이지에서 식당 이름 클릭 시 식당 상세정보 페이지로 이동
* 식당 위치, 상세정보, 작성된 리뷰 확인

## 마이페이지
<p align="center"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214005441-62ab40d6-de27-442a-b56d-5f19ebb818b1.gif"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214005474-9b23032e-e206-4dfb-b5f3-eb58ad5aa67f.gif"><img width="32%" alt="" src="https://user-images.githubusercontent.com/74584001/214005486-54bdde42-0e8e-4643-8d63-82038bd0eeb2.gif"></p>

* 사용자가 추천 받아 자주 먹은 메뉴 확인
* 로그인 이후에 추천 받은 메뉴만 누적 및 등록

* 사용자가 작성한 총 리뷰 확인
* 별점 순, 최신 순으로 정렬 

* 사용자가 좋아요 체크한 총 식당 리스트 확인
