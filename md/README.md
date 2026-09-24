# 👥 Usuarios CRUD — Modularización MVC

Aplicación web desarrollada en Python con **Flask** que implementa las operaciones básicas **CRUD** (Create, Read, Update, Delete) sobre una base de datos **MySQL**, organizada mediante el patrón de arquitectura **MVC** (Modelo-Vista-Controlador) y configurada con variables de entorno de manera segura.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python
* **Framework Web:** Flask
* **Base de Datos:** MySQL
* **OR/Driver:** PyMySQL
* **Gestor de Entorno y Dependencias:** Pipenv
* **Variables de Entorno:** python-dotenv
* **Frontend:** HTML5, CSS3, Bootstrap 5

---

## 📁 Estructura del Proyecto

```text
USUARIOS_CRUD_MVC/
│
├── .env
├── .gitignore
├── Pipfile
├── Pipfile.lock
├── README.md
├── server.py
│
├── flask_app/
│   ├── bd/
│   │   └── esquema_usuarios.sql
│   ├── config/
│   │   └── mysqlconnection.py
│   ├── controllers/
│   │   └── usuarios.py
│   ├── models/
│   │   └── usuario.py
│   ├── static/
│   │   └── css/
│   │       └── style.css
│   ├── templates/
│   │   ├── index.html
│   │   ├── nuevo.html
│   │   ├── detalle.html
│   │   └── editar.html
│   └── __init__.py
│
└── resources/
    └── esquema_usuarios.mwb