# ict04_myapp
// 로컬과 연결 ict04_myapp

// git 의 시작
1. $ git init
=> 초기화 시킨 후 해당 폴더에서 .git 파일이 생성되었는지 확인한다.
Initialized empty Git repository in D:/DEV/workspace_git_ict04/ex03_company/myapp/.git/

2. $ touch 프로젝트설정.txt
=> touch 명령어로 파일 생성하기(프로젝트설정.txt) ** 띄워쓰기 안먹히니 주의할 것 **

3. $ git add .
=> 커밋하기

4. $ git commit -m "프로젝트 설정완료"
=> 버전 관리 시작 (버전에 대한 이름 부여)

5. $ git log
=> 커밋된 내역(log) 확인

6. 커밋 할 내용이 있는지 확인하기
=> $ git status
On branch master
nothing to commit, working tree clean

7. $ git remote add origin https://github.com/Derek0910/ict04_myapp.git
=> 프로젝트를 관리할 git hub 주소를 지정해주기

8. $ git remote -v
=> 부여할 주소와 연결되었는지 확인하기

9. $ git ls-remote
=> remote 된 내역(list) 보이기

10. $ git push origin master
=> 로그인 창으로 연결됨 (인증 필요)

11. 아이디와 패스워드 입력하여 인증 완료 되면
=>
/*
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 252 bytes | 252.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Derek0910/ict04_myapp/pull/new/master
remote:
To https://github.com/Derek0910/ict04_myapp.git
// * [new branch]      master -> master
* /
위 창이 뜸
