# Django

## django 프로젝트 생성 전  루틴
1. 가상환경 생성
- $ python -m venv venv

2. 가상환경 활성화
- $ source venv/bin/activate

3. django 설치(버전 명시 x -> 4.0설치됨)
- $ pip install django==3.2.18

4. 의존성 파일 생성 (패키지 설치마다 진행)
- $ pip freeze > requirements.txt

## django 프로젝트 생성
- $ django-admin startproject firstpjt .
- (firstpjt라는 이름의 프로젝트 생성. 프로젝트 이름 변경 가능. '.'은 현재위치를 가리킴)

## django 서버 실행
- $ python manage.py runserver
---

> ## django 프로젝트 생성 루틴 정리
```
**cd desktop -> cd 파일이름**
1. 데스크탑에 파일 생성
2. Terminal에 python -m venv venv
3. source venv/bin/activate
4. pip install django==3.2.18
5. pip freeze > requirements.txt
6. $ django-admin startproject firstpjt .
7. Vscode 실행 후 .gitignore 파일 생성
8. command+shift+p 검색창에 interpreter 별표 표시된거 커서 두고 엔터 그 다음에 터미널 열기
9. pip list
10. [gitignore](https://www.toptal.com/developers/gitignore/) 접속해서 windows, macOs, python, visualstudiocode, Django 검색 후 전체 선택해서 복사한 다음 .gitignore 파일에 복붙
11. git init
12. git status
13. git add .
14. git commit -m'firstcommit'
15. python manage.py runserver

**서버 끄기 == control + c**
```