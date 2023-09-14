<h1 align="center">Hi 👋, I'm JayPark</h1>
<h3 align="center">A passionate Backend developer from South-Korea</h3>

<p align="right"> <img src="https://komarev.com/ghpvc/?username=jayyyyp&label=Profile%20views&color=0e75b6&style=flat" alt="jayyyyp" /> </p>




<h3 align="left">Introdution</h3>

<p>
	Hi, I'm Jay Park!<br>
    I'm experiendced with a range of back-end technologies, specialized primarily in JAVA.
</p>
<h3 align="left">Profile</h3>
<p>
Name : 박재현(Jay Park)<br>
Email : pjae9726@gmail.com<br>
Tech Blog : (https://www.notion.so/Coding-Diary-f58aa2dd0fee4523bb0cb76dbefc1e04)
</p>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>

---

<details>
<summary>GitHub 이용방법</summary>
<div markdown="1">


## LF will be replaced by CRLF in 해결 방안
- git config --global core.autocrlf true  입력

## ![rejected] master → master (fetch first)
- git push origin +master
- 위의 경우, 변경 내용만 반영되는 것이 아닌, **강제로 소스 전체가 push** 되어버림.

## git push origin master 입력 시, err:src refspec master does not match any 발생 
- git init
  git add .
  git commit -m “message”
  git remote add origin “github.com/my_ssh_address”
  git push -u origin master
  
- 만약 master 브랜치가 없어서 발생하는 오류일시,
  git checkout -b ‘master’
  git push origin master
  
## 깃 안에서 파일 삭제하기
- - Github에 삭제할 파일을 누른다.
- 오른쪽 상단의 ``` 을 누르고, delete를 누른다.
- 맨 밑으로 가서 commit changes 까지 누르면 반영

## 파일 탐색기 내에서 삭제했을 때에
1. 단 삭제를 미루고 다른 파일을 먼저 커밋 하기  
    git restore —staged (파일이름)
2. 원하는 파일을 스테이지에 올리기
    git add anotherfile.txt
3. 스테이지된 다른 파일을 커밋하기
    git commit -m “커밋 메시지”
4. 이제 삭제할 파일을 다시 스테이지 후, 커밋
    git rm (삭제할 파일명.확장자)
    git commit -m “커밋 메시지”
</div>
</details>

---

<details>
<summary>Git-flow 사용법</summary>
<div markdown="1">
노션 링크 : (https://www.notion.so/Git-Flow-e813b9a4a62943d58b090b0abfc6d91d)
</div>
</details>

---

<details>
<summary>July</summary>
<div markdown="1">
	16th - JPA API 복습(https://github.com/Jayyyyp/Spring_blog_real)<br>
	17th - JPA 페이징 처리 복습 및 노션정리(https://www.notion.so/JPA-Java-Persistence-API-15747b96c59c452dbc617cb1c93912d3)<br>
	18th - 스프링 시큐리티 복습 및 노션정리(https://www.notion.so/Spring-Security-4235730cbc7c4ea7844fda64f6c15847)<br>
	19th - 객체지향 책 복습<br>
	20th - 스프링 시큐리티 기초 완료(회원가입, 로그인, 로그아웃)<br>
	21st - JWT 로그인 설정 및 refresh토큰 공부(https://www.notion.so/JWT-refresh-token-e2dbf32c3a5d45cd932450321746872f)<br>
	22nd - 리액트 기초 공부(https://www.notion.so/React-5d3f7850eaec4ca697c49035fd6a8f25)<br>
	23rd - 스프링부트3 스프링 시큐리티 공부1<br>
	24th - 리액트 컴포넌트 공부(https://www.notion.so/1-React-Component-cf6ee1e6bc1b4ba7acdd1a9195510f8f)<br>
	25th - 스프링부트3 스프링 시큐리티 공부2<br>
	26th - 팀 프로젝트 기획 문서 제작 및 정리<br>
	27th - 리액트 이벤트 바인딩 공부1<br>
	28th - 리액트 이벤트 바인딩 공부2<br>
	29th - api 기초 공부 및 검색 api 개념 정리(https://www.notion.so/API-b65c763132bd49ec82e4d44c10850de2)<br>
	30th - naver 검색 api 응용해보기(https://www.notion.so/API-fb6ba0556a2642eba26fb854524269f2)<br>
	31st - naver cloud 기초(https://www.notion.so/Cloud-4637c5490bb74f309f2bb53f9c38afd7)<br>
</div>
</details>

<details>
<summary>August</summary>
<div markdown="1">
	1st - 11번가 open api 활용해보기<br>
	2nd - 멘토링 질문 정리 및 공부<br>
	3rd - Jira 툴 노션 정리 및 애자일 방법론 공부(https://www.notion.so/jayyyyp/Jira-8633442a8834465087e6dd800393a6e4)<br>
	      11번가 jsoup 크롤링 실패(https://github.com/Jayyyyp/KKINI_crawling)<br>
	4th - 11번가 jsoup 크롤링 성공(https://github.com/Jayyyyp/KKINI_crawling)<br>
	      크롤링 정리[https://www.notion.so/jayyyyp/4a067d07e72744edb405aa91cf0c4918]<br>
	5th - 11번가 Selenium 크롤링 실패(https://github.com/Jayyyyp/KKINI_crawling)<br>
	크롤링 데이터 정제 및 API 데이터와 매핑 방법 공부<br>
	6th - 11번가 Selenium 크롤링 성공(https://github.com/Jayyyyp/KKINI_crawling)<br>
	7th - 11번가 Selenium 크롤링_페이지별로 데이터 뽑기 실패<br>
	8th - 검색 기능 기초 공부<br>
	9th - 검색 기능 기초 구현 1 <br>
	10th - 검색 기능 기초 구현 2 <br>
	11st - 검색 기능 기초 구현 성공(https://github.com/Jayyyyp/KKINI_Search)<br>
	12nd - 검색 기능 기초 구현 정리(https://www.notion.so/jayyyyp/fb30d7df25484d279293836d25d9302f),<br>
	       스프링부트 JPA책 공부<br>
	13rd - 스프링부트 JPA책 실습(https://github.com/Jayyyyp/JPA_study)<br>
	       스프링부트 JPA책 정리_93p(https://www.notion.so/jayyyyp/with-JPA-9a098c9b14084d0ea7388d94592be274)<br>
	14th - 검색 기능 추가(카테고리 검색 가능, 완성된 단어를 치지않아도 2글자 이상 검색하면 자동으로 트래킹)<br>
		평점 CRUD 기능 추가를 위한 웹서핑<br>
	15th - 평점 CRUD 기능 중 CR부분 구현완료<br>
		수정과 삭제 부분은 실패(사용자 쿠키 저장이 안되는 상황)<br>
	16th - 평점 수정과 삭제 성공(사용자 id를 더미데이터로 쓰기)<br>
	17th - 평점 사진 업로드 최종 성공(https://github.com/Jayyyyp/KKINI_Search)<br>
	18th - enum클래스란?(https://www.notion.so/jayyyyp/enum-c71488bdf4084796a279d0a9f933e02d)<br>
	19th - 프로젝트 연습 jsp -> 리액트 변환 시키기<br>
	20th - Refactoring 방법 고찰(https://www.notion.so/jayyyyp/Refactoring-ea1055154d1a45748f2ece01801aadff)<br>
		프로젝트 연습 코딩에 적용하기<br>
	21st - Item, Category refactoring 완료<br>
	22nd - 프로젝트 repository에서 검색 기능 구현<br>
	23rd - Back-end와 Front-end 연동(리액트)<br>
	24th - 프로젝트 코드 수정(Category 엔터티 Product로 흠수시키기)<br>
	25th - 프로젝트 코드 리팩토링<br>
	26th - 프로젝트 코드 부가검색기능 추가(자동완성, 띄어쓰기 무시)<br>
	27th - 프로젝트 코드 리팩토링 및 검색 기능 구현 완료<br>
	28th - 검색 기능 추가 리팩토링 및 공부<br>
	29th - 프로젝트 카테고리 분류 기능 구현<br>
	30th - 프로젝트 필터 기능 구현<br>
	31st - 프로젝트 필터 기능 테스트 및 리액트 적용<br>
</div>
</details>
<details>
<summary>September</summary>
	<div markdown="1">
		1st - 프로젝트 필터 기능 리팩토링<br>
		2nd - 프로젝트 필터 기능 리팩토링 및 REST API 공부<br>
		3rd - 프로젝트 필터 기능 쿼리문 간소화 고찰
		4th - 프로젝트 필터 기능 쿼리문 추가
		5th - 프로젝트 필터 기능 리팩토링
		6th - 프로젝트 필터 기능 테스트코드 수정
		7th - 프로젝트 리액트 컴포넌트/컨테이너 분리
		8th - 프로젝트 리액트 컴포넌트/컨테이너 추가 공부(Hook)<br>
		9th - 프로젝트 리액트 컴포넌트/컨테이너/API Client/페이지 분리 <br>
		10th - 프로젝트 필터(backend) 버그 수정 -> NullPointerException <br>
		11st - 프로젝트 예외 처리 대신 Null로 처리 -> 상품이 없을때, 예외처리되지 않게<br>
		12nd - 프로젝트 상품 상세페이지 구현<br>
		13rd - 프로젝트 이용약관 및 개인정보처리 부분 작성<br>
		14th - 
	</div>
</details>
