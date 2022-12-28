# GitHub

> ## 초기 원격저장소 설정하는 법
1. New Repository
2. 저장소 설정하기(이름,저장소 설명-옵션, 공개 여부-public,)
3. 로컬 저장소에 원격 저장소 정보 설정하기
4. $ git remote add origin https://github.com/hyunjinsin02/저장소이름.git
5. 원격 저장소의 정보를 확인하기 git remote -v (v=verbose) 

> ## 로컬 저장소의 버전을 원격 저장소로 Push하기
$ git push origin master


> ## 로컬 저장소의 버전을 원격 저장소로 Pull하기
$ git pull origin master

> ## 원격저장소 프로젝트 시작
- 가지고 오는 행위=clone
1. code 클릭
2. 주소옆 버튼 클릭
3. 바탕화면 우클릭 git bash 
4. $ git clone https://github.com/GitHubUsername/저장소이름.git 입력

- Clone과 Pull의 차이점
Clone : 원격저장소 복제
Pull : 원격저장소 커밋 가져오기

> 명령어 정리
- git clone <url> : 원격 저장소 복제
- git remote -v : 원격저장소 정보 확인
- git remote add <원격저장소> <url> : 원격저장소 추가(일반적으로 origin)
- git remote rm <원격저장소> : 원격저장소 삭제
- git push <원격저장소> <브랜치> : 원격저장소에 push (내 것 공유)
- git pull <원격저장소> <브랜치> : 원격저장소로부터 pull (다른 사람 거 가져오기)