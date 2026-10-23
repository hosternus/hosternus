<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="hosternus — async Python services and the infra they run on" src="assets/header-light.svg" width="100%">
</picture>

<br>

### About

Backend developer who also owns the infrastructure. I write async Python services, then provision, deploy and monitor the servers they run on, so a feature goes from code to production without changing hands.

- **Backend** — REST APIs on FastAPI, event-driven services on FastStream and RabbitMQ, MySQL, MariaDB and Redis behind SQLAlchemy and Pydantic
- **Infrastructure** — Terraform and Ansible across Google, Yandex, VK, Selectel, Cloud.ru and Timeweb clouds; Docker behind Nginx or Caddy; CI/CD on GitHub Actions
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
  <img alt="SQL" src="https://img.shields.io/badge/SQL-%23E38C00.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiPjxlbGxpcHNlIGN4PSIxMiIgY3k9IjUuNSIgcng9IjgiIHJ5PSIzIi8%2BPHBhdGggZD0iTTQgNS41djEzYzAgMS42NiAzLjU4IDMgOCAzczgtMS4zNCA4LTN2LTEzTTQgMTJjMCAxLjY2IDMuNTggMyA4IDNzOC0xLjM0IDgtMyIvPjwvZz48L3N2Zz4%3D">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii0yIC0yIDEwNCAxMDQiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0yNCAyMUMyMyAyMSAyMiAyMSAyMSAyMUwyMSAyMUwyMSAyMUMyMiAyMyAyMyAyMyAyNCAyNEMyNCAyNSAyNSAyNiAyNSAyN0wyNSAyN0MyNiAyNyAyNyAyNiAyNyAyNEMyNiAyMyAyNiAyMyAyNiAyM0MyNSAyMiAyNSAyMiAyNCAyMVpNOTIgNzlDODcgNzkgODMgODAgNzkgODFDNzggODEgNzcgODEgNzcgODNDNzcgODMgNzcgODQgNzggODVDNzggODYgODAgODggODEgODlDODIgOTAgODQgOTEgODUgOTJDODggOTQgOTEgOTUgOTMgOTZDOTUgOTcgOTYgOTggOTggOTlDOTkgMTAwIDk5IDEwMSAxMDAgMTAxTDEwMCAxMDFDMTAwIDEwMCA5OSA5OSA5OSA5OUM5OCA5OCA5OCA5NyA5NyA5N0EzMiAzMiAwIDAgMCA5MCA5MEM4OCA4OSA4MyA4NiA4MiA4NEw4MiA4NEM4NCA4NCA4NSA4MyA4NyA4M0M4OSA4MiA5MSA4MiA5MyA4MkM5NSA4MSA5NiA4MSA5NyA4MUw5NyA4MEM5NSA3OSA5NSA3NyA5MyA3NkE4OSA4OSAwIDAgMCA4MiA2OEM4MCA2NyA3OCA2NiA3NSA2NUM3NSA2NCA3MyA2NCA3MyA2M0M3MiA2MiA3MSA2MCA3MCA1OEExNzcgMTc3IDAgMCAxIDY0IDQ3QzYzIDQ0IDYzIDQxIDYxIDM5QzU0IDI4IDQ3IDIxIDM1IDE0QzMzIDEzIDMwIDEyIDI3IDExQzI1IDExIDIzIDExIDIyIDExQzIxIDExIDIwIDkgMTkgOUMxNSA2IDUgMSAyIDhDMCAxMiA1IDE3IDYgMTlDOCAyMCA5IDIyIDEwIDI0QzEwIDI1IDEwIDI2IDExIDI3QzEyIDMwIDEzIDM0IDE0IDM2QzE1IDM4IDE2IDM5IDE3IDQwQzE3IDQxIDE4IDQxIDE4IDQzQzE3IDQ0IDE3IDQ2IDE3IDQ4QzE0IDU1IDE1IDY1IDE5IDcwQzIwIDcyIDIyIDc2IDI2IDc0QzI5IDczIDI4IDY5IDI5IDY2QzI5IDY1IDI5IDY0IDMwIDY0TDMwIDY0QzMwIDY2IDMxIDY4IDMyIDcwQzM0IDczIDM4IDc2IDQxIDc5QzQzIDgwIDQ0IDgyIDQ2IDgzTDQ2IDgyTDQ2IDgyQzQ1IDgyIDQ1IDgyIDQ0IDgxQTM0IDM0IDAgMCAxIDQxIDc3QTg4IDg4IDAgMCAxIDMzIDY1QzMyIDYzIDMxIDYxIDMwIDU4QzMwIDU4IDMwIDU2IDI5IDU2QzI4IDU3IDI3IDU5IDI2IDYxQzI1IDYzIDI1IDY3IDI0IDcxQzI0IDcxIDI0IDcxIDI0IDcxQzIyIDcwIDIxIDY4IDIwIDY2QzE4IDYxIDE4IDU0IDIwIDQ4QzIwIDQ3IDIyIDQzIDIxIDQxQzIxIDQwIDIwIDM5IDE5IDM4QTI1IDI1IDAgMCAxIDE2IDM0QzE1IDMwIDE0IDI2IDEyIDIyQzExIDIxIDEwIDE5IDkgMTdDOCAxNSA2IDE0IDUgMTJDNSAxMSA0IDEwIDUgOUM1IDkgNSA4IDYgOEM3IDggOSA5IDEwIDlDMTMgMTAgMTUgMTEgMTcgMTJDMTggMTMgMTkgMTQgMjAgMTVMMjEgMTVDMjMgMTUgMjYgMTUgMjggMTVDMzEgMTYgMzUgMTggMzcgMjBBNjAgNjAgMCAwIDEgNTggNDNDNTkgNDQgNTkgNDYgNjAgNDdDNjIgNTEgNjMgNTQgNjUgNTdDNjYgNjAgNjcgNjMgNjkgNjZDNzAgNjcgNzUgNjggNzYgNjlDNzggNzAgODAgNzAgODEgNzFDODMgNzIgODUgNzQgODggNzVDODkgNzYgOTIgNzggOTIgNzlaIi8%2BPC9zdmc%2B">
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
  <img alt="Selectel Cloud" src="https://img.shields.io/badge/Selectel%20Cloud-%23EB4247.svg?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjIgMiAyMCAyMCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyLjMzMzUgMTcuNjMzMUMxMy4xOTQzIDE3LjYzMzEgMTMuOTQ0MiAxNy40MzM1IDE0LjU1NTQgMTcuMDMzOEMxNS4xMTA5IDE2LjY2MyAxNS4zODg3IDE2LjE3ODMgMTUuNDQ0NSAxNS42MDhIMTcuOTk5OUMxNy45NDQ3IDE2LjQ2MzUgMTcuNjk0IDE3LjIwNSAxNy4yMjI1IDE3LjgzMjZDMTYuNjY2NCAxOC41NDUyIDE1Ljk3MjMgMTkuMDg3MiAxNS4wODMzIDE5LjQ1OEMxNC4xOTQzIDE5LjgyODggMTMuMjIxOSAyMCAxMi4xNjYxIDIwQzExLjA4MzMgMjAgMTAuMTEwOSAxOS44MDA0IDkuMjIxOTEgMTkuNDAxM0M4LjMzMzQ3IDE5LjAwMTYgNy42MTEyMiAxOC40NjAyIDcuMDU1NzMgMTcuNzE4N0M2LjQ5MzA0IDE2Ljk3MTQgNi4xMjkyMSAxNi4wODY4IDUuOTk5OTUgMTUuMTUxNkw4LjU1NTQ0IDE0Ljc1MjVDOC43Nzc5OCAxNS42NjUyIDkuMjIxOTEgMTYuMzQ4OSA5LjkxNjU3IDE2Ljg2MjZDMTAuNjExMiAxNy4zNzYyIDExLjQxNjkgMTcuNjMzMSAxMi4zMzM1IDE3LjYzMzFaTTE1LjkxNjYgMTEuNzAwN0MxNi40OTcgMTEuOTkzNCAxNy4wMDE1IDEyLjQyMzQgMTcuMzg4NyAxMi45NTUzQzE3LjcyNTggMTMuNDMxMiAxNy45Mjc2IDEzLjk5MzkgMTcuOTcxOCAxNC41ODA3SDE1LjI0OTVDMTUuMTk0MyAxNC40NjY3IDE1LjEzODUgMTQuMzgxMSAxNS4wNTUyIDE0LjI5NTVDMTQuNzc3NCAxNC4wMTAzIDE0LjM2MDUgMTMuNzU0MSAxMy43Nzc0IDEzLjU4MjlMOS44ODgzOSAxMi4zODQ5QzguOTQ0MTcgMTIuMTI4MSA4LjE2NjE0IDExLjcwMDcgNy41MjcyNiAxMS4xMjk3QzYuODg4MzkgMTAuNTU5NCA2LjU4MzA0IDkuNjc0OTggNi41ODMwNCA4LjUwNTk4QzYuNTgzMDQgNy41NjQ4NyA2LjgzMjYxIDYuNzM3NzEgNy4zMDUzIDYuMDgxNzdDNy43Nzc0MSA1LjM5NzQ5IDguNDE1NyA0Ljg4NDQzIDkuMjQ5NTIgNC41NDE5OUMxMC4wODI4IDQuMTcxMjIgMTAuOTk5NCA0LjAyODM0IDExLjk5OTQgNEMxMi45OTk0IDQgMTMuOTE2NiA0LjE5OTU2IDE0LjcyMTYgNC41NDE5OUMxNS41MTIxIDQuODYwMTcgMTYuMjEwMiA1LjM4MDQ0IDE2Ljc0OTggNi4wNTM0M0MxNy4yNzcxIDYuNzA5MzcgMTcuNjY2NCA3LjUzNjUzIDE3Ljg4ODQgOC40Nzc2NEwxNS4yNTAxIDguOTM0MDJDMTUuMDgzMyA4LjE2NDEzIDE0LjY5NCA3LjUzNjUzIDE0LjA4MjggNy4wODAxNUMxMy40NzE1IDYuNjIzNzYgMTIuNzc2OCA2LjM5NTg3IDExLjk3MTggNi4zNjY5NEMxMS40OTk3IDYuMzY2OTQgMTEuMDI3NSA2LjQyNDIxIDEwLjU4MyA2LjU5NTQyQzEwLjEzODUgNi43NjY2NCA5Ljc3NzQxIDYuOTk0NTQgOS41MjcyNiA3LjMwODYzQzkuMjc3MTIgNy42MjIxNCA5LjEzODUzIDcuOTY0NTggOS4xMzg1MyA4LjM2MzFDOS4xMzg1MyA4LjkwNTY4IDkuMzYwNSA5LjMwNDggOS43NDk4IDkuNTYxNjJDMTAuMTY2MSA5LjgxNzg2IDEwLjY5MzQgMTAuMDQ2MyAxMS4zNjA1IDEwLjIxNzZMMTQuMDI3NSAxMS4wMTU4QzE0LjcyMTYgMTEuMjE1NCAxNS4zNjA1IDExLjQ0MzggMTUuOTE2NiAxMS43MDA3WiIvPjwvc3ZnPg%3D%3D">
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
