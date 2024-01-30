## 설문 커스텀마이징 서비스, FormFlex

```
→ 다양한 질문 유형 제공 : 객관식, 주관식, 체크박스, 드롭 다운 등 다양한 질문 유형 제공
→ 맞춤형 디자인 생성 : 설문의 스타일, 테마, 글꼴 등을 사용자가 원하는 대로 선택하여 사용 가능
→ 설문 데이터 제공 : 공개된 설문의 경우, 설문의 결과를 파이 차트를 통해 확인 가능하고 엑셀 파일로도 다운 가능 
```

## 🔗 System Architecture
<img width="785" alt="스크린샷 2024-01-30 오전 3 56 22" src="https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/d96629c9-ee04-47b2-b129-1b8083f15fa0">


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


## 📊 Monitoring
> Prometheus & Grafana

![8D9CC5F1-4DF5-4891-A58F-6D063FA97B6E](https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/d99ba487-4852-4e63-8bb8-a1bf06e7fdad)

> cAdvisor

![0E43D22A-682C-486F-813A-D1345FAC7EAA](https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/93b8180e-b937-4380-935f-78c986ce5827)

> ELK

![5820F0C2-BBF7-4A74-BDC1-5152C814E45A](https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/109b3ff3-506f-4a00-ae64-0c5ebf2de579)

> Google Analytics
<img width="1536" alt="스크린샷 2024-01-30 오전 1 29 44" src="https://github.com/SV-Winter-BootCamp-Team-C/.github/assets/101851472/cdac410c-4bf1-4af1-9853-c9271795ecaf">


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


## 👥 Member
<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>Name</th>
        <td width="100" align="center">곽소정</td>
        <td width="100" align="center">김민성</td>
        <td width="100" align="center">강성용</td>
        <td width="100" align="center">이진복</td>
        <td width="100" align="center">장희선</td>
    </tr>
    <tr>
        <th>Profile</th>
        <td width="100" align="center">
            <a href="https://github.com/ssojungg">
                <img src="https://avatars.githubusercontent.com/u/126966126?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/mskim98">
                <img src="https://avatars.githubusercontent.com/u/74662759?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/KangSeongYong">
                <img src="https://avatars.githubusercontent.com/u/97003669?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/jjinbok">
                <img src="https://avatars.githubusercontent.com/u/126658197?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Jade9846">
                <img src="https://avatars.githubusercontent.com/u/101115635?v=4" width="60" height="60">
            </a>
        </td>
    </tr>
    <tr>
        <th>Role</th>
        <td width="150" align="center">
            Leader<br>
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/ssojungg">
                <img src="http://img.shields.io/badge/ssojungg-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/mskim98">
                <img src="http://img.shields.io/badge/mskim98-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/KangSeongYong">
                <img src="http://img.shields.io/badge/KangSeongYong-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/jjinbok">
                <img src="http://img.shields.io/badge/jjinbok-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Jade9846">
                <img src="http://img.shields.io/badge/Jade9846-green?style=social&logo=github"/>
            </a>
        </td>
    </tr>
    </tbody>
</table>

<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>Name</th>
        <td width="100" align="center">조은주</td>
        <td width="100" align="center">김성욱</td>
        <td width="100" align="center">백지윤</td>
    </tr>
    <tr>
        <th>Profile</th>
        <td width="100" align="center">
            <a href="https://github.com/dmswn1004">
                <img src="https://avatars.githubusercontent.com/u/101851472?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/castlewook99">
                <img src="https://avatars.githubusercontent.com/u/154862467?v=4" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/baekjiyun">
                <img src="https://avatars.githubusercontent.com/u/71875528?v=4" width="60" height="60">
            </a>
        </td>
    </tr>
    <tr>
        <th>Role</th>
        <td width="150" align="center">
          Frontend<br>
          Design
        </td>
        <td width="150" align="center">
          Frontend<br>
          Design
        </td>
        <td width="150" align="center">
          Frontend<br>
          Design
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/dmswn1004">
                <img src="http://img.shields.io/badge/dmswn1004-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/castlewook99">
                <img src="http://img.shields.io/badge/castlewook99-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/baekjiyun">
                <img src="http://img.shields.io/badge/baekjiyun-green?style=social&logo=github"/>
            </a>
        </td>
    </tr>
    </tbody>
</table>

<div align="right">
    <b><a href="#설문-커스텀마이징-서비스-formflex">⬆️ Back to Top</a></b>
</div>
