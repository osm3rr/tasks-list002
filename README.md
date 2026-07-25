# ✅ Tasks List

Una aplicación sencilla y elegante desarrollada con Django para gestionar una lista de tareas de forma práctica y visual.

![Django](https://img.shields.io/badge/Django-5.2.16-green)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey)

---

## 🌟 Descripción del proyecto

Tasks List es un proyecto base de Django diseñado para mostrar cómo crear una app de tareas desde cero, utilizando modelos, vistas, plantillas y una base de datos SQLite.

Este proyecto sirve tanto como ejemplo de aprendizaje como punto de partida para construir una aplicación de gestión de tareas más completa en el futuro.

---

## ✨ Características

- Vista principal con la lista de tareas
- Modelo de tareas con descripción y fechas automáticas
- Arquitectura Django organizada por aplicaciones
- Configuración lista para ejecutar localmente
- Base de datos SQLite incluida por defecto

---

## 🛠️ Tecnologías utilizadas

- Python
- Django 5.2.16
- SQLite
- HTML y plantillas Django

---

## 📁 Estructura del proyecto

```text
tasks_list/
│
├── django_base/         # Configuración principal del proyecto Django
├── tasks/               # Aplicación de tareas
├── templates/           # Plantillas HTML del proyecto
├── db.sqlite3           # Base de datos local
├── manage.py            # Script principal de Django
├── requirements.txt     # Dependencias del proyecto
└── README.md            # Documentación del proyecto
```

---

## 🚀 Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- Python 3.x
- pip
- virtualenv o venv

---

## ⚙️ Instalación

1. Clona el repositorio:

```bash
git clone <url-del-repositorio>
cd tasks_list
```

2. Crea y activa un entorno virtual:

En Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

En Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Aplica las migraciones:

```bash
python manage.py migrate
```

5. Inicia el servidor de desarrollo:

```bash
python manage.py runserver
```

6. Abre tu navegador en:

```text
http://127.0.0.1:8000/
```

---

## 🧱 Modelo actual

El proyecto incluye un modelo de tareas con los siguientes campos:

- description: descripción de la tarea
- created_at: fecha de creación automática
- updated_at: fecha de actualización automática

---

## ▶️ Uso básico

Una vez que el servidor esté corriendo, verás la página principal donde se muestran las tareas registradas.

Para crear un superusuario y acceder al panel de administración:

```bash
python manage.py createsuperuser
```

Luego puedes ingresar a:

```text
http://127.0.0.1:8000/admin/
```

---

## 🧪 Ejecutar pruebas

```bash
python manage.py test
```

---

## 💡 Próximas mejoras

Ideas para expandir este proyecto:

- Agregar creación, edición y eliminación de tareas
- Implementar formularios con validaciones
- Añadir estado de tarea (pendiente/completada)
- Mejorar la interfaz visual con CSS o Bootstrap
- Agregar autenticación de usuarios

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Haz un fork del repositorio
2. Crea una rama con tu cambio
3. Envía un pull request

---

## 📌 Nota

Este proyecto está pensado como una base clara y simple para aprender Django, ideal para principiantes o para servir como punto de partida en futuros desarrollos.
