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

## ⚙️ Cómo ejecutar el proyecto

### 🐳 Opción 1: Levantar todo con Docker

> Asegúrate de tener Docker instalado en tu máquina.

```bash
# Clona el repositorio backend
git clone https://github.com/DarcherDev/sre-backend.git
cd sre-backend

# Levanta los servicios
docker-compose up --build -d

# Clona el repositorio frontend
cd..
git clone https://github.com/DarcherDev/sre-frontend.git
cd sre-frontend

# Instala Angular CLI (si no lo tienes)
npm install -g @angular/cli@16

# Instala dependencias
npm install

# Corre la aplicación
npm start   # o bien: ng serve -o

