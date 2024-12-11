# Aplicacion Proyectos
¡Bienvenido a la Aplicación de Gestión de Proyectos! Este software está diseñado para gestionar proyectos, tareas y flujos de trabajo de forma eficiente. Incluye autenticación segura, vistas interactivas (como Kanban), y características avanzadas para equipos y usuarios individuales.

Tabla de Contenidos
	1.	Descripción
	2.	Características
	3.	Tecnologías Utilizadas
	4.	Instalación
	5.	Uso
	6.	Estructura del Proyecto
	7.	Endpoints del Backend
	8.	Contribuciones
	9.	Licencia

Descripción

La Aplicación de Gestión de Proyectos permite a los usuarios:
	•	Crear y gestionar proyectos.
	•	Organizar tareas en vistas Kanban.
	•	Colaborar en equipo mediante asignación de roles.
	•	Visualizar estadísticas de progreso y plazos.

Esta herramienta es ideal para equipos pequeños y medianos que buscan optimizar sus procesos.

Características
	•	Autenticación segura: Registro e inicio de sesión con contraseñas encriptadas y tokens JWT.
	•	Gestión de proyectos: Crear, actualizar y eliminar proyectos.
	•	Vista Kanban: Organiza las tareas por estado (Pendiente, En Progreso, Completada).
	•	Panel de control: Estadísticas de progreso y plazos de entrega.
	•	Escalable y seguro: Implementado con Node.js, PostgreSQL y Docker.


 Tecnologías Utilizadas
	•	Backend:
	•	Node.js + Express.js
	•	PostgreSQL + Sequelize
	•	bcrypt (para encriptación de contraseñas)
	•	JSON Web Tokens (JWT)
	•	Infraestructura:
	•	Docker (para despliegues consistentes)
	•	NGINX (como servidor proxy)
	•	Validación y Seguridad:
	•	Joi (validación de datos)
	•	Helmet (seguridad de cabeceras HTTP)
	•	Frontend (opcional si está implementado):
	•	React.js con Material-UI

 Instalación

Requisitos previos
	1.	Node.js y npm instalados: Descargar Node.js
	2.	PostgreSQL instalado: Instalar PostgreSQL
	3.	Docker (opcional): Instalar Docker
