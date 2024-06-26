# Django 서버 구동하기

## 1. Git hub 연결하기
**mstec_django 리포지토리 생성 후 연결**
1. 내 컴퓨터와 Git과 연결이 되어있는 지 확인하기
`$git config --global user.email `
`$git config --global user.name `

2. github에서 리포지토리 만들기

3. 프로젝트 디렉토리에서 깃 시작하기 
`$ git init`

4. 연결하기
`$ git remote add origin 'https://깃허브 리포지토리 주소'`
연결 후 확인하기
`$ git remote -v`



## 2. Django 프로젝트 시작하기
1. 디렉토리 생성 후 이동하기
pwd : 현재 디렉토리 확인
cd : 이동할 디렉토리
cd .. : 뒤로가기

2. 가상환경 생성(이놈이 중요)
`$ python -m venv myenv(얘는 그냥 이름 짓기 나름)`

3. 가상환경 실행
`$ source myenv/Scripts/activate`

4. 가상환경 끄기
`$ deactivate`

5. 가상환경 켜졌는 지 확인 (venv) pip freeze + 한 번 해보자. 

6. Django 다운로드
`$ pip install django==4.2.4`

7. dashboard 프로젝트 생성
`$ django-admin startproject dashboard .`    . <-현재 디렉토리(내가 위치한 곳)

8. django 서버 실행하기(로켓 봐야함)
`$ python manage.py runserver`
127.0.0.1:8000 


---------------------------------------

## 기타 1. 작업을 한 뒤 형상 관리(Git)

**작업을 한 뒤**
`$ git add .` (내가 작업한 내용 모두를 staging area 올리겠다.)

`$ git commit -m '커밋명' (커밋하기) 

`$ git push origin master (푸쉬하기)




##2024-06-26숙제

1. Mtv 패턴 뭔지 알아보기.(100자)

2. 관계형데이터베이스 조금 더 이해해보기

3. 관계형 데이터베이스 종류들 그냥 한 번 보기.

4. SQL(structured query language)이 뭔지 알아보기 3줄
(50~60자이내로 정리하기)
