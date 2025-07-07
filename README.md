# 🧠 Proyecto para prueba de Desarrollador Mid

Este repositorio agrupa el frontend y backend desarrollados como parte de la prueba técnica para la posición de desarrollador.  
El sistema implementa un **registro escolar** con operaciones CRUD y validaciones.

---

## 📁 Estructura del proyecto

Este repositorio contiene enlaces directos a los dos subproyectos:

- 🔗 [Frontend (Angular)](https://github.com/DarcherDev/sre-frontend.git)
- 🔗 [Backend (Spring Boot)](https://github.com/DarcherDev/sre-backend.git)

---

## 🚀 Tecnologías usadas

| Capa       | Tecnologías                                                   |
|------------|---------------------------------------------------------------|
| Frontend   | Angular 16.2.16, Angular CLI, TypeScript, Angular Material     |
| Backend    | Java 21, Spring Boot 3.3.2, PostgreSQL, Flyway, Swagger        |
| Contenedores | Docker, Docker Compose                                      |

---

## ⚙️ ¿Cómo ejecutar el proyecto?

### 🐳: ejecutar todo Docker 

> Asegúrate de tener [Docker](https://docs.docker.com/get-docker/) instalado.

Desde la raíz del repositorio clonado (`sistema-registro-escolar-mid/`), ejecuta:

si maneja linux en bash remplazar ```start``` con ```xdg-open``` en el bash

```bash
docker-compose up --build -d && start http://localhost:4200/
