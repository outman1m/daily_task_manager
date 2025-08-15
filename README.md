# Daily Task Manager API

Django REST API to manage daily tasks with categories. Auth-protected, per-user data.

## Endpoints
- `POST /api/categories/` | `GET /api/categories/` | `PUT/DELETE /api/categories/<id>/`
- `POST /api/tasks/` | `GET /api/tasks/` | `GET/PUT/DELETE /api/tasks/<id>/`

## Quick start
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver

