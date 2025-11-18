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
| 1–3 | Sprint 1 | Análisis y frontend estático | HTML5, CSS3, Bootstrap | T1, T2, T3 | Wireframes, maquetas HTML estáticas |
| 4–6 | Sprint 2 | Interactividad frontend | JavaScript, DOM | T4, T5, T6 | Frontend interactivo con JS |
| 7–9 | Sprint 3 | Backend PHP + BD | PHP, MySQL, phpMyAdmin | T7, T8, T9 | CRUD básico con PHP vanilla |
| 10–12 | Sprint 4 | Introducción Laravel | Laravel básico, rutas, vistas | T10, T11, T12 | Migración a Laravel, vistas Blade |
| 13–15 | Sprint 5 | Modelos y Eloquent | Laravel intermedio, ORM | T13, T14, T15 | Sistema completo con Eloquent |
| 16–18 | Sprint 6 | Funcionalidades avanzadas | Laravel avanzado, Auth | T16, T17, T18 | Autenticación y features avanzadas |
| 19–21 | Sprint 7 | Optimización y UX | Laravel + JavaScript | T19, T20 | Aplicación optimizada y pulida |
| 22–24 | Sprint 8 | Testing y calidad | PHPUnit, debugging | T21, T22 | Testing implementado |
| 25–27 | Sprint 9 | Despliegue | Docker, producción | T23, T24 | Aplicación desplegada |

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

| ID | Tarea | Descripción Específica | Sprint | Tecnología | Estimación | Prioridad |
|----|-------|------------------------|--------|------------|-------------|-----------|
| T1 | Análisis y wireframes | Definición requisitos, casos de uso, wireframes con herramientas | Sprint 1 | Análisis | 6h | Alta |
| T2 | Maquetación HTML/CSS | Estructura HTML semántica, diseño CSS con Bootstrap 5 | Sprint 1 | HTML/CSS | 8h | Alta |
| T3 | Navegación y layout | Layout responsive, navegación entre páginas, estructura base | Sprint 1 | HTML/CSS | 4h | Alta |
| T4 | Interactividad JavaScript | Validaciones formularios, manipulación DOM, eventos | Sprint 2 | JavaScript | 8h | Alta |
| T5 | Simulación datos frontend | Arrays JS para simular proyectos/tareas, render dinámico | Sprint 2 | JavaScript | 6h | Alta |
| T6 | LocalStorage básico | Persistencia temporal datos en navegador, CRUD simulado | Sprint 2 | JavaScript | 4h | Media |
| T7 | Base datos MySQL | Diseño BD, tablas con phpMyAdmin, datos de prueba | Sprint 3 | MySQL | 4h | Alta |
| T8 | PHP CRUD básico | Scripts PHP para Create, Read, Update, Delete con MySQL | Sprint 3 | PHP/MySQL | 10h | Alta |
| T9 | Conexión frontend-backend | Integración formularios HTML con scripts PHP | Sprint 3 | PHP | 4h | Alta |
| T10 | Instalación Laravel | Setup Laravel, configuración básica, estructura proyecto | Sprint 4 | Laravel | 4h | Alta |
| T11 | Rutas y controladores | Definir rutas, controladores básicos, estructura MVC | Sprint 4 | Laravel | 8h | Alta |
| T12 | Vistas Blade | Migrar HTML a plantillas Blade, layouts, componentes | Sprint 4 | Laravel | 6h | Alta |
| T13 | Modelos Eloquent | Crear modelos, migrations, relaciones básicas | Sprint 5 | Laravel/Eloquent | 6h | Alta |
| T14 | CRUD con Eloquent | Reescribir CRUD usando Eloquent ORM | Sprint 5 | Laravel/Eloquent | 8h | Alta |
| T15 | Validaciones Laravel | Form requests, validaciones backend, mensajes error | Sprint 5 | Laravel | 4h | Media |
| T16 | Autenticación Laravel | Sistema login/logout con Laravel Auth | Sprint 6 | Laravel Auth | 8h | Alta |
| T17 | Roles y permisos | Middleware, roles usuario, control acceso | Sprint 6 | Laravel | 6h | Media |
| T18 | Funcionalidades avanzadas | Comentarios, asignaciones, dashboard con métricas | Sprint 6 | Laravel | 4h | Media |
| T19 | AJAX y mejoras UX | Peticiones asíncronas, updates sin reload | Sprint 7 | Laravel/JS | 8h | Media |
| T20 | Optimización frontend | Responsive final, UX/UI pulido, accesibilidad | Sprint 7 | CSS/JS | 8h | Alta |
| T21 | Testing básico | Tests unitarios modelos, tests funcionales rutas | Sprint 8 | PHPUnit | 8h | Media |
| T22 | Debugging y calidad | Corrección bugs, logging, optimización queries | Sprint 8 | Laravel | 8h | Media |
| T23 | Docker básico | Dockerfile, docker-compose, containerización | Sprint 9 | Docker | 8h | Alta |
| T24 | Documentación y entrega | README, manual usuario, presentación final | Sprint 9 | Documentación | 8h | Media |

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
| 1–3 | Sprint 1 | Análisis y maquetación biblioteca | HTML5, CSS3, Bootstrap | T1, T2, T3 | Diseño biblioteca, formularios estáticos |
| 4–6 | Sprint 2 | Simulación catálogo frontend | JavaScript, DOM | T4, T5, T6 | Catálogo interactivo con JS |
| 7–9 | Sprint 3 | Backend PHP bibliotecario | PHP, MySQL, phpMyAdmin | T7, T8, T9 | CRUD libros y usuarios con PHP |
| 10–12 | Sprint 4 | Migración Laravel biblioteca | Laravel básico, rutas | T10, T11, T12 | Sistema biblioteca en Laravel |
| 13–15 | Sprint 5 | Lógica préstamos Eloquent | Laravel intermedio, ORM | T13, T14, T15 | Sistema préstamos con modelos |
| 16–18 | Sprint 6 | Funciones bibliotecarias | Laravel avanzado | T16, T17, T18 | Multas, reservas, autenticación |
| 19–21 | Sprint 7 | Optimización biblioteca | Laravel + JS | T19, T20 | Búsquedas, reportes, UX |
| 22–24 | Sprint 8 | Testing biblioteca | PHPUnit | T21, T22 | Testing lógica bibliotecaria |
| 25–27 | Sprint 9 | Despliegue biblioteca | Docker | T23, T24 | Sistema desplegado |

### 📊 Relación Sprints con RA y Criterios de Evaluación - BiblioTech

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | a) Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Modelo procesos bibliotecarios, E/R biblioteca, entorno configurado |
| **Sprint 2** | RA2 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Gestión libros completa, sistema ISBN, categorización automática |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto | Sistema usuarios multi-rol, perfiles bibliotecarios, validaciones |
| **Sprint 4** | RA2 | c) Se han identificado las fases o partes que componen el proyecto y su contenido, d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance | Sistema préstamos completo, control disponibilidad, verificaciones |
| **Sprint 5** | RA2 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, f) Se ha realizado el presupuesto económico correspondiente | Control multas automatizado, validación devoluciones, cálculos |
| **Sprint 6** | RA2, RA3 | g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Sistema reservas funcional, notificaciones automáticas |
| **Sprint 7** | RA3 | b) Se han determinado los recursos y la logística necesarios para cada actividad, h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución | Catálogo funcional optimizado, estadísticas biblioteca |
| **Sprint 8** | RA3 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución | UX bibliotecaria optimizada, interfaz accesible |
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

| Semana | Sprint | Objetivo principal | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis y configuración eventos | T1, T2, T3 | Definición eventos, Laravel + roles configurados |
| 4–6 | Sprint 2 | CRUD eventos completo | T4, T5 | Gestión completa de eventos con categorías |
| 7–9 | Sprint 3 | Sistema de inscripciones | T6, T7 | Inscripciones y control de plazas funcional |
| 10–12 | Sprint 4 | Calendario y visualización | T8, T9 | Vista calendario dinámico y timeline eventos |
| 13–15 | Sprint 5 | Búsqueda y filtros avanzados | T10, T11 | Sistema búsqueda y filtros múltiples |
| 16–18 | Sprint 6 | Multimedia y ubicaciones | T12, T13 | Gestión imágenes y Google Maps integrado |
| 19–21 | Sprint 7 | Notificaciones y valoraciones | T14, T15 | Sistema avisos y feedback usuarios |
| 22–24 | Sprint 8 | Frontend optimizado | T16, T17 | Interfaz eventos mejorada y responsive |
| 25–27 | Sprint 9 | Testing y lanzamiento | T18, T19 | Pruebas flujos y despliegue final |

### 📊 Relación Sprints con RA y Criterios de Evaluación - EventosLocal

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | b) Se han caracterizado las empresas tipo indicando la estructura organizativa y las funciones de cada departamento, i) Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto | Análisis tipos eventos locales, base datos configurada, documentación |
| **Sprint 2** | RA2 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, h) Se ha definido y elaborado la documentación necesaria para su diseño | Gestión eventos completa, sistema categorías, validaciones |
| **Sprint 3** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, c) Se han identificado las fases o partes que componen el proyecto y su contenido | Sistema inscripciones funcional, control plazas tiempo real |
| **Sprint 4** | RA3, RA2 | a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución, d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance | Calendario dinámico funcional, timeline eventos interactivo |
| **Sprint 5** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Sistema búsqueda optimizado, UX filtros avanzados |
| **Sprint 6** | RA2 | f) Se ha realizado el presupuesto económico correspondiente, g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo | Subida imágenes eventos, Google Maps funcional |
| **Sprint 7** | RA2, RA3 | i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto, c) Se han identificado las necesidades de permisos y autorizaciones para llevar a cabo las actividades | Avisos automáticos email, sistema valoraciones funcional |
| **Sprint 8** | RA3 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución | UX eventos optimizada, galería multimedia, navegación intuitiva |
| **Sprint 9** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | Pruebas completas flujos eventos, API desplegada productiva |

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

| Semana | Sprint | Objetivo principal | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis y catálogo base | T1, T2, T3 | Requisitos e-commerce, CRUD productos y categorías |
| 4–6 | Sprint 2 | Usuarios y autenticación | T4, T5 | Sistema clientes y panel administración |
| 7–9 | Sprint 3 | Carrito de compra | T6, T7 | Carrito funcional y persistente |
| 10–12 | Sprint 4 | Checkout y pedidos | T8, T9 | Proceso compra y gestión pedidos |
| 13–15 | Sprint 5 | Búsqueda y administración | T10, T11 | Búsqueda productos y panel admin completo |
| 16–18 | Sprint 6 | Multimedia y reportes | T12, T13 | Gestión imágenes y estadísticas ventas |
| 19–21 | Sprint 7 | Frontend e-commerce | T14, T15 | Interfaz tienda optimizada y responsive |
| 22–24 | Sprint 8 | Testing y optimización | T16, T17 | Pruebas flujos compra y rendimiento |
| 25–27 | Sprint 9 | Lanzamiento tienda | T18, T19 | Despliegue final y documentación completa |

### 📊 Relación Sprints con RA y Criterios de Evaluación - TiendaOnline

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1 | c) Se han identificado las necesidades más demandadas a las empresas, e) Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas | Análisis e-commerce básico, modelo productos y categorías configuradas |
| **Sprint 2** | RA2 | a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto, b) Se ha realizado el estudio de viabilidad técnica del mismo | Autenticación clientes/admin funcional, gestión usuarios completa |
| **Sprint 3** | RA2 | c) Se han identificado las fases o partes que componen el proyecto y su contenido, h) Se ha definido y elaborado la documentación necesaria para su diseño | Carrito compra funcional, almacenamiento sesión, persistencia |
| **Sprint 4** | RA2 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, e) Se han previsto los recursos materiales y personales necesarios para realizarlo | Flujo compra completo, gestión pedidos, estados transición |
| **Sprint 5** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Motor búsqueda productos, panel admin completo funcional |
| **Sprint 6** | RA2 | g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo, i) Se han identificado los aspectos que se deben controlar para garantizar la calidad del proyecto | Imágenes productos optimizadas, estadísticas ventas tiempo real |
| **Sprint 7** | RA3 | b) Se han determinado los recursos y la logística necesarios para cada actividad, d) Se han determinado los procedimientos de actuación o ejecución de las actividades | UX tienda optimizada, navegación intuitiva, proceso compra fluido |
| **Sprint 8** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, b) Se han definido los indicadores de calidad para realizar la evaluación | Pruebas críticas transacciones, optimización queries y rendimiento |
| **Sprint 9** | RA4 | e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto, f) Se ha establecido el procedimiento para la participación en la evaluación de los usuarios o clientes | Tienda online desplegada productiva, manual administrador completo |

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

### 📊 Relación Sprints con RA y Criterios de Evaluación - TiendaOnline

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1, RA2 | Análisis e-commerce, CRUD avanzado | Modelo de datos, catálogo productos |
| **Sprint 2** | RA2, RA3 | Integración compleja, sesiones | Sistema usuarios, carrito persistente |
| **Sprint 3** | RA2, RA5 | Lógica de negocio, validaciones | Checkout, gestión estados pedidos |
| **Sprint 4** | RA3, RA2 | Interfaces administrativas, búsqueda | Panel admin, motor búsqueda |
| **Sprint 5** | RA4, RA2 | Gestión archivos, reportes | Subida imágenes, estadísticas |
| **Sprint 6** | RA3 | UX e-commerce, conversión | Interfaz optimizada, responsive |
| **Sprint 7** | RA5 | Testing transacciones, flujos críticos | Pruebas de compra completas |
| **Sprint 8** | RA4, RA6 | Despliegue comercial, documentación | Tienda en producción, manual admin |

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

| Semana | Sprint | Objetivo principal | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis y perfiles usuarios | T1, T2, T3 | Definición red social, usuarios y autenticación |
| 4–6 | Sprint 2 | CRUD recetas completo | T4, T5 | Gestión recetas y subida fotos funcional |
| 7–9 | Sprint 3 | Valoraciones y comentarios | T6, T7 | Sistema rating y feedback implementado |
| 10–12 | Sprint 4 | Favoritos y categorización | T8, T9 | Lista favoritos y organización contenido |
| 13–15 | Sprint 5 | Búsqueda y feed social | T10, T11 | Motor búsqueda y timeline dinámico |
| 16–18 | Sprint 6 | Funciones sociales avanzadas | T12, T13 | Seguimiento usuarios y notificaciones |
| 19–21 | Sprint 7 | Frontend social optimizado | T14, T15 | Interfaz red social mejorada y responsive |
| 22–24 | Sprint 8 | Testing y optimización | T16, T17 | Pruebas interacciones y rendimiento |
| 25–27 | Sprint 9 | Comunidad online | T18, T19 | Despliegue final y documentación comunidad |

### 📊 Relación Sprints con RA y Criterios de Evaluación - RecetasFáciles

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1, RA2 | d) Se han valorado las oportunidades de negocio previsibles en el sector, a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto | Análisis comunidad culinaria, perfiles usuarios funcionales |
| **Sprint 2** | RA2 | b) Se ha realizado el estudio de viabilidad técnica del mismo, h) Se ha definido y elaborado la documentación necesaria para su diseño | Sistema recetas completo, subida imágenes optimizadas |
| **Sprint 3** | RA2, RA3 | c) Se han identificado las fases o partes que componen el proyecto y su contenido, c) Se han identificado las necesidades de permisos y autorizaciones para llevar a cabo las actividades | Sistema valoraciones funcional, comentarios interactivos |
| **Sprint 4** | RA2, RA3 | d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Sistema favoritos funcional, categorías dinámicas organizadas |
| **Sprint 5** | RA3, RA2 | b) Se han determinado los recursos y la logística necesarios para cada actividad, e) Se han previsto los recursos materiales y personales necesarios para realizarlo | Motor búsqueda recetas, timeline personalizado funcional |
| **Sprint 6** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, d) Se han determinado los procedimientos de actuación o ejecución de las actividades | Sistema seguimiento usuarios, notificaciones automáticas |
| **Sprint 7** | RA3 | f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución, h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución | UX social optimizada, navegación culinaria intuitiva |
| **Sprint 8** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, b) Se han definido los indicadores de calidad para realizar la evaluación | Pruebas comunidad culinaria, rendimiento interacciones |
| **Sprint 9** | RA4 | e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto, f) Se ha establecido el procedimiento para la participación en la evaluación de los usuarios o clientes | Comunidad culinaria desplegada, guías usuario completas |

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

| Semana | Sprint | Objetivo principal | Tareas del Backlog | Revisión / Entregable |
|--------|---------|--------------------|--------------------|----------------------|
| 1–3 | Sprint 1 | Análisis y perfiles fitness | T1, T2, T3 | Definición métricas, usuarios con datos físicos |
| 4–6 | Sprint 2 | Sistema entrenamientos | T4, T5 | CRUD actividades y tipos ejercicios |
| 7–9 | Sprint 3 | Dashboard y métricas | T6, T7 | Vista principal con estadísticas básicas |
| 10–12 | Sprint 4 | Gráficos y visualización | T8, T9 | Chart.js implementado y progressos visuales |
| 13–15 | Sprint 5 | Objetivos y calendario | T10, T11 | Sistema metas y vista calendario entrenamientos |
| 16–18 | Sprint 6 | Logros y gamificación | T12, T13 | Sistema logros y recordatorios automáticos |
| 19–21 | Sprint 7 | Estadísticas avanzadas | T14, T15 | Reportes personales y análisis progreso |
| 22–24 | Sprint 8 | Frontend fitness optimizado | T16, T17 | UX fitness mejorada y responsive design |
| 25–27 | Sprint 9 | App fitness completa | T18, T19 | Testing, despliegue y documentación final |

### 📊 Relación Sprints con RA y Criterios de Evaluación - FitnessTracker

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1, RA2 | e) Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas, a) Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto | Análisis requisitos fitness, perfiles usuarios deportivos, objetivos definidos |
| **Sprint 2** | RA2, RA3 | b) Se ha realizado el estudio de viabilidad técnica del mismo, b) Se han determinado los recursos y la logística necesarios para cada actividad | Sistema actividades completo, categorización ejercicios funcional |
| **Sprint 3** | RA2, RA3 | c) Se han identificado las fases o partes que componen el proyecto y su contenido, a) Se han secuenciado las actividades ordenándolas en función de las necesidades de ejecución | Vista principal fitness, estadísticas tiempo real funcionales |
| **Sprint 4** | RA3, RA2 | d) Se han determinado los procedimientos de actuación o ejecución de las actividades, d) Se han establecido los objetivos que se pretenden conseguir identificando su alcance | Gráficos Chart.js interactivos, progreso visual optimizado |
| **Sprint 5** | RA2, RA3 | e) Se han previsto los recursos materiales y personales necesarios para realizarlo, f) Se han planificado la asignación de recursos materiales y humanos y los tiempos de ejecución | Metas personales funcionales, calendario dinámico entrenamientos |
| **Sprint 6** | RA2, RA3 | f) Se ha realizado el presupuesto económico correspondiente, g) Se ha hecho la valoración económica que da respuesta a las condiciones de la implementación | Sistema logros gamificado, recordatorios automáticos programados |
| **Sprint 7** | RA2 | g) Se han identificado las necesidades de financiación para la puesta en marcha del mismo, h) Se ha definido y elaborado la documentación necesaria para su diseño | Análisis estadístico avanzado, informes progreso detallados |
| **Sprint 8** | RA3 | h) Se ha definido y elaborado la documentación necesaria para la implementación o ejecución, e) Se han identificado los riesgos inherentes a la ejecución definiendo el plan de prevención | UX fitness optimizada, navegación deportiva intuitiva |
| **Sprint 9** | RA4 | a) Se ha definido el procedimiento de evaluación de las actividades o intervenciones, e) Se ha definido y elaborado la documentación necesaria para la evaluación de las actividades y del proyecto | App fitness desplegada productiva, manual usuario fitness completo |

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

### 📈 **Stack Técnico Unificado**
- **Backend:** Laravel 10 + Blade + MySQL
- **Frontend:** Bootstrap 5 + JavaScript Vanilla
- **Deployment:** Docker + GitHub Actions
- **Testing:** PHPUnit básico + testing manual
- **Metodología:** 8 sprints de 3 semanas cada uno

**🕒 Duración:** 7 meses (135-189 horas totales, 15-21h por sprint)  
**🎓 Nivel:** Intermedio de 2º DAW  
**📚 Enfoque:** Consolidación de Laravel + buenas prácticas**

## 📋 **Tabla Resumen: Sprints vs RA por Proyecto (7 meses)**

| Proyecto | Sprint 1 | Sprint 2 | Sprint 3 | Sprint 4 | Sprint 5 | Sprint 6 | Sprint 7 | Sprint 8 | Sprint 9 |
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| **TaskManager Pro** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |
| **BiblioTech** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |
| **EventosLocal** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |
| **TiendaOnline** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |
| **RecetasFáciles** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |
| **FitnessTracker** | RA1 | RA2 | RA2 | RA2 | RA2 | RA3 | RA3 | RA4 | RA4 |

### 🎯 **Patrón de Evaluación por Sprint (7 meses):**
- **Sprint 1:** **RA1** (Análisis del sector, identificación de necesidades, justificación del proyecto)
- **Sprints 2-5:** **RA2** (Diseño completo del proyecto, arquitectura, documentación técnica)
- **Sprints 6-7:** **RA3** (Planificación de ejecución, metodología ágil, gestión de recursos)
- **Sprints 8-9:** **RA4** (Control y seguimiento, métricas, evaluación continua, entrega final)

### 📊 **Distribución de Entregables por RA:**

#### **RA1 - Sprint 1 (Análisis del Sector)**
- Estudio de empresas del sector TIC
- Identificación de necesidades del mercado
- Justificación del proyecto elegido
- Marco legal y ayudas disponibles
- Plan inicial de trabajo

#### **RA2 - Sprints 2-5 (Diseño del Proyecto)**
- Documentación técnica completa
- Estudio de viabilidad
- Arquitectura del sistema
- Especificaciones funcionales
- Presupuesto y recursos

#### **RA3 - Sprints 6-7 (Planificación de Ejecución)**
- Metodología ágil implementada
- Cronograma de desarrollo
- Gestión de riesgos
- Procedimientos de trabajo
- Asignación de recursos

#### **RA4 - Sprints 8-9 (Control y Seguimiento)**
- Sistema de métricas implementado
- Control de calidad
- Gestión de cambios
- Evaluación con usuarios
- Documentación final

### 📋 Product Backlog - TiendaOnline

| Fase | Tarea | Tipo | Estimación | Prioridad |
|------|--------|-------|-------------|------------|
| **Análisis** | Análisis de e-commerce | Análisis | 4h | Alta |
| **Análisis** | Diseño de base de datos | Análisis | 6h | Alta |
| **Desarrollo** | CRUD productos | Desarrollo | 12h | Alta |
| **Desarrollo** | CRUD categorías | Desarrollo | 8h | Alta |
| **Desarrollo** | Sistema de usuarios | Desarrollo | 10h | Alta |
| **Desarrollo** | Carrito de compra | Desarrollo | 16h | Alta |
| **Desarrollo** | Proceso checkout | Desarrollo | 14h | Alta |
| **Desarrollo** | Gestión de pedidos | Desarrollo | 12h | Media |
| **Desarrollo** | Panel administración | Desarrollo | 10h | Media |
| **Desarrollo** | Búsqueda productos | Desarrollo | 8h | Media |
| **Desarrollo** | Subida imágenes | Desarrollo | 6h | Media |
| **Desarrollo** | Reportes básicos | Desarrollo | 8h | Baja |
| **Desarrollo** | Frontend responsive | Desarrollo | 14h | Alta |
| **Pruebas** | Testing flujos compra | Prueba | 8h | Alta |
| **Despliegue** | Docker setup | Despliegue | 4h | Alta |
| **Documentación** | Manual administrador | Documentación | 6h | Media |

### 📋 Product Backlog - RecetasFáciles

| Fase | Tarea | Tipo | Estimación | Prioridad |
|------|--------|-------|-------------|------------|
| **Análisis** | Análisis red social | Análisis | 4h | Alta |
| **Análisis** | Diseño base de datos | Análisis | 4h | Alta |
| **Desarrollo** | Sistema usuarios | Desarrollo | 8h | Alta |
| **Desarrollo** | CRUD recetas | Desarrollo | 14h | Alta |
| **Desarrollo** | Subida de fotos | Desarrollo | 8h | Alta |
| **Desarrollo** | Sistema valoraciones | Desarrollo | 10h | Media |
| **Desarrollo** | Comentarios | Desarrollo | 8h | Media |
| **Desarrollo** | Lista favoritos | Desarrollo | 6h | Media |
| **Desarrollo** | Búsqueda avanzada | Desarrollo | 10h | Media |
| **Desarrollo** | Feed recetas | Desarrollo | 8h | Media |
| **Desarrollo** | Categorías | Desarrollo | 6h | Baja |
| **Desarrollo** | Frontend bootstrap | Desarrollo | 12h | Alta |
| **Pruebas** | Testing interacciones | Prueba | 6h | Media |
| **Despliegue** | Containerización | Despliegue | 4h | Alta |
| **Documentación** | Guía usuario | Documentación | 4h | Media |

### 📋 Product Backlog - FitnessTracker

| Fase | Tarea | Tipo | Estimación | Prioridad |
|------|--------|-------|-------------|------------|
| **Análisis** | Análisis métricas fitness | Análisis | 4h | Alta |
| **Análisis** | Diseño base de datos | Análisis | 4h | Alta |
| **Desarrollo** | Perfiles usuario | Desarrollo | 8h | Alta |
| **Desarrollo** | CRUD entrenamientos | Desarrollo | 12h | Alta |
| **Desarrollo** | Dashboard básico | Desarrollo | 10h | Alta |
| **Desarrollo** | Gráficos Chart.js | Desarrollo | 12h | Media |
| **Desarrollo** | Calendario fitness | Desarrollo | 8h | Media |
| **Desarrollo** | Sistema objetivos | Desarrollo | 10h | Media |
| **Desarrollo** | Logros y badges | Desarrollo | 8h | Baja |
| **Desarrollo** | Estadísticas | Desarrollo | 8h | Media |
| **Desarrollo** | Recordatorios | Desarrollo | 6h | Baja |
| **Desarrollo** | Frontend responsive | Desarrollo | 12h | Alta |
| **Pruebas** | Testing cálculos | Prueba | 6h | Media |
| **Despliegue** | Docker y CI/CD | Despliegue | 4h | Alta |
| **Documentación** | Manual fitness | Documentación | 4h | Media |

---
### 🔧 **Consideraciones Técnicas**
- Todos los proyectos incluyen **CI/CD** para automatización
- **Testing** obligatorio en todas las fases
- **Documentación** como parte integral del proyecto
- **Escalabilidad** considerada desde el diseño

### 📈 **Evaluación Continua**
- **Revisiones semanales** con criterios específicos
- **Entregas incrementales** cada 2 semanas
- **Peer review** del código entre compañeros
- **Presentaciones técnicas** regulares

### 🌟 **Valor Añadido**
Cada proyecto puede ser **portfolio real** para el estudiante, con potencial de:
- Publicación en GitHub como proyecto destacado
- Inclusión en CV como experiencia práctica
- Base para trabajos fin de estudios superiores
- Semilla para proyectos emprendedores

---

## 🎓 **Metodología de Aprendizaje Progresivo**

### 📅 **Evolución Tecnológica por Sprints**

| Periodo | Sprints | Tecnologías | Objetivos de Aprendizaje |
|---------|---------|-------------|--------------------------|
| **Fase 1** | 1-2 | HTML5, CSS3, JavaScript, Bootstrap | Consolidar frontend, interactividad básica |
| **Fase 2** | 3 | PHP vanilla, MySQL, phpMyAdmin | Introducir backend, persistencia datos |
| **Fase 3** | 4-5 | Laravel básico/intermedio, Eloquent | Migrar a framework, ORM, arquitectura MVC |
| **Fase 4** | 6-7 | Laravel avanzado, Auth, AJAX | Funcionalidades completas, optimización UX |
| **Fase 5** | 8-9 | Testing, Docker, despliegue | Calidad código, containerización, producción |

### 🎯 **Ventajas de esta Metodología**

#### ✅ **Para Estudiantes:**
- **Progresión natural:** De lo conocido (HTML/CSS) a lo nuevo (Laravel/Docker)
- **Confianza gradual:** Éxitos tempranos con tecnologías familiares
- **Comprensión profunda:** Entender el "por qué" de los frameworks
- **Portfolio incremental:** Cada sprint añade valor al proyecto

#### ✅ **Para Docentes:**
- **Flexibilidad temporal:** Adaptable al ritmo real de aprendizaje
- **Evaluación granular:** RA específicos por cada fase tecnológica
- **Soporte escalonado:** Más ayuda en fases nuevas (Laravel), menos en conocidas (HTML)
- **Recuperación posible:** Estudiantes rezagados pueden ponerse al día

### 🔄 **Estrategia de Transición**

#### **Sprints 1-2: Consolidación Frontend**
- Reforzar HTML5, CSS3, JavaScript
- Introducir Bootstrap 5 y responsive design
- Simulación de datos con LocalStorage/arrays JS
- **Objetivo:** Confianza y competencia en frontend

#### **Sprint 3: Puente Backend**
- PHP básico para conectar con conocimiento previo
- MySQL directo para entender persistencia
- CRUD manual para valorar después las facilidades de Laravel
- **Objetivo:** Comprender la lógica backend sin complejidad framework

#### **Sprints 4-5: Adopción Laravel**
- Migración gradual del código PHP vanilla
- Comparar antes/después para apreciar ventajas
- Introducir conceptos MVC paso a paso
- **Objetivo:** Adopción natural del framework

#### **Sprints 6-7: Dominio Laravel**
- Funcionalidades avanzadas cuando ya dominan lo básico
- Autenticación, middleware, optimizaciones
- **Objetivo:** Competencia profesional en Laravel

#### **Sprints 8-9: Profesionalización**
- Testing, Docker, despliegue cuando el código funciona
- Documentación y presentación profesional
- **Objetivo:** Preparación para entorno laboral

### 📚 **Recursos de Apoyo Sugeridos**

#### **Sprint 1-2:** Documentación frontend
- MDN Web Docs, Bootstrap documentation
- Tutoriales JavaScript interactivos

#### **Sprint 3:** PHP básico
- PHP.net documentation
- Tutoriales MySQL básicos

#### **Sprint 4-5:** Laravel learning
- Laravel documentation, Laracasts
- Tutoriales migración PHP → Laravel

#### **Sprint 6-9:** Laravel avanzado
- Laravel ecosystem (testing, deployment)
- Docker básico para developers

---
