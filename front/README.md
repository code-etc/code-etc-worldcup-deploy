- docker 이미지로 배포하였다
- 현재 이미지: `daehwan2/worldcup:0.10`


`docker run -d --name worldcup-front -p 3000:3000 --rm --pull always daehwan2/worldcup:0.10`

실행 후

http://localhost:3000/ 로 접속
