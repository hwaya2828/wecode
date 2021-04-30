<h1> About Git </h1>

<h3> Git 명령어 정리 </h3>

- __git .init__ : 이 명령어를 입력하기 전까지는 일반 디렉토리였지만, git init으로 초기화를 시키면 해당 디렉토리를 로컬 git 저장소로 등록함

- __git branch -M main__ : git 기본 branch 이름을 'master'에서 'main'으로 변경함

- __git remote add origin__ : 현재의 로컬 저장소를 github에 있는 특정 repository에 연결함

- __git add .__ :  status에 나온 변경사항을 모두 스테이지에 올려줌

- __git commit -m "COMMIT내용"__ : 현재 commit 대상이 되어있는 파일을 한 번에 모두 commit 시키며, -m 뒤에는 버전 관리를 위한 commit 메시지를 작성해야함

- __git push -u origin  "PUSH할브랜치이름"__ : 로컬 저장소에 있던 파일을 원격 저장소로 보내줌



