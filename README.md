# [NOMBRE DEL PROYECTO]
Equipo TIKI, Base de Datos II (6 ciclo), UNJBG.

## 📌 Qué es
[NO DEFINIDO] es una plataforma web colaborativa enfocada en [NO DEFINIDO]. El objetivo principal de este repositorio es el diseño, implementación y consumo de la base de datos centralizada alojada en un servidor homelab para la asignatura de BD II.

## 🏗️ Estructura del Proyecto
El repositorio sigue una arquitectura modular separando la documentación, el código fuente y los scripts de la base de datos:

*   **`docs/`**: Documentación técnica (arquitectura, contratos de API, procesos semanales).
*   **`src/`**: Código fuente de la aplicación.
    *   `frontend/`: Interfaz de usuario, módulos y componentes compartidos.
    *   `backend/`: Lógica del servidor, configuración y controladores organizados por módulos.
*   **`base-datos/`**: Scripts fundamentales para la asignatura.
    *   `estructura.sql`: DDL de la base de datos (creación de tablas, relaciones, índices y vistas).
    *   `datos-prueba.sql`: DML para poblar la base de datos con información inicial/semilla.
*   **`pruebas/`**: Scripts de pruebas de integración.

## 🚀 Cómo se levanta (Entorno Local/Homelab)
*Pendiente hasta que se defina el stack tecnológico y exista código ejecutable.* 

## 🤝 Reglas de Colaboración (Git)
Para asegurar la integridad del código en este proyecto colaborativo, aplicamos las siguientes reglas:
*   **Prohibido el push directo:** No se pueden hacer commits directamente a las ramas `main` o `develop`.
*   **Ramas de trabajo:** Toda nueva característica o script de base de datos debe trabajarse en una rama separada.
*   **Pull Requests (PR):** Los cambios se integran a `develop` únicamente mediante PRs revisados por al menos un compañero de equipo.

## 👥 Integrantes
*   Alex Jeanpier Chata Chino - [Administración del repositorio ...]
*   [Nombre del Integrante 2] - [Rol en el equipo]
*   [Nombre del Integrante 3] - [Rol en el equipo]