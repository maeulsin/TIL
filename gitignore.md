# gitignore
- 일반적인 개발 프로젝트에서 버전 관리를 별도로 하지 않는 파일
- Git 저장소에 .gitignore 파일을 생성하고 해당 내용 관리
- 작성 예시
  - 특정 파일 : a.txt(모든 a.txt), test/a.txt(테스트 폴더의 a.txt)
  - 특정 디렉토리 : /my_secret
  - 특정 확장자 : *.exe
  - 예외 처리 : !b.exe

> **이미 커밋된 파일은 반드시 삭제해야 .gitignore로 적용됨**
  *프로젝트 시작전 미리 설정하기!!*

# 파일 종류
- 개발 언어 
  - 예시) 파이썬 : venv/, 자바스크립트 : node_modules/
- 개발 환경
  - 운영체제 (windows, mac. linux)
  - 텍스트 에디터 / IDE (visual studio code 등)
  