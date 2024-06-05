# 입9팔9
![목업](https://github.com/yonaisgood/2989-Project/assets/124084624/3914eb2c-2b73-4566-87e9-f9d424c960cd)

- <a href="">🔗 [서비스링크](https://wear9sell9.netlify.app/) (https://wear9sell9.netlify.app/)</a>
- 🔒 서비스 이용을 위한 테스트 계정
   - ID: 21test@test.com
   - Password: 123456 
<br>
<br>

## <span id="index">목차</span>
[1. 프로젝트 소개](#1-프로젝트-소개) <br>
[2. 팀원 소개](#2-팀원-소개)<br>
[3. 개발 환경](#3-개발-환경)  <br>
[4. 팀 협업 방식](#4-팀-협업-방식)  <br>
[5. 구현 기능](#5-구현-기능)<br>
<br>
<br>

# 1. 프로젝트 소개
<br>

> `입9팔9`는 데일리룩과 취향을 공유하는 SNS로 공유한 제품판매가 가능합니다. <br>`입9팔9`는 새컨핸드 제품 사용과 지속가능한 패션을 지향합니다.
 <br>
 <br>
 
  ### [프로젝트 기간]
- 2023년 6월 1일 ~ 2023년 6월 28일
<img width="1155" alt="스크린샷 2023-06-26 오후 3 59 50" src="https://github.com/FRONTENDSCHOOL5/final-21-WeMet21-Already29/assets/126529523/67960d65-6d1d-4a37-95b3-6ea16ee211bc">
 <br>
 <br>

# 2. 팀원 소개
 <br>

|FE 최범관(팀장)|FE 박경보(팀원)|FE 유하은(팀원)|FE 한상헌(팀원)|
| :---: | :---: | :---: | :---: |                                                       
| <a href="https://github.com/KwanBeom"> 🔗 KwanBeom </a>|<a href="https://github.com/kyeongboo-coder">🔗 kyeongboo-coder </a> |<a href="https://github.com/yonsinthefish">🔗yonaisgood </a>|<a href="https://github.com/Skyllerrr">🔗 skyllerrr </a> 
<p align="right"><a href="#index" style='color: white; '>목차로 ▲</a></p>

 <br>
 <br>
 
# 3. 개발 환경


### [기술스택]

|**프론트엔드**|<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/>  <img src="https://img.shields.io/badge/Styled Components-DB7093?style=flat-square&logo=styled-components&logoColor=white"/>|
| :---| :--- |
|**백엔드**|[멋쟁이 사자처럼에서 제공받은 API 명세](https://www.notion.so/16312a05a4c7456db8073785be95cda6)|
|**도구 및 라이브러리** | <img src="https://img.shields.io/badge/Eslint-4B32C3?style=flat-square&logo=Eslint&logoColor=white"/>  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=white"/>  <img src="https://img.shields.io/badge/VisualStudioCode-007ACC?style=flat-square&logo=VisualStudioCode&logoColor=white"/>  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/>    
|**협업 및 프로젝트 관리** | <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/>  <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"/>
|**디자인** | [<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/>](https://www.figma.com/file/OFzYcxwkMzX9U9ljo06ow8/21%EC%A1%B0-%ED%99%94%EC%9D%B4%EB%9D%B5!!!!?type=design&node-id=27-1212&mode=design&t=fXS6bC8hoYKtFX1v-0)   |
  <br> 

<br>

### [커밋컨벤션]
```
feat        : 기능 (새로운 기능)  
fix         : 버그 (버그 수정)  
refactor    : 리팩토링  
design      : CSS 등 사용자 UI 디자인 변경  
comment     : 필요한 주석 추가 및 변경  
style       : 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없음)  
docs        : 문서 수정 (문서 추가, 수정, 삭제, README)  
test        : 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없음)  
chore       : 기타 변경사항 (빌드 스크립트 수정, assets, 패키지 매니저 등)  
init        : 초기 생성  
rename      : 파일 혹은 폴더명을 수정하거나 옮기는 작업만 한 경우  
remove      : 파일을 삭제하는 작업만 수행한 경우
```
<br>

### [폴더구조]
```
 입9팔9
├──🗃️ public
└──🗃️ src
    ├──🗂️ assets/images
    ├──🗂️ components
        ├──📁 Button
        ├──📁 FollowButton
        ├──📁 FollowItem
        ├──📁 Footer
        ├──📁 Header
        ├──📁 HeaderMenu
        ├──📁 Modal
        ├──📁 Post
        ├──📁 Products
        ├──📁 Profile
        ├──📁 ShareModal
        ├──📁 UserList
    ├──🗂️ contexts/ModalContext
    ├──🗂️ hooks
    ├──🗂️ pages
        ├──📁 404
        ├──📁 FollowList
        ├──📁 HomeFeed
        ├──📁 IntroLogin
        ├──📁 Login
        ├──📁 Post
        ├──📁 PostDetail
        ├──📁 PostUpload
        ├──📁 ProductDetail
        ├──📁 ProductList
        ├──📁 Profile
        ├──📁 ProfileSettings
        ├──📁 Search
        ├──📁 SignUp
        ├──📁 Splash
        ├──📁 UploadProduct
    ├──🗂️ routes
    ├──🗂️ style
    └──🗂️ utils
```
<p align="right"><a href="#index" style='color: white; '>목차로 ▲</a></p>

<br>
<br>

## 4. 팀 협업 방식
```
- GitHub issue : 프로젝트 작업 개선사항 및 추가 될 기능을 기록하여 작업일정을 팀원들과 공유했습니다. 
- 데일리스크럼 : 매일 9시 ,17 금일 작업 내용과 진행 상황을 공유했습니다.
- GitHub wiki : 팀내 공유되야 하는 정보와 회의내용을 기록하였습니다.
- Live share : VSC 의 Live share를 사용하여 더 나은 코드를 위한 토론을 진행하였습니다.
- 오프라인 회의 : 정기 오프라인 회의를 통해 진행상황을 공유하며 일정조율 및 작업방향을 맞춰가는 시간을 가졌습니다
```

📌 [GitHub Wiki](https://github.com/FRONTENDSCHOOL5/final-21-WeMet21-Already29/wiki/%F0%9F%93%9C-%ED%9A%8C%EC%9D%98%EB%A1%9D)
<p align="right"><a href="#index" style='color: white; '>목차로 ▲</a></p>

<br>
<br>

## 5. 구현 기능
<a href="https://github.com/FRONTENDSCHOOL5/final-21-WeMet21-Already29/wiki/%F0%9F%93%91-%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%83%81%EC%84%B8-%EC%84%A4%EB%AA%85#2-%EC%9D%B4%EB%A9%94%EC%9D%BC%EB%A1%9C-%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85%ED%94%84%EB%A1%9C%ED%95%84-%EC%84%A4%EC%A0%95">🔗 각 페이지에 대한 상세 설명 페이지로 이동하기  </a>
<br>

### 1) 계정 생성 & 로그인/로그아웃
|스플래시|이메일로 회원가입|로그인|
| :---: | :---: | :---: |
|![1스플래시](https://github.com/yonaisgood/2989-Project/assets/124084624/c81a0415-5c2a-4553-901f-c5483dfde7da)|![2회원가입](https://github.com/yonaisgood/2989-Project/assets/124084624/fd610d57-72e6-47a0-96c8-cbd9ccd40e0e)|![3로그인](https://github.com/yonaisgood/2989-Project/assets/124084624/49071e6a-bbf3-4dec-a4c7-bb02a70d4020)|
|로그아웃|로딩 페이지|
|![3-1 로그아웃](https://github.com/yonaisgood/2989-Project/assets/124084624/6ad63c74-5353-482f-ac64-5b3be62a9732)|![6 로딩](https://github.com/yonaisgood/2989-Project/assets/124084624/25e9365d-a2bc-493a-86bb-cb737a3b7974)|

<br>

### 2) 홈피드 & 검색
홈피드|유저검색|
| :---: | :---: |
|![4홈피드](https://github.com/yonaisgood/2989-Project/assets/124084624/cd20edf7-9d3e-4182-823b-6671aa616b93)|![5 유저검색](https://github.com/yonaisgood/2989-Project/assets/124084624/e69fb7c1-7027-49f2-9cd3-d639e354db80)|
<br>

### 3) 게시물 CRUD
|게시물등록(다중선택)|게시물 수정/삭제|게시물 상세 페이지|
| :---: | :---: | :---: |
|![7 게시글작성](https://github.com/yonaisgood/2989-Project/assets/124084624/04190aeb-4b0b-4197-abe3-fee3ca7ca86b)|![상품 수정 : 삭제](https://github.com/yonaisgood/2989-Project/assets/124084624/330c1951-4422-434f-a204-8a795dd8e050)|![9 게시글상세(모아보기)](https://github.com/yonaisgood/2989-Project/assets/124084624/3861ecf9-b456-4378-a11d-db4abcfd47f8)|
|좋아요&댓글|댓글 삭제|
|![10 좋아요 댓글](https://github.com/yonaisgood/2989-Project/assets/124084624/d54ff915-19a9-4a00-97fb-c25a786d081f)|![11  댓글삭제](https://github.com/yonaisgood/2989-Project/assets/124084624/711b11fb-8e28-439f-a026-e3c3b7dcfcf4)|
<br>

### 4) 프로필
|내 프로필(팔로워/잉)|내 프로필수정|
| :---: | :---: |
|![12  내 프로필(팔로워:잉)](https://github.com/yonaisgood/2989-Project/assets/124084624/fa93bdee-4e59-4723-bed1-7bfa6f72d7e1)| ![13  프로필수정](https://github.com/yonaisgood/2989-Project/assets/124084624/bdff0289-846a-400f-84f7-efaa1a4accb2)| 

<br>

### 5) 상품 CRUD
|상품등록|상품 수정/삭제|판매상품 확인(카테고리별)|
| :---: | :---: | :---: |
|![상품등록](https://github.com/yonaisgood/2989-Project/assets/124084624/56e08a54-610c-4887-a7f9-22cde660e390)|![상품 수정 : 삭제](https://github.com/yonaisgood/2989-Project/assets/124084624/0fe5e542-53a0-4076-9666-4c09d359cbb0)|![판매상품 카테고리별 확인](https://github.com/yonaisgood/2989-Project/assets/124084624/dda8e936-4c77-4b54-af63-c79989398d23)|



<p align="right"><a href="#index" style='color: white; '>목차로 ▲</a></p>

  <br>
  <br>

