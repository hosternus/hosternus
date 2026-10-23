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
  <img alt="FastStream" src="https://img.shields.io/badge/FastStream-%2356B7E0.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgLTI1IDUxMiA1MTIiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Im00OTkuNjEsMzU2Ljg3bC05Mi42MS0xNjAuNDEtMzYuNDgtNjMuMTktMTAuNDYsMjUxLjAyYy4wNywyLjg2LS43OCw2LjA1LTIuNTEsOC42LTIuOTgsNC40MS03LjQyLDUuMzEtOS45MiwyLjAybC4wMi0uMDMtNjguODUtOTAuNDgtMTA3LjEzLDM4LjA5di4wNGMtMy44OSwxLjM4LTcuMTEtMS44LTcuMi03LjEyLS4wNS0zLjA4Ljk3LTYuMjIsMi42LTguNTdMMzI3LjEsNTguMDdsLTEyLjcxLTIyLjAyYy0yNS45NS00NC45NC05MC44Mi00NC45NC0xMTYuNzcsMGwtOTIuNjEsMTYwLjQxTDEyLjM5LDM1Ni44N2MtMjUuOTUsNDQuOTQsNi40OSwxMDEuMTIsNTguMzgsMTAxLjEyaDM3MC40NWM1MS45LDAsODQuMzMtNTYuMTgsNTguMzgtMTAxLjEyWiIvPjwvc3ZnPg%3D%3D">
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
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjEwLjggMi42IDguNCA4LjQiPjxjbGlwUGF0aCBpZD0iYyI%2BPHBhdGggZD0iTTEwLjggMi42SDE5LjJWMTFIMTcuNlY5Ljk1SDEwLjhaIi8%2BPC9jbGlwUGF0aD48cGF0aCBjbGlwLXBhdGg9InVybCgjYykiIGZpbGw9IiNmZmYiIGQ9Ik0xNi40MDUgNS41MDFjLS4xMTUgMC0uMTkzLjAxNC0uMjc0LjAzM3YuMDEzaC4wMTRjLjA1NC4xMDQuMTQ2LjE4LjIxNC4yNzMuMDU0LjEwNy4xLjIxNC4xNTQuMzJsLjAxNC0uMDE1Yy4wOTQtLjA2Ni4xNC0uMTcyLjE0LS4zMzMtLjA0LS4wNDctLjA0Ni0uMDk0LS4wOC0uMTQtLjA0LS4wNjctLjEyNi0uMS0uMTgtLjE1M3pNNS43NyAxOC42OTVoLS45MjdhNTAuODU0IDUwLjg1NCAwIDAwLS4yNy00LjQxaC0uMDA4bC0xLjQxIDQuNDFIMi40NWwtMS40LTQuNDFoLS4wMWE3Mi44OTIgNzIuODkyIDAgMDAtLjE5NSA0LjQxSDBjLjA1NS0xLjk2Ni4xOTItMy44MS40MS01LjUzaDEuMTVsMS4zMzUgNC4wNjRoLjAwOGwxLjM0Ny00LjA2NGgxLjA5NWMuMjQyIDIuMDE1LjM4NCAzLjg2LjQyOCA1LjUzem00LjAxNy00LjA4Yy0uMzc4IDIuMDQ1LS44NzYgMy41MzMtMS40OTIgNC40Ni0uNDgyLjcxNi0xLjAxIDEuMDczLTEuNTgzIDEuMDczLS4xNTMgMC0uMzQtLjA0Ni0uNTY2LS4xMzh2LS40OTRjLjExLjAxNy4yNC4wMjYuMzg2LjAyNi4yNjggMCAuNDgzLS4wNzUuNjQ3LS4yMjIuMTk3LS4xOC4yOTUtLjM4Mi4yOTUtLjYwNSAwLS4xNTUtLjA3Ny0uNDctLjIzLS45NDRMNi4yMyAxNC42MTVoLjkxbC43MjcgMi4zNmMuMTY0LjUzNi4yMzMuOTEuMjA1IDEuMTIzLjQtMS4wNjQuNjc4LTIuMjI3LjgzNS0zLjQ4M3ptMTIuMzI1IDQuMDhoLTIuNjN2LTUuNTNoLjg4NXY0Ljg1aDEuNzQ1em0tMy4zMi4xMzVsLTEuMDE2LS41Yy4wOS0uMDc2LjE3Ny0uMTU4LjI1NS0uMjUuNDMzLS41MDYuNjQ4LTEuMjU4LjY0OC0yLjI1MyAwLTEuODMtLjcxOC0yLjc0Ni0yLjE1NS0yLjc0Ni0uNzA0IDAtMS4yNTQuMjMyLTEuNjUuNjk3LS40My41MDgtLjY0NiAxLjI1Ni0uNjQ2IDIuMjQ1IDAgLjk3Mi4xOSAxLjY4Ni41NzQgMi4xNC4zNS40MS44NzcuNjE1IDEuNTgzLjYxNS4yNjQgMCAuNTA2LS4wMzMuNzI1LS4wOThsMS4zMjUuNzcyLjM2LS42MjJ6TTE1LjUgMTcuNTg4Yy0uMjI1LS4zNi0uMzM3LS45NC0uMzM3LTEuNzM2IDAtMS4zOTMuNDI0LTIuMDkgMS4yNy0yLjA5LjQ0MyAwIC43Ny4xNjcuOTc3LjUuMjI0LjM2Mi4zMzYuOTM2LjMzNiAxLjcyMyAwIDEuNDA0LS40MjQgMi4xMDgtMS4yNyAyLjEwOC0uNDQ1IDAtLjc3LS4xNjctLjk3OC0uNXptLTEuNjU4LS40MjVjMCAuNDctLjE3Mi44NTYtLjUxNiAxLjE1Ni0uMzQ0LjMtLjgwMy40NS0xLjM4NC40NS0uNTQzIDAtMS4wNjQtLjE3Mi0xLjU3My0uNTE1bC4yMzctLjQ3NmMuNDM4LjIyLjgzMy4zMjggMS4xOS4zMjguMzMyIDAgLjU5My0uMDczLjc4My0uMjJhLjc1NC43NTQgMCAwMC4zLS42MTVjMC0uMzMtLjIzLS42MS0uNjQ4LS44NDUtLjM4OC0uMjEzLTEuMTYzLS42NTctMS4xNjMtLjY1Ny0uNDIyLS4zMDctLjYzMi0uNjM2LS42MzItMS4xNzcgMC0uNDUuMTU3LS44MS40Ny0xLjA4NS4zMTUtLjI3OC43Mi0uNDE1IDEuMjItLjQxNS41MTIgMCAuOTguMTM2IDEuNC40MWwtLjIxMy40NzZhMi43MjYgMi43MjYgMCAwMC0xLjA2NC0uMjNjLS4yODMgMC0uNTAyLjA2OC0uNjU0LjIwNmEuNjg1LjY4NSAwIDAwLS4yNDguNTI0YzAgLjMyOC4yMzQuNjEuNjY2Ljg1LjM5My4yMTUgMS4xODcuNjcgMS4xODcuNjcuNDMzLjMwNS42NDguNjMuNjQ4IDEuMTY4em05LjM4Mi01Ljg1MmMtLjUzNS0uMDE0LS45NS4wNC0xLjI5Ny4xODgtLjEuMDQtLjI2LjA0LS4yNzQuMTY3LjA1NS4wNTMuMDYzLjE0LjExLjIxNC4wOC4xMzQuMjE4LjMxMy4zNDYuNDA3LjE0LjExLjI4LjIxNi40MjcuMzEuMjYuMTYuNTU1LjI1NS44MS40MTYuMTQ1LjA5NC4yOTMuMjEzLjQ0LjMxMy4wNzMuMDUuMTIuMTQuMjE0LjE3MnYtLjAyYy0uMDQ2LS4wNi0uMDYtLjE0Ny0uMTA1LS4yMTQtLjA2Ny0uMDY3LS4xMzQtLjEyNy0uMi0uMTkzYTMuMjIzIDMuMjIzIDAgMDAtLjY5NS0uNjc1Yy0uMjE0LS4xNDYtLjY4Mi0uMzUtLjc3LS41OTVsLS4wMTMtLjAxNGMuMTQ2LS4wMTMuMzItLjA2Ni40Ni0uMTA2LjIyNy0uMDYuNDM1LS4wNDcuNjctLjEwNi4xMDYtLjAyNy4yMTMtLjA2LjMyLS4wOTR2LS4wNmMtLjEyLS4xMi0uMjEtLjI4My0uMzM0LS4zOTVhOC44NjcgOC44NjcgMCAwMC0xLjEwNC0uODIzYy0uMjEtLjEzNC0uNDc2LS4yMi0uNjk3LS4zMzQtLjA4LS4wNC0uMjE0LS4wNi0uMjYtLjEyNy0uMTItLjE0Ni0uMTktLjM0LS4yNzUtLjUxNGExNy42OSAxNy42OSAwIDAxLS41NDctMS4xNjNjLS4xMi0uMjYyLS4xOTMtLjUyMy0uMzQtLjc2My0uNjktMS4xMzctMS40MzctMS44MjYtMi41ODYtMi41LS4yNDctLjE0LS41NDMtLjItLjg1Ni0uMjc0LS4xNjctLjAwOC0uMzM0LS4wMi0uNS0uMDI3LS4xMS0uMDQ3LS4yMTYtLjE3NC0uMzEtLjIzNS0uMzgtLjI0LTEuMzY0LS43Ni0xLjY0NC0uMDcyLS4xOC40MzQuMjY3Ljg2Mi40MjIgMS4wODIuMTE1LjE1My4yNi4zMjguMzQuNS4wNDcuMTE2LjA2LjIzNS4xMDcuMzU2LjEwNi4yOTQuMjA3LjYyMi4zNDcuODk3LjA3My4xNC4xNTMuMjg3LjI0Ny40MTMuMDU0LjA3My4xNDYuMTA3LjE2Ny4yMjctLjA5NC4xMzYtLjEuMzM0LS4xNTQuNS0uMjQuNzU3LS4xNDYgMS42OTMuMTk0IDIuMjUuMTA3LjE2Ni4zNjIuNTM0LjcwMy4zOTMuMy0uMTIuMjM0LS41LjMyLS44MzUuMDItLjA4LjAwNy0uMTMzLjA0OC0uMTg3di4wMTVjLjA5NC4xODguMTg4LjM2Ny4yNzQuNTU1LjIwNi4zMjguNTY2LjY2OC44NjcuODk1LjE2LjEyLjI4Ny4zMjguNDg3LjQwMnYtLjAyaC0uMDE1Yy0uMDQzLS4wNTgtLjEtLjA4Ni0uMTU0LS4xMzNhMy40NDUgMy40NDUgMCAwMS0uMzUtLjQgOC43NiA4Ljc2IDAgMDEtLjc0Ny0xLjIxOGMtLjExLS4yMS0uMjAyLS40MzYtLjI5LS42NDMtLjA0LS4wOC0uMDQtLjItLjEwNy0uMjQtLjEuMTQ2LS4yNDcuMjczLS4zMi40NTMtLjEyNy4yODgtLjE0LjY0Mi0uMTg4IDEuMDEtLjAyNy4wMDctLjAxNCAwLS4wMjcuMDE0LS4yMTQtLjA1Mi0uMjg3LS4yNzQtLjM2Ny0uNDYtLjItLjQ3NS0uMjMzLTEuMjM4LS4wNi0xLjc4NS4wNDctLjE0LjI0Ny0uNTgyLjE2Ny0uNzE2LS4wNDItLjEyNy0uMTc0LS4yLS4yNDctLjMwM2EyLjQ3OCAyLjQ3OCAwIDAxLS4yNC0uNDI3Yy0uMTYtLjM3NC0uMjQtLjc4OC0uNDE0LTEuMTYyLS4wOC0uMTczLS4yMi0uMzU0LS4zMzQtLjUxMy0uMTI3LS4xOC0uMjY3LS4zMDctLjM2OC0uNTItLjAzMy0uMDczLS4wOC0uMTk0LS4wMjctLjI3NC4wMTQtLjA1NC4wNDItLjA3NS4wOTQtLjA5LjA4OC0uMDcyLjMzNS4wMjIuNDIyLjA2Mi4yNDcuMS40NTUuMTk0LjY2Mi4zMzQuMDk0LjA2Ni4xOTUuMTkzLjMxNS4yMjZoLjE0Yy4yMTQuMDQ3LjQ1NS4wMTQuNjU1LjA3My4zNTUuMTE0LjY3NS4yOC45NjIuNDZhNS45NTMgNS45NTMgMCAwMTIuMDg1IDIuMjg2Yy4wOC4xNTQuMTE1LjI5NS4xODguNDU1LjE0LjMzLjMxMy42NjMuNDU1Ljk4Mi4xNC4zMTUuMjc1LjYzNi40NzYuODk3LjEuMTQuNTAyLjIxMy42ODIuMjg2LjEzMy4wNi4zNC4xMTUuNDYuMTg4LjIzLjE0LjQ1NC4zLjY3LjQ1NC4xMS4wNzYuNDQzLjI0My40NjMuMzc4eiIvPjwvc3ZnPg%3D%3D">
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
  <img alt="Portainer" src="https://img.shields.io/badge/Portainer-%232E2F33.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLjU2IDApIHNjYWxlKC4wNzkzKSIgZD0iTTIwNS43OSw2OS43M3YtMTQuODVoMjMuMzd2LTEzLjM2aC04MC4yN2wtNTQuODItMzEuNjJWMGgtMTkuMzV2OS44N2wtNTQuODgsMzEuNjVIMHYxMy4zNmg3NC43MXYyNDcuODdoMTkuMzVWNTQuODhoMTA0LjA0djE0LjYzYy0xLjItLjAyLTIuNDEtLjAzLTMuNjQtLjAzaC04NS44djIzMy4yN2g2Ny4xNXYtNzMuNTJoMTguNzNjNTkuMiwwLDk0LjA1LTE4LjMxLDk0LjA1LTc4Ljg0di0yLjA2YzAtNTYuMzgtMzAuNS03Ni4yMy04Mi43OS03OC42Wk03NC43MSw0MS41MmgtMzguODZsMzguODYtMjIuNDJ2MjIuNDJaTTk0LjA2LDQxLjUydi0yMi4zOWwzOC44MSwyMi4zOWgtMzguODFaTTIyNy40MiwxNzUuMjVoLTUxLjc2di01MS43NmgyMi40M3YtNTMuOThjMi42MS4wMyw1LjE4LjEsNy42OS4yMXY1My43NmgyMS42NHY1MS43NloiLz48L3N2Zz4%3D">
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
  <img alt="Cloud.ru" src="https://img.shields.io/badge/Cloud.ru-%23222222.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjUgNSAzOCAzOCI%2BPHBhdGggZmlsbD0iIzI2RDA3QyIgZD0iTTQyIDI2VjM0LjkwMTRMMjUuOTk3IDQyTDI2IDI2SDQyWk00MiAyMlYxMy4wOTg2TDI2IDZWMjJINDJaTTYgMTMuMDk4NlYzNC45MDE0TDIyIDQyVjZMNiAxMy4wOTg2WiIvPjwvc3ZnPg%3D%3D">
  <img alt="Timeweb Cloud" src="https://img.shields.io/badge/Timeweb%20Cloud-%23454CEE.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjIyLjEgMjIgNzYgNzYiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik04NC4zMzQ3IDU5LjgyMjNMNDYuNTUyNSAyMi41TDM1Ljg1OTQgMzMuNTE5TDYyLjIzNTcgNTkuODIyM0wzNS44NTk0IDg2LjQ4MUw0Ni41NTI1IDk3LjVMODQuMzM0NyA1OS44MjIzWiIvPjwvc3ZnPg%3D%3D">
</p>

###### CI & tooling

<p>
  <img alt="Git" src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white">
  <img alt="Dependabot" src="https://img.shields.io/badge/Dependabot-%23025E8C.svg?style=for-the-badge&logo=dependabot&logoColor=white">
  <img alt="Trivy" src="https://img.shields.io/badge/Trivy-%231904DA.svg?style=for-the-badge&logo=trivy&logoColor=white">
  <img alt="VS Code" src="https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIzLjE1IDIuNTg3TDE4LjIxLjIxYTEuNDk0IDEuNDk0IDAgMCAwLTEuNzA1LjI5bC05LjQ2IDguNjMtNC4xMi0zLjEyOGEuOTk5Ljk5OSAwIDAgMC0xLjI3Ni4wNTdMLjMyNyA3LjI2MUExIDEgMCAwIDAgLjMyNiA4Ljc0TDMuODk5IDEyIC4zMjYgMTUuMjZhMSAxIDAgMCAwIC4wMDEgMS40NzlMMS42NSAxNy45NGEuOTk5Ljk5OSAwIDAgMCAxLjI3Ni4wNTdsNC4xMi0zLjEyOCA5LjQ2IDguNjNhMS40OTIgMS40OTIgMCAwIDAgMS43MDQuMjlsNC45NDItMi4zNzdBMS41IDEuNSAwIDAgMCAyNCAyMC4wNlYzLjkzOWExLjUgMS41IDAgMCAwLS44NS0xLjM1MnptLTUuMTQ2IDE0Ljg2MUwxMC44MjYgMTJsNy4xNzgtNS40NDh2MTAuODk2eiIvPjwvc3ZnPg%3D%3D">
  <img alt="Prettier" src="https://img.shields.io/badge/Prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black">
  <img alt="Homebrew" src="https://img.shields.io/badge/Homebrew-%23FBB040.svg?style=for-the-badge&logo=homebrew&logoColor=black">
</p>

###### AI & automation

<p>
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-%23D97757.svg?style=for-the-badge&logo=claudecode&logoColor=white">
  <img alt="Codex" src="https://img.shields.io/badge/Codex-%23000000.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAABYlAAAWJQFJUiTwAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAbGSURBVHgBzZo%2FbBtVHMd%2FZzuJA0gYCYlsOFO7xRFDy1R3olucqd0SJtiSjiCknBckpjZjBxRn7BR3owOqs5Wp7tZKoDgSQysh4UqUOCG2eZ%2F3%2FOznv%2FfObqJ%2BpfPZd%2B%2Fufn%2B%2Bvz%2FvnQN5FwjbGZFGQSRYUb%2ByIu2c2tSxIOOMqpktqKpzz9X3ioSLNZkRgUwLhA4aW9KWvPqVl6mgldmVGZSJr0BX8Pb2gIVnRUltxbiKxFOgeLJzAYL3I5BQdhaL%2FsN9EJ5k1dADw%2B1LQU1tN328kYgaIMWzDSX4s0sUHmSVwZ5JeFqIGjhZgeKpokyzdKGUGQuyWOtA03YCxlNIC98K5X3AhLgYrYB2ndLeE5l0IFvXklK4mpRsxvyuvmqrrSX71aZUjlsyM4LkpuzM7w8dHhqoAxbO%2B9Fm63pSwhspLTSo1dt6n830bl1SStx9fK6%2FZ9LmWL3B1hZ%2FBHUl1%2BpgYI9S4Eh0EEVjJ5%2FSwiPI7m9Nuf%2B02SfUZi4pO%2Bo8ynDcKmlRqRkPlZ43xQ%2Bq8IXpVfdIsu88vJd2ZOSD%2FOcJKRXmtMW%2F%2FPlMyi9a0jjvH5NZCDStEDydCjSlfvm9pa%2Fhd24poc%2Bzf%2FzH8PUjsCT57wOp%2FFjpqtQ9pakjR%2BKJo60Fbdnl3dMubSw4vrc2J%2FmsSXLlF4ZCg%2BM4zzjGEzM39888aAWVFpYlZN%2BfRnfEE1iMh8JtVygsDWWefTOvhYMiCLX%2B8L8h4QHnVx%2Bcas%2FklgLZvpb0eDrp9d%2Ftrjr609P6brbhgesPDXXA5kpS7t0ywYwVi4fERD8noJ1WfIDzBDYeRRw8GscL1gP5iCv0g7FsqAIX4UH9pHeegEb44uG5EuKsT3iuPbg9J08252VPxQ3CoowFGYlgRhEMEY2eFzp3CbbEQ3j28BnXjwI0CSvnXQu6lMJrnOd67qOV6fAf2HuuLPn2l4kbRgGT9yf2OU825o11lXDw%2Bbgenb8LV5JdjwE8s%2FrAxMPXj0xMkGbxBkpWX8epCRp5WvuERNAHl9qADQ%2Bj8xz0QuGDOz3rIizXW8%2FwHa7bzISSKAveNCQGGoVElPU3coaTcDQKhmoL3QxEkLMna2FplzKAOCFLGf6b4x%2BnJQbauURnHjsWWJQg8%2B1nsChCsZGh2LuUwTvb11J94zfVeVtPGOOej4CuNNlJI2xa9BUeQQaD3FKG83iAdItHClcSQ4rzLJvRohGsRCowqoexyCxKbNiUqVPrnf5MhBL0VKRTv6IWZCJnZJR4bujm7eprY%2BGD2%2FM6g%2FhZyypgKENGspThHha2fqxdjZ4sUg8iRz16aYLXBrN5SLPLa5tBMrGCT3T7wD0GgYcM1XwU0IWsXZ80wPY7WMpVguM2g0ABvMDmZhkXZox4w3dswvQV44FFSIe4vqT46rrbzSAEru1pXF6j1L2vTND6Us10p15Zr5Ywq2OTQRwUO0UMyiCM27PYDDKYLomRoy2VNq%2Bn9HGfbGbvyzM9FWgd%2B4zMfWY4iaV1v6%2BassHCZNOl7XcKnUC0bUQ9osrq3qnTevgUTtZYUz4ecGEDDwtjaTYER8jsx0YAO5Gxc2EfyyP83lqq27b4Fc6gqhRolEXSe1FDrRBUZioslrYpkD3WthzHSyg0WNCIkVFeoNWw3S7UsQsAHqiobvQTgrgSNbL80gizdmU4EyEswsNzPMQxV3hqiO1oR3kDoyD87tOm57QStKusUNiUcigRXSlZQRchZW2qpc0Sdg5AbQDuw3XboDIQcwGAUm7uh3LWEPvPx88zRiNgWd5OaBr3o%2BoBrmeaCJhdDeZ7BB83kbETdjZ3bmzryii6eaDCR8c0PzUk%2FwOdTX7SFU%2F%2FbEmg5EYoUiOCvv5H5NXbnuDffpHUGYoxLJN892uvarsgXXIPa%2F14SJTU%2BpBepXOWVf5W88yFI58VOWqBW9DAYNM3KQMRE0x4gO2JYmLZrtD1ItLTC3ooK2rKasdvzAIVwNp2PfTqpwmdWZY%2BCswMKzDeYZp579acNgDjodSLv%2BIK31JvcT4o218jlhYbM78LcJcUR8EG8xSWrynLL7sHZl7cnQQUoYKvLJn0eVwnHTenCVgxSSbwWNwF4cmm%2BowsbpeLxLqEC%2BWhoyPHhosl4Y3hewN4Pyw8mNzfhiehxFgzvRgg%2FIfhuLPRDXr4ljfwe5f%2Fnkxz%2Fm6HDWMR4zWrPBHPFx%2BzQ7%2FBX%2Fd5zRrvRfeFU0pbfVcJHvpeMcVfDfAGby8TG%2FLO0BFc0vftiwtfzPBnD02rvFnZnrrwVUR3wvEFt5heARddZVDE%2FuXGjRdt4bru4UWODcfT5WmFdvE%2FJeqz44iuBr4AAAAASUVORK5CYII%3D">
  <img alt="Perplexity" src="https://img.shields.io/badge/Perplexity-%23000000.svg?style=for-the-badge&logo=perplexity&logoColor=088F8F">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-%23EA4B71.svg?style=for-the-badge&logo=n8n&logoColor=white">
</p>

###### Systems

<p>
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-%23E95420.svg?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img alt="Alpine Linux" src="https://img.shields.io/badge/Alpine%20Linux-%230D597F.svg?style=for-the-badge&logo=alpinelinux&logoColor=white">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-%23000000.svg?style=for-the-badge&logo=apple&logoColor=white">
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
