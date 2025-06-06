# Task Backend

Backend en Django para gestión de tareas.

## Requisitos

- Python 3.11 o superior
- pip

## Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/MrLechoza/Task-Backend.git
   cd task-backend/taskmanager
   ```

2. Crea y activa un entorno virtual:
   ```sh
   python -m venv venv
   venv\Scripts\activate
   ```

3. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```

4. Aplica migraciones:
   ```sh
   python manage.py migrate
   ```

5. Corre el servidor:
   ```sh
   python manage.py runserver
   ```

## Endpoints principales

- `GET/POST /tasks/`
- `GET/PUT /tasks/<id>/`

## Notas

- El archivo `db.sqlite3` es solo para desarrollo.
- Puedes crear un superusuario con:
  ```sh
  python manage.py createsuperuser
  ```

---
