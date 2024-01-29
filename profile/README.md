## 설문 커스텀마이징 서비스, FormFlex

## 🛠️ Tech Stack
| Frontend | Backend | DevOps | Monitoring |  ETC |
|:--------:|:-------:|:------:|:----------:|:----:|
|<img src="https://img.shields.io/badge/vite-646CFF?style=flat-square&logo=vite&logoColor=white" /><br><img src="https://img.shields.io/badge/React-%2361DAFB?style=flat-square&logo=React&logoColor=white"/><br><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white" /><br><img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white" /><br><img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white" /><br><img src="https://img.shields.io/badge/reactquery-FF4154?style=flat-square&logo=reactquery&logoColor=white" />|<img src="https://img.shields.io/badge/express-000000?style=flat-square&logo=express&logoColor=white" /><br><img src="https://img.shields.io/badge/postgresql-4169E1?style=flat-square&logo=postgresql&logoColor=white" /><br><img src="https://img.shields.io/badge/amazonrds-527FFF?style=flat-square&logo=amazonrds&logoColor=white" />|<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/><br><img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=NGINX&logoColor=white"/><br><img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat-square&logo=Amazon EC2&logoColor=white"/>|<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=Grafana&logoColor=white"/><br><img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=Prometheus&logoColor=white"/><br><img src="https://img.shields.io/badge/googleanalytics-E6522C?style=flat-square&logo=googleanalytics&logoColor=white"/>|<img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"/><br><img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/><br><img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/><br><img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=Swagger&logoColor=white"/><br><img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat-square&logo=GitHub Actions&logoColor=white"/>|


## 💾 ERD
![formflex_erd_수정](https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/227944cc-ad8d-4df8-a8ee-b119559a8a15)

## ✨ API
<details>
<summary>Swagger</summary>
  <img width="1153" alt="스크린샷 2024-01-30 오전 1 03 28" src="https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/0dbb0f12-45a8-4378-a44a-887570b2152e">
  <img width="1153" alt="스크린샷 2024-01-30 오전 1 03 48" src="https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/8ca56814-cb9f-4179-a93f-6fe51f6961c9">
  <img width="1153" alt="스크린샷 2024-01-30 오전 1 04 00" src="https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/d54fcdc6-83a6-4772-be68-87d4328ceb9b">
</details>

## 🔑 Installation
### 1. Clone Repository
```
git clone https://github.com/SV-Winter-BootCamp-Team-C/project.git
```

### 2. .env setting
> frontend
```bash
VITE_APP_REGION=
VITE_APP_ACCESS_KEY_ID=
VITE_APP_SECRET_ACCESS_KEY_ID=
VITE_APP_BUCKET_NAME=
VITE_APP_GOOGLE_ANALYTICS=
```
> backend
```bash
DB_HOST=
DB_USERNAME=
DB_PASSWORD= 
DB_DATABASE= 
DB_PORT= 
NODE_DOCKER_PORT= 
GMAIL_OAUTH_USER= 
GMAIL_OAUTH_CLIENT_ID= 
GMAIL_OAUTH_CLIENT_SECRET= 
GMAIL_OAUTH_REFRESH_TOKEN= 
AWS_S3_SECRET_KEY=
AWS_S3_ACCESS_KEY=
AWS_S3_REGION=
AWS_BUCKET=
PEXELS_API_KEY= 
OPEN_AI_KEY=
RABBITMQ_USER=
RABBITMQ_PASSWORD=
```
### 3. Docker 명령어 실행
```
docker-compose -f docker-compose.prod.yml up --build
```
