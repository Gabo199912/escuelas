# 🎓 Sistema de Gestión Escolar

🚀 **Aplicación web para la administración académica de centros educativos**, diseñada para centralizar los procesos de inscripción, gestión de estudiantes, asignación de cursos, registro de calificaciones y generación de boletas.

El sistema busca facilitar el trabajo administrativo y docente mediante una plataforma organizada, segura y accesible desde dispositivos móviles.

> 🚧 **Estado del proyecto:** En desarrollo. Proyecto personal orientado a aplicar buenas prácticas de ingeniería de software y arquitectura de aplicaciones.

---

## ✨ Funcionalidades principales

### 🔐 Seguridad y usuarios
- Inicio de sesión con autenticación y autorización mediante roles.
- Gestión de usuarios: administrador, director, maestro y secretaría.
- Un usuario puede tener múltiples roles y sus permisos se complementan.
- Control de acceso según las responsabilidades de cada usuario.

### 🏫 Gestión académica
- Administración de ciclos escolares.
- Gestión de grados, especialidades y secciones.
- Administración de cursos y asignaturas.
- Inscripción de alumnos por ciclo escolar y clase.
- Asignación de maestros a sus respectivas clases.

### 📚 Gestión de calificaciones
- Registro de notas por bimestre (de 0 a 100 puntos).
- Control de ingreso de notas según las clases asignadas a cada maestro.
- Cálculo automático de promedios con redondeo `HALF_UP`.
- Regla de aprobación establecida en 60 puntos.
- Cierre de bimestres.
- Correcciones de notas con justificación obligatoria.

### 📊 Reportes y seguimiento
- Generación de boletas de calificaciones en PDF.
- Exportación de listados y reportes a Excel.
- Consulta del rendimiento académico de los estudiantes.
- Historial de modificaciones y auditoría de cambios.

### 📱 Accesibilidad
- Interfaz web adaptable a dispositivos móviles.
- Acceso desde diferentes dispositivos mediante conexión a internet.

### 🔔 Funcionalidades adicionales (opcionales)
- Notificaciones mediante Telegram.
- Control y seguimiento de cobros escolares.

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Aplicación |
|---|---|
| ☕ Java 21 | Lenguaje de programación principal |
| 🍃 Spring Boot | Desarrollo del backend |
| 🔒 Spring Security | Autenticación y autorización |
| ⚛️ React | Desarrollo del frontend |
| 🐘 PostgreSQL | Sistema gestor de base de datos |
| 🛠️ Flyway | Control de versiones y migraciones de BD |
| 📦 Maven | Gestión de dependencias y construcción |

---

## 🗄️ Arquitectura y base de datos

La estructura de la base de datos se desarrolla de manera incremental mediante **migraciones con Flyway**, permitiendo mantener un control organizado de los cambios en el esquema.

Los módulos de base de datos contemplados son:

1. 🔐 Seguridad y gestión de usuarios.
2. 📝 Auditoría e historial de cambios.
3. 🏫 Estructura académica.
4. 👨‍🎓 Inscripción de estudiantes.
5. 📚 Cursos y asignaciones docentes.
6. 📊 Registro de notas y promedios.
7. 📄 Generación de boletas y reportes.

---

## 📌 Estado del desarrollo

El proyecto se organiza en fases para facilitar su planificación, implementación y seguimiento.

| Fase | Descripción | Estado |
|---|---|---|
| 0️⃣ | Preparación del entorno y planificación | ⏳ Pendiente |
| 1️⃣ | Login, usuarios e inscripción | ⏳ Pendiente |
| 2️⃣ | Registro de notas, promedios y boletas | ⏳ Pendiente |
| 3️⃣ | Telegram, cobros y funcionalidades adicionales | ⏳ Pendiente |

---

## 🎯 Objetivos del proyecto

- Aplicar principios de programación orientada a objetos.
- Implementar una arquitectura organizada y mantenible.
- Diseñar una base de datos relacional normalizada.
- Aplicar buenas prácticas de seguridad y control de acceso.
- Implementar auditoría para garantizar la trazabilidad de los cambios.
- Desarrollar una API REST para la comunicación entre frontend y backend.
- Construir una aplicación escalable y preparada para futuras funcionalidades.

---

## ⚠️ Aviso

Este proyecto se encuentra en desarrollo y tiene fines personales y educativos.

Los datos utilizados para pruebas y demostraciones son completamente ficticios. Este repositorio no contiene información real de estudiantes, docentes, encargados ni instituciones educativas.

---

## 👨‍💻 Autor

**Angel Gabriel Vásquez Argueta**

Desarrollador de software interesado en el desarrollo backend, bases de datos, arquitectura de software y tecnologías web.

