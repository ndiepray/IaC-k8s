Nginx 웹 서버 echo-ip
---
Nginx 웹 서버에서 사용자 요청에 응답하며 사용자의 IP를 응답하는 기능을 제공
- Dockerfile : echo-ip 도커 이미지를 빌드하는 데 사용하는 파일
- Jenkinsfile : Pipeline 실습을 위해 작성된 파일
- cert.crt : echo-ip의 Nginx에서 HTTPS 접속 시 사용하는 인증서 파일
- cert.key : echo-ip의 Nginx에서 HTTPS 접속 시 사용하는 비밀 키 파일
- nginx.conf : echo-ip의 응답을 설정하기 위한 Nginx 설정 파일
