# :heart_eyes_cat: `Welcome to Ounce Server` :heart_eyes_cat:

<div>
 <img src="https://user-images.githubusercontent.com/45676906/87784220-d8f44180-c870-11ea-9821-9ea4a09e8b26.jpg" width="200" height="200">
 <img src="https://user-images.githubusercontent.com/55784772/87793259-f977c800-c87f-11ea-816e-bc99f55c040d.png" width="200" height="200">
 <img src="https://user-images.githubusercontent.com/45676906/87784325-02ad6880-c871-11ea-9008-5e7f6cc57a04.jpg" width="200" height="200">
 
</div>
<br>

### `기록부터 선택까지, 온스가 함께합니다.`

고양이들은 입맛이 까다로워, 집사들은 성공확률이 높은 시도를 위해 먹여본 캣푸드를 따로 기록하고 있습니다. 

저희는 이러한 집사들의 고민을 해결하기 위해 직관적인 기록, 서로의 목록 공유, 입맛이 비슷한 고양이 추천 기능을 제공하고 있습니다.


:smiley_cat: <b>SOPT 26th APPJAM</b>

:smiley_cat: <b>Project Period : 2020.06.27 ~ 2020.07.18</b>

:smiley_cat: <b>[API Specification](https://github.com/We-are-Ounce/OUNCE_Server/wiki)</b>

<br>

## `사용된 도구`

- [JavaScript]() - 객체 기반의 스크립트 프로그래밍 언어
- [Node.js]() - Chrome V8 자바스크립트 엔진으로 빌드된 자바스크립트 런타임
- [Express.js]() - Node.js 웹 애플리케이션 프레임워크
- [NPM]() - 자바 스크립트 패키지 관리자
- [PM2]() - Express 앱용 프로세스 관리자
- [VSCode]() - 편집기
- [MySQL]() - DataBase
- [JWT]() - 토큰기반 인증
- [AWS EC2]() - 클라우드 환경 컴퓨팅 시스템
- [AWS RDS]() - 클라우드 환경 데이터베이스 관리 시스템
- [AWS S3]() - 클라우드 환경 데이터 저장소

<br>

## `온스 팀원 구성`

- 기획 3명
- 디자인 3명
- 안드로이드 3명
- iOS 4명
- Server 3명

<br>

### :open_file_folder: `기능 명세서 및 역할 분담`

![기능 명세](https://user-images.githubusercontent.com/55784772/87781603-eeb33800-c86b-11ea-9570-c3549c04fe34.PNG)

<br>

프로젝트 기간: 2020-06 ~ 2020-07

프로젝트에서 맡았던 역할은 크게 데이터베이스 설계, API 개발, AWS 인프라 설계입니다. 

1. 데이터베이스 설계

뷰 와이어프레임을 보면서 MySQL 기반의 DB 모델링을 하였습니다. 테이블 간의 관계는 어떻게 되며, 데이터의 중복은 최대한 어떻게 막고 최적화 하며 설계할 수 있을까에 대해서 서버 팀원들과 함께 논의하며 설계하였습니다. 


2. API 개발

CRUD 기반의 API 개발을 하였습니다. API 개발을 하면서 계층 별로 역할을 나눠서 개발하려고 하였고, 비즈니스 로직 작성 및 쿼리 작성을 통해 개발을 진행하였습니다. 

3. AWS 인프라 설계

AWS EC2 인스턴스를 만들고 보안그룹 세팅을 하여 서버 호스팅을 하였습니다. 그리고 AWS RDS 서비스를 활용하여 MySQL 데이터베이스 서버 환경을 구축하였고, 사진 업로드 파일을 저장하기 위해 AWS S3 환경을 구축하였습니다. 그리고 EC2 서버에 필요한 환경 세팅 및 모듈 설치를 하였고 프로젝트 코드를 서버에 올려서 실제 서버 내에서 코드가 동작하도록 하였습니다. 


- 프로젝트 느낀점

프로젝트를 하기 전에는 앱의 뷰를 보고 테이블 간의 관계가 어떻게 되고, 어떻게 정규화를 시켜야 효율적인 DB 설계를 할 수 있을까에 대한 감각이 없었습니다. 하지만 프로젝트를 하면서 DB 설계의 경험을 익히고 팀원들과 고민하면서 공부를 할 수 있었습니다.  그래서 프로젝트가 끝날 때는 뷰를 보고 데이터베이스 설계가 머리속에 어느정도 그려질 수 있도록 성장할 수 있었습니다. 

2. API 개발

하나의 앱을 개발하면서 진행하는 첫 프로젝트였기 때문에 DB 설계, 인프라 설계, API 개발, 협업 모든 것이 낯설었습니다. 예를 들어, 프로젝트를 진행하기 전에는 아주 단순한 쿼리를 작성해보았지만, 프로젝트에 개발하면서는 여러 테이블을 조인하고 서브 쿼리를 작성하면서 개발하면서 쿼리 작성 능력도 늘 수 있었습니다. 또한 GET, POST 방식은 언제 써야 하는지도 잘 몰랐지만, 프로젝트가 끝났을 때는 HTTP에 대한 개념도 조금이나마 이해할 수 있었습니다. 

온스는 2주간의 합숙을 하면서 진행했던 프로젝트 였습니다. 2주 동안 프로젝트에 온전히 집중하였고 프로젝트가 끝났을 때는 데이터베이스 설계, 쿼리 작성, API CRUD 개발 등에 대해서 자신감이 생겼습니다. 서버 개발에 조금 더 흥미를 가지며 실력도 향상할 수 있고 다양한 파트와 협업도 경험할 수 있었던 정말 값진 경험이었습니다. 

<br>

## `ERD(Entity Relationship Diagram)`

![ERD](https://user-images.githubusercontent.com/55784772/87702220-18208500-c7d4-11ea-8e54-f83f972f1d83.PNG)

<br>

## `🌐 SERVER ARCHITECTURE`


![스크린샷 2021-04-22 오전 12 54 02](https://user-images.githubusercontent.com/45676906/115583862-3e47f800-a305-11eb-8dde-f32c4788c49f.png)


<br>

## `Contributor`

- ### [정효원](https://github.com/Jeong-Hyowon)
- ### [손예지](https://github.com/yezgoget)
- ### [최정균](https://github.com/wjdrbs96)


<br>

## `OUNCE 프로젝트`
- ### [SERVER](https://github.com/We-are-Ounce/OUNCE_Server)
- ### [ANDROID](https://github.com/We-are-Ounce/OUNCE_Android)
- ### [IOS](https://github.com/We-are-Ounce/OUNCE_iOS)