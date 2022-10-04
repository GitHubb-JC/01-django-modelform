# Django CRUD 

## 1. 가상환경 및 Django 설치

### 1. 가상환경 생성 및 실행

* 가상환경 폴더를 `.gitignore`로 설정을 해둔다.

```bash
$ python -m venv venv
$ source venv/Scripts/activate
(venv) $
```

### 2. Django 설치 및 기록

```
$ pip install django==3.2.13
$ pip freeze > requirements.txt
```

### 3. Django 프로젝트 생성

```bash
$ django-admin startproject pjt .
```

## 2. articles app 

### 1. app 생성

### 2. app 등록

### 3. urls.py 설정 

## 3. Model 정의 (DB 설계)

### 1. 클래스 정의

### 2. 마이그레이션 파일 생성

### 3. DB 반영(`migrate`)