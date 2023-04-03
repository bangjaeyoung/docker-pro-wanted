1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
- 애플리케이션이 컴퓨팅 환경 간 신속하고 신뢰성 있게 실행될 수 있도록 코드와 종속성이 있는 것들을 패키징하는 SW의 표준 단위이다.

2. 도커란 무엇입니까? (100자 이내로 요약)
- 위와 같이 리눅스의 컨테이너라 기술을 통해 프로세스를 격리하여 실행하고 관할 수 있게 해주는 오픈소스 프로젝트이다.
- 어플리케이션 실행에 필요한 모든 것을 포함하여 가볍고 Standalone 으로 실행 가능하게 해준다.

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
- 도커 파일 : 도커에서 이미지를 생성하기 위해 작성하는 파일, 만들 이미지에 대한 정보를 기술해 둔 템플릿
- 도커 이미지 : 어플리케이션에 필요한 소스코드, 라이브러리, 종속성, 도구 및 응용프로그램을 포함한 파일
- 도커 컨테이너 : 도커 이미지를 실행한 상태

4. [실전 미션] 도커 설치하기 (참조: [도커 공식 설치 페이지](https://docs.docker.com/engine/install/))
- 아래 `도커 설치부터 실행 튜토리얼`을 참조하여 도커를 설치하고, 도커 컨테이너를 실행한 화면을 캡쳐해서 Pull Request에 올리세요.