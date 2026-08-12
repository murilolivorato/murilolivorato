# Murilo Livorato

I build backend systems — Laravel and Python — where search, queues, and billing have to keep working under load.

Ten years on APIs in production. Most recently I architected a real-estate platform in Laravel: segmented-domain REST API with multi-guard OAuth, asynchronous Elasticsearch bulk indexing over the catalog, Redis/Horizon matching decoupled from the request cycle, and recurring Pagar.me subscriptions with automatic reconciliation. Alongside it, Python services on Flask for the AI side — Cloud Vision image moderation and Cloud Natural Language text scoring. All of it containerized and running on GCP: Cloud Run, GKE, Cloud Storage, with CI/CD and Terraform.

## Projects

| Repo | What it gives you |
|---|---|
| [laravel_docker_enviroment](https://github.com/murilolivorato/laravel_docker_enviroment) ★18 | A Laravel dev stack that boots on `docker compose up` — PHP 8.2, Nginx, MySQL 8, Mailhog — so a new dev is productive on day one instead of day three. |
| [laravel_sso](https://github.com/murilolivorato/laravel_sso) ★15 | Single sign-on across several Laravel apps via Passport, for teams who split one product into multiple codebases and don't want three login screens. |
| [vue-laravel-crud](https://github.com/murilolivorato/vue-laravel-crud) ★11 | The Laravel API + Vue SPA wiring most projects rewrite from scratch — auth, validation, and CRUD already connected. |
| [gcp-vision-moderation-api-flask-docker](https://github.com/murilolivorato/gcp-vision-moderation-api-flask-docker) | A Flask API that scores uploads against your own moderation taxonomy via Cloud Vision and answers approve / review / block — for platforms taking user images without a human in the loop. |
| [text-moderation-api-python](https://github.com/murilolivorato/text-moderation-api-python) | Flask service wrapping Cloud Natural Language for sentiment, syntax, and safety scoring — the text half of the same moderation problem. |
| [k8s-react-python-ci-cd-deploy](https://github.com/murilolivorato/k8s-react-python-ci-cd-deploy) | React + Python on Kubernetes with a working GitHub Actions pipeline — the deployment glue most tutorials leave as an exercise. |
| [larave_error_logging_with_elasticsearch](https://github.com/murilolivorato/larave_error_logging_with_elasticsearch) ★2 | Ships every Laravel exception into Elasticsearch, so debugging production is a search query instead of grepping log files. |
| [real-time-notifications-laravel-reverb-vue](https://github.com/murilolivorato/real-time-notifications-laravel-reverb-vue) ★2 | Self-hosted WebSocket broadcasting with Laravel Reverb — real-time notifications without a SaaS bill or a polling loop. |

## Working with

**Backend**

![PHP](https://img.shields.io/badge/PHP_8-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Data & Search**

![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=flat-square&logo=quasar&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Testing**

![Pest](https://img.shields.io/badge/Pest-F7B93E?style=flat-square&logo=pestphp&logoColor=black)
![PHPUnit](https://img.shields.io/badge/PHPUnit-366488?style=flat-square&logo=php&logoColor=white)

## Writing

I publish walkthroughs at [medium.com/@murilolivorato](https://medium.com/@murilolivorato) — most repos here are the runnable code behind an article.

## Contact

Open to remote backend work, PHP or Python — [LinkedIn](https://www.linkedin.com/in/murilo-livorato-80985a4a/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/murilo-livorato-80985a4a/)
[![Medium](https://img.shields.io/badge/Medium-black?style=for-the-badge&logo=medium)](https://medium.com/@murilolivorato)
