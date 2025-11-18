# 🚀 PROPUESTAS DE PROYECTOS INTERMODULARES - 2º DAW
## Versión Simplificada para Nivel Intermedio

## 📋 Índice de Proyectos

1. **TaskManager Pro** - Sistema de gestión de tareas para equipos
2. **BiblioTech** - Sistema de gestión bibliotecaria digital
3. **EventosLocal** - Plataforma de eventos comunitarios
4. **TiendaOnline** - E-commerce básico para pequeños negocios
5. **RecetasFáciles** - Red social de recetas de cocina
6. **FitnessTracker** - Aplicación de seguimiento deportivo básico

## 🎯 **Especificaciones Técnicas Unificadas**
- **Duración:** 7 meses (27 semanas, 5-7h/semana = 135-189h total)
- **Sprints:** 9 sprints de 3 semanas cada uno (15-21h por sprint)
- **Evolución tecnológica:**
  - **Sprints 1-2:** HTML5, CSS3, JavaScript, PHP vanilla, MySQL básico
  - **Sprints 3-4:** Introducción Laravel (instalación, rutas, vistas)
  - **Sprints 5-7:** Laravel intermedio (modelos, controladores, Eloquent)
  - **Sprints 8-9:** Laravel avanzado, Docker, despliegue
- **Base de datos:** MySQL con phpMyAdmin → Eloquent ORM
- **Control de versiones:** Git + GitHub (introducido gradualmente)

---

## 🎯 **Resultados de Aprendizaje (RA) y Criterios de Evaluación**

### **RA1. Identifica necesidades del sector productivo, relacionándolas con proyectos tipo que las puedan satisfacer.**

**Criterios de evaluación:**
a) Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen.  
b) Se han caracterizado las empresas tipo indicando la estructura organizativa y las funciones de cada departamento.  
c) Se han identificado las necesidades más demandadas a las empresas.  
d) Se han valorado las oportunidades de negocio previsibles en el sector.  
e) Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas.  
f) Se han determinado las características específicas requeridas al proyecto.  
g) Se han determinado las obligaciones fiscales, laborales y de prevención de riesgos y sus condiciones de aplicación.  
h) Se han identificado posibles ayudas o subvenciones para la incorporación de nuevas tecnologías de producción o de servicio que se proponen.  
i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto.

---

### **RA2. Diseña proyectos relacionados con las competencias expresadas en el título, incluyendo y desarrollando las fases que lo componen.**

**Criterios de evaluación:**
a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto.  
b) Se ha realizado el estudio de viabilidad técnica del mismo.  
c) Se han identificado las fases o partes que componen el proyecto y su contenido.  
d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance.  
e) Se han previsto los recursos materiales y personales necesarios para realizarlo.  
f) Se ha realizado el presupuesto económico correspondiente.  
g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo.  
h) Se ha definido y elaborado la documentación necesaria para su diseño.  
i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto.


---

### **RA3. Planifica la ejecución del proyecto, determinando el plan de intervención y la documentación asociada.**

**Criterios de evaluación:**
a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución.  
b) Se han determinado los recursos y la logística necesarios para cada actividad.  
c) Se han identificado las necesidades de permisos y autorizaciones para llevar a cabo las actividades.  
d) Se han determinado los procedimientos de actuación o ejecución de las actividades.  
e) Se han identificado los riesgos inherentes a la ejecución definiendo el plan de prevención de riesgos y los medios y equipos necesarios.  
f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución.  
g) Se ha hecho la valoración económica que da respuesta a las condiciones de la implementación.  
h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución.

---

### **RA4. Define los procedimientos para el seguimiento y control en la ejecución del proyecto, justificando la selección de variables e instrumentos empleados.**

**Criterios de evaluación:**
a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones.  
b) Se han definido los indicadores de calidad para realizar la evaluación.  
c) Se ha definido el procedimiento para la evaluación de las incidencias que puedan presentarse durante la realización de las actividades, su posible solución y registro.  
d) Se ha definido el procedimiento para gestionar los posibles cambios en los recursos y en las actividades, incluyendo el sistema de registro de los mismos.  
e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto.  
f) Se ha establecido el procedimiento para la participación en la evaluación de los usuarios o clientes y se han elaborado los documentos específicos.  
g) Se ha establecido un sistema para garantizar el cumplimiento del pliego de condiciones del proyecto cuando este existe.

---

## Proyecto 1 – TaskManager Pro

**Descripción:** Sistema web para gestión de tareas y proyectos en equipos pequeños, con funcionalidades básicas de asignación, seguimiento de estado y comentarios colaborativos.

**Objetivo:** Crear una herramienta sencilla que permita organizar el trabajo en equipo, asignar tareas y hacer seguimiento del progreso de proyectos.

**Características funcionales principales:**
- Sistema de registro y login de usuarios
- CRUD de proyectos y tareas
- Asignación de tareas a usuarios
- Estados de tareas (pendiente, en progreso, completada)
- Sistema de comentarios en tareas
- Dashboard básico con estadísticas
- Notificaciones por email (básicas)
- Búsqueda y filtrado de tareas

**Tecnologías:**
- **Backend:** Laravel 10 con Blade Templates
- **Frontend:** HTML5, CSS3, JavaScript Vanilla, Bootstrap 5
- **Base de datos:** MySQL 8.0 con Eloquent ORM
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions básico
- **Adicionales:** Laravel Mail, Middleware de autenticación

**Módulos DAW implicados:**
- **PROG:** Lógica de negocio básica, algoritmos de filtrado
- **LMSGI:** Formularios HTML, estructura semántica
- **BBDD:** Relaciones 1:N y N:M básicas, consultas Eloquent
- **DWES:** MVC con Laravel, autenticación, middleware
- **DWEC:** Interactividad con JavaScript, validaciones cliente
- **DIW:** Responsive design con Bootstrap, UX básica
- **SI:** Configuración básica de servidor, seguridad web
- **DAW:** Containerización básica, automatización
- **EDE:** Git workflow, debugging, testing básico

**Criterios de evaluación predominantes:**
- **RA1:** Análisis de requisitos simples, diseño MVC básico
- **RA2:** Desarrollo CRUD completo, buenas prácticas Laravel
- **RA3:** Interfaz funcional y responsive
- **RA4:** Despliegue con Docker básico
- **RA5:** Testing manual y unitario básico
- **RA6:** Documentación clara y defensa técnica

### 🗓️ Sprint Planning - TaskManager Pro (7 meses)

### 🗓️ Sprint Planning - TaskManager Pro (7 meses - Progresión Gradual)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R gestor tareas completo |
| 4–6 | Sprint 2 | Maquetación frontend tareas | HTML5, CSS3, Bootstrap, JS | T4, T5, T6 | Interfaz estática completa con tareas JS dinámicas |
| 7–9 | Sprint 3 | Backend PHP y base de datos | PHP, MySQL, PDO | T7, T8, T9 | CRUD tareas funcional con PHP vanilla |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Eloquent | T10, T11, T12 | Proyecto Laravel con vistas Blade y modelos |
| 13–15 | Sprint 5 | Eloquent y validaciones | Laravel ORM, Form Requests | T13, T14, T15 | Sistema completo con Eloquent y validaciones |
| 16–18 | Sprint 6 | Autenticación y roles | Laravel Auth, Middleware | T16, T17, T18 | Sistema login con roles y features avanzadas |
| 19–21 | Sprint 7 | Optimización y UX | AJAX, Laravel + JavaScript | T19, T20, T21 | Aplicación optimizada con AJAX |
| 22–24 | Sprint 8 | Testing y calidad | PHPUnit, Laravel Debugbar | T22, T23 | Testing implementado y optimizado |
| 25–27 | Sprint 9 | Dockerización y despliegue | Docker, Docker Compose | T24 | Aplicación contenerizada y desplegada |

### 📊 Relación Sprints con RA y Criterios de Evaluación - TaskManager Pro

| Sprint | RA Principal | Criterios de Evaluación | Entregables Clave |
|--------|--------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | c) Se han identificado las necesidades más demandadas a las empresas, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis sector gestión tareas, wireframes, maquetas HTML estáticas |
| **Sprint 2** | RA3 | a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Frontend interactivo con DOM, simulación datos JS |
| **Sprint 3** | RA2 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, b) Se ha realizado el estudio de viabilidad técnica del mismo | Backend PHP básico, modelo datos, scripts MySQL |
| **Sprint 4** | RA2 | c) Se han identificado las fases o partes que componen el proyecto y su contenido, h) Se ha definido y elaborado la documentación necesaria para su diseño | Migración Laravel, estructura MVC, documentación técnica |
| **Sprint 5** | RA2 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto | Sistema Eloquent completo, validaciones, calidad código |
| **Sprint 6** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Sistema Auth, panel administración, features avanzadas |
| **Sprint 7** | RA3 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución | Optimización UX, interactividad avanzada, cronograma |
| **Sprint 8** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, b) Se han definido los indicadores de calidad para realizar la evaluación | Testing funcional, métricas implementadas, depuración |
| **Sprint 9** | RA4 | e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto, f) Se ha establecido el procedimiento para la participación en la evaluación de los usuarios o clientes | Despliegue Docker, documentación final, evaluación |

### 📋 Product Backlog Detallado - TaskManager Pro (Progresión Tecnológica)

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis requisitos gestor tareas | Estudio flujos trabajo: proyectos, tareas, equipos, asignaciones | Sprint 1 | 4h | Alta |
| T2 | Wireframes gestor tareas | Diseño mockups: dashboard, lista tareas, kanban, formularios | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R proyectos | Diagrama E/R: proyectos, tareas, usuarios, equipos, asignaciones | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML tareas | HTML semántico: dashboard, kanban, lista tareas, formularios | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS gestor | CSS Bootstrap: dashboard, cards tareas, kanban responsive | Sprint 2 | 6h | Alta |
| T6 | JavaScript tareas dinámicas | Kanban interactivo JS, drag & drop, LocalStorage simulado | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL tareas | Creación tablas: proyectos, tareas, usuarios, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP tareas | Scripts PHP para gestión tareas: crear, listar, editar, eliminar | Sprint 3 | 6h | Alta |
| T9 | Asignaciones PHP | Lógica PHP: asignar tareas, cambiar estados, integración frontend | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel | Setup Laravel, configuración básica, estructura proyecto | Sprint 4 | 6h | Alta |
| T11 | Rutas y controladores | Definir rutas, controladores básicos, estructura MVC | Sprint 4 | 6h | Alta |
| T12 | Vistas Blade | Migrar HTML a plantillas Blade, layouts, componentes | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent | Crear modelos, migrations, relaciones básicas | Sprint 5 | 6h | Alta |
| T14 | CRUD con Eloquent | Reescribir CRUD usando Eloquent ORM | Sprint 5 | 6h | Alta |
| T15 | Validaciones Laravel | Form requests, validaciones backend, mensajes error | Sprint 5 | 6h | Media |
| T16 | Autenticación Laravel | Sistema login/logout con Laravel Auth | Sprint 6 | 6h | Alta |
| T17 | Roles y permisos | Middleware, roles usuario, control acceso | Sprint 6 | 6h | Media |
| T18 | Funcionalidades avanzadas | Comentarios, asignaciones, dashboard con métricas | Sprint 6 | 6h | Media |
| T19 | AJAX y mejoras UX | Peticiones asíncronas, updates sin reload | Sprint 7 | 6h | Media |
| T20 | Optimización frontend | Responsive final, UX/UI pulido, accesibilidad | Sprint 7 | 6h | Alta |
| T21 | Notificaciones y dashboard | Sistema notificaciones, métricas avanzadas dashboard | Sprint 7 | 6h | Media |
| T22 | Testing básico | Tests unitarios modelos, tests funcionales rutas | Sprint 8 | 8h | Media |
| T23 | Debugging y calidad | Corrección bugs, logging, optimización queries | Sprint 8 | 10h | Media |
| T24 | Docker y despliegue | Dockerfile, docker-compose, containerización y despliegue | Sprint 9 | 18h | Alta |

---

## Proyecto 2 – BiblioTech

**Descripción:** Sistema de gestión bibliotecaria digital que permite catalogar libros, gestionar préstamos, reservas y usuarios de biblioteca de forma sencilla e intuitiva.

**Objetivo:** Digitalizar la gestión básica de una biblioteca pequeña, facilitando el control de inventario de libros y préstamos a usuarios.

**Características funcionales principales:**
- Gestión de usuarios (bibliotecarios y lectores)
- Catálogo de libros con búsqueda básica
- Sistema de préstamos y devoluciones
- Reservas de libros disponibles
- Historial de préstamos por usuario
- Control de fechas límite y multas básicas
- Reportes simples de actividad
- Panel de administración básico

**Tecnologías:**
- **Backend:** Laravel 10 con Blade + AJAX básico
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Base de datos:** MySQL 8.0
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Adicionales:** Carbon para fechas, Laravel Notifications

**Módulos DAW implicados:**
- **PROG:** Lógica de préstamos, cálculo de multas
- **LMSGI:** Formularios, estructura de datos
- **BBDD:** Relaciones complejas, consultas de reportes
- **DWES:** CRUD avanzado, cálculos de fechas
- **DWEC:** Búsqueda dinámica, confirmaciones
- **DIW:** Interfaz bibliotecaria amigable
- **SI:** Gestión de usuarios, permisos
- **DAW:** Automatización de despliegue
- **EDE:** Testing de lógica de negocio

### 🗓️ Sprint Planning - BiblioTech (7 meses - Progresión Gradual)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R biblioteca completo |
| 4–6 | Sprint 2 | Frontend HTML/CSS/JS catálogo | HTML5, CSS3, Bootstrap, JavaScript | T4, T5, T6 | Catálogo interactivo estático con JS |
| 7–9 | Sprint 3 | Backend PHP y base datos | PHP, MySQL, PDO | T7, T8, T9 | CRUD PHP funcional con MySQL |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Artisan | T10, T11, T12 | Proyecto migrado a Laravel MVC |
| 13–15 | Sprint 5 | Modelos Eloquent y préstamos | Eloquent ORM, Migrations | T13, T14, T15 | Sistema préstamos con Eloquent |
| 16–18 | Sprint 6 | Autenticación y funcionalidades | Laravel Auth, Middleware | T16, T17, T18 | Sistema completo autenticado |
| 19–21 | Sprint 7 | Optimización y reportes | Ajax, Chart.js | T19, T20 | UX optimizada, estadísticas |
| 22–24 | Sprint 8 | Testing y calidad | PHPUnit, Debugging | T21, T22 | Tests implementados, bugs corregidos |
| 25–27 | Sprint 9 | Despliegue y documentación | Docker, Docker Compose | T23, T24 | Aplicación desplegada, documentación |

### 📊 Relación Sprints con RA y Criterios de Evaluación - BiblioTech

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | c) Se han identificado las necesidades más demandadas a las empresas, f) Se han determinado las características específicas requeridas al proyecto, i) Se ha elaborado el guión de trabajo | Análisis procesos bibliotecarios, wireframes UI, modelo E/R completo |
| **Sprint 2** | RA2 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Frontend HTML/CSS/JS interactivo, catálogo con búsqueda dinámica |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto | Backend PHP funcional, base datos MySQL, CRUD operativo |
| **Sprint 4** | RA2 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, h) Se ha definido y elaborado la documentación necesaria | Proyecto Laravel estructurado, rutas y vistas Blade |
| **Sprint 5** | RA2 | e) Se han previsto los recursos materiales y personales necesarios, i) Se han identificado los aspectos de calidad del proyecto | Modelos Eloquent, sistema préstamos y devoluciones |
| **Sprint 6** | RA2, RA3 | f) Se ha realizado el presupuesto económico, a) Se han secuenciado las actividades ordenándolas en función de las necesidades | Autenticación, sistema reservas, búsqueda avanzada |
| **Sprint 7** | RA3 | b) Se han determinado los recursos y la logística necesarios, h) Se ha definido y elaborado la documentación de implementación | Reportes estadísticos, UX optimizada responsive |
| **Sprint 8** | RA4 | a) Se ha definido el procedimiento de evaluación, b) Se han definido los indicadores de calidad | Tests implementados, debugging completado |
| **Sprint 9** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Sistema biblioteca productivo, manual bibliotecario completo |

### 📋 Product Backlog Detallado - BiblioTech

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis procesos bibliotecarios | Estudio workflows biblioteca: préstamos, devoluciones, catalogación | Sprint 1 | 4h | Alta |
| T2 | Wireframes y diseño UI | Diseño mockups: catálogo, préstamos, panel admin con Figma/Balsamiq | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R biblioteca | Diagrama E/R: libros, usuarios, préstamos, multas, reservas | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML catálogo | Estructura HTML semántica: listado libros, detalle, búsqueda | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS biblioteca | CSS Bootstrap responsive: cards libros, tablas, formularios | Sprint 2 | 6h | Alta |
| T6 | JavaScript búsqueda | Filtrado dinámico catálogo, ordenación, simulación datos JS | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL | Creación tablas MySQL, relaciones, índices, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP libros | Scripts PHP para Create, Read, Update, Delete libros con PDO | Sprint 3 | 6h | Alta |
| T9 | Conexión frontend-backend | Integración formularios HTML con scripts PHP, validaciones | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel | Setup Laravel, configuración .env, estructura proyecto biblioteca | Sprint 4 | 4h | Alta |
| T11 | Migración a Blade | Convertir HTML a plantillas Blade, layouts, componentes catálogo | Sprint 4 | 8h | Alta |
| T12 | Rutas y controladores | Rutas RESTful libros, controladores LibroController, UserController | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent | Modelos Libro, Usuario, Prestamo con relaciones y validaciones | Sprint 5 | 6h | Alta |
| T14 | Sistema préstamos | Lógica préstamos Eloquent: disponibilidad, registro, devolución | Sprint 5 | 8h | Alta |
| T15 | Cálculo multas | Algoritmo multas: días retraso × tarifa, gestión pagos | Sprint 5 | 4h | Media |
| T16 | Autenticación Laravel | Laravel Breeze, login bibliotecario/socio, roles permisos | Sprint 6 | 8h | Alta |
| T17 | Sistema reservas | Reservas libros no disponibles, notificaciones disponibilidad | Sprint 6 | 6h | Media |
| T18 | Búsqueda avanzada | Búsqueda por título, autor, ISBN, filtros Ajax disponibilidad | Sprint 6 | 4h | Media |
| T19 | Reportes estadísticas | Estadísticas: libros prestados, usuarios activos, multas | Sprint 7 | 8h | Media |
| T20 | Optimización UX | Mejoras responsive, accesibilidad, navegación intuitiva | Sprint 7 | 8h | Alta |
| T21 | Testing biblioteca | Tests unitarios préstamos, multas, validaciones PHPUnit | Sprint 8 | 8h | Media |
| T22 | Debugging y calidad | Corrección bugs, logging, optimización queries biblioteca | Sprint 8 | 8h | Media |
| T23 | Docker biblioteca | Dockerfile, docker-compose, containerización sistema | Sprint 9 | 8h | Alta |
| T24 | Documentación final | Manual bibliotecario, guía usuarios, procesos gestión | Sprint 9 | 8h | Media |
| **Documentación** | Manual bibliotecario | Documentación | 8h | Media |

---

## Proyecto 3 – EventosLocal

**Descripción:** Plataforma web para la gestión y promoción de eventos comunitarios locales, donde organizadores pueden publicar eventos y usuarios pueden buscar y apuntarse a actividades de su zona.

**Objetivo:** Facilitar la organización y difusión de eventos locales, mejorando la participación ciudadana en actividades comunitarias.

**Características funcionales principales:**
- Registro de organizadores y participantes
- Creación y gestión de eventos
- Inscripción a eventos con límite de plazas
- Calendario de eventos
- Búsqueda por categoría y fecha
- Sistema de valoraciones básico
- Notificaciones de eventos próximos
- Mapa básico de ubicaciones

**Tecnologías:**
- **Backend:** Laravel 10 con Eloquent
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Base de datos:** MySQL 8.0
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Adicionales:** Google Maps API básica, Laravel Events

**Módulos DAW implicados:**
- **PROG:** Lógica de inscripciones, validaciones
- **LMSGI:** Formularios de eventos, estructura
- **BBDD:** Relaciones eventos-usuarios
- **DWES:** Gestión de archivos, API externa
- **DWEC:** Calendario interactivo, mapas
- **DIW:** UX para eventos, galería de imágenes
- **SI:** Gestión de archivos multimedia
- **DAW:** Despliegue automatizado
- **EDE:** Testing de flujos de usuario

### 🗓️ Sprint Planning - EventosLocal (7 meses)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|--------------------|-----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R eventos completo |
| 4–6 | Sprint 2 | Maquetación frontend eventos | HTML5, CSS3, Bootstrap, JS | T4, T5, T6 | Interfaz estática completa con calendario interactivo |
| 7–9 | Sprint 3 | Backend PHP y base de datos | PHP, MySQL, PDO | T7, T8, T9 | CRUD eventos funcional con inscripciones |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Eloquent | T10, T11, T12 | Proyecto Laravel con vistas Blade y modelos |
| 13–15 | Sprint 5 | Autenticación y roles | Laravel Auth, Gates/Policies | T13, T14, T15 | Sistema login con roles organizador/asistente |
| 16–18 | Sprint 6 | Búsqueda, filtros y mapa | Laravel Query Builder, Google Maps API | T16, T17, T18 | Búsqueda avanzada y geolocalización eventos |
| 19–21 | Sprint 7 | Multimedia y notificaciones | Storage, Mailable, Cron | T19, T20, T21 | Imágenes eventos y avisos automáticos |
| 22–24 | Sprint 8 | Optimización y testing | PHPUnit, Laravel Debugbar | T22, T23 | Tests unitarios y rendimiento optimizado |
| 25–27 | Sprint 9 | Dockerización y despliegue | Docker, Docker Compose | T24 | Aplicación contenerizada y desplegada |

### 📊 Relación Sprints con RA y Criterios de Evaluación - EventosLocal

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | d) Se han identificado las necesidades más demandadas para el sector productivo, e) Se han identificado las características específicas del proyecto, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis tipos eventos locales, wireframes UI, modelo E/R completo |
| **Sprint 2** | RA1, RA2 | f) Se han determinado los aspectos que se deben incluir en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Maquetación HTML completa, estilos CSS responsivos, calendario JS funcional |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto y su contenido | Base datos MySQL, CRUD PHP eventos, sistema inscripciones PHP |
| **Sprint 4** | RA2, RA3 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Proyecto Laravel configurado, vistas Blade, modelos Eloquent |
| **Sprint 5** | RA2, RA3 | i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto, d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance | Sistema autenticación, middleware roles, políticas acceso |
| **Sprint 6** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Búsqueda avanzada, filtros múltiples, Google Maps integrado |
| **Sprint 7** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, c) Se han identificado las necesidades de permisos y autorizaciones para llevar a cabo las actividades | Gestión imágenes eventos, notificaciones email, valoraciones |
| **Sprint 8** | RA3, RA4 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones | Tests unitarios PHPUnit, optimización rendimiento, debugging |
| **Sprint 9** | RA4 | c) Se han aplicado indicadores de calidad a las actividades diseñadas en el proyecto, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Dockerfile, docker-compose.yml, aplicación desplegada productiva |

### 📋 Product Backlog Detallado - EventosLocal

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis eventos comunitarios | Estudio tipos eventos locales: culturales, deportivos, sociales, categorización | Sprint 1 | 4h | Alta |
| T2 | Wireframes eventos | Diseño mockups: listado eventos, detalle, inscripción, calendario | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R eventos | Diagrama E/R: eventos, categorías, inscripciones, usuarios, organizadores | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML eventos | HTML semántico: cards eventos, formulario publicar, detalle evento | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS eventos | CSS Bootstrap: tarjetas, calendario visual, formularios responsive | Sprint 2 | 6h | Alta |
| T6 | JavaScript calendario | Calendario interactivo JS, filtros fecha, simulación eventos | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL eventos | Creación tablas: eventos, inscripciones, categorías, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP eventos | Scripts PHP para gestión eventos: crear, listar, editar, eliminar | Sprint 3 | 6h | Alta |
| T9 | Inscripciones PHP | Lógica inscripciones PHP: verificar plazas, registrar, confirmar | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel | Setup Laravel eventos, configuración, estructura proyecto | Sprint 4 | 4h | Alta |
| T11 | Migración a Blade eventos | Convertir HTML a Blade, layouts, componentes eventos | Sprint 4 | 8h | Alta |
| T12 | Rutas y controladores eventos | Rutas RESTful eventos, EventoController, InscripcionController | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent eventos | Modelos Evento, Inscripcion, Categoria con relaciones | Sprint 5 | 6h | Alta |
| T14 | Sistema inscripciones Laravel | Lógica Eloquent: control plazas, inscripciones, validaciones | Sprint 5 | 8h | Alta |
| T15 | Búsqueda y filtros | Búsqueda eventos: texto, categoría, fecha, ubicación con Ajax | Sprint 5 | 4h | Media |
| T16 | Autenticación eventos | Laravel Breeze, roles organizador/participante, permisos | Sprint 6 | 8h | Alta |
| T17 | Gestión imágenes eventos | Subida imágenes, galería eventos, optimización | Sprint 6 | 6h | Media |
| T18 | Google Maps integración | Ubicaciones en mapa, marcadores eventos, enlace rutas | Sprint 6 | 4h | Baja |
| T19 | Notificaciones email | Avisos: confirmación inscripción, recordatorios, cancelaciones | Sprint 7 | 8h | Media |
| T20 | Sistema valoraciones | Valoraciones eventos asistidos, comentarios, puntuaciones | Sprint 7 | 8h | Baja |
| T21 | Optimización UX eventos | Responsive final, navegación intuitiva, accesibilidad | Sprint 8 | 8h | Alta |
| T22 | Testing eventos | Tests: inscripciones, límites, validaciones, flujos completos | Sprint 8 | 8h | Alta |
| T23 | Docker eventos | Containerización aplicación, docker-compose, configuración | Sprint 9 | 8h | Alta |
| T24 | Documentación eventos | Manual organizadores, guía usuarios, procesos gestión | Sprint 9 | 8h | Alta |

---

## Proyecto 4 – TiendaOnline

**Descripción:** E-commerce básico para pequeños negocios con catálogo de productos, carrito de compra, gestión de pedidos y panel de administración sencillo.

**Objetivo:** Crear una tienda online funcional pero simple que permita a pequeños comercios vender sus productos por internet de forma fácil.

**Características funcionales principales:**
- Catálogo de productos con categorías
- Carrito de compra persistente
- Proceso de checkout básico
- Gestión de pedidos (estados básicos)
- Panel de administración de productos
- Búsqueda de productos
- Sistema de usuarios clientes
- Reportes básicos de ventas

**Tecnologías:**
- **Backend:** Laravel 10 con sesiones
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Base de datos:** MySQL 8.0
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Adicionales:** Laravel Storage, intervention/image

### 🗓️ Sprint Planning - TiendaOnline (7 meses)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|--------------------|-----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R e-commerce completo |
| 4–6 | Sprint 2 | Maquetación frontend tienda | HTML5, CSS3, Bootstrap, JS | T4, T5, T6 | Interfaz estática completa con carrito JS |
| 7–9 | Sprint 3 | Backend PHP y base de datos | PHP, MySQL, PDO, Sesiones | T7, T8, T9 | CRUD productos funcional con carrito PHP |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Eloquent | T10, T11, T12 | Proyecto Laravel con vistas Blade y modelos |
| 13–15 | Sprint 5 | Autenticación y checkout | Laravel Auth, Middleware | T13, T14, T15 | Sistema login con proceso compra funcional |
| 16–18 | Sprint 6 | Búsqueda y panel admin | Laravel Query Builder, Gates | T16, T17, T18 | Búsqueda avanzada y administración completa |
| 19–21 | Sprint 7 | Multimedia y reportes | Storage, Charts, Laravel Excel | T19, T20, T21 | Imágenes productos y estadísticas ventas |
| 22–24 | Sprint 8 | Optimización y testing | PHPUnit, Laravel Debugbar | T22, T23 | Tests transacciones y rendimiento optimizado |
| 25–27 | Sprint 9 | Dockerización y despliegue | Docker, Docker Compose | T24 | Tienda contenerizada y desplegada |

### 📊 Relación Sprints con RA y Criterios de Evaluación - TiendaOnline

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | c) Se han identificado las necesidades más demandadas a las empresas, e) Se han identificado las características específicas del proyecto, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis requisitos e-commerce, wireframes UI, modelo E/R comercial |
| **Sprint 2** | RA1, RA2 | f) Se han determinado los aspectos que se deben incluir en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Maquetación HTML completa, estilos CSS responsivos, carrito JS funcional |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto y su contenido | Base datos MySQL, CRUD PHP productos, carrito PHP con sesiones |
| **Sprint 4** | RA2, RA3 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Proyecto Laravel configurado, vistas Blade, modelos Eloquent |
| **Sprint 5** | RA2, RA3 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto | Sistema autenticación, checkout completo, gestión pedidos |
| **Sprint 6** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Motor búsqueda productos, panel admin completo, roles |
| **Sprint 7** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo | Gestión imágenes productos, estadísticas ventas, reportes |
| **Sprint 8** | RA3, RA4 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones | Tests transacciones, optimización queries, debugging |
| **Sprint 9** | RA4 | c) Se han aplicado indicadores de calidad a las actividades diseñadas en el proyecto, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Dockerfile, docker-compose.yml, tienda desplegada productiva |

### 📋 Product Backlog Detallado - TiendaOnline

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis requisitos e-commerce | Estudio flujos tienda: catálogo, carrito, checkout, gestión pedidos | Sprint 1 | 4h | Alta |
| T2 | Wireframes tienda | Diseño mockups: home, catálogo, producto, carrito, checkout | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R comercial | Diagrama E/R: productos, categorías, usuarios, pedidos, carrito | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML tienda | HTML semántico: catálogo, ficha producto, carrito, formularios | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS e-commerce | CSS Bootstrap: cards productos, carrito, checkout responsive | Sprint 2 | 6h | Alta |
| T6 | JavaScript carrito | Carrito dinámico JS, agregar/eliminar productos, LocalStorage | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL tienda | Creación tablas: productos, categorías, pedidos, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP productos | Scripts PHP para gestión catálogo: crear, listar, editar productos | Sprint 3 | 6h | Alta |
| T9 | Carrito PHP sesiones | Lógica carrito PHP: sesiones, agregar items, calcular totales | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel tienda | Setup Laravel, configuración, estructura proyecto e-commerce | Sprint 4 | 4h | Alta |
| T11 | Migración a Blade tienda | Convertir HTML a Blade, layouts tienda, componentes productos | Sprint 4 | 8h | Alta |
| T12 | Rutas y controladores | Rutas RESTful, ProductoController, PedidoController, CarritoController | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent tienda | Modelos Producto, Categoria, Pedido, LineaPedido con relaciones | Sprint 5 | 6h | Alta |
| T14 | Sistema pedidos Laravel | Lógica Eloquent: gestión pedidos, estados, control stock | Sprint 5 | 8h | Alta |
| T15 | Búsqueda y filtros | Búsqueda productos: texto, categoría, precio, disponibilidad | Sprint 5 | 4h | Media |
| T16 | Autenticación tienda | Laravel Breeze, roles cliente/admin, panel administración | Sprint 6 | 8h | Alta |
| T17 | Gestión imágenes productos | Subida múltiples imágenes, galería producto, optimización | Sprint 6 | 6h | Media |
| T18 | Reportes ventas | Estadísticas: ventas por producto, ingresos, productos populares | Sprint 6 | 4h | Baja |
| T19 | Proceso checkout completo | Checkout multi-paso: datos envío, resumen, confirmación pedido | Sprint 7 | 8h | Alta |
| T20 | Optimización UX tienda | Mejoras navegación, filtros avanzados, paginación, breadcrumbs | Sprint 7 | 8h | Alta |
| T21 | Testing e-commerce | Tests: carrito, checkout, stock, validaciones pedidos | Sprint 8 | 8h | Alta |
| T22 | Optimización rendimiento | Caché productos, índices BD, queries optimizadas | Sprint 8 | 8h | Media |
| T23 | Docker tienda | Containerización, docker-compose, configuración producción | Sprint 9 | 8h | Alta |
| T24 | Documentación comercial | Manual administrador, guía productos, procesos gestión | Sprint 9 | 8h | Media |

---

## Proyecto 5 – RecetasFáciles

**Descripción:** Red social básica donde usuarios pueden compartir recetas de cocina, valorar las de otros usuarios, crear listas de favoritos y buscar recetas por ingredientes.

**Objetivo:** Crear una comunidad online para compartir y descubrir recetas caseras de forma sencilla e intuitiva.

**Características funcionales principales:**
- Registro y perfiles de usuarios
- CRUD de recetas con fotos
- Sistema de valoraciones (estrellas)
- Comentarios en recetas
- Lista de recetas favoritas
- Búsqueda por ingredientes o nombre
- Categorías de recetas (postres, platos principales, etc.)
- Feed de últimas recetas

**Tecnologías:**
- **Backend:** Laravel 10 con Eloquent
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Base de datos:** MySQL 8.0
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Adicionales:** Laravel Storage, image optimization

### 🗓️ Sprint Planning - RecetasFáciles (7 meses)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|--------------------|-----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R red social completo |
| 4–6 | Sprint 2 | Maquetación frontend social | HTML5, CSS3, Bootstrap, JS | T4, T5, T6 | Interfaz estática completa con feed interactivo |
| 7–9 | Sprint 3 | Backend PHP y base de datos | PHP, MySQL, PDO | T7, T8, T9 | CRUD recetas funcional con comentarios PHP |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Eloquent | T10, T11, T12 | Proyecto Laravel con vistas Blade y modelos |
| 13–15 | Sprint 5 | Autenticación y favoritos | Laravel Auth, Relaciones Eloquent | T13, T14, T15 | Sistema login con favoritos y categorización |
| 16–18 | Sprint 6 | Búsqueda y feed social | Laravel Query Builder, Pagination | T16, T17, T18 | Motor búsqueda y timeline dinámico |
| 19–21 | Sprint 7 | Funciones sociales avanzadas | Notifications, Events, Jobs | T19, T20, T21 | Seguimiento usuarios y notificaciones |
| 22–24 | Sprint 8 | Optimización y testing | PHPUnit, Laravel Debugbar | T22, T23 | Tests interacciones y rendimiento optimizado |
| 25–27 | Sprint 9 | Dockerización y despliegue | Docker, Docker Compose | T24 | Comunidad contenerizada y desplegada |

### 📊 Relación Sprints con RA y Criterios de Evaluación - RecetasFáciles

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | d) Se han valorado las oportunidades de negocio previsibles en el sector, e) Se han identificado las características específicas del proyecto, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis red social culinaria, wireframes UI, modelo E/R social |
| **Sprint 2** | RA1, RA2 | f) Se han determinado los aspectos que se deben incluir en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Maquetación HTML completa, estilos CSS responsivos, feed JS dinámico |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto y su contenido | Base datos MySQL, CRUD PHP recetas, comentarios y valoraciones PHP |
| **Sprint 4** | RA2, RA3 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Proyecto Laravel configurado, vistas Blade, modelos Eloquent |
| **Sprint 5** | RA2, RA3 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, c) Se han identificado las necesidades de permisos y autorizaciones para llevar a cabo las actividades | Sistema autenticación, favoritos funcional, categorías |
| **Sprint 6** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Motor búsqueda recetas, timeline personalizado, paginación |
| **Sprint 7** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, d) Se han determinado los procedimientos de actuación o ejecución de las actividades | Seguimiento usuarios, notificaciones automáticas, eventos |
| **Sprint 8** | RA3, RA4 | f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución, a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones | Tests PHPUnit, optimización rendimiento, debugging |
| **Sprint 9** | RA4 | c) Se han aplicado indicadores de calidad a las actividades diseñadas en el proyecto, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Dockerfile, docker-compose.yml, comunidad desplegada productiva |

### 📋 Product Backlog Detallado - RecetasFáciles

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis red social culinaria | Estudio funcionalidades: perfiles, recetas, interacciones, seguimiento | Sprint 1 | 4h | Alta |
| T2 | Wireframes red social | Diseño mockups: feed, perfil, receta, formulario publicar | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R social | Diagrama E/R: usuarios, recetas, valoraciones, comentarios, favoritos | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML recetas | HTML semántico: feed, card receta, perfil, formulario ingredientes | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS social | CSS Bootstrap: cards recetas, perfil usuario, feed responsive | Sprint 2 | 6h | Alta |
| T6 | JavaScript interactivo | Feed dinámico JS, valoraciones estrellas, simulación datos recetas | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL social | Creación tablas: usuarios, recetas, comentarios, favoritos, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP recetas | Scripts PHP para gestión recetas: crear, listar, editar, eliminar | Sprint 3 | 6h | Alta |
| T9 | Comentarios y valoraciones PHP | Lógica PHP: agregar comentarios, calcular rating, gestionar favoritos | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel social | Setup Laravel, configuración, estructura proyecto red social | Sprint 4 | 4h | Alta |
| T11 | Migración a Blade social | Convertir HTML a Blade, layouts feed, componentes recetas | Sprint 4 | 8h | Alta |
| T12 | Rutas y controladores social | Rutas RESTful, RecetaController, PerfilController, InteraccionController | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent social | Modelos Usuario, Receta, Comentario, Valoracion con relaciones | Sprint 5 | 6h | Alta |
| T14 | Sistema interacciones | Lógica Eloquent: comentarios, valoraciones, favoritos, relaciones | Sprint 5 | 8h | Alta |
| T15 | Feed personalizado | Algoritmo feed: recetas seguidos, populares, búsqueda avanzada | Sprint 5 | 4h | Media |
| T16 | Autenticación social | Laravel Breeze, perfiles usuarios, edición perfil, foto avatar | Sprint 6 | 8h | Alta |
| T17 | Sistema seguimiento | Seguir/dejar seguir usuarios, lista seguidores/seguidos | Sprint 6 | 6h | Media |
| T18 | Notificaciones Laravel | Notificaciones: nuevos comentarios, valoraciones, seguidores | Sprint 6 | 4h | Baja |
| T19 | Gestión imágenes recetas | Subida imágenes recetas, galería pasos, optimización | Sprint 7 | 8h | Alta |
| T20 | Optimización UX social | Infinite scroll, búsqueda instantánea, navegación fluida | Sprint 7 | 8h | Alta |
| T21 | Testing red social | Tests: interacciones, feed, valoraciones, comentarios | Sprint 8 | 8h | Alta |
| T22 | Optimización social | Caché feed, índices BD, queries optimizadas | Sprint 8 | 8h | Media |
| T23 | Docker comunidad | Containerización, docker-compose, configuración producción | Sprint 9 | 8h | Alta |
| T24 | Documentación comunidad | Guía usuarios, normas comunidad, manual moderación | Sprint 9 | 8h | Media |

---

## Proyecto 6 – FitnessTracker

**Descripción:** Aplicación web para el seguimiento básico de actividad física, donde usuarios pueden registrar entrenamientos, establecer objetivos y ver su progreso de forma visual.

**Objetivo:** Ayudar a las personas a mantener un registro de su actividad física y motivarse mediante el seguimiento de objetivos personales.

**Características funcionales principales:**
- Registro de usuarios con datos físicos básicos
- Logging de entrenamientos (tipo, duración, intensidad)
- Establecimiento de objetivos semanales/mensuales
- Dashboard con gráficos de progreso
- Calendario de entrenamientos
- Sistema de logros básicos
- Estadísticas personales
- Recordatorios de entrenamientos

**Tecnologías:**
- **Backend:** Laravel 10 con Carbon para fechas
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5, Chart.js
- **Base de datos:** MySQL 8.0
- **Despliegue:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Adicionales:** Chart.js para gráficos, Laravel Scheduler

### 🗓️ Sprint Planning - FitnessTracker (7 meses)

| Semana | Sprint | Objetivo principal | Tecnologías | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|--------------------|-----------------------|
| 1–3 | Sprint 1 | Análisis, diseño UI y modelo E/R | Figma/Balsamiq, Diagrama E/R | T1, T2, T3 | Wireframes, modelo E/R fitness completo |
| 4–6 | Sprint 2 | Maquetación frontend fitness | HTML5, CSS3, Bootstrap, Chart.js | T4, T5, T6 | Dashboard estático completo con gráficos JS |
| 7–9 | Sprint 3 | Backend PHP y base de datos | PHP, MySQL, PDO | T7, T8, T9 | CRUD entrenamientos funcional con métricas PHP |
| 10–12 | Sprint 4 | Migración a Laravel | Laravel, Blade, Eloquent | T10, T11, T12 | Proyecto Laravel con vistas Blade y modelos |
| 13–15 | Sprint 5 | Autenticación y objetivos | Laravel Auth, Validaciones | T13, T14, T15 | Sistema login con metas personales funcional |
| 16–18 | Sprint 6 | Calendario y visualización | FullCalendar.js, Laravel Collections | T16, T17, T18 | Calendario entrenamientos y progreso visual |
| 19–21 | Sprint 7 | Gamificación y recordatorios | Notifications, Tasks Scheduling | T19, T20, T21 | Logros, recordatorios automáticos, estadísticas |
| 22–24 | Sprint 8 | Optimización y testing | PHPUnit, Laravel Debugbar | T22, T23 | Tests métricas y rendimiento optimizado |
| 25–27 | Sprint 9 | Dockerización y despliegue | Docker, Docker Compose | T24 | App fitness contenerizada y desplegada |

### 📊 Relación Sprints con RA y Criterios de Evaluación - FitnessTracker

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | e) Se han identificado las características específicas del proyecto, d) Se han valorado las oportunidades de negocio previsibles en el sector, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis métricas fitness, wireframes UI, modelo E/R fitness |
| **Sprint 2** | RA1, RA2 | f) Se han determinado los aspectos que se deben incluir en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Maquetación HTML completa, estilos CSS responsivos, gráficos Chart.js |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto y su contenido | Base datos MySQL, CRUD PHP entrenamientos, cálculos métricas PHP |
| **Sprint 4** | RA2, RA3 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Proyecto Laravel configurado, vistas Blade, modelos Eloquent |
| **Sprint 5** | RA2, RA3 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto | Sistema autenticación, objetivos personales, validaciones |
| **Sprint 6** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Calendario entrenamientos, visualización progreso, gráficos |
| **Sprint 7** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, d) Se han determinado los procedimientos de actuación o ejecución de las actividades | Sistema logros, recordatorios automáticos, estadísticas avanzadas |
| **Sprint 8** | RA3, RA4 | h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución, a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones | Tests PHPUnit, optimización cálculos, debugging |
| **Sprint 9** | RA4 | c) Se han aplicado indicadores de calidad a las actividades diseñadas en el proyecto, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Dockerfile, docker-compose.yml, app fitness desplegada productiva |

### 📋 Product Backlog Detallado - FitnessTracker

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis métricas fitness | Estudio métricas: tipos ejercicio, duración, calorías, objetivos | Sprint 1 | 4h | Alta |
| T2 | Wireframes app fitness | Diseño mockups: dashboard, registro entrenamiento, estadísticas | Sprint 1 | 6h | Alta |
| T3 | Modelo E/R fitness | Diagrama E/R: usuarios, entrenamientos, ejercicios, objetivos, métricas | Sprint 1 | 8h | Alta |
| T4 | Maquetación HTML dashboard | HTML semántico: dashboard principal, formulario entrenamiento, gráficos | Sprint 2 | 6h | Alta |
| T5 | Estilos CSS fitness | CSS Bootstrap: dashboard deportivo, cards estadísticas, responsive | Sprint 2 | 6h | Alta |
| T6 | JavaScript métricas | Cálculos JS: calorías, progreso, gráficos Chart.js, simulación datos | Sprint 2 | 6h | Alta |
| T7 | Base datos MySQL fitness | Creación tablas: usuarios, entrenamientos, ejercicios, objetivos, datos prueba | Sprint 3 | 6h | Alta |
| T8 | CRUD PHP entrenamientos | Scripts PHP para gestión entrenamientos: registrar, listar, editar | Sprint 3 | 6h | Alta |
| T9 | Cálculos métricas PHP | Lógica PHP: calorías quemadas, progreso objetivos, estadísticas | Sprint 3 | 6h | Alta |
| T10 | Instalación Laravel fitness | Setup Laravel, configuración, estructura proyecto fitness | Sprint 4 | 4h | Alta |
| T11 | Migración a Blade fitness | Convertir HTML a Blade, layouts dashboard, componentes métricas | Sprint 4 | 8h | Alta |
| T12 | Rutas y controladores fitness | Rutas RESTful, EntrenamientoController, ObjetivoController, MetricaController | Sprint 4 | 6h | Alta |
| T13 | Modelos Eloquent fitness | Modelos Entrenamiento, Ejercicio, Objetivo, Metrica con relaciones | Sprint 5 | 6h | Alta |
| T14 | Sistema objetivos Laravel | Lógica Eloquent: crear objetivos, calcular progreso, validaciones | Sprint 5 | 8h | Alta |
| T15 | Dashboard dinámico | Dashboard Ajax: actualización tiempo real, métricas actuales | Sprint 5 | 4h | Media |
| T16 | Autenticación fitness | Laravel Breeze, perfiles fitness: datos físicos, nivel actividad | Sprint 6 | 8h | Alta |
| T17 | Gráficos avanzados | Visualizaciones Chart.js: líneas progreso, barras comparativas | Sprint 6 | 6h | Media |
| T18 | Calendario entrenamientos | Vista calendario entrenamientos, planificación semanal | Sprint 6 | 4h | Media |
| T19 | Sistema logros gamificación | Logros automáticos: rachas, hitos, medallas, puntos motivación | Sprint 7 | 8h | Media |
| T20 | Estadísticas avanzadas | Análisis tendencias, comparativas periodos, reportes progreso | Sprint 7 | 8h | Media |
| T21 | Optimización UX fitness | Interface responsive, widgets personalizables, navegación rápida | Sprint 8 | 8h | Alta |
| T22 | Testing fitness | Tests: cálculos calorías, progreso objetivos, métricas | Sprint 8 | 8h | Alta |
| T23 | Docker app fitness | Containerización, docker-compose, configuración producción | Sprint 9 | 8h | Alta |
| T24 | Documentación fitness | Manual usuario, guía entrenamientos, plan uso app | Sprint 9 | 8h | Alta |

---

## 📊 Resumen Comparativo Simplificado

| Proyecto | Complejidad | CRUD Principal | Funcionalidad Destacada | Dificultad |
|----------|-------------|----------------|------------------------|------------|
| **TaskManager Pro** | Básica | Tareas/Proyectos | Asignaciones | ⭐⭐ |
| **BiblioTech** | Media | Libros/Préstamos | Cálculo fechas | ⭐⭐⭐ |
| **EventosLocal** | Media | Eventos/Inscripciones | API Maps | ⭐⭐⭐ |
| **TiendaOnline** | Media | Productos/Pedidos | Carrito compra | ⭐⭐⭐ |
| **RecetasFáciles** | Básica | Recetas/Comentarios | Red social | ⭐⭐ |
| **FitnessTracker** | Media | Entrenamientos | Gráficos | ⭐⭐⭐ |

<!-- ## 💡 Recomendaciones Simplificadas

### 🎯 **Para Empezar (Estudiantes Noveles)**
- **TaskManager Pro** o **RecetasFáciles**

### 🔧 **Nivel Intermedio**
- **BiblioTech**, **EventosLocal** o **FitnessTracker**

### 🚀 **Más Desafiante**
- **TiendaOnline** (por la lógica de e-commerce) -->






