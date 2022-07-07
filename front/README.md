- docker 이미지로 배포하였다
- 현재 이미지: `tion6514/front:0.1`

`docker run -d --name worldcup-front -p 3000:3000 --rm --pull always tion6514/front:0.1`

실행 후

http://localhost:3000/ 로 접속
