# DB-Coursework-2026-I
Este repositorio contiene los proyectos desarrollados durante el curso de Bases de Datos en el semestre 2026-1.

---

## Proyecto 1: Bazar de Ropa
Sistema integral para la gestión de inventario y ventas de un bazar.

### 🛠️ Tecnologías
* **Backend:** FastAPI con SQLAlchemy (ORM).
* **Base de Datos:** PostgreSQL con vistas para reportes de stock y ventas.
* **Frontend:** JavaScript vanilla (Fetch API) y CSS modular.

### 🖼️ Previews
- <img width="2474" height="1329" alt="image" src="https://github.com/user-attachments/assets/f8a8d918-b0eb-40e0-b517-c7f1923737d0" />

- <img width="2614" height="1207" alt="2" src="https://github.com/user-attachments/assets/8b984eda-d9ff-4111-9496-9dcee597ed06" />

- <img width="2469" height="1468" alt="3" src="https://github.com/user-attachments/assets/8197c31e-7013-4ff3-b1ef-7c6c05e7663c" />

- <img width="2700" height="1610" alt="image" src="https://github.com/user-attachments/assets/b382ae67-8eb4-44c5-ba46-0e08fe3d10ef" />

### 🔗 Enlaces
**Código Fuente:** [Repositorio en GitHub](https://github.com/jr-devel/doly)

**Demo en Vivo:** [Bazar Ropa Web](https://bazar-ropa-project-web.onrender.com)
  
## Proyecto 2: Tienda de videojuegos
# 🛠️ Sistema de Administración de Tienda (PHP)
Este es un panel de administración web ligero y funcional diseñado para gestionar las operaciones básicas de una tienda. Permite centralizar el registro de clientes, control de inventario y el historial de ventas en una interfaz limpia y responsiva.

## 🚀 Características
El panel se divide en dos módulos principales:

➕ Gestión de Registros
Registro de Clientes: Alta de nuevos usuarios en la base de datos.

Registro de Productos: Gestión de inventario entrante.

Registro de Ventas: Interfaz dedicada para procesar transacciones de forma rápida.

🔍 Consultas e Informes
Visualización de Datos: Tablas detalladas de clientes y productos.

Historial de Ventas: Seguimiento completo de las transacciones realizadas.

Buscador Inteligente: Filtro rápido para localizar productos específicos en el inventario.

🛠️ Tecnologías Utilizadas
PHP: Lógica del lado del servidor.

HTML5 & CSS3: Estructura y diseño moderno utilizando CSS Grid para una interfaz adaptable.

Google Fonts & Emojis: Para una experiencia de usuario visualmente intuitiva.

## 📂 Estructura del Proyecto
El archivo index.php actúa como el núcleo del sistema, conectando con los siguientes módulos (asegúrate de tenerlos creados):


 - ├── index.php                # Panel principal (Dashboard)
 - ├── registrar_cliente.php    # Formulario de alta de clientes
 - ├── registrar_producto.php   # Formulario de alta de productos
 - ├── registrar_venta.php      # Proceso de venta
 - ├── ver_clientes.php         # Listado de clientes
 - ├── ver_productos.php        # Listado de inventario
 - ├── ver_ventas.php           # Historial transaccional
 - └── buscar_producto.php      # Motor de búsqueda

 ---

## 📰 Diagramas del proyecto

### 🔷 Diagrama EER
- <img width="1280" height="430" alt="Diapositiva2" src="https://github.com/user-attachments/assets/3bdf3714-e2c1-4dae-86de-0450de5a5ec9" />

 ---

 ### 🔷 Diagrama relacional
 - <img width="1280" height="720" alt="Diapositiva3" src="https://github.com/user-attachments/assets/bb21bef3-7b9c-4751-a6e1-84d5679816d2" />

 ---

## 🎨 Vista Previa de la Interfaz
El diseño cuenta con un estilo moderno con efectos de elevación (hover) y una paleta de colores profesional:
- <img width="1280" height="720" alt="Diapositiva1" src="https://github.com/user-attachments/assets/25c494e5-ccbb-481b-8465-034dcd8c2995" />
- <img width="1280" height="720" alt="Diapositiva2" src="https://github.com/user-attachments/assets/42ce88f3-3a78-424a-bf24-e297de265c39" />
- <img width="1280" height="720" alt="Diapositiva3" src="https://github.com/user-attachments/assets/b9d30503-6760-4823-b9c4-43190f1bffb2" />
- <img width="1280" height="720" alt="Diapositiva4" src="https://github.com/user-attachments/assets/a6ce7788-13d0-408d-a0d5-3ae2f1b32971" />

🟢 Verde: Acciones positivas (Clientes).

🔵 Azul: Acciones informativas (Productos/Sistema).

🔴 Rojo: Acciones críticas o de salida (Ventas).

## Proyecto 3: fabrica de jueguetes 
Sistema de gestión para un bazar de ropa.

### Previews
- <img width="1890" height="864" alt="image" src="https://github.com/user-attachments/assets/52973b93-4d97-4bac-9279-31514caaeb16" />

- <img width="1917" height="876" alt="image" src="https://github.com/user-attachments/assets/ba7b2786-0cd9-4831-9a0d-d1fc3c86e3c3" />

- <img width="1895" height="867" alt="image" src="https://github.com/user-attachments/assets/daf218ba-7090-4eb0-b7cd-db92a39ec191" />

- <img width="1892" height="875" alt="image" src="https://github.com/user-attachments/assets/d6c23f17-4008-495f-9855-2111dc3d3927" />

### Enlaces
- [Repositorio en GitHub](https://github.com/24l3x/Proyecto-Base-de-datos)

- [Página Web](https://juguetesdars.page.gd/)


## Proyecto 2: 
---

<img width="275" height="138" alt="DOLY_LOGO-bg_white-font_black-Corporative2" src="https://github.com/user-attachments/assets/9a2b55ea-9934-446d-8e97-855ffb9eafea" />

## DOLY — Documentación del Proyecto

Última actualización: 2026-01-06

---

## Resumen ejecutivo

DOLY es una plataforma web para gestión de asistencia vial y administración de servicios relacionados con clientes, empresas y recursos (vehículos, equipos y operadores). Está construida como una aplicación monolítica en Flask con SQLAlchemy (PostgreSQL) y una capa de frontend basada en plantillas Jinja2, SCSS y JavaScript estático.

Este README ofrece una visión completa y accionable para desarrolladores, administradores y equipos de operaciones: arquitectura, guía de instalación y ejecución, estructura de carpetas, flujos principales, seguridad, despliegue y resolución de problemas.

---
### 🔗 Enlaces
---
**Código Fuente:** [Repositorio en GitHub](https://github.com/LunaEMG/bazar_ropa_project)

**Deploy:** [DOLY Logistic](https://doly-a04d1513c532.herokuapp.com/auth/login)

---

## Vista Previa de la PWA
<img width="1853" height="897" alt="image" src="https://github.com/user-attachments/assets/045bee93-c156-47c5-8a35-fe4248533db3" />
<img width="1268" height="761" alt="image" src="https://github.com/user-attachments/assets/d0bf2de4-75b9-4316-aea3-3ef05c705a92" />
<img width="462" height="429" alt="image" src="https://github.com/user-attachments/assets/b6385135-a4aa-40c1-913a-ff389dc5b05c" />


---

## Contenido

- Resumen ejecutivo
- Arquitectura
- Componentes principales
- Requisitos
- Configuración local (desarrollo)
- Ejecución y pruebas
- Despliegue
- Estructura del proyecto (resumen)
- Base de datos y ERD
- Seguridad y buenas prácticas
- Logs, monitoreo y troubleshooting
- Contribución y estilo de código
- Contacto y licencia

---

## Arquitectura (alto nivel)

- Frontend: plantillas Jinja2 + CSS (SCSS compilado) + JS estático. El navegador consume recursos estáticos y las páginas renderizadas por Flask.
- Backend: Flask (factory pattern) con Blueprints (`views`, `auth`, etc.). Lógica de negocio en controladores y modelos SQLAlchemy.
- Persistencia: PostgreSQL (esquema definido en `app/utilities/Documentation/Database/ServiceDDL.sql`).
- Utilidades/Docs: `app/utilities/Documentation/` contiene DDL, DML y diagramas ERD.
- Infraestructura: despliegue por Heroku (Procfile presente) o similar; variables sensibles vía `.env`.

---

## Componentes principales

- `app/__init__.py`: fábrica de la app y registro de blueprints.
- `app/auth.py`: registro, login, logout y control de sesiones.
- `app/views.py` / `app/views_client.py`: rutas públicas y paneles.
- `app/database.py`: inicialización de `SQLAlchemy` y utilidades de conexión.
- `app/models/`: modelos por entidad (cada archivo define una entidad, todos con `db.Model` y `@dataclass`).
- `app/templates/`: plantillas Jinja2 agrupadas por sección (auth, landpage, client, admin).
- `app/static/`: assets compilados y JS.
- `app/utilities/Documentation/Database/`: DDL, DML y ERD (Mermaid) para referencia y migraciones manuales.

---

## Requisitos

- Python 3.10+ (entorno virtual recomendado)
- PostgreSQL (o servicio compatible: Neon, ElephantSQL, etc.)
- Node.js/npm (solo si vas a compilar SCSS o usar herramientas front-end)
- Dependencias Python: ver `requirements.txt`

Instalación rápida en Bash (Windows WSL o Linux/macOS):

```bash
# crear y activar venv
python -m venv venv
source venv/Scripts/activate   # Windows bash (adapta según shell)

# instalar dependencias
pip install -r requirements.txt
```

Asegúrate de definir variables de entorno en `.env` (ejemplo en `.env.example` si existe):

- `SECRET_KEY` — clave secreta Flask
- `DATABASE_URL` — URL SQLAlchemy (p.ej. postgresql+psycopg2://user:pass@host/dbname)

---

## Configuración local (desarrollo)

1. Configura tu `.env` con `SECRET_KEY` y `DATABASE_URL`.
2. Crea la base de datos o usa la existente.
3. Ejecuta el DDL para crear tablas (opcionalmente con una herramienta de migraciones):

```bash
# desde la carpeta raíz del proyecto
psql "$DATABASE_URL" -f app/utilities/Documentation/Database/ServiceDDL.sql
```

4. Para cargar datos de ejemplo (DML):

```bash
psql "$DATABASE_URL" -f app/utilities/Documentation/Database/ServiceDML.sql
```

5. Inicia la app en modo desarrollo:

```bash
export FLASK_APP=app
export FLASK_ENV=development
flask run
```

O usando el runner incluido:

```bash
python run.py
```

---

## Ejecución y pruebas

- Tests unitarios: existen pruebas de conexión y entorno en `app/test/`. Ejecuta con `pytest` si lo tienes configurado:

```bash
pytest -q
```

- Revisión rápida de imports de modelos (útil tras cambios en modelos):

```bash
python -c "import importlib, pkgutil, sys; sys.path.append('c:/workspace/DOLY'); pkg='app.models'; m=importlib.import_module(pkg); mods=[name for _,name,_ in pkgutil.iter_modules(m.__path__)]; print(mods)"
```

---

## Despliegue

- Heroku: `Procfile` presente. Asegúrate de configurar variables de entorno en el dashboard y habilitar la conexión a la base de datos.
- Contenedores: crea un Dockerfile si prefieres contenedores; asegúrate de usar un entrypoint que ejecute `gunicorn`.

Recomendación de producción:
- Servir estáticos desde CDN o bucket (S3)
- Usar `gunicorn` detrás de un proxy (NGINX)
- Habilitar TLS/HTTPS

---

## Estructura del proyecto (resumen)

```
DOLY/
├─ app/
│  ├─ __init__.py
│  ├─ auth.py
│  ├─ database.py
│  ├─ models/ (entidades SQLAlchemy)
│  ├─ templates/
│  ├─ static/
│  └─ utilities/
└─ run.py
```

(Ver árbol completo en la raíz del repo si lo necesitas en `tree.txt`)

---

## Base de datos y ERD

- Los scripts DDL/DML están en `app/utilities/Documentation/Database/`.
- El ERD está en `app/utilities/Documentation/Database/utils/ERD.md` en formato Mermaid. Puedes pegar ese contenido en https://mermaid.live para visualizarlo.

---

## Seguridad y buenas prácticas

- Nunca subas credenciales al repositorio (.env debe estar en `.gitignore`).
- Hashea contraseñas con `werkzeug.security.generate_password_hash` (ya usado en la app).
- Valida y sanea entradas del usuario tanto en cliente como en servidor (tu app ya aplica checks y constraints en la DB).
- Usa HTTPS y HSTS en producción.
- Revisa `server_default` y `CHECK` constraints en modelos para evitar inconsistencias.

---

## Logs, monitoreo y troubleshooting

- Logs se escriben en `app/utilities/logs/data.log` y mediante `app/log_control.py`.
- Para investigar errores comunes:
  - Revisa la salida de Flask y el archivo de logs
  - Verifica que `DATABASE_URL` esté accesible desde la red donde corre la app
  - Comprueba integridad del esquema: `psql "$DATABASE_URL" -c "\d+"` para revisar tablas

---

## Contribuir

- Sigue el estilo de código del repositorio: usa `black`/`isort` si están configurados.
- Cada modelo debe vivir en su propio archivo dentro de `app/models/` con `@dataclass` y `db.Model`.
- Abre Pull Requests descriptivos y referencia issues.

---

## Contacto

- Mantenedor: equipo DOLY (repositorio: `jr-devel/doly`)
- Para incidencias: abrir issue en el repositorio o escribir a dolylogistic@gmail.com

---

## Licencia

- Este proyecto está licenciado bajo la **MIT License**. El archivo `LICENSE` se encuentra en la raíz del repositorio.
- Copyright (c) 2026 jr-devel.

---

Si quieres, genero también:
- Un `README` en inglés.
- Un `CONTRIBUTING.md` con normas de commits y PRs.
- Un `tree.txt` automático con el árbol completo del proyecto.

---

## Árbol completo del proyecto (estado actual)

```
DOLY/
├─ .gitignore
├─ Procfile
├─ run.py
├─ requirements.txt
└─ app/
  ├─ __init__.py
  ├─ auth.py
  ├─ database.py
  ├─ log_control.py
  ├─ views.py
  ├─ views_client.py
  ├─ test/
  │  ├─ test_env.py
  │  └─ test_conn.py
  ├─ models/
  │  ├─ AuditLog.py
  │  ├─ Assistance.py
  │  ├─ Client.py
  │  ├─ ClientType.py
  │  ├─ Client_Vehicle.py
  │  ├─ Communication.py
  │  ├─ Company.py
  │  ├─ Company_Employee.py
  │  ├─ Discount.py
  │  ├─ Employee.py
  │  ├─ EmployeeType.py
  │  ├─ Evidence.py
  │  ├─ Invoice.py
  │  ├─ MaintenanceLog.py
  │  ├─ Notification.py
  │  ├─ Payment.py
  │  ├─ Persona.py
  │  ├─ Resource.py
  │  ├─ Resource_Company.py
  │  ├─ ResourceType.py
  │  ├─ Review.py
  │  ├─ Service.py
  │  ├─ ServiceType.py
  │  ├─ Service_Discount.py
  │  ├─ Session.py
  │  ├─ Settings.py
  │  ├─ Status.py
  │  ├─ SubResourceType.py
  │  ├─ Tracking.py
  │  ├─ UserAccount.py
  │  ├─ Vehicle.py
  │  └─ VehicleType.py
  ├─ templates/
  │  ├─ base.html
  │  ├─ header.html
  │  ├─ footer.html
  ├─ templates/admin/
  │  └─ index.html
  ├─ templates/auth/
  │  ├─ login.html
  │  └─ signup.html
  ├─ templates/client/
  │  └─ dashboard.html
  ├─ templates/landpage/
  │  ├─ index.html
  │  ├─ about.html
  │  ├─ contact.html
  │  ├─ help.html
  │  └─ services.html
  ├─ static/
  │  ├─ manifest.json
  │  ├─ css/
  │  │  └─ style.min.css
  │  ├─ js/
  │  │  ├─ app.js
  │  │  ├─ modernizr.js
  │  │  └─ sw.js
  │  └─ img/
  │     └─ logos/
  │        ├─ DOLY_LOGO-extended.png
  │        ├─ DOLY_LOGO-bg_white-font_orange.png
  │        ├─ DOLY_LOGO-bg_white-font_orange_square.png
  │        ├─ DOLY_LOGO-bg_orange-font_black.png
  │        ├─ DOLY_LOGO-bg_orange-font_black_square.png
  │        ├─ DOLY_LOGO-bg_black-font_orange.png
  │        ├─ DOLY_LOGO-bg_black-font_orange_square.png
  │        ├─ DOLY_LOGO-bg_aqua-font_orange.png
  │        ├─ DOLY_LOGO-bg_aqua-font_orange_square.png
  │        └─ ico/
  │           ├─ DOLY_LOGO-extended.ico
  │           ├─ DOLY_LOGO-bg_white-font_orange.ico
  │           ├─ DOLY_LOGO-bg_orange-font_black.ico
  │           ├─ DOLY_LOGO-bg_black-font_orange.ico
  │           └─ DOLY_LOGO-bg_aqua-font_orange.ico
  └─ utilities/
    └─ logs/
      └─ data.log
```

## Proyecto 4: 

### 🛠️ Tecnologías
* **Backend:** JavaScript con Prisma (ORM).
* **Base de Datos:** SupaBase (PostgreSQL).
* **Frontend:** Render con HTML con JavaScript.

### 🖼️ Previews
- <img width="1920" height="998" alt="cap1" src="https://github.com/user-attachments/assets/21ba206c-453e-4d6e-aa84-e4c5e69d8836" />

- <img width="1920" height="946" alt="cap2" src="https://github.com/user-attachments/assets/2fdbd6a4-4a2b-459e-a2f4-1c17eb5ff7c2" />

- <img width="1920" height="949" alt="cap3" src="https://github.com/user-attachments/assets/2cab073c-523e-4c55-9b6a-4984e0cf2dd1" />

- <img width="1920" height="1000" alt="cap4" src="https://github.com/user-attachments/assets/9bd10ce4-8bd6-4bc7-a1a8-d12d8aae531f" />

### 🔗 Enlaces
**Código en Github:** [Repositorio en GitHub](https://github.com/GabrielEC9/proyecto_BD_practica31)

**Pagina Web** [Bazar Ropa Web](https://proyecto-bd-practica31.onrender.com/login.html)
