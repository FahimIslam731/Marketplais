# Marketplais  
A full-stack marketplace platform developed by Fahim A. Islam  
GitHub: [github.com/FahimIslam731/Marketplais](https://github.com/FahimIslam731/Marketplais)

---

## Project Overview  
**Marketplais** is a web-based marketplace system built end-to-end, showcasing a production-style architecture combining backend, frontend, authentication, and data management. It was developed to demonstrate full-lifecycle software engineering skills—from database design and server APIs to user interface and deployment tooling.

Key aspects:  
- Built using Django (Python) for the backend, serving RESTful endpoints and handling business logic.  
- Persistent data storage with SQLite (for ease of setup) and designed with modular data models for extensibility.  
- User authentication, listing management (create/read/update/delete items), shopping workflow (browse, purchase, manage orders).  
- Front-end interface (HTML/CSS/JavaScript) integrated with backend APIs, providing responsive UI for users and administrators.  
- Project organized with environment management (via Poetry), version control, and modular app structure.

---

## Features  
- User registration & login with secure session handling.  
- Item listing: users can upload items with descriptions, images, pricing, categories.  
- Browsing interface: search, filter, and sort items by category, price, etc.  
- Shopping cart & order processing workflow.  
- Admin dashboard: monitor listings, users, orders.  
- Media handling: image uploads and storage.  
- Clean project structure: `django_project/`, `core/`, `dashboard/`, `item/`, `media/`, and more.  
- Deployable via Replit with minimal configuration (for demonstration).

---

## Tech Stack  
- Backend: Python3, Django Web Framework  
- Frontend: HTML5, CSS3, JavaScript (vanilla)  
- Database: SQLite (for demo; production-ready design)  
- Dependency management: Poetry (`pyproject.toml`, `poetry.lock`)  
- Hosting/Deployment: Replit (with `replit.nix`)  
- Version control: Git, GitHub  
- Additional: Media uploads, Django static/media config, modular app architecture.

---

## Project Structure  
```text
Marketplais/
├─ django_project/        # Django settings, URL config, WSGI/ASGI entry
├─ core/                  # Core app: common utilities, base models, helpers
├─ dashboard/             # Admin-style dashboard app for user/item/order oversight
├─ item/                  # Marketplace items: listing model, views, templates
├─ media/                 # Uploaded media (images) directory
├─ manage.py              # Django management script
├─ pyproject.toml         # Poetry project config
├─ poetry.lock            # Locked dependencies
├─ README.md              # This file
└─ …other files and folders
```
