# `Cake it`

<div>
 <img src="https://user-images.githubusercontent.com/45676906/115995286-a9e7d900-a615-11eb-9895-fe046cf5c906.png" width="200" height="200">
</div>

### `따뜻한 사람이 되고 싶지만 어려울 때, 당신이 찾던 레터링케이크 주문 서비스`


- 프로젝트 기간 : 2021.02 ~ ing
- [API Specification](https://github.com/project-cake-it/api-doc/wiki)

<br>

## `사용된 도구`

- [Java]() - Java 15
- [Spring Boot]() - Spring Boot 웹 프레임워크
- [Maven]() - 의존성 관리 프로그램
- [Tomcat]() - 웹 애플리케이션 서버
- [MyBatis]() - SQL Mapper
- [MySQL]() - DataBase
- [AWS EC2]() - 클라우드 환경 컴퓨팅 시스템
- [AWS RDS]() - 클라우드 환경 데이터베이스 관리 시스템
- [AWS S3]() - 클라우드 환경 객체 스토리지
- [JWT]() - 토큰 기반 인증, 인가
- [Git]() - 버전 관리 시스템
- [Tool]() - Github, Notion, Slack

<br>

## `케이크 잇 팀원 구성`

- 기획 1명
- 디자인 2명
- 안드로이드 3명
- iOS 3명
- Server 3명

<br>

## `상세 업무 및 성과`

1. DataBase 모델링

기획, 디자인에서 만든 와이어프레임 및 View를 보고 MySQL 기반의 테이블 설계를 혼자 진행하였습니다. 테이블 사이의 관계를 정의하고 정규화 과정을 거쳐서 데이터의 중복을 줄이려고 노력하였습니다. 기획 단계에서 세부적으로 나누어지는 것들이 많아 테이블도 많이 나오고 테이블 관계를 설계하는 것이 다른 것에 비해 쉽지는 않았지만 DB 설계를 하는 좋은 경험을 할 수 있었습니다. 

2. 소셜로그인 개발(카카오, 네이버, 구글, 애플)

소셜 로그인 4개를 개발하는 역할을 맡았습니다.  1~2개가 아니라 4개의 소셜 로그인을 개발하는 것이었기 때문에 단순하게 코드를 작성하면 유연하지 못한 코드를 작성하게 된다고 판단했습니다. 
변화에 유연하게 대처할 수 있도록 디자인 패턴인 전략패턴, 팩토리 메소드 패턴을 사용하여 설계를 하였습니다. 이렇게 설계를 했을 때 다른 소셜 로그인이 추가되어도 Service 계층의 수정이 없이 인터페이스를 구현하는 구현체만 만들어주면 되도록 하여 유연하게 구성할 수 있었습니다.

3. Spring Logback Slack Appender로 Slack 로그 출력

클라이언트가 서버와 통신할 때 무언가 잘 되지 않았을 때, 서버의 잘못인지 클라이언트의 잘못인지 판단하기 애매한 상황이 있었습니다. 또한 구체적으로 어떤 에러인지 한번에 파악하기가 쉽지 않다는 문제점이 있었습니다. 이러한 문제를 해결하여 업무 효율을 높이기 위해서 Logback Slack Appender를 통해서 Slack 채널에 로그를 찍는 것을 구현하였습니다. 

<br> <br>

## `ERD`

![11](https://user-images.githubusercontent.com/45676906/115995116-f41c8a80-a614-11eb-924a-7e794b4f5d13.png)



<br> <br>

## `서버 아키텍쳐`

![스크린샷 2021-04-25 오후 10 10 49](https://user-images.githubusercontent.com/45676906/115994716-190ffe00-a613-11eb-84b0-adea2bbce66c.png)



<br>

## `기여자`

- ### [배다슬](https://github.com/bghgu)
- ### [이상윤](https://github.com/syndersonLEE)
- ### [최정균](https://github.com/wjdrbs96)