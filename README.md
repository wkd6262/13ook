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
### - 사전조사
|북적북적 ui/ux 기능 참고 |밀리의 서재 ui/ux ,기능 참고|북모리 ui/ux 기능 참고|
|---|---|---|
|![Untitled (1)](https://github.com/13ook/13ook/assets/142865132/1b29fc9e-adfa-4db3-bf86-22557359d777)|![Untitled](https://github.com/13ook/13ook/assets/142865132/2ab59fb2-256a-46d0-ad90-361da5511942)|![Untitled (2)](https://github.com/13ook/13ook/assets/142865132/fc83f705-134f-41ae-988a-6f735dace5a5)


### - 고려사항
|FrontEnd|BackEnd|Data-Base|
|---|---|---|
|- 언어: JavaScript (React) - 프레임워크: React.js - 모듈화된 CSS인 module.css 사용|- Node.js, Express, Axios 활용한 서버 개발 - 엔드포인트, GET 및 POST 메소드 이해 - mongoDB 연결을 통한 데이터 저장|- CORS 이슈 해결 및 데이터베이스 통신 원활하게 - Open API 사용법 숙지 및 데이터 가공 후 내보내기 계획


### - 팀원 소개
|장원준|권지민|김민재|
|---|---|---|
|<img width="100px" src="https://github.com/wkd6262/wkd6262/assets/142865132/894e4b9b-cba5-4c6d-b232-f853396afdf5"/>| <img width="100px" src="https://github.com/13ook/13ook/assets/142865132/9d711c6f-3d66-4fc3-9ba6-70a6805f9758"/>|<img width="100px" src="https://github.com/13ook/13ook/assets/142865132/2e733434-5e0e-4ef4-bc54-a0e508bfd25f"/>|
|Github 관리|Notion 관리|발표 및 자료관리|

### - 역할 분담
  <br/>

  | ... | 페이지 |기능 구현| 리펙토링 |
  |---|---|---|---|
  | 장원준 |- 메인 페이지<br> - 검색 페이지<br> - UI 디자인 <br> |- 현재 읽고 있는 책 리스트 <br> - 도서 검색 및 도서 상세 페이지  구현 <br> - 상세 페이지 저장 시 내 서재로 데이터 이동 |- 외부 API 연결 :알라딘API(검색기능,베스트셀러, 신간목록) <br> - 파일 병합|
  | 김민재 |- 로그인 페이지<br> - 책방 페이지 | - 로그인 <br> - 로그아웃 <br> -베스트셀러 및 신간 리스트 출력|- 외부 API 연결 : 카카오 로그인API|
  | 권지민 |- 피드 페이지<br> - 내서재 페이지 |- 회원가입 <br> - 한줄리뷰 및 하이라이트 작성 <br> - 작성된 데이터를 피드 페이지에 출력 <br> - 내서재 메모장 기능 구현 |- 회원가입 및 로그인 mongoDB 연결 <br> - 클라우드타입 배포 |

<br/>

</details>
<br />

  

<div align="center">
  
## 핵심기능 시연 ##

| 로그인                                                 | 메인                                                             |
| ------------------------------------------------------ | ----------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262.github.io/assets/142865132/eeeb82dd-1ccd-4643-9e19-876d05a35dce" width="350"> | <img src="https://github.com/13ook/13ook/assets/142865132/b66d73e9-3310-4af1-8e1b-75d83d49bf5e" width="350"> |
| 피드                                             | 검색                                                     |
| <img src="https://github.com/13ook/13ook/assets/142865132/48ef9e93-5e63-46e1-b51e-94ab10d2bbac" width="350"> | <img src="https://github.com/13ook/13ook/assets/142865132/e35289f5-ab5e-4143-86d3-978995fd67cf" width="350"> |
| 책방                                              | 내 서재                                                                 |
| <img src="https://github.com/13ook/13ook/assets/142865132/f3fb2d39-e728-45d3-98dc-37622db0c16b" width="350"> |<img src="https://github.com/13ook/13ook/assets/142865132/9c7ad68b-3d9c-425d-b505-77794135788a" width="350">|

</div>

<br/>

## 2. 개발 일정 및 진행 방식  

### - 개발 일정

  프로젝트 기획: 2023.12.01 ~ 2023.12.06 <br/>
  프로젝트 개발: 2023.12.07 ~ 2023.12.20

### - 스크럼

- 1주차 이후 매일 오후 개별 작업 파일 공동으로 합치기
- 20시 개별 작업 중 미해결 코드가 있을 경우 디스코드를 통해 의견 공유 및 문제 해결
- 매주 주말 스터디 및 문제사항 정리

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
  - [x] 주제 선정 및 역할 분담 <br>
  - [x] 프로젝트 선정 및 프로젝트 명 선정
</details>

<details>
  <summary>🖇️ 231202 ~ 231203</summary>
  
  <br/>

<p>
  유저 시나리오 워크플로우 작성 및 사용자 시나리오 작성
</p>
  - [x] 피그잼으로 유저시나리오와 사용자 시나리오 작성
  - [x] 의견을 모아 수정한 후 제출
</details>

<details>
  <summary>🖇️ 231204 </summary>
  
  <br/>

  * 평택역 할리스 13:00 샘플 UI 작업으로 인한 미팅
  * 13:00 ~ 18:30 샘플 UI 작업 및 API 호출 방안 토의
  * 노션 정리 / 깃 관리
</details>

<details>
  <summary>🖇️ 231205 </summary>
  
  <br/>
* 요구사항 분석
* Sample UI 피드백 반영 및 수정
* 디렉토리 구조 구상
* 테마, 컨셉 및 재구상
* 주말 간 작업에 대한 토의
* 유저 시나리오 워크플로우 작성 및 사용자 시나리오 작성
  - [x] 피그잼으로 유저시나리오와 사용자 시나리오 작성
  - [x] 의견을 모아 수정한 후 제출
  - [x] 알라딘 API 추출 완료
    - [ 😵 ] CORS 보안 이슈로 인해 콘솔 에러 출력
      - [x] Node.js를 이용해 서버 구축
      - [x] 서버 구축으로 인해 CORS 이슈 문제 해결
    - [ 😵 ] xml 방식의 API로 인해 배열이 출력이 안 되는 이슈 발생
</details>

<details>
  <summary>🖇️ 231206 </summary>
  
  <br/>

* Sample UI 피드백
* 디렉토리 구조 작성
* 알라딘 API 서버 스터디
</details>

<details>
  <summary>🖇️ 231207 </summary>
  
  <br/>

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
</details>

<details>
  <summary>🖇️ 231208 </summary>
  
  <br/>
* 검색 컴포넌트에 카테고리 별 검색 기능 구현
    - [x] Link to 함수를 이용해 컴포넌트 이동으로 카테고리 검색 구현
      - [ 😵 ] 정리되지 않은 "/"링크로 인해 작업의 지연
          - [x] 메인 컴포넌트에 대한 링크 정리와 이해
</details>

<details>
  <summary>🖇️ 231209 </summary>
  
  <br/>
  1. **SPA 라우터 정리**
    - 미정리된 SPA 라우터 중 "/" 링크들을 체계적으로 정리, 각 링크에 대한 명확한 설명과 역할을 기록하여 프로젝트의 가독성을 향상
2. **Link to 함수를 활용한 카테고리 검색 구현**
    - 정리된 링크들을 기반으로 Link to 함수를 적절히 활용하여 도서명과 저자명에 대한 카테고리 검색을 구현 성공 이를 통해 사용자들이 효과적으로 원하는 정보를 찾을 수 있도록 지원.
3. **컴포넌트 통합**
    - 각 팀원이 맡은 컴포넌트를 정리하고 효율적으로 합침으로써 프로젝트의 일관성과 성능을 향상, 각자의 전문성을 살려 협업을 통한 원활한 진행을 이룸.
</details>

<details>
  <summary>🖇️ 231211 </summary>
      
  <br/>
1. **Feed 한 줄 리뷰 별점 저장 구현**
    - 사용자가 입력한 별점을 구현하는 과정에서, 디스코드 토의에서 나온 의견을 참고하여 LocalStorage에 저장하는 방식으로 구현.
2. **Mybook 중복 저장 현상 해결**
    - Mybook 컴포넌트에서 발생한 중복 저장 문제에 대한 해결책으로, 저장버튼이 동일한 값으로 저장되는 문제를 발견. 이에 대한 해결책으로 로컬스토리지에 **`Savebooks`**와 **`Savebooks2`** 따로 저장소를 만들어 작업하여 중복 저장 현상을 해결.

**팀원 의견:**

- [권지민]: "별점 저장 구현이 잘 이뤄졌습니다. 사용자 경험을 고려한 구현이라 좋아요."
- [장원준]: "Mybook 중복 저장 문제를 로컬스토리지를 분리하여 처리한 것이 좋은 해결책이었습니다."
- [김민재]: "학원이 끝나고도 디스코드로 토의를 하여 문제점을 해결한 점이 좋았습니다.”

</details>

<details>
  <summary>🖇️ 231213 </summary>
  
  <br/>
1. **Main 컴포넌트 햄버거 메뉴 토의**
    - 팀 끼리 대면하여 햄버거 메뉴를 어느 부분에 써야할지를 토의했고 토의 결과 메인 페이지에만 적용하기로 하여 사용자의 이동 편리성을 상승
2. **Css겹침 이슈 토의**
    - 각자 담당하여 맡은 컴포넌트에 module,scss등을 쓰지 않아 겹침 이슈가 발생하여 팀끼리 화상채팅을 통하여 각자 어떤 방향으로 수정하고싶은지 의견을 수렴하여 module.css로 결정하여 수정

**팀원 의견:**

- [권지민]: "사이드 메뉴, 햄버거 메뉴에 대한 토의를 잘 마무리 한 거 같아서 좋았습니다."
- [장원준]: "css겹침에 대한 이슈가 발생했을 때 당황하지 않고 토의로 풀어간 점이 좋았습니다."
- [김민재]: “팀원의 적극적인 태도로 의견충돌 없이 수월하게 진행 되었습니다.”
</details>

<details>
  <summary>🖇️ 231216 </summary>
  
  <br/>
1. **책 제목 글자 수 해결에 대한 의견** 
    - {book.title.toString.slice(0, 10) || "알 수 없음"}… 이렇게 해결하려 했지만 되지 않아 팀끼리 의견을 나눠서 종합해보았지만 어느 방법으로 해결이 되지 않아 학원 선생님께 질문을 하여{book.title.toString().slice(0, 10) || "알 수 없음"}…으로 해결하였음
2. **부족한 점에 대한 의견 종합**
    - 마진,패딩,크기 값들이 일정하지 않아 css에 대한 전체적인 수정이 필요하다는 의견
    - Library 컴포넌트 디자인 구성을 어떻게 할지에 대한 의견
    - Main 컴포넌트 책 저장 목록 n권 표시에 대한 의견
    - 포인트 컬러 정하기에 대한 의견
</details>

<details>
  <summary>🖇️ 231219 </summary>
  
  <br/>
1. 발표 및 **마무리 피드백 종합**
    - Ppt,깃허브 정리,노션 정리, 파일 종합 및 수정 에 대한 역할 분담을 정하고 마무리 작업
2. **발표 피드백 종합**
    - ppt 기술 부분, 디자인, 문제 해결 설명 부분 수정
3. **디자인 의견 토의**
    - 마무리 작업 중 디자인에 대해 개선해야할 점을 파악하여 수정
</details>

