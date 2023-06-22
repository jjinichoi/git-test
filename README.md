# Git command 정리
- `git init`
- `git remote add origin <remote repository url>`
- `git add <file name>`
- `git commit`
- `git push origin <branch name>`
- `git pull origin <branch name>`
- `git merge <branch name>`

---
## git init

- git을 시작할때 사용하는 명령어로 저장소를 생성한다.

## git remote add origin <remote repository url>

- git과 github를 연결시켜주는 명령어이다.
- 명령어를 나눠서 설명을 한다면 아래와 같다.
	- `git remote add` : git에 연결 추가를 할게 -> 뭐를?
	- `origin <remote repository url>` : 레파지토리의 주소를 origin이라는 별명으로 설정해서 가져올게!
    >여기서 별명인 origin은 임의로 수정가능하지만 origin이라고 하는것이 컨벤션
    
## git add <file name>

- 변경된 파일을 추가준비를 하라는 명령어로 두가지의 작성방법이 있다.
	- `git add <file name>` : 해당 파일만 추가
	- `git add .` : 변경된 파일 모두 추가(주로 사용됨)

## git commit

- add로 준비된 파일들을 실제로 적용하는 것이며 두가지의 작성방법이 있다.
(commit 메세지는 작업내용에 대해 간단한 영문단어로 작성 후 어떤 작업을 했는지 설명 작성)
	- `git commit -m "ADD : 이름 수정" `: commit 메세지 한줄만 작성 시
 	- `git commit` : commit 메세지 여러줄 작성 시
    
## git push origin <branch name>

- commit한 파일을 명령어에 가르킨 branch에 github에 올리는 명령어

## git pull origin <branch name>
- 명령어에 가르킨 branch의 파일들을 로컬 git으로 받아오는 명령어

## git merge <branch name>
- 다른 branch를 현재 checkout된 branch의에 합치는 명령어
