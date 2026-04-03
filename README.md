<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:364f6b&height=200&section=header&text=Khabib%20Toshev&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%7C%20Python%20%7C%20Django&descAlignY=58&descAlign=50" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Khabib%20Toshev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khabib-toshev)
[![LeetCode](https://img.shields.io/badge/LeetCode-thekhabib-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/thekhabib)
[![Gmail](https://img.shields.io/badge/Gmail-contact%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khabibtoshev@gmail.com)
[![Profile views](https://komarev.com/ghpvc/?username=thekhabib&style=for-the-badge&color=364f6b)](https://github.com/thekhabib)

</div>

---

## 🧑‍💻 About Me

```python
developer = {
    "name":       "Khabib Toshev",
    "location":   "Tashkent, Uzbekistan 🇺🇿",
    "focus":      ["Backend Development", "REST API Design", "Clean Architecture"],
    "stack":      ["Python", "Django", "FastAPI", "PostgreSQL", "Redis", "Docker"],
    "currently":  "Building production-grade Django services with CI/CD pipelines",
    "daily":      "LeetCode grinder 🧠 — solving DSA problems in Python",
    "goal":       "Write code that is easy to read, test, and maintain",
    "open_to":    "Backend roles, freelance projects, open source collaboration",
}
```

---

## 🚀 Tech Stack

<div align="center">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django%20REST-ff1709?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Other
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Telegram Bot](https://img.shields.io/badge/Telegram%20Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

</div>

---

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📚 Sifat Library
**Multi-tenant library management platform**

A production-ready system managing multiple libraries with isolated data per tenant. Members link their Telegram accounts via bot and receive real-time notifications.

**Key features:**
- 🏛️ Multi-tenant: separate domain, members & settings per library
- 📱 Telegram bot integration for member linking & notifications
- ⏰ Celery Beat for automated overdue tracking
- 📊 Daily/monthly statistics dashboard
- 🌍 4-language support (uz, cy, ru, en)
- 🔐 JWT auth + SMS OTP via Eskiz.uz
- 🚀 GitLab CI/CD pipeline with Docker

**Stack:** `Django 5` `PostgreSQL` `Redis` `Celery` `Docker` `GitLab CI/CD`

![Private](https://img.shields.io/badge/Repo-Private-red?style=flat-square&logo=github)

</td>
<td width="50%" valign="top">

### 🏭 Navoiy Sanoat
**Industrial zone management REST API**

A government-level platform for managing industrial zones, entrepreneurs, and projects in Navoiy region. Built with performance and multilingual support at its core.

**Key features:**
- 🏗️ Hierarchical data: Zone → Entrepreneur → Project
- ⚡ Redis cache with smart signal-based invalidation
- 🖼️ Generic FK image system (one model, any object)
- 🌍 4-language i18n (uz, en, ru, cy)
- 🛡️ Rate throttling for public endpoints
- 🎨 Custom Jazzmin admin panel
- 📄 Swagger API documentation

**Stack:** `Django 5` `PostgreSQL` `Redis` `Docker` `CKEditor5`

![Private](https://img.shields.io/badge/Repo-Private-red?style=flat-square&logo=github)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖼️ Image AI Bot
**Telegram bot powered by AI image processing**

A feature-rich Telegram bot with 15+ image manipulation tools, combining classic image processing with cutting-edge AI models.

**Key features:**
- 🧠 GPT-4o for text extraction, sales copy & image captioning
- 🎨 AI style transfer (Ghibli, Anime, Watercolor, 3D Clay)
- 🧹 Background removal with `rembg`
- 🏪 Marketplace product card generation via KIE AI
- 🎤 Voice-to-text (Faster Whisper) for prompt input
- 📱 QR code generator with custom image overlays
- 🎞️ Slideshow video generation from images

**Stack:** `Aiogram 3` `OpenAI GPT-4o` `rembg` `MoviePy` `Docker`

![Private](https://img.shields.io/badge/Repo-Private-red?style=flat-square&logo=github)

</td>
<td width="50%" valign="top">

### 🏪 Gulistan Bazaar
**Market rental contract management system**

A backend system for managing shop/stall rentals in a market. Handles contracts, auto-generates payment schedules, and tracks overdue payments via Celery.

**Key features:**
- 📋 Daily & monthly rental contracts
- 📅 Auto-generated payment schedules via Django signals
- 💳 Payment tracking with cascade updates
- ⚠️ Celery Beat for overdue detection
- 🏬 Unit status (Empty / Pending / Paid / Overdue)
- 📖 Full Swagger documentation

**Stack:** `Django 5` `PostgreSQL` `Celery` `Docker`

![Private](https://img.shields.io/badge/Repo-Private-red?style=flat-square&logo=github)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=thekhabib&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" width="48%" />
  <img src="https://streak-stats.demolab.com?user=thekhabib&theme=tokyonight&hide_border=true" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thekhabib&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="40%" />
</div>

---

## 🧠 LeetCode Progress

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/thekhabib?theme=dark&font=Fira%20Code&ext=heatmap)](https://leetcode.com/u/thekhabib)

</div>

---

<div align="center">

*"First, solve the problem. Then, write the code."*

⭐ If you find my work interesting, feel free to follow or connect!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:364f6b,100:1a1b27&height=100&section=footer" width="100%"/>

</div>
