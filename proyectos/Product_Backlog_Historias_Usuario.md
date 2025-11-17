# 📋 Product Backlog basado en Historias de Usuario

## 🎯 ¿Qué son las Historias de Usuario?

Las **Historias de Usuario** (User Stories) son descripciones cortas y simples de una funcionalidad contada desde la perspectiva del usuario final. Son la unidad fundamental del Product Backlog en metodologías ágiles como Scrum.

### 📝 Estructura de una Historia de Usuario

Una historia de usuario sigue el formato estándar:

```
Como [tipo de usuario]
Quiero [realizar una acción/funcionalidad]
Para [obtener un beneficio/valor]
```

**Ejemplo:**
```
Como usuario registrado
Quiero poder crear nuevas tareas
Para organizar mi trabajo diario
```

---

## 🏗️ Componentes del Product Backlog

Un Product Backlog completo debe incluir:

1. **ID Historia**: Identificador único de la historia de usuario (ej: US-001)
2. **Enunciado de la Historia**: Descripción usando el formato estándar
3. **Tareas Técnicas**: Descomposición técnica de la historia en tareas implementables
4. **Estado**: Situación actual (Pendiente, En progreso, Completada)
5. **Dimensión de Esfuerzo**: Estimación en horas o puntos de historia
6. **Sprint**: Sprint al que está asignada la historia
7. **Prioridad**: Importancia relativa (Alta, Media, Baja)

### 🎲 Criterios de Aceptación

Cada historia debe incluir **criterios de aceptación** que definen cuándo se considera completada:

- Son condiciones específicas y medibles
- Definen el comportamiento esperado
- Permiten validar que la funcionalidad cumple con lo requerido

**Ejemplo de Criterios de Aceptación:**
```
✓ El formulario muestra campos: título, descripción, fecha límite
✓ Todos los campos son obligatorios
✓ Se muestra mensaje de éxito tras crear la tarea
✓ La tarea aparece en el listado inmediatamente
```

---

## 📊 Ejemplo Práctico: Product Backlog TaskManager Pro

A continuación se presenta el Product Backlog completo del proyecto **TaskManager Pro** estructurado mediante historias de usuario:

### 🗂️ Leyenda de Estados

- **Pendiente**: Historia no iniciada
- **En progreso**: Historia en desarrollo activo
- **Completada**: Historia finalizada y validada
- **Bloqueada**: Historia con impedimentos

### 📏 Estimación de Esfuerzo

- Las estimaciones están en **horas de trabajo**
- Basadas en sprints de 3 semanas (15-21h por sprint)
- Consideran la curva de aprendizaje de los alumnos

---

## 📋 PRODUCT BACKLOG - TASKMANAGER PRO

### Sprint 1: Análisis y Frontend Estático (Semanas 1-3)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-001** | **Como** Product Owner<br>**Quiero** tener un análisis detallado de las necesidades del sistema<br>**Para** entender qué funcionalidades debe tener la aplicación | • Análisis de requisitos funcionales y no funcionales<br>• Definición de casos de uso principales<br>• Identificación de roles de usuario<br>• Creación de wireframes iniciales | Pendiente | 6h | 1 | Alta |
| **US-002** | **Como** usuario<br>**Quiero** ver una página de inicio atractiva<br>**Para** entender qué ofrece la aplicación | • Maquetación HTML5 semántica de landing page<br>• Diseño CSS con Bootstrap 5<br>• Sección hero con call-to-action<br>• Sección de características principales | Pendiente | 4h | 1 | Alta |
| **US-003** | **Como** usuario<br>**Quiero** navegar entre diferentes páginas<br>**Para** explorar todas las funcionalidades | • Estructura HTML de páginas principales<br>• Menú de navegación responsive<br>• Footer con información de contacto<br>• Sistema de rutas estático | Pendiente | 4h | 1 | Alta |

**Criterios de Aceptación US-001:**
- ✓ Documento de requisitos con al menos 8 funcionalidades principales
- ✓ Identificados 3 roles de usuario: Admin, Usuario estándar, Invitado
- ✓ Wireframes de 5 pantallas principales
- ✓ Casos de uso documentados con flujos principales y alternativos

**Criterios de Aceptación US-002:**
- ✓ Landing page responsive en mobile, tablet y desktop
- ✓ Cumple estándares HTML5 semánticos
- ✓ Tiempo de carga < 2 segundos
- ✓ Call-to-action visible sin hacer scroll

**Criterios de Aceptación US-003:**
- ✓ Navegación funcional entre todas las páginas
- ✓ Menú hamburguesa en móvil
- ✓ Página activa resaltada en menú
- ✓ Footer presente en todas las páginas

---

### Sprint 2: Interactividad Frontend con JavaScript (Semanas 4-6)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-004** | **Como** usuario<br>**Quiero** validar los formularios antes de enviarlos<br>**Para** asegurarme de que introduzco datos correctos | • Validación JavaScript de campos obligatorios<br>• Validación de formatos (email, fecha)<br>• Mensajes de error en tiempo real<br>• Prevención de envío con datos inválidos | Pendiente | 8h | 2 | Alta |
| **US-005** | **Como** usuario<br>**Quiero** ver mis tareas en una lista dinámica<br>**Para** tener una vista general de mi trabajo | • Array JavaScript para almacenar tareas<br>• Función para renderizar lista dinámicamente<br>• Manipulación del DOM para añadir/eliminar<br>• Template HTML para items de tarea | Pendiente | 6h | 2 | Alta |
| **US-006** | **Como** usuario<br>**Quiero** que mis datos persistan al recargar la página<br>**Para** no perder mi trabajo | • Implementación de LocalStorage<br>• Serialización de datos a JSON<br>• Carga de datos al iniciar<br>• Sincronización automática | Pendiente | 4h | 2 | Media |

**Criterios de Aceptación US-004:**
- ✓ No se permite enviar formularios con campos vacíos
- ✓ Validación de formato email (contiene @ y dominio)
- ✓ Fechas no pueden ser anteriores a hoy
- ✓ Mensajes de error claros y en español

**Criterios de Aceptación US-005:**
- ✓ Lista muestra todas las tareas almacenadas
- ✓ Cada tarea muestra: título, descripción, estado, fecha
- ✓ Actualización inmediata al añadir/eliminar
- ✓ Interfaz responsive y usable

**Criterios de Aceptación US-006:**
- ✓ Datos persisten tras recargar navegador
- ✓ Funciona en modo incógnito (con limitaciones esperadas)
- ✓ Manejo de errores si LocalStorage está lleno
- ✓ Datos se sincronizan automáticamente

---

### Sprint 3: Backend PHP y Base de Datos (Semanas 7-9)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-007** | **Como** desarrollador<br>**Quiero** tener una base de datos bien diseñada<br>**Para** almacenar la información de forma eficiente | • Diseño del modelo E/R<br>• Normalización a 3FN<br>• Creación de tablas en MySQL<br>• Scripts de datos de prueba (seeders) | Pendiente | 4h | 3 | Alta |
| **US-008** | **Como** desarrollador<br>**Quiero** operaciones CRUD básicas con PHP<br>**Para** gestionar tareas desde el servidor | • Script PHP para CREATE (insertar tarea)<br>• Script PHP para READ (listar/ver tarea)<br>• Script PHP para UPDATE (modificar tarea)<br>• Script PHP para DELETE (eliminar tarea) | Pendiente | 10h | 3 | Alta |
| **US-009** | **Como** usuario<br>**Quiero** que el frontend se conecte con el backend<br>**Para** persistir mis datos en el servidor | • Conexión PHP-MySQL con PDO<br>• Integración formularios HTML con PHP<br>• Manejo de errores de conexión<br>• Redirecciones tras operaciones | Pendiente | 4h | 3 | Alta |

**Criterios de Aceptación US-007:**
- ✓ Base de datos normalizada (3FN)
- ✓ Tablas: usuarios, proyectos, tareas, comentarios
- ✓ Claves primarias y foráneas correctamente definidas
- ✓ Al menos 10 registros de prueba por tabla

**Criterios de Aceptación US-008:**
- ✓ CREATE: Inserta tarea y retorna ID
- ✓ READ: Lista todas las tareas de un usuario
- ✓ UPDATE: Modifica tarea existente
- ✓ DELETE: Elimina tarea (soft o hard delete)
- ✓ Prevención de SQL Injection con prepared statements

**Criterios de Aceptación US-009:**
- ✓ Formulario HTML envía datos a script PHP
- ✓ PHP procesa datos y los inserta en BD
- ✓ Mensajes de éxito/error mostrados al usuario
- ✓ Redirección automática tras operación exitosa

---

### Sprint 4: Introducción a Laravel (Semanas 10-12)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-010** | **Como** desarrollador<br>**Quiero** migrar el proyecto a Laravel<br>**Para** aprovechar las ventajas del framework | • Instalación de Laravel 10<br>• Configuración de entorno (.env)<br>• Estructura de directorios Laravel<br>• Migración inicial de archivos | Pendiente | 4h | 4 | Alta |
| **US-011** | **Como** desarrollador<br>**Quiero** definir las rutas de la aplicación<br>**Para** organizar el enrutamiento correctamente | • Definición de rutas en web.php<br>• Creación de controladores básicos<br>• Implementación de métodos resource<br>• Grupos de rutas con middleware | Pendiente | 8h | 4 | Alta |
| **US-012** | **Como** desarrollador<br>**Quiero** usar plantillas Blade<br>**Para** crear vistas reutilizables y mantenibles | • Migración HTML a plantillas Blade<br>• Creación de layout principal<br>• Componentes reutilizables<br>• Sistema de secciones (@section, @yield) | Pendiente | 6h | 4 | Alta |

**Criterios de Aceptación US-010:**
- ✓ Laravel instalado y funcionando correctamente
- ✓ Configuración de base de datos en .env
- ✓ Servidor de desarrollo levantado (php artisan serve)
- ✓ Página de bienvenida de Laravel visible

**Criterios de Aceptación US-011:**
- ✓ Rutas definidas siguiendo convenciones RESTful
- ✓ Controladores organizados en app/Http/Controllers
- ✓ Rutas agrupadas lógicamente (auth, admin, etc.)
- ✓ Nombres de rutas definidos para uso en vistas

**Criterios de Aceptación US-012:**
- ✓ Layout principal con header, contenido, footer
- ✓ Herencia de plantillas funcionando (@extends)
- ✓ Componentes para elementos repetitivos (botones, cards)
- ✓ Todas las páginas usan Blade

---

### Sprint 5: Modelos Eloquent y ORM (Semanas 13-15)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-013** | **Como** desarrollador<br>**Quiero** crear modelos Eloquent<br>**Para** interactuar con la base de datos de forma elegante | • Creación de modelos (Task, Project, User)<br>• Definición de fillable/guarded<br>• Configuración de casts y dates<br>• Creación de migrations | Pendiente | 6h | 5 | Alta |
| **US-014** | **Como** desarrollador<br>**Quiero** establecer relaciones entre modelos<br>**Para** gestionar asociaciones de datos | • Relación User hasMany Tasks<br>• Relación Task belongsTo User<br>• Relación Project hasMany Tasks<br>• Relación Many-to-Many si necesario | Pendiente | 8h | 5 | Alta |
| **US-015** | **Como** usuario<br>**Quiero** validaciones robustas en el servidor<br>**Para** garantizar la integridad de los datos | • Form Requests personalizados<br>• Reglas de validación complejas<br>• Mensajes de error personalizados<br>• Validaciones únicas en BD | Pendiente | 4h | 5 | Media |

**Criterios de Aceptación US-013:**
- ✓ Modelos creados con convenciones Laravel
- ✓ Migrations ejecutadas correctamente
- ✓ Fillable definido para asignación masiva
- ✓ Seeders para datos de prueba

**Criterios de Aceptación US-014:**
- ✓ Relaciones definidas correctamente
- ✓ Eager loading funciona para prevenir N+1
- ✓ Relaciones inversas definidas
- ✓ Puede acceder a datos relacionados fácilmente

**Criterios de Aceptación US-015:**
- ✓ Validación de todos los campos críticos
- ✓ Mensajes de error en español
- ✓ Validación de unicidad funciona
- ✓ Redirección con errores a formulario

---

### Sprint 6: Autenticación y Funcionalidades Avanzadas (Semanas 16-18)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-016** | **Como** usuario<br>**Quiero** poder registrarme en la aplicación<br>**Para** tener mi propia cuenta | • Implementación Laravel Breeze/UI<br>• Formularios de registro<br>• Hash de contraseñas con bcrypt<br>• Envío de email de verificación (opcional) | Pendiente | 8h | 6 | Alta |
| **US-017** | **Como** usuario registrado<br>**Quiero** iniciar sesión<br>**Para** acceder a mi información privada | • Formulario de login<br>• Autenticación con Laravel Auth<br>• Middleware auth en rutas protegidas<br>• Remember me funcional | Pendiente | 6h | 6 | Alta |
| **US-018** | **Como** usuario<br>**Quiero** comentar en las tareas<br>**Para** comunicarme con mi equipo | • Modelo Comment con relaciones<br>• Formulario de comentarios<br>• Visualización de comentarios por tarea<br>• Edición/eliminación de propios comentarios | Pendiente | 4h | 6 | Media |

**Criterios de Aceptación US-016:**
- ✓ Formulario de registro validado
- ✓ Contraseñas hasheadas en BD
- ✓ Email único por usuario
- ✓ Redirección a dashboard tras registro

**Criterios de Aceptación US-017:**
- ✓ Login con email y contraseña
- ✓ Sesión persistente con "Recuérdame"
- ✓ Rutas protegidas redirigen a login
- ✓ Logout funcional

**Criterios de Aceptación US-018:**
- ✓ Cualquier usuario puede comentar
- ✓ Comentarios asociados a tarea correcta
- ✓ Solo autor puede editar/eliminar su comentario
- ✓ Comentarios ordenados cronológicamente

---

### Sprint 7: Optimización y UX (Semanas 19-21)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-019** | **Como** usuario<br>**Quiero** actualizar tareas sin recargar la página<br>**Para** tener una experiencia más fluida | • Peticiones AJAX con Fetch API<br>• Endpoints API en Laravel<br>• Actualización dinámica del DOM<br>• Spinners de carga | Pendiente | 8h | 7 | Media |
| **US-020** | **Como** usuario móvil<br>**Quiero** que la aplicación se vea bien en mi dispositivo<br>**Para** poder trabajar desde cualquier lugar | • Revisión responsive completa<br>• Mejoras de UX en mobile<br>• Touch gestures si aplicable<br>• Testing en múltiples dispositivos | Pendiente | 8h | 7 | Alta |

**Criterios de Aceptación US-019:**
- ✓ Operaciones CRUD sin recargar página
- ✓ Feedback visual durante operaciones
- ✓ Manejo de errores AJAX
- ✓ Fallback si JavaScript deshabilitado

**Criterios de Aceptación US-020:**
- ✓ Responsive desde 320px hasta 1920px
- ✓ Imágenes optimizadas para móvil
- ✓ Formularios usables en pantallas pequeñas
- ✓ Probado en iOS y Android

---

### Sprint 8: Testing y Calidad (Semanas 22-24)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-021** | **Como** desarrollador<br>**Quiero** tener tests automatizados<br>**Para** garantizar que el código funciona correctamente | • Tests unitarios con PHPUnit<br>• Tests de características (Feature Tests)<br>• Tests de modelos y relaciones<br>• Cobertura mínima 70% | Pendiente | 8h | 8 | Media |
| **US-022** | **Como** equipo de desarrollo<br>**Quiero** corregir bugs detectados<br>**Para** entregar un producto de calidad | • Logging de errores con Laravel Log<br>• Debugging con Laravel Debugbar<br>• Optimización de queries N+1<br>• Corrección de bugs reportados | Pendiente | 8h | 8 | Media |

**Criterios de Aceptación US-021:**
- ✓ Suite de tests ejecutable con `php artisan test`
- ✓ Tests para funcionalidades críticas
- ✓ Tests de autenticación y autorización
- ✓ Cobertura reportada con phpunit --coverage

**Criterios de Aceptación US-022:**
- ✓ Logs almacenados en storage/logs
- ✓ No hay errores 500 en flujos principales
- ✓ Queries optimizadas (sin N+1)
- ✓ Tiempo de respuesta < 500ms en promedio

---

### Sprint 9: Despliegue y Documentación (Semanas 25-27)

| ID Historia | Enunciado de la Historia | Tareas Técnicas Asociadas | Estado | Esfuerzo | Sprint | Prioridad |
|-------------|--------------------------|---------------------------|--------|----------|--------|-----------|
| **US-023** | **Como** DevOps<br>**Quiero** containerizar la aplicación<br>**Para** facilitar el despliegue en cualquier entorno | • Creación de Dockerfile<br>• Configuración docker-compose.yml<br>• Servicios: app, nginx, mysql<br>• Variables de entorno para producción | Pendiente | 8h | 9 | Alta |
| **US-024** | **Como** nuevo desarrollador<br>**Quiero** documentación clara del proyecto<br>**Para** poder entender y contribuir fácilmente | • README.md completo<br>• Guía de instalación paso a paso<br>• Documentación de API<br>• Manual de usuario básico | Pendiente | 8h | 9 | Media |

**Criterios de Aceptación US-023:**
- ✓ Docker build exitoso sin errores
- ✓ docker-compose up levanta todos los servicios
- ✓ Aplicación accesible en localhost
- ✓ Datos persisten tras reiniciar contenedores

**Criterios de Aceptación US-024:**
- ✓ README incluye requisitos y pasos de instalación
- ✓ Documentación de rutas API principales
- ✓ Capturas de pantalla en manual de usuario
- ✓ Troubleshooting de problemas comunes

---

## 📊 Resumen del Product Backlog

### Distribución por Sprint

| Sprint | Número de Historias | Esfuerzo Total | Prioridad Alta | Prioridad Media | Prioridad Baja |
|--------|---------------------|----------------|----------------|-----------------|----------------|
| Sprint 1 | 3 | 14h | 3 | 0 | 0 |
| Sprint 2 | 3 | 18h | 2 | 1 | 0 |
| Sprint 3 | 3 | 18h | 3 | 0 | 0 |
| Sprint 4 | 3 | 18h | 3 | 0 | 0 |
| Sprint 5 | 3 | 18h | 2 | 1 | 0 |
| Sprint 6 | 3 | 18h | 2 | 1 | 0 |
| Sprint 7 | 2 | 16h | 1 | 1 | 0 |
| Sprint 8 | 2 | 16h | 0 | 2 | 0 |
| Sprint 9 | 2 | 16h | 1 | 1 | 0 |
| **TOTAL** | **24** | **152h** | **17** | **7** | **0** |

### Distribución por Prioridad

```
Alta:   17 historias (70.8%)  ████████████████████
Media:   7 historias (29.2%)  ████████
Baja:    0 historias (0%)     
```

### Progresión Tecnológica

1. **Sprints 1-2**: Frontend estático + JavaScript vanilla
2. **Sprint 3**: Backend PHP + MySQL
3. **Sprints 4-5**: Laravel básico + Eloquent
4. **Sprint 6**: Autenticación + Features avanzadas
5. **Sprints 7-8**: Optimización + Testing
6. **Sprint 9**: Despliegue + Documentación

---

## 💡 Consejos para los Alumnos

### ✅ Buenas Prácticas al trabajar con Historias de Usuario

1. **Descomponer historias grandes**: Si una historia necesita más de 12h, divídela
2. **Definir criterios de aceptación claros**: Siempre incluye condiciones verificables
3. **Priorizar valor de negocio**: Las historias más importantes primero
4. **Estimar en equipo**: Usa técnicas como Planning Poker
5. **Refinar constantemente**: El backlog es un documento vivo

### ⚠️ Errores Comunes a Evitar

- ❌ Escribir historias técnicas sin perspectiva de usuario
- ❌ Historias demasiado grandes (épicas sin descomponer)
- ❌ Falta de criterios de aceptación
- ❌ Estimaciones poco realistas
- ❌ No revisar el backlog regularmente

### 🎯 Definición de "Terminado" (Definition of Done)

Una historia se considera **completada** cuando:

- ✅ Todo el código está implementado y funciona
- ✅ Todos los criterios de aceptación se cumplen
- ✅ El código está revisado (code review)
- ✅ Los tests pasan correctamente
- ✅ La funcionalidad está documentada
- ✅ Se ha hecho demo al Product Owner
- ✅ Está desplegada en el entorno correspondiente

---

## 📚 Referencias y Recursos

- **User Stories Applied** - Mike Cohn
- **Scrum Guide** - Ken Schwaber & Jeff Sutherland
- [Mountain Goat Software - User Stories](https://www.mountaingoatsoftware.com/agile/user-stories)
- [Atlassian - Writing User Stories](https://www.atlassian.com/agile/project-management/user-stories)

---

**Nota para el profesor**: Este documento puede ser usado como material didáctico para enseñar a los alumnos cómo construir y gestionar un Product Backlog basado en historias de usuario. Se recomienda hacer ejercicios prácticos de escritura de historias y estimación en equipo.
