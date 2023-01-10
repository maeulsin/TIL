# GIT

- Git은 분산버전관리시스템으로 코드의 버전을 관리하는 도구

## git init
- 특정 폴더를 git 저장소(repository)를 만들어 git으로 관리

## **버전 기록**
1. 작업을 하고
2. 변경된 파일을 모아(add)
3. 버전으로 남긴다. (commit)

## Git은 파일을 modified, staged, committed로 관리
- modified: 파일이 수정된 상태 (add 명령어를 통하여 staging area로)
- staged : 수정한 파일을 곧 커밋할 것이라고 표시한 상태(commit 명령어로 저장소)
- committed: 커밋이 된 상태

## Git 기초 명령어
- git init: 로컬 저장소 생성
- git add <파일명>: 특정 파일/폴더의 변경사항 추가
- git commit -m '<커밋메시지>': 커밋(버전 기록)
- git status: 상태 확인
- git log: 버전 확인

