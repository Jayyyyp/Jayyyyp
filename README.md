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

## 파일 탐색기 내에서 삭제했을 때
1. 단 삭제를 미루고 다른 파일을 먼저 커밋 하기  
    git restore —staged (파일이름)
2. 원하는 파일을 스테이지에 올리기
    git add anotherfile.txt
3. 스테이지된 다른 파일을 커밋하기
    git commit -m “커밋 메시지”
4. 이제 삭제할 파일을 다시 스테이지 후, 커밋
    git rm (삭제할 파일명.확장자)
    git commit -m “커밋 메시지”
