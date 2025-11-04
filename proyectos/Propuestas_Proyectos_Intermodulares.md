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

| Sprint | RA Principales | Criterios de Evaluación | Entregables Clave |
|--------|----------------|-------------------------|-------------------|
| **Sprint 1** | RA1, RA3 | Análisis requisitos, diseño interfaz, maquetación | Wireframes, HTML/CSS estático |
| **Sprint 2** | RA3, RA2 | Interactividad frontend, manipulación DOM | JavaScript funcional, simulación datos |
| **Sprint 3** | RA2, RA4 | Desarrollo backend básico, gestión BD | CRUD PHP, conexión MySQL |
| **Sprint 4** | RA2, RA1 | Migración Laravel, arquitectura MVC | Estructura Laravel, rutas y vistas |
| **Sprint 5** | RA2, RA5 | Modelos ORM, validaciones | Sistema Eloquent, calidad código |
| **Sprint 6** | RA2, RA4 | Autenticación, funcionalidades avanzadas | Auth Laravel, features completas |
| **Sprint 7** | RA3, RA5 | Optimización UX, integración AJAX | Interfaz pulida, experiencia usuario |
| **Sprint 8** | RA5 | Testing, debugging, calidad código | Tests implementados, bugs corregidos |
| **Sprint 9** | RA4, RA6 | Despliegue, documentación técnica | App desplegada, documentación completa |

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
| **Sprint 1** | RA1, RA4 | Análisis de procesos bibliotecarios, diseño de datos | Modelo de procesos, E/R, entorno configurado |
| **Sprint 2** | RA2, RA3 | Implementa CRUD complejo, gestiona códigos especializados | Gestión libros con ISBN, categorización |
| **Sprint 3** | RA2, RA5 | Gestiona roles y permisos, validaciones específicas | Sistema usuarios multi-rol, validaciones |
| **Sprint 4** | RA2, RA5 | Implementa lógica compleja, cálculos de fechas | Sistema préstamos, control disponibilidad |
| **Sprint 5** | RA2, RA5 | Algoritmos de cálculo, gestión de errores | Control multas, validación devoluciones |
| **Sprint 6** | RA3, RA2 | Funcionalidades avanzadas, notificaciones | Reservas, sistema notificaciones |
| **Sprint 7** | RA3, RA6 | Búsqueda dinámica, generación reportes | Catálogo funcional, estadísticas |
| **Sprint 8** | RA3 | Interfaz especializada, usabilidad bibliotecaria | UX optimizada, accesibilidad |
| **Sprint 9** | RA5, RA4, RA6 | Testing crítico, despliegue, documentación | Sistema productivo, manual bibliotecario |

### 📋 Product Backlog Detallado - BiblioTech

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis procesos bibliotecarios | Estudio workflows biblioteca básicos: préstamos, devoluciones, usuarios | Sprint 1 | 4h | Alta |
| T2 | Diseño base datos | E/R biblioteca: libros, usuarios, préstamos, multas básicas | Sprint 1 | 4h | Alta |
| T3 | Configuración Laravel | Setup Laravel, autenticación multi-rol, seeders datos prueba | Sprint 1 | 10h | Alta |
| T4 | CRUD Libros básico | Modelo libros: título, autor, ISBN, ubicación, estado disponibilidad | Sprint 2 | 8h | Alta |
| T5 | Frontend gestión libros | Formularios libros, listado con búsqueda simple, validaciones | Sprint 2 | 8h | Alta |
| T6 | Sistema usuarios biblioteca | Tipos usuario: socio, empleado. Perfiles con datos contacto | Sprint 3 | 6h | Alta |
| T7 | Gestión perfiles | CRUD usuarios, asignación roles, validaciones formularios | Sprint 3 | 10h | Alta |
| T8 | Sistema préstamos básico | Lógica préstamos: verificar disponibilidad, registrar préstamo | Sprint 4 | 10h | Alta |
| T9 | Frontend préstamos | Interfaz préstamos: buscar libro, seleccionar usuario, confirmar | Sprint 4 | 6h | Alta |
| T10 | Control devoluciones | Proceso devolución: marcar devuelto, calcular días retraso básico | Sprint 5 | 8h | Alta |
| T11 | Cálculo multas simple | Algoritmo multas básico: días retraso × tarifa fija | Sprint 5 | 8h | Media |
| T12 | Sistema reservas básico | Reservar libros no disponibles, notificación disponibilidad | Sprint 6 | 10h | Media |
| T13 | Búsqueda catálogo | Búsqueda por título, autor, ISBN, filtros disponibilidad | Sprint 6 | 6h | Media |
| T14 | Reportes bibliotecarios | Estadísticas básicas: libros prestados, usuarios activos | Sprint 7 | 8h | Baja |
| T15 | Frontend bibliotecario | UX biblioteca: scanner códigos, atajos, pantallas trabajo | Sprint 7 | 8h | Media |
| T16 | Frontend responsive | Optimización móvil, navegación táctil para tablets | Sprint 8 | 10h | Alta |
| T17 | Testing lógica biblioteca | Tests: cálculos fechas, multas, disponibilidad, validaciones | Sprint 8 | 6h | Media |
| T18 | Despliegue biblioteca | Docker, configuración producción, backup datos | Sprint 9 | 8h | Alta |
| T19 | Documentación biblioteca | Manual bibliotecario, guía usuarios, procesos básicos | Sprint 9 | 8h | Media |
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
| **Sprint 1** | RA1, RA4 | Análisis de eventos comunitarios, arquitectura | Tipos de eventos definidos, base configurada |
| **Sprint 2** | RA2, RA3 | Implementa CRUD eventos, gestiona categorías | Gestión eventos completa con validaciones |
| **Sprint 3** | RA2, RA5 | Lógica inscripciones, control límites | Sistema inscripciones, control plazas |
| **Sprint 4** | RA3, RA2 | Visualización interactiva, manipulación DOM | Calendario dinámico, timeline eventos |
| **Sprint 5** | RA2, RA3 | Búsqueda avanzada, filtros múltiples | Sistema búsqueda, UX optimizada |
| **Sprint 6** | RA4, RA2 | Gestión archivos, integración APIs externas | Subida imágenes, Google Maps funcional |
| **Sprint 7** | RA2, RA3 | Servicios externos, notificaciones | Avisos automáticos, sistema valoraciones |
| **Sprint 8** | RA3 | Interfaz coherente, experiencia usuario | UX eventos optimizada, galería multimedia |
| **Sprint 9** | RA5, RA4, RA6 | Testing flujos, despliegue, documentación | Pruebas completas, API desplegada |

### 📋 Product Backlog Detallado - EventosLocal

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis eventos comunitarios | Estudio tipos eventos locales básicos: culturales, deportivos, categorías | Sprint 1 | 4h | Alta |
| T2 | Diseño base datos eventos | E/R: eventos, categorías, inscripciones, usuarios básicos | Sprint 1 | 4h | Alta |
| T3 | Configuración Laravel eventos | Setup Laravel, autenticación usuarios/organizadores básica | Sprint 1 | 10h | Alta |
| T4 | CRUD Eventos básico | Modelo eventos: título, descripción, fecha, ubicación texto, plazas | Sprint 2 | 8h | Alta |
| T5 | Frontend gestión eventos | Formularios eventos, validación fechas, listado simple | Sprint 2 | 8h | Alta |
| T6 | Sistema inscripciones | Lógica inscripciones: verificar plazas, registrar inscripción | Sprint 3 | 8h | Alta |
| T7 | Frontend inscripciones | Interfaz inscripciones: formulario, confirmación simple | Sprint 3 | 8h | Alta |
| T8 | Vista calendario básica | Calendario mensual con eventos, navegación fechas | Sprint 4 | 10h | Media |
| T9 | Lista eventos | Vista cronológica eventos, filtro por proximidad | Sprint 4 | 6h | Media |
| T10 | Búsqueda eventos | Búsqueda por texto, categoría, fecha básica | Sprint 5 | 8h | Media |
| T11 | Filtros básicos | Filtros: fecha, categoría, disponibilidad plazas | Sprint 5 | 8h | Media |
| T12 | Gestión imágenes | Subida imagen evento, mostrar en listado | Sprint 6 | 8h | Media |
| T13 | Ubicaciones básicas | Texto ubicación, enlace Google Maps externo | Sprint 6 | 8h | Baja |
| T14 | Notificaciones email | Avisos email: confirmación inscripción, recordatorios | Sprint 7 | 8h | Media |
| T15 | Sistema valoraciones básico | Valorar eventos asistidos, puntuaciones simples | Sprint 7 | 8h | Baja |
| T16 | Frontend eventos responsive | UX eventos: tarjetas responsive, navegación móvil | Sprint 8 | 10h | Alta |
| T17 | Galería imágenes | Mostrar imágenes eventos, galería básica | Sprint 8 | 6h | Media |
| T18 | Testing flujos eventos | Tests: inscripciones, límites plazas, validaciones | Sprint 9 | 8h | Alta |
| T19 | Despliegue eventos | Docker, configuración producción, manual básico | Sprint 9 | 8h | Alta |

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
| **Sprint 1** | RA1, RA4 | Análisis e-commerce, diseño catálogo | Modelo productos, categorías configuradas |
| **Sprint 2** | RA2, RA3 | Sistema usuarios, panel administración | Autenticación clientes/admin funcional |
| **Sprint 3** | RA2, RA5 | Lógica carrito, sesiones persistentes | Carrito funcional, almacenamiento sesión |
| **Sprint 4** | RA2, RA5 | Proceso checkout, gestión pedidos | Flujo compra completo, estados pedidos |
| **Sprint 5** | RA2, RA3 | Búsqueda avanzada, administración | Motor búsqueda, panel admin completo |
| **Sprint 6** | RA4, RA2 | Gestión multimedia, reportes | Imágenes productos, estadísticas ventas |
| **Sprint 7** | RA3 | Interfaz e-commerce, experiencia compra | UX tienda optimizada, navegación intuitiva |
| **Sprint 8** | RA5 | Testing transacciones, rendimiento | Pruebas críticas, optimización queries |
| **Sprint 9** | RA4, RA6 | Despliegue producción, documentación | Tienda desplegada, manual administrador |

### 📋 Product Backlog Detallado - TiendaOnline

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis requisitos e-commerce | Estudio flujos tienda básicos: catálogo, carrito, checkout simple | Sprint 1 | 4h | Alta |
| T2 | Diseño base datos comercial | E/R: productos, categorías, usuarios, pedidos, carrito | Sprint 1 | 4h | Alta |
| T3 | CRUD Productos y Categorías | Gestión catálogo: crear productos, categorías, precios, stock | Sprint 1 | 10h | Alta |
| T4 | Sistema usuarios clientes | Registro clientes, perfiles básicos, autenticación | Sprint 2 | 6h | Alta |
| T5 | Panel administración básico | Área admin: gestión productos básica, listado pedidos | Sprint 2 | 10h | Alta |
| T6 | Carrito compra backend | Lógica carrito: agregar productos, calcular totales, sesiones | Sprint 3 | 8h | Alta |
| T7 | Carrito compra frontend | Interfaz carrito: vista productos, cantidad, eliminar items | Sprint 3 | 8h | Alta |
| T8 | Proceso checkout básico | Flujo compra: datos cliente, resumen pedido, confirmación | Sprint 4 | 10h | Alta |
| T9 | Gestión pedidos simple | Estados pedidos básicos: pendiente, procesando, completado | Sprint 4 | 6h | Alta |
| T10 | Búsqueda productos | Búsqueda por nombre, filtros categoría, disponibilidad | Sprint 5 | 8h | Media |
| T11 | Panel admin completo | Gestión avanzada productos, reportes pedidos básicos | Sprint 5 | 8h | Media |
| T12 | Gestión imágenes productos | Subida imagen producto, mostrar en catálogo | Sprint 6 | 8h | Media |
| T13 | Reportes ventas básicos | Estadísticas: productos vendidos, ingresos básicos | Sprint 6 | 8h | Baja |
| T14 | Frontend tienda responsive | UX e-commerce: navegación categorías, ficha producto móvil | Sprint 7 | 10h | Alta |
| T15 | Optimización UX compra | Mejoras usabilidad: breadcrumbs, filtros, paginación | Sprint 7 | 6h | Media |
| T16 | Testing flujos e-commerce | Tests: carrito, checkout, gestión stock básico | Sprint 8 | 8h | Alta |
| T17 | Optimización rendimiento | Caché productos, índices BD básicos | Sprint 8 | 8h | Media |
| T18 | Despliegue tienda | Docker tienda, configuración básica producción | Sprint 9 | 8h | Alta |
| T19 | Documentación comercial | Manual administrador, guía configuración productos | Sprint 9 | 8h | Media |

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
| **Sprint 1** | RA1, RA2 | Análisis social, autenticación | Modelo usuarios, perfiles funcionales |
| **Sprint 2** | RA2, RA4 | CRUD complejo, gestión archivos | Sistema recetas, subida imágenes |
| **Sprint 3** | RA2, RA3 | Interactividad, validaciones | Valoraciones, sistema comentarios |
| **Sprint 4** | RA2, RA3 | Funcionalidades usuario, organización | Favoritos, categorías dinámicas |
| **Sprint 5** | RA3, RA2 | Búsqueda avanzada, algoritmos feed | Motor búsqueda, timeline personalizado |
| **Sprint 6** | RA2, RA3 | Funciones sociales, notificaciones | Seguimiento, sistema avisos |
| **Sprint 7** | RA3 | Interfaz social, experiencia usuario | UX optimizada, navegación social |
| **Sprint 8** | RA5 | Testing interacciones, validación social | Pruebas comunidad, rendimiento |
| **Sprint 9** | RA4, RA6 | Despliegue social, documentación | Comunidad desplegada, guías usuario |

### 📋 Product Backlog Detallado - RecetasFáciles

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis red social culinaria | Estudio funciones básicas: perfiles, recetas, interacciones simples | Sprint 1 | 4h | Alta |
| T2 | Diseño base datos social | E/R: usuarios, recetas, valoraciones, comentarios, favoritos | Sprint 1 | 4h | Alta |
| T3 | Sistema perfiles usuarios | Registro usuarios, perfiles personalizados, foto perfil | Sprint 1 | 10h | Alta |
| T4 | CRUD Recetas básico | Modelo recetas: ingredientes, pasos, dificultad, categorías | Sprint 2 | 8h | Alta |
| T5 | Frontend recetas | Formulario recetas: ingredientes dinámicos, subida foto | Sprint 2 | 8h | Alta |
| T6 | Sistema valoraciones | Rating estrellas (1-5), contador valoraciones simple | Sprint 3 | 6h | Media |
| T7 | Sistema comentarios | CRUD comentarios en recetas, mostrar temporal | Sprint 3 | 10h | Media |
| T8 | Lista favoritos | Agregar/quitar favoritos, vista favoritos usuario | Sprint 4 | 6h | Media |
| T9 | Categorías recetas | Gestión categorías: postres, principales, vegetariano | Sprint 4 | 10h | Media |
| T10 | Búsqueda recetas | Motor búsqueda: ingredientes, nombre, categoría | Sprint 5 | 8h | Media |
| T11 | Feed básico | Timeline recetas: recientes, populares básico | Sprint 5 | 8h | Media |
| T12 | Seguimiento usuarios | Seguir/dejar seguir usuarios, listas básicas | Sprint 6 | 8h | Baja |
| T13 | Notificaciones básicas | Avisos: nuevos comentarios, valoraciones | Sprint 6 | 8h | Baja |
| T14 | Frontend social responsive | UX social: feed visual, tarjetas recetas responsivas | Sprint 7 | 10h | Alta |
| T15 | Optimización UX | Infinite scroll básico, búsqueda mejorada | Sprint 7 | 6h | Media |
| T16 | Testing interacciones | Tests: comentarios, valoraciones, favoritos | Sprint 8 | 8h | Alta |
| T17 | Optimización rendimiento | Caché básico, optimización queries principales | Sprint 8 | 8h | Media |
| T18 | Despliegue comunidad | Docker, configuración social básica | Sprint 9 | 8h | Alta |
| T19 | Documentación comunidad | Manual usuarios, guías contenido básicas | Sprint 9 | 8h | Media |

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
| **Sprint 1** | RA1, RA2 | Análisis métricas fitness, modelado datos | Perfiles usuarios, objetivos definidos |
| **Sprint 2** | RA2, RA3 | CRUD entrenamientos, tipos ejercicios | Sistema actividades, categorización |
| **Sprint 3** | RA2, RA3 | Dashboard funcional, métricas básicas | Vista principal, estadísticas tiempo real |
| **Sprint 4** | RA3, RA2 | Visualizaciones, manipulación DOM | Gráficos Chart.js, progreso visual |
| **Sprint 5** | RA2, RA3 | Sistema objetivos, planificación | Metas personales, calendario dinámico |
| **Sprint 6** | RA2, RA3 | Gamificación, automatización | Logros, recordatorios programados |
| **Sprint 7** | RA2, RA6 | Algoritmos estadísticas, reportes | Análisis avanzado, informes progreso |
| **Sprint 8** | RA3 | Interfaz fitness, experiencia deportiva | UX optimizada, navegación intuitiva |
| **Sprint 9** | RA5, RA4, RA6 | Testing métricas, despliegue, documentación | App desplegada, manual usuario fitness |

### 📋 Product Backlog Detallado - FitnessTracker

| ID | Tarea | Descripción Específica | Sprint | Estimación | Prioridad |
|----|-------|------------------------|--------|-------------|-----------|
| T1 | Análisis métricas fitness | Estudio métricas básicas: tipos ejercicio, duración, calorías | Sprint 1 | 4h | Alta |
| T2 | Diseño base datos fitness | E/R: usuarios_fitness, entrenamientos, ejercicios, objetivos | Sprint 1 | 4h | Alta |
| T3 | Perfiles usuarios fitness | Registro con datos físicos: peso, altura, nivel actividad | Sprint 1 | 10h | Alta |
| T4 | CRUD Entrenamientos | Gestión sesiones: fecha, duración, tipo, intensidad básica | Sprint 2 | 8h | Alta |
| T5 | Catálogo ejercicios | Biblioteca ejercicios: cardio, fuerza, flexibilidad | Sprint 2 | 8h | Alta |
| T6 | Dashboard principal | Vista resumen: entrenamientos semana, métricas básicas | Sprint 3 | 8h | Alta |
| T7 | Métricas básicas | Cálculos: calorías totales, tiempo entrenado semanal | Sprint 3 | 8h | Media |
| T8 | Gráficos progreso | Visualización básica con Chart.js: líneas temporales | Sprint 4 | 10h | Media |
| T9 | Indicadores visuales | Barras progreso objetivos, medidores nivel | Sprint 4 | 6h | Media |
| T10 | Sistema objetivos | Crear metas: peso objetivo, entrenamientos semanales | Sprint 5 | 8h | Media |
| T11 | Calendario entrenamientos | Vista calendario con entrenamientos realizados | Sprint 5 | 8h | Media |
| T12 | Sistema logros básico | Logros automáticos: racha entrenamientos, hitos básicos | Sprint 6 | 8h | Baja |
| T13 | Recordatorios simples | Avisos básicos entrenamientos programados | Sprint 6 | 8h | Baja |
| T14 | Estadísticas básicas | Análisis progreso: tendencias, comparativas semanales | Sprint 7 | 8h | Media |
| T15 | Reportes simples | Resumen progreso, estadísticas mensuales básicas | Sprint 7 | 8h | Baja |
| T16 | Frontend fitness responsive | UX deportiva: dashboard móvil, formularios rápidos | Sprint 8 | 10h | Alta |
| T17 | Optimización UX fitness | Navegación rápida, widgets dashboard básicos | Sprint 8 | 6h | Media |
| T18 | Testing métricas | Tests: cálculos calorías, progreso objetivos básicos | Sprint 9 | 8h | Alta |
| T19 | Despliegue app fitness | Docker, configuración básica, documentación usuario | Sprint 9 | 8h | Alta |

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
| **TaskManager Pro** | RA1,RA4 | RA2,RA3 | RA2,RA5 | RA3,RA2 | RA2,RA3 | RA3,RA4 | RA3,RA6 | RA5 | RA4,RA6 |
| **BiblioTech** | RA1,RA4 | RA2,RA3 | RA2,RA5 | RA2,RA5 | RA2,RA5 | RA3,RA2 | RA3,RA6 | RA3 | RA5,RA4,RA6 |
| **EventosLocal** | RA1,RA4 | RA2,RA3 | RA2,RA5 | RA3,RA2 | RA2,RA3 | RA4,RA2 | RA2,RA3 | RA3 | RA5,RA4,RA6 |
| **TiendaOnline** | RA1,RA4 | RA2,RA3 | RA2,RA5 | RA2,RA5 | RA2,RA3 | RA4,RA2 | RA3 | RA5 | RA4,RA6 |
| **RecetasFáciles** | RA1,RA2 | RA2,RA4 | RA2,RA3 | RA2,RA3 | RA3,RA2 | RA2,RA3 | RA3 | RA5 | RA4,RA6 |
| **FitnessTracker** | RA1,RA2 | RA2,RA3 | RA2,RA3 | RA3,RA2 | RA2,RA3 | RA2,RA3 | RA2,RA6 | RA3 | RA5,RA4,RA6 |

### 🎯 **Patrón de Evaluación por Sprint (7 meses):**
- **Sprints 1-2:** Enfoque en **RA1** (Análisis/Diseño) y **RA2** (Desarrollo inicial)
- **Sprints 3-5:** Consolidación **RA2** (Funcionalidades core) y **RA3** (Interfaz)  
- **Sprints 6-7:** Integración **RA3** (UX avanzada) y **RA4** (Recursos técnicos)
- **Sprint 8:** Concentración en **RA3** (Interfaz final) y **RA5** (Testing)
- **Sprint 9:** Culminación con **RA4** (Despliegue), **RA5** (Pruebas) y **RA6** (Documentación)

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
