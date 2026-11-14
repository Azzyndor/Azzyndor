<p align="center">
  <img src="assets/header.svg" alt="Azzy — Backend Engineer · Server Infrastructure" width="100%"/>
</p>

<p align="center">
  <a href="mailto:azam.dj2015@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FF8A3D" alt="Email"/></a>
  <a href="https://goldenpixel.uz/"><img src="https://img.shields.io/badge/Golden%20Pixel-0D1117?style=for-the-badge&logo=googlechrome&logoColor=FF8A3D" alt="Golden Pixel"/></a>
  <img src="https://img.shields.io/badge/Uzbekistan-0D1117?style=for-the-badge&logo=googlemaps&logoColor=FF8A3D" alt="Location"/>
  <img src="https://komarev.com/ghpvc/?username=Azzyndor&style=for-the-badge&color=0D1117&label=Profile+views" alt="Profile views"/>
</p>

### About

I build backend systems for real businesses and run the servers they live on.
My APIs are written in **Go** on **PostgreSQL** and deployed with **Docker** behind **nginx** on Linux servers that I administer.
I've built online payments with **Payme**, order processing and Telegram integrations, and I write client apps in **Flutter / Dart**.
I use AI tools to speed up research, reviews and routine work, and I check everything they produce.

---

### Projects in production

#### <img src="https://img.shields.io/badge/-%E2%97%8F-FF8A3D?style=flat-square" height="14"/> [Caramel Cake](https://caramel-cake.uz/) &nbsp;<sub>Ordering platform for a bakery and cafe · solo, full-stack + DevOps</sub>

- **Backend in Go:** REST API with a layered architecture (handlers → services → repositories), PostgreSQL through `pgx` with SQL migrations, and unit tests for the core modules.
- **Payments:** Payme merchant API, with transaction states, callbacks and a payment workflow attached to each order.
- **Orders and delivery:** cart, checkout and order history. Couriers' locations are tracked live, and addresses are geocoded with the Google Geocoding API.
- **Auth and security:** JWT access and refresh tokens, email password reset over SMTP, captcha, input sanitising and security middleware.
- **Operations:** admin and manager panels, promotions and campaigns, Telegram notifications for staff.
- **Client and infrastructure:** Flutter app for web and mobile; Docker Compose stack behind nginx on a Linux server.

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
  <img src="https://img.shields.io/badge/Payme-33CCCC?style=flat-square" alt="Payme"/>
  <img src="https://img.shields.io/badge/Google%20Maps%20API-4285F4?style=flat-square&logo=googlemaps&logoColor=white" alt="Google Maps API"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="nginx"/>
  &nbsp;<a href="https://caramel-cake.uz/"><img src="https://img.shields.io/badge/Live-caramel--cake.uz-FF8A3D?style=flat-square&labelColor=0D1117" alt="Live"/></a>
</p>

#### <img src="https://img.shields.io/badge/-%E2%97%8F-FF8A3D?style=flat-square" height="14"/> [Jasmin House](https://jasmin-house.uz/) &nbsp;<sub>Website and ordering system for a cafe in Urgench · with Golden Pixel</sub>

- **Backend in Go:** API for the menu (40+ items), cart, orders, users and promotions, stored in PostgreSQL.
- **Online payments:** Payme merchant integration, with tests for the merchant handler.
- **Staff panel:** order approval, order history, products and menu settings, role management, and a promotions admin page.
- **Telegram bot:** notifies managers about new orders and helps them handle orders from Telegram.
- **Frontend:** fast multi-page site in Russian, Uzbek and English, with delivery-address geolocation and online ordering.
- **CI/CD:** each push to `main` deploys to the server over SSH through GitHub Actions. The stack runs in Docker Compose behind nginx.

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Payme-33CCCC?style=flat-square" alt="Payme"/>
  <img src="https://img.shields.io/badge/Telegram%20Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Bot"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="nginx"/>
  <img src="https://img.shields.io/badge/i18n-RU%20%C2%B7%20UZ%20%C2%B7%20EN-555?style=flat-square" alt="RU, UZ, EN"/>
  &nbsp;<a href="https://jasmin-house.uz/"><img src="https://img.shields.io/badge/Live-jasmin--house.uz-FF8A3D?style=flat-square&labelColor=0D1117" alt="Live"/></a>
</p>

#### <img src="https://img.shields.io/badge/-%E2%97%8F-FF8A3D?style=flat-square" height="14"/> [Golden Pixel](https://goldenpixel.uz/) &nbsp;<sub>Web studio · co-developer</sub>

- Studio that designs, builds and launches web products for local businesses.
- On the studio's own site I worked on the visual design, fixed bugs and improved performance.

<p>
  <img src="https://img.shields.io/badge/UI%20%2F%20Visual-0D1117?style=flat-square" alt="UI and visual design"/>
  <img src="https://img.shields.io/badge/Bug%20fixing-0D1117?style=flat-square" alt="Bug fixing"/>
  <img src="https://img.shields.io/badge/Optimization-0D1117?style=flat-square" alt="Optimization"/>
  &nbsp;<a href="https://goldenpixel.uz/"><img src="https://img.shields.io/badge/Live-goldenpixel.uz-FF8A3D?style=flat-square&labelColor=0D1117" alt="Live"/></a>
</p>

---

### Tech stack

<table>
  <tr>
    <td width="160"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=go,dart,flutter,bash,js&theme=dark" alt="Go, Dart, Flutter, Bash, JavaScript"/></td>
  </tr>
  <tr>
    <td><b>Servers & infra</b></td>
    <td><img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,docker,nginx,postgres,cloudflare,git,githubactions&theme=dark" alt="Linux, Ubuntu, Debian, Docker, nginx, PostgreSQL, Cloudflare, Git, GitHub Actions"/></td>
  </tr>
  <tr>
    <td><b>AI tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude"/>
      <img src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" alt="GitHub Copilot"/>
    </td>
  </tr>
</table>

| Area | What I do |
|---|---|
| **Linux administration** | Setting up and hardening servers, SSH, users and permissions, systemd services |
| **Web serving** | nginx reverse proxy, TLS certificates, domains and DNS |
| **Containers & CI/CD** | Dockerfiles, Docker Compose stacks, GitHub Actions deploys over SSH |
| **Databases** | PostgreSQL schemas, migrations, backups |
| **Backend** | REST APIs in Go, JWT auth with refresh tokens, payment provider integrations |
| **AI-assisted work** | Code review, debugging, docs and config drafts, always reviewed and tested before production |

---

### 2026 activity

<p align="center">
  <img src="assets/activity-2026.svg" alt="2026 GitHub activity: contributions, commits, heatmap, monthly totals and languages" width="100%"/>
</p>

