# Home About

<p align="center">
  <img src="https://img.shields.io/badge/Django-5.x-092E20?logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Status-Ready-4CAF50" alt="Status" />
</p>

Un proyecto web sencillo desarrollado con Django para mostrar una landing page y una vista de información sobre la empresa o el autor.

## ✨ Características

- Arquitectura básica de Django
- App modular `pages`
- Vistas para inicio y acerca de
- Templates reutilizables con herencia
- Configuración lista para arrancar localmente

## 🧩 Estructura del proyecto

```text
home-about/
├── django_base/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── pages/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates/
│   ├── _base.html
│   ├── home.html
│   └── about.html
├── manage.py
├── requirements.txt
├── db.sqlite3
├── .gitignore
└── README.md
```

## 🌐 Rutas principales

- `/` → Página de inicio
- `/about/` → Página “Acerca de”

## 🚀 Instalación y ejecución

### 1. Clona el repositorio

```bash
git clone <url-del-repositorio>
cd home-about
```

### 2. Crea un entorno virtual

```bash
python -m venv .venv
```

### 3. Activa el entorno virtual

Windows (PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

Linux/macOS:

```bash
source .venv/bin/activate
```

### 4. Instala las dependencias

```bash
pip install -r requirements.txt
```

### 5. Aplica migraciones

```bash
python manage.py migrate
```

### 6. Inicia el servidor

```bash
python manage.py runserver
```

Luego abre en tu navegador:

```text
http://127.0.0.1:8000/
```

## 🛠️ Tecnologías usadas

- Django
- Python
- SQLite
- HTML + Django Templates

## 📌 Notas

Este proyecto funciona como base para una pequeña web personal o landing page, y puede ampliarse fácilmente con secciones adicionales, formularios, autenticación, modelos y más contenido.

## 👤 Autor

Proyecto desarrollado para mostrar una base simple, limpia y lista para personalizar.

---

Si quieres, también puedo dejarte una versión aún más premium del README con:

- logo personalizado
- sección de captura de pantalla
- badges de tecnologías
- instrucciones para despliegue en Render/Heroku/Vercel
- estilo más corporativo o más moderno
