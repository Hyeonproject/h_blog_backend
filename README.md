<h1>Rest API Blog backend</h1>
사랑하는 사람의 과제를 도와주기 위해서 만들어봤습니다.<br>
잡다한거 말고 기술적인거만 받고 피드백 받고 훈수는 안 받습니다.<br>
읽어주신 여러분 감사합니다.

주 목적은 블로그를 만들기 위해서 React와 통신하는 Rest API를 만드는 것이 목표입니다.

<h2>기술스택</h2>
Python + Django + Django Rest Framework를 통해서 Rest API를 만들었습니다.<br>
DBMS로는 MongoDB를 사용했습니다. model mapping은 Djongo 라이브러리를 사용했습니다.<br>
<br>
Django Rest Framework에서 Json Web Token 방식으로 인증을 만들었습니다.<br>
이 부분에서 Django Rest Frmaework Simple JWT 라는 라이브러리를 활용하였습니다.<br>
<br>
나머지 자세한 부분은 requirements.txt를 참고하여주시길 바랍니다.

<h2>실제 운영 환경</h2>
실제로 지금 프로젝트를 위해서 운영을 하고 있습니다.
Ubuntu 18.04LTS 네이버클라우드 서버 컴퓨터에서 작업했습니다.<br>
Nginx를 통해서 HTTP 프로토콜을 구현하였습니다.<br>
비동기 시스템이 적합하지 않다고 생각해서 WSGI를 gunicorn을 사용했습니다.<br>
가상화는 miniconda를 활용했습니다.<br>
- ubuntu + nginx + gunicorn + django

<h2>현재 달성</h2>
- 기본 설계 구현대로 Rest API 구현 완료<br>
- Rest API JWT 인증 완료 <br>
- 서버 구동 환경에서 테스트 및 기본적인 보안 완료<br>

<h2>해야할 것</h2>
- Django Rest Framework 테스트 코드 (가능하면)<br>
- 가능하면 https로 구현하기<br>