<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="hosternus — async Python services and the infra they run on" src="assets/header-light.svg" width="100%">
</picture>

<br>

### About

Backend developer who also owns the infrastructure. I write async Python services, then provision, deploy and monitor the servers they run on, so a feature goes from code to production without changing hands.

- **Backend** — REST APIs on FastAPI, event-driven services on FastStream and RabbitMQ, MySQL, MariaDB and Redis behind SQLAlchemy and Pydantic
- **Infrastructure** — Terraform and Ansible across Google, Yandex, VK, Cloud.ru and Timeweb clouds; Docker behind Nginx or Caddy; CI/CD on GitHub Actions
- **Observability** — Prometheus and VictoriaMetrics for metrics, Grafana for dashboards
- **Automation** — n8n workflows, plus Claude Code and Codex in the daily loop
- **Also** — studying computer science; the C++ labs are public

### Stack

<!-- stack -->
###### Backend

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-%233670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white">
  <img alt="FastStream" src="https://img.shields.io/badge/FastStream-%232C5BB4.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIuMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBkPSJNMiA4LjVxMi41LTMgNSAwdDUgMCA1IDAgNSAwTTIgMTUuNXEyLjUtMyA1IDB0NSAwIDUgMCA1IDAiLz48L3N2Zz4%3D">
  <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white">
  <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-%23D71F00.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white">
  <img alt="Gunicorn" src="https://img.shields.io/badge/Gunicorn-%23499848.svg?style=for-the-badge&logo=gunicorn&logoColor=white">
  <img alt="Jinja" src="https://img.shields.io/badge/Jinja-%237E0C1B.svg?style=for-the-badge&logo=jinja&logoColor=white">
  <img alt="JWT" src="https://img.shields.io/badge/JWT-%23000000.svg?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
  <img alt="uv" src="https://img.shields.io/badge/uv-%23DE5FE9.svg?style=for-the-badge&logo=uv&logoColor=white">
  <img alt="Ruff" src="https://img.shields.io/badge/Ruff-%23261230.svg?style=for-the-badge&logo=ruff&logoColor=D7FF64">
  <img alt="ty" src="https://img.shields.io/badge/ty-%23261230.svg?style=for-the-badge&logo=ty&logoColor=46EBE1">
  <img alt="PyPI" src="https://img.shields.io/badge/PyPI-%23ECECEC.svg?style=for-the-badge&logo=pypi&logoColor=1f73b7">
</p>

###### API

<p>
  <img alt="Swagger" src="https://img.shields.io/badge/Swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black">
  <img alt="Scalar" src="https://img.shields.io/badge/Scalar-%231A1A1A.svg?style=for-the-badge&logo=scalar&logoColor=white">
  <img alt="Insomnia" src="https://img.shields.io/badge/Insomnia-%23000000.svg?style=for-the-badge&logo=insomnia&logoColor=5849BE">
</p>

###### Data & queues

<p>
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-%23003545.svg?style=for-the-badge&logo=mariadb&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-%2307405E.svg?style=for-the-badge&logo=sqlite&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-%23FF6600.svg?style=for-the-badge&logo=rabbitmq&logoColor=white">
</p>

###### Infrastructure

<p>
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white">
  <img alt="Ansible" src="https://img.shields.io/badge/Ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-%230DB7ED.svg?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Portainer" src="https://img.shields.io/badge/Portainer-%2313BEF9.svg?style=for-the-badge&logo=portainer&logoColor=white">
  <img alt="Nginx" src="https://img.shields.io/badge/Nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white">
  <img alt="Caddy" src="https://img.shields.io/badge/Caddy-%231F88C0.svg?style=for-the-badge&logo=caddy&logoColor=white">
  <img alt="NetBird" src="https://img.shields.io/badge/NetBird-%231B1F23.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMiAzMiI%2BPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC41IDQuNSkiPjxwYXRoIGQ9Ik0yMS40NjMxIDAuNTIzNDM4QzE3LjgxNzMgMC44NTc5MTMgMTYuMDAyOCAyLjk1Njc1IDE1LjMxNzEgNC4wMTg3MUw0LjY2NDA2IDIyLjQ3MzRIMTcuNTE2M0wzMC4xOTI5IDAuNTIzNDM4SDIxLjQ2MzFaIiBmaWxsPSIjRjY4MzMwIi8%2BPHBhdGggZD0iTTE3LjUyNjUgMjIuNDczN0wwIDMuODg1MjVDMCAzLjg4NTI1IDE5LjgxNzcgLTEuNDQxMjggMjEuNzQ5MyAxNS4xNzM4TDE3LjUyNjUgMjIuNDczN1oiIGZpbGw9IiNGNjgzMzAiLz48cGF0aCBkPSJNMTQuOTIzNiA0LjcwNTYzTDkuNTQ2ODggMTQuMDIwOEwxNy41MTU4IDIyLjQ3NDdMMjEuNzM4NSAxNS4xNThDMjEuMDY5NiA5LjQ0NjgyIDE4LjI4NTEgNi4zMjc4NCAxNC45MjM2IDQuNjk3MjciIGZpbGw9IiNGMDUyNTIiLz48L2c%2BPC9zdmc%2B">
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white">
  <img alt="VictoriaMetrics" src="https://img.shields.io/badge/VictoriaMetrics-%23621773.svg?style=for-the-badge&logo=victoriametrics&logoColor=white">
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white">
</p>

###### Cloud

<p>
  <img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=for-the-badge&logo=googlecloud&logoColor=white">
  <img alt="Yandex Cloud" src="https://img.shields.io/badge/Yandex%20Cloud-%235282FF.svg?style=for-the-badge&logo=yandexcloud&logoColor=white">
  <img alt="VK Cloud" src="https://img.shields.io/badge/VK%20Cloud-%230077FF.svg?style=for-the-badge&logo=vk&logoColor=white">
  <img alt="Cloud.ru" src="https://img.shields.io/badge/Cloud.ru-%231A9F5B.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTYuNSAxOWgxMWE0LjUgNC41IDAgMCAwIC45LTguOTFBNi41IDYuNSAwIDAgMCA1LjggOS4wNiA1IDUgMCAwIDAgNi41IDE5eiIvPjwvc3ZnPg%3D%3D">
  <img alt="Timeweb Cloud" src="https://img.shields.io/badge/Timeweb%20Cloud-%232F6BFF.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTYuNSAxOWgxMWE0LjUgNC41IDAgMCAwIC45LTguOTFBNi41IDYuNSAwIDAgMCA1LjggOS4wNiA1IDUgMCAwIDAgNi41IDE5eiIvPjwvc3ZnPg%3D%3D">
</p>

###### CI & tooling

<p>
  <img alt="Git" src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white">
  <img alt="Dependabot" src="https://img.shields.io/badge/Dependabot-%23025E8C.svg?style=for-the-badge&logo=dependabot&logoColor=white">
  <img alt="Trivy" src="https://img.shields.io/badge/Trivy-%231904DA.svg?style=for-the-badge&logo=trivy&logoColor=white">
  <img alt="VS Code" src="https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIuMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBkPSJNOCA2IDIgMTJsNiA2TTE2IDZsNiA2LTYgNk0xNCA0bC00IDE2Ii8%2BPC9zdmc%2B">
  <img alt="Prettier" src="https://img.shields.io/badge/Prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black">
  <img alt="Homebrew" src="https://img.shields.io/badge/Homebrew-%23FBB040.svg?style=for-the-badge&logo=homebrew&logoColor=black">
</p>

###### AI & automation

<p>
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-%23D97757.svg?style=for-the-badge&logo=claudecode&logoColor=white">
  <img alt="Codex" src="https://img.shields.io/badge/Codex-%23000000.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIuNCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBkPSJtNCA3IDUgNS01IDVNMTIgMThoOCIvPjwvc3ZnPg%3D%3D">
  <img alt="Perplexity" src="https://img.shields.io/badge/Perplexity-%23000000.svg?style=for-the-badge&logo=perplexity&logoColor=088F8F">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-%23EA4B71.svg?style=for-the-badge&logo=n8n&logoColor=white">
</p>

###### Systems

<p>
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-%23E95420.svg?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img alt="Alpine Linux" src="https://img.shields.io/badge/Alpine%20Linux-%230D597F.svg?style=for-the-badge&logo=alpinelinux&logoColor=white">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-%23000000.svg?style=for-the-badge&logo=macos&logoColor=F0F0F0">
  <img alt="Arm" src="https://img.shields.io/badge/Arm-%230091BD.svg?style=for-the-badge&logo=arm&logoColor=white">
  <img alt="x86" src="https://img.shields.io/badge/x86-%234B5563.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI%2BPHJlY3QgeD0iNiIgeT0iNiIgd2lkdGg9IjEyIiBoZWlnaHQ9IjEyIiByeD0iMS41Ii8%2BPHBhdGggZD0iTTkgMnYzTTE1IDJ2M005IDE5djNNMTUgMTl2M00yIDloM00yIDE1aDNNMTkgOWgzTTE5IDE1aDMiLz48L2c%2BPHJlY3QgeD0iOS41IiB5PSI5LjUiIHdpZHRoPSI1IiBoZWlnaHQ9IjUiIGZpbGw9IiNmZmYiLz48L3N2Zz4%3D">
  <img alt="Homebridge" src="https://img.shields.io/badge/Homebridge-%23491F59.svg?style=for-the-badge&logo=homebridge&logoColor=white">
</p>

###### Workspace

<p>
  <img alt="Figma" src="https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white">
  <img alt="Miro" src="https://img.shields.io/badge/Miro-%23F2CA02.svg?style=for-the-badge&logo=miro&logoColor=black">
  <img alt="Obsidian" src="https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white">
  <img alt="Notion" src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white">
  <img alt="Trello" src="https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=trello&logoColor=white">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-%232CA5E0.svg?style=for-the-badge&logo=telegram&logoColor=white">
  <img alt="Discord" src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white">
  <img alt="Google Meet" src="https://img.shields.io/badge/Google%20Meet-%2300897B.svg?style=for-the-badge&logo=googlemeet&logoColor=white">
  <img alt="Safari" src="https://img.shields.io/badge/Safari-%23000000.svg?style=for-the-badge&logo=safari&logoColor=white">
  <img alt="DuckDuckGo" src="https://img.shields.io/badge/DuckDuckGo-%23DE5833.svg?style=for-the-badge&logo=duckduckgo&logoColor=white">
  <img alt="Google" src="https://img.shields.io/badge/Google-%234285F4.svg?style=for-the-badge&logo=google&logoColor=white">
</p>
<!-- /stack -->
