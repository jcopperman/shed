# Shed

**Shed** is a lightweight, no-vendor control panel for managing your self-hosted services on bare metal.

Designed for developers, homelabbers, and small infra owners who want:

- 🔧 Local control of Docker-based apps and websites
- 🧱 Git-based deployments and logs
- 🧘 Zero cloud dependencies
- 🔐 Pure FastAPI + HTMX stack

---

## 🧰 Features

- List all site projects from `/var/www/{project_name}/`
- View Docker Compose service status
- Restart containers
- Tail logs
- Pull from Git
- Fully local – run behind Nginx or serve on `localhost`

---

## 🏗 Directory Layout

Your services must live in `/srv/sites/{project_name}/` and include:
