# 13ook 📚
<br>

## 1. 프로젝트 개요  

### - 프로젝트 소개

<h4>‘13ook’ 서비스의 이름은 숫자 ‘13’과 단어 ‘book’을 합쳐 만들어진 명칭 입니다.</h4>

<p>자신이 읽은 책에 대해 종이와 펜이 없더라도 언제 어디서든 편히 생각을 기록할 수 있으며,
도서별 짧은 리뷰와 책 속 명언을 적을 수 있는 하이라이트 페이지를 통해 다양하게 활용할 수 있는 서비스 입니다.</p>

<h4>🌟  프로젝트 목표</h4>

```
  [📖] 알라딘 API를 활용하여 데이터를 출력한다.
  [💾] 출력 된 API를 통해 베스트 셀러, 신간, 리뷰를 출력한다.
  [🧾] 출력 된 값을 통해 도서를 기록, 저장한다.
  [📔] 도서 기록 시 닉네임, 작성 시간, 한 줄 리뷰, 책표지를 보여주는 화면을 출력한다.
```
### - 팀원 소개
|장원준|권지민|김민재|
|---|---|---|
|<img width="100px" src="https://github.com/13ook/13ook/assets/142865132/2e733434-5e0e-4ef4-bc54-a0e508bfd25f"/>| <img width="100px" src="https://github.com/13ook/13ook/assets/142865132/9d711c6f-3d66-4fc3-9ba6-70a6805f9758"/>|<img width="100px" src="https://github.com/13ook/13ook/assets/142865132/2e733434-5e0e-4ef4-bc54-a0e508bfd25f"/>|
|Github 관리|Notion 관리|발표 및 자료관리|

### - 역할 분담

<details>
  <summary> 내용 작성 필요</summary>
  
  <br/>

<h align="center">[여기도 작성 필요]</h>

<br/>

</details>

<br/>

## 2. 개발 일정 및 진행 방식  

### - 개발 일정

  프로젝트 기획 2023.12.01 ~ 2023.12.06 <br/>
  프로젝트 개발: 2023.12.07 ~ 2023.12.20

### - 스크럼

- 1주차 이후 매일 오후 개별 작업 파일 공동으로 합치기
- 20시 개별 작업 중 미해결 코드가 있을 경우 디스코드를 통해 의견 공유 및 문제 해결
- 매주 주말 스터디 및 문제사항 정

### - 초기 개발 진행방식 

<details>
  <summary> 내용 작성 필요</summary>
  
  <br/>

<h align="center">[여기도 작성 필요]</h>

<br/>

</details>

<br/>

## 3. 기술 및 개발 환경  

<h4>⚙️  사용 기술</h4>

| FrontEnd | BackEnd | Design | Tools |
| :----: | :----: | :----: | :----: |
| <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/styledcomponents-CC6699?style=flat-square&logo=styledcomponents&logoColor=white"> <img src="https://img.shields.io/badge/axios-7F2B7B?style=flat-square&logo=axios&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black"> | <img src="https://img.shields.io/badge/REST API-000000?style=flat-square&logo=logoColor=white"> <img src="https://img.shields.io/badge/nodedotjs-green.svg?style=flat-square&logo=nodedotjs&logoColor=black"> <img src="https://img.shields.io/badge/express-red.svg?style=flat-square&logo=express&logoColor=black"> | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/figma-F24E1E?style=flat-square&logo=figma&logoColor=white"> | <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000.svg?style=flat-square&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"> | 


<h4>- 기술스택 적용 이유</h4>

### 📌 axios 라이브러리를 통한 서버통신 관리
* 외부 API를 프로미스 기반에 비동기 작업으 관리하기 위해 사용.  
* .get() 메서드를 사용하여 간단하게 GET 요청
* 코드를 간결하고 직관적으로 유지

### 📌  express 프레임워크를 사용한 이유
* 개발 규칙을 강제하여 코드 및 구조의 통일성 향상 
* 보편적으로 많이 사용되기 때문에 충분한 래퍼런스와 구글링을 통해 초심자도 사용 가능
* 알라딘 API 사용에서 발생되는 CORS 이슈 해결

### 📌 mongoDB를 이용한 데이터 저장
* 스키마 관리가 필요 없으며 쉽게 사용이 가능하고, 개발에서 편리성이 좋다
* 이미 성숙기에 접어들어 운용, 개발, 유틸리티에 부족함이 없다

## 4. 주요 기능

- ####  도서 추천 및 정보 제공

  알라딘 API를 활용하여 사용자에게 최신 베스트셀러 및 신간 도서 정보를 제공. 이를 통해 사용자는 독서에 대한 다양한 옵션을 쉽게 찾아볼 수 있다.

- ####  도서 검색 기능

  사용자가 원하는 책을 빠르게 찾을 수 있는 검색 기능을 구현. 카테고리 별 검색을 활용하여 특정 도서를 쉽게 찾아볼 수 있습니다.

- ####  한 줄 리뷰 작성

  책 상세 페이지에서 사용자가 짧고 간편하게 리뷰를 작성할 수 있는 기능을 제공합. 이를 통해 사용자는 짧은 리뷰를 통해 도서에 대한 별점을 공유할 수 있습니다.

- ####  하이라이트 작성

  사용자가 도서 내용 중에서 마음에 드는 글귀를 간편하게 작성하고 저장할 수 있는 기능을 제공. 사용자는 독서 중에 감명깊은 구절을 쉽게 찾아볼 수 있다.

- ####  카테고리 별 저장

  사용자가 자신의 현재 도서 상황에 맞는 도서 저장 카테고리 설정할 수 있는 기능을 제공. 이를 통해 사용자는 저장별 도서를 한눈에 확인 가.
  
  <br>
  
## 5. 문제 및 해결방안

### 🌐 CORS 이슈

 - ### 문제상황
   1. 알라딘 API를 활용하여 정보를 가져오는중 CORS발생
   2. 브라우저에서 직접적인 API 호출이 차단 되어 정보를 가져올 수 없었음.
 - ### 해결방안
   디버깅 과정을 통해 데이터 형식 확인 후 투스트링 태그를 사용해 데이터 형식을 문자열로 반환 이후 슬라이스 태그를 같이 사용해 글자 수 제한
   
### 🌐 API 글자 수 제한

 - ### 문제상황
   1. 알라딘 오픈 API를 사용해 책 정보를 가져오는 중 글자 수 제한 코드가 적용 안됨         
   2. 불러온 API 값이 문자열이 아닌 다른 데이터 형식이라 슬라이스 태그를 넣어도 적용 안    
 - ### 해결방안
   EXPRESS 서버를 도입하여 클라이언트가 EXPRESS 서버를 통해 알라딘 API의 정보를 받기 위해 간단한 서버 구축과 CORS 미들웨어를 활용해 모든 도메인의 요청을 허용하도록 설정
      
### 🌐 API 출력을 위한 SERVER 구조 문제

 - ### 문제상황
   1. API를 통해 추출하는 데이터에 대한 태그가 많을 경우 NODE 사용 미숙으로 문제 발생 
   2. 추출할 데이터를 변경 시킬때마다 URL을 수정해서 새로 열어 데이터를 가져오기만 해서 원하는 태그에 따라  SERVER가 많아져야 하는 것에 대한 고민
 - ### 해결방안
    하나의 SERVER에서 작업 할 수 있다는 피드백을 받음 GET을 사용해 경로를 지정할 경우 하나의 SERVER를 사용해도 다수의 태그에 결과값을 불러 올 수 있다는 걸 깨닫고 실행 하면서 문제를 해결
      
### 🌐 카카오톡 자동 로그인

 - ### 문제상황
   1. 카카오톡 로그인을 이용해서 로그인을 하고 로그아웃을 하고 다시 로그인을 하는 과정에서 로그인 창이 뜨지 않고 로그인했던 아이디로 자동 로그인 되어버
 - ### 해결방안
   로그아웃 버튼을 누르면 로컬 스토리지와 쿠키 삭제 코드를 적용 시킴 카카오톡 로그아웃 함수도 적용 로컬과 쿠키는 삭제를 했지만 로그인페이지에 정보가 그대로 남아있어 경험과 지식 부족으로 문제를 해결하지 못함.
      
### 🌐 별점 데이터 전달

 - ### 문제상황
   1. 저장 페이지에서 별점을 지정 후 저장 버튼을 통해 데이터 전송 시 출력 페이지에서 지정한 별점 값이 아닌 기본값만 출력되는 전송오류 발생.
 - ### 해결방안
   저장값을 받아오는 페이지에서 함수를 이용해 드래그한 별점에 현재 상태를 출력해 슷자 단위 데이터로 변환하여 전달 받는 페이지로 정확한 값을 넘기니 기본 값이 아닌 정확한 출력 값을 입력 받음.
      
### 🌐 삭제버튼 해당 도서 페이지 안으로 이동

 - ### 문제상황
   1. 기존 ui 기준으로 작업 후 ui가 수정되며 삭제 버튼을 페이지 안으로 넣어야하는 문제 발생.v페이지 안으로 들어간 삭제버튼 클릭 시 해당 데이터가 삭제되지 않으며 , 삭제될 경우 태그별 리스트에 같은 도서가 있을 경우 함께 삭제되는 문제 발생.
 - ### 해결방안
   로컬스토리지에 저장된 도서목록을 삭제할 도서를 제외한 목록으로 필터링하여 제거하고 제거 된 목록으로 업데이트 하여 구현하였다.
   
<br>

## < 일간 회의 기록 >

<details>
  <summary>🖇️ 231201</summary>
  
  <br/>

<p>
  주제 선정 및 역할 분담
</p>
<br>
  - [x] 주제 선정 및 역할 분담 <br>
  - [x] 프로젝트 선정 및 프로젝트 명 선정
</details>

<br/>


<h3>🖇️ 231202 ~ 231203</h3>
* 유저 시나리오 워크플로우 작성 및 사용자 시나리오 작성
  - [x] 피그잼으로 유저시나리오와 사용자 시나리오 작성
  - [x] 의견을 모아 수정한 후 제출

<h3>🖇️ 231204</h3>
* 평택역 할리스 13:00 샘플 UI 작업으로 인한 미팅
* 13:00 ~ 18:30 샘플 UI 작업 및 API 호출 방안 토의
* 노션 정리 / 깃 관리

<h3>🖇️ 231204 ~ 231205</h3>
* 유저 시나리오 워크플로우 작성 및 사용자 시나리오 작성
  - [x] 피그잼으로 유저시나리오와 사용자 시나리오 작성
  - [x] 의견을 모아 수정한 후 제출
  - [x] 알라딘 API 추출 완료
    - [ 😵 ] CORS 보안 이슈로 인해 콘솔 에러 출력
      - [x] Node.js를 이용해 서버 구축
      - [x] 서버 구축으로 인해 CORS 이슈 문제 해결
    - [ 😵 ] xml 방식의 API로 인해 배열이 출력이 안 되는 이슈 발생
      
<h3>🖇️ 231205</h3>
* 요구사항 분석
* Sample UI 피드백 반영 및 수정
* 디렉토리 구조 구상
* 테마, 컨셉 및 재구상
* 주말 간 작업에 대한 토의

      
<h3>🖇️ 231206</h3>
* Sample UI 피드백
* 디렉토리 구조 작성
* 알라딘 API 서버 스터디

<h3>🖇️ 231207</h3>
* KaKao로그인 API 구현⛏
  - [x] API 활용을 통해 로그인 화면 구현
    - [ 😵 ] 카카오 로그인을 한 번 하면 기록이 남아 과정 없이 지나가는 현상 발생
      - [x] 로그아웃 버튼을 만들어 초기화 하여 해결
* 여러 API를 한 곳에 호출 구현✨
  - [x] api 2개 연결 성공
    - [ 😵 ] 2개에 대한 쿼리 값이 달라 호출이 되지 않는 문제 발생
      - [x] 해당하는 쿼리 값을 찾아 구현
* 로그인 성공,실패 - 성공 화면 - 메인으로 연결🎊
  - [x] 클라이언트에서 정한 ID,PW으로 로그인 화면 구현
    - [ 😵 ] 저장소가 없어 고유 값으로 로그인 구현x
* 키워드 검색, 검색 결과 값 호출, 상세페이지 구현🔑
  - [x] 키워드 검색 호출
  - [x] 검색 값을 받아 값 호출
    - [ 😵 ] 결과 값을 받은 책을 누르면 에러 발생
      - [x] Link 클릭 시 해당 아이템의 정보를 전달하도록 수정
      - [x]  <Link to={`/info/${result.isbn}`} state={{ bookInfo: result }}>
      - [x] currentLocation.state && currentLocation.state.bookInfo; 로케이션을 사용해 값을 받아 고유의 번호로 링크 출력 
<h3>🖇️ 231208</h3>
* 검색 컴포넌트에 카테고리 별 검색 기능 구현
    - [x] Link to 함수를 이용해 컴포넌트 이동으로 카테고리 검색 구현
      - [ 😵 ] 정리되지 않은 "/"링크로 인해 작업의 지연
          - [x] 메인 컴포넌트에 대한 링크 정리와 이해
    

