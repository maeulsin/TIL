# Django

## django 프로젝트 생성 전  루틴
1. 가상환경 생성
$ python -m venv venv

2. 가상환경 활성화
$ source venv/bin/activate

3. django 설치(버전 명시 x -> 4.0설치됨)
$ pip install django==3.2.18

4. 의존성 파일 생성 (패키지 설치마다 진행)
$ pip freeze > requirements.txt

## django 프로젝트 생성
- $ django-admin startproject firstpjt .
(firstpjt라는 이름의 프로젝트 생성. 프로젝트 이름 변경 가능. '.'은 현재위치를 가리킴)

## django 서버 실행
$ python manage.py runserver
