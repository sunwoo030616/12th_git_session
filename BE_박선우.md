# 1주차 git session 

깃 & 깃허브

깃의 원리: 하나의 파일에 수정사항을 계속 반영 [Add&Commit]해주는 똑똑한 프로그램

깃+깃허브: 깃은 파일에 대한 역사책을 쓰고, 출판사는 깃허브이다.[Push] 모두가 깃허브를 통해 역사책을 공유받을 수 있다 [Pull]
## 깃 사용법(혼자)

  프로젝트 처음에 한번만
  1.Github에서 개인 레포지토리 생성
  2.로컬에서 폴더 생성후,사용자 등록
  3.생성한 개인 레포지토리에 연결
  프로젝트 내내 반복
  4.폴더에서 파일 수정,편집
  5.폴더에서 파일 수정 사항 반영하기
  6.폴더를 push하여 개인 레포지토리에 반영

##  깃 사용법(같이)
  프로젝트 처음에 한번만
  1.Github에서 레포지토리 생성 (=중앙 레포지토리)
  2.각 인원은 해당 중앙 레포지토리를 fork하여 개인 레포지토리 생성
  3.폴더 생성 후, 중앙 레포지토리와 개인 레포지토리 연결(origin과 upstream)
  프로젝트 내내 반복
  4.Branch 생성, 폴더에서 파일 수정,편집 (작업 직전 upstream에서 pull 필수)
  5.폴더에서 파일 수정 사항 add, commit으로 반영하기
  6.폴더를 push하여 개인 레포지토리에 반영하기
  7.개인 레포지토리에서 Pull request하기
  8.중앙 레포지토리에서 코드 확인 후 merge 받기
  9.폴더의 main브랜치에 수정사항 반영
  10.예전 브랜치 삭제(이후4~10반복)

## Framework와 Django
 Framework? 웹 서비스를 만들어주는 기계
 Django? 파이썬으로 작성된 웹 애플리케이션 프레임워크
 -Django 개발 환경 세팅하기
 Workspace 생성 > Visual Studio Code 열기 > 폴더 만들기 > Git repository 생성하기 > Git 연동하기
 > 가상환경 설정하기 
 1.가상환경 설치 $ pip 3 install pipenv 
 2.가상환경 켜기 $ pipenv shell
 >Django 설치하기
 1.장고 설치: $ pip install django
 2.프로젝트 파일 생성: $django-admin startproject [project name]
 >Settings.py 초기 설정하기 
 >App생성
 1.앱 설치: $ python manage.py startapp [appname]
 2.settings.py에 설치한 앱 등록
 >서버 실행
 1.migrate하기: $ python manage.py migrate
 $ python manage.py makemigrations
 2.서버 실행하기: $ python manage.py runserver
 >project,app 비교하기>project 살펴보기> app살펴보기
 끝


