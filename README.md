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
<summary>JULY</summary>
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
</div>
</details>
