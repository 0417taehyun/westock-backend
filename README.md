# Stock X

> 중고 신발 경매 사이트 [ Hince ] clone project

## Table of contents

- [General info](#general-info)
- [Modeling](#modeling)
- [Technologies](#technologies)
- [Features](#features)

## General info

- 개발기간 : 2020. 08. 31 - 2020. 09. 11
- 팀원 : Front-end(김동호, 류상욱, 송다슬, 이영섭) Back-end(왕민욱, 이충희, 이태현)

## Modeling

- 사이트 : https://aquerytool.com:443/aquerymain/index/?rurl=ee256e1a-149a-4b2e-850b-0b961e7ad838&
- 비밀번호 : 786v0a

## Technologies

### Tools

- Git(Control Commit history by Squash and Rebase)
- [Agile](https://www.notion.so/0417taehyun/Portfolio-3368151da4144e178d48c652a13e5b2b#2e5331841c4e4f2fabab45d8bfb83939)
- AWS

### Back-End

- Python
- Unittest
- Django Web Framework
- CORS headers
- Beautiful Soup
- Selenium
- MySQL
- Bcrypt, JWT
- OAuth (Kakao Social Login)
- RESTful API
- Docker
- AWS (EC2, RDS)

## Features

### 담당 역할

#### 이태현

- **정규 표현식**을 활용한 이메일 및 비밀번호 **유효성 검사** 기능 구현
- 필드 옵션( **`unique`** )과 ORM( **`filter.exists`** ) 등 **디버깅**을 통한 비교로 효율적인 API 기능 구현
- **Bcrypt**를 활용한 비밀번호 **암호화** 기능 구현
- **JWT**를 활용한 **로그인 토큰** 발행 기능 구현
- 특정 페이지 접근 제한을 위한 **Access Token**을 통한 **Login Decorator** 기능 구현
- **OAuth**를 활용한 **소셜 로그인** 기능 구현
- **Unittest**를 활용한 **TDD** 지향 개발
- **Docker**를 활용한 **컨테이너 가상화** 및 배포