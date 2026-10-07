# Capítulo IV: Product Design

En este capítulo detallamos las directrices visuales, arquitectónicas y de experiencia de usuario que guiarán el desarrollo de AI-ToDu. El diseño de nuestro producto se fundamenta en heurísticas de usabilidad estandarizadas, garantizando una curva de aprendizaje mínima y una alta eficiencia operativa para las MYPES.

## 4.1. Style Guidelines

El sistema de diseño de AI-ToDu se fundamenta en principios de claridad, confianza y eficiencia operativa. Dado que la plataforma será utilizada por dueños y administradores de MYPES, así como por jefes de logística y operarios de almacén con diferentes niveles de experiencia tecnológica, la interfaz debe priorizar la legibilidad, la intuición y la consistencia visual en todos los puntos de contacto.

### 4.1.1. General Style Guidelines

La identidad visual de AI-ToDu se fundamenta en los elementos conceptuales de una plataforma digital orientada a la gestión de inventario, ventas y despachos. El diseño integra conceptos relacionados con la organización de productos, el control de existencias, la centralización de información y la automatización de procesos empresariales. El tono de comunicación es profesional, directo y resolutivo, diseñado para transmitir confianza B2B en el entorno de las Micro y Pequeñas Empresas.

**4.1.1.1. Branding**

Para AI-ToDu, el branding se diseñó para mostrar innovación tecnológica, control empresarial y eficiencia operativa. Los elementos conceptuales del isotipo representan la centralización de la información, el seguimiento de los productos y la conexión entre los procesos de almacén, ventas y despacho.

El diseño incluye el imagotipo y el nombre del producto “AI-ToDu” de forma clara y legible, permitiendo que la marca sea reconocida fácilmente dentro de la Landing Page, la aplicación web, los documentos del proyecto y los dispositivos móviles.

<p align="center">
  <img src="Images/Branding-Logo.png" width="400" alt="Logo de AI-ToDu">
</p>

**4.1.1.2. Typography**

La tipografía de AI-ToDu ha sido definida con el objetivo de mantener una interfaz clara, profesional y legible. La familia tipográfica principal de la plataforma es **Inter**, seleccionada por su alta legibilidad en interfaces digitales y su versatilidad para establecer distintos niveles de jerarquía visual:

* **Page Title / H1:** Inter Bold, 32 px
* **Section Heading / H2:** Inter SemiBold, 24 px
* **Subheading / H3:** Inter SemiBold, 20 px
* **Body Text:** Inter Regular, 16 px
* **Small / Auxiliary Text:** Inter Regular, 14 px
* **Labels / Caption:** Inter Regular, 12 px

El interlineado se establece aproximadamente entre 1.3 y 1.5 veces el tamaño de la fuente, favoreciendo la lectura tanto en bloques de contenido como en interfaces que presentan información operativa.

**4.1.1.3. Paleta de Colores**

La paleta de colores de AI-ToDu busca transmitir confianza, innovación y eficiencia. Se utilizan tonos corporativos para la navegación y colores semánticos para comunicar los estados del sistema:

* **Corporate Navy (`#0F172A`):** Títulos, navegación y elementos estructurales.
* **Primary Teal (`#0D9488`):** Botones y acciones principales.
* **Teal Light (`#CCFBF1`):** Fondos informativos y elementos destacados.
* **Background Light (`#F8FAFC`):** Fondo general de la aplicación.
* **Success Green (`#16A34A`):** Operaciones completadas y stock disponible.
* **Warning Amber (`#F59E0B`):** Stock bajo y revisiones pendientes.
* **Error Red (`#DC2626`):** Stock agotado, errores e incidencias críticas.

**4.1.1.4. Spacing**

El sistema de espaciado se basa en una cuadrícula de 4 píxeles, permitiendo mantener consistencia entre los diferentes componentes. La escala utilizada es:
* **4 px:** Separación mínima (ej. ícono y etiqueta).
* **8 px:** Elementos relacionados del mismo grupo.
* **12 px:** Componentes pequeños o separaciones internas frecuentes.
* **16 px:** Separación interna de componentes (tarjetas, formularios).
* **24 px:** Separación visual clara entre tarjetas y subsecciones.
* **32 px:** División de bloques principales dentro de una vista.
* **48 px:** Separación amplia entre secciones de la Landing Page.

**4.1.1.5. Iconography**

La iconografía sigue un estilo simple, lineal, reconocible y consistente. Se priorizan íconos de apariencia limpia, evitando ilustraciones excesivamente complejas. Entre los principales elementos representados se encuentran: Dashboard, Inventario, Registrar entrada/salida, Ventas, Despachos, Reportes, Alertas, y Perfil.
Los íconos no reemplazan por completo el contenido textual en las operaciones importantes; se acompañan de una etiqueta descriptiva para reducir la carga cognitiva.

**4.1.1.6. Tone of Communication and Applied Language**

El tono de comunicación es claro, profesional, respetuoso, sereno y orientado a la acción. Se evitan tecnicismos innecesarios y mensajes ambiguos.
* **Acciones:** “Registrar entrada”, “Registrar salida”, “Registrar merma”, “Buscar producto”, “Ver detalles”.
* **Estados y datos:** “Stock disponible”, “Stock bajo”, “Stock agotado”, “Producto en cuarentena”, “Movimiento registrado”.

### 4.1.2. Web Style Guidelines

En el diseño visual de AI-ToDu se utiliza una línea gráfica moderna, profesional y funcional. La jerarquía visual se construye mediante la tipografía Inter, tamaños diferenciados y colores de alto contraste (Corporate Navy y Primary Teal). Los componentes interactivos presentan estados visuales claros (*normal, hover, focus, active*). Se utilizan tarjetas con bordes suaves y tablas organizadas. Además, el diseño *responsive* permite que AI-ToDu conserve su funcionalidad en computadoras, tablets y smartphones.

<div style="page-break-after: always"></div>

## 4.2. Information Architecture

La arquitectura de información de AI-ToDu está diseñada para que visitantes y usuarios operativos encuentren lo que necesitan con el menor número de clics posible, reduciendo la fricción.

### 4.2.1. Organization Systems

Para AI-ToDu se opta por una organización visual jerárquica con elementos secuenciales. El contenido se organiza en categorías como “Dashboard”, “Inventario”, “Ventas”, “Despachos”, “Reportes” y “Configuración”. En determinadas secciones se incorporan flujos secuenciales que guían al usuario paso a paso (ej. registrar una entrada o crear una transacción comercial).

<p align="center">
  <em>Enlace a la estructura en Miro: <a href="https://miro.com/app/board/uXjVHlZ7CiQ=/?share_link_id=480881319023">Ver Arquitectura de Información AI-ToDu</a></em>
</p>

### 4.2.2. Labeling Systems

El sistema de etiquetas utiliza una terminología clara y uniforme:

| Sección / Etiqueta | Descripción |
| :--- | :--- |
| **Inicio / Dashboard** | Presenta un resumen del estado del negocio, incluyendo ventas, inventario, alertas y rentabilidad. |
| **Inventario / Inventory** | Permite consultar y administrar los productos, SKU, cantidades, ubicaciones y estados. |
| **Registrar entrada / Register Input** | Permite ingresar nueva mercadería y actualizar la cantidad disponible. |
| **Registrar salida / Register Output** | Permite registrar la salida de productos por venta o despacho. |
| **Registrar merma / Register Loss** | Permite registrar productos dañados, vencidos o perdidos. |
| **Ventas / Sales** | Permite crear y consultar transacciones comerciales y estados de pago. |
| **Despachos / Shipments** | Permite gestionar manifiestos, productos enviados y estados de entrega. |
| **Reportes / Reports** | Presenta información sobre ventas, stock, mermas, movimientos y rentabilidad. |
| **Usuarios y roles / Users and Roles** | Permite administrar las cuentas y asignar permisos. |
| **Configuración / Settings** | Permite gestionar los datos del negocio y las preferencias del sistema. |

### 4.2.3. SEO Tags and Meta Tags

Los metadatos se definen con el objetivo de posicionar correctamente la plataforma y proporcionar información clara a los navegadores:

| Página | Title | Description | Keywords | Author |
| :--- | :--- | :--- | :--- | :--- |
| **Landing Page** | AI-ToDu \| Gestión de inventario y ventas para MYPES | Centraliza el inventario, las ventas y despachos mediante una plataforma web sencilla. | inventario MYPE, control de stock, gestión de ventas, AI-ToDu | IA-INNOVATION Team |
| **Login / Registro** | Accede a AI-ToDu \| Iniciar sesión o registrarse | Inicia sesión o crea una cuenta en AI-ToDu para gestionar las operaciones de tu negocio. | AI-ToDu, iniciar sesión, registro, inventario, MYPES | IA-INNOVATION Team |
| **Dashboard** | Dashboard \| AI-ToDu | Consulta el estado de tu inventario, ventas, mermas, alertas y principales indicadores. | dashboard, inventario, ventas, reportes, rentabilidad | IA-INNOVATION Team |

La Landing Page utilizará el atributo `lang="es-PE"` y el Meta Tag `viewport` para mantener una presentación adaptable a diferentes tamaños de pantalla.

### 4.2.4. Searching Systems

AI-ToDu incorpora mecanismos de búsqueda y filtrado ágiles.

**Searching System para productos:**
| Criterio | Descripción |
| :--- | :--- |
| **SKU** | Localiza un producto mediante su código único. |
| **Nombre** | Busca artículos por coincidencia de texto. |
| **Categoría** | Filtra productos de una categoría específica. |
| **Ubicación** | Busca artículos según su zona o repisa. |

**Searching System mediante filtros:**
| Filtro | Descripción |
| :--- | :--- |
| **Fecha** | Filtra registros por un periodo. |
| **Tipo de movimiento** | Muestra entradas, salidas o mermas. |
| **Estado** | Filtra productos disponibles, con stock bajo, agotados o en cuarentena. |

*Nota: El dueño o administrador puede buscar en todos los módulos, mientras que el operario de almacén solo accede a la información permitida por su rol.*

### 4.2.5. Navigation Systems

**Navegación de la Landing Page:**
Utiliza una navegación horizontal en escritorio y un menú hamburguesa adaptable en móviles. Incorpora llamados a la acción dirigidos a los dueños ("Registrarse") y operarios.

**Navegación para el Dueño o Administrador (Web App):**
| Nombre | Descripción |
| :--- | :--- |
| **Dashboard** | Presenta indicadores de ventas, inventario, mermas y rentabilidad. |
| **Inventario** | Permite consultar productos, stock y movimientos. |
| **Ventas / Despachos** | Gestión de transacciones comerciales y salidas de mercadería. |
| **Reportes / Roles** | Información financiera y administración de permisos de empleados. |

**Navegación para el Operario de Almacén:**
| Nombre | Descripción |
| :--- | :--- |
| **Inicio** | Presenta tareas pendientes y alertas de inventario. |
| **Registrar entrada / salida / merma** | Accesos rápidos enfocados en la operación física del almacén. |
| **Buscar producto** | Localización rápida de artículos por SKU. |

<div style="page-break-after: always"></div>

## 4.3. Landing Page UI Design

La propuesta visual traduce nuestras decisiones de Arquitectura de Información y Guías de Estilo en una interfaz orientada a la conversión B2B. El diseño se enfoca en transmitir confianza institucional y guiar al visitante hacia el registro.

### 4.3.1. Landing Page Wireframe

Hemos priorizado la heurística de "Diseño estético y minimalista", asegurando que el *Hero Section* contenga una propuesta de valor clara y un único *Call to Action* prominente.

<p align="center">
  <img src="Images/Landing-Wireframes.jpg" width="800" alt="Landing Page Wireframes Desktop y Mobile">
  <br><em>Enlace a Figma: <a href="https://www.figma.com/design/ANY4VrfpB2hySc15nBdAhz/Sin-t%C3%ADtulo?node-id=0-1&t=k8B8SCaVRYBwmB9R-1">Ver Wireframes AI-ToDu</a></em>
</p>

### 4.3.2. Landing Page Mock-up

Los mock-ups integran nuestro *Design System*. Utilizamos la paleta de colores corporativa (Navy y Teal) para resaltar los botones de acción sobre fondos limpios, cumpliendo con los estándares de contraste (WCAG).

<p align="center">
  <img src="Images/Landing-Mockups.jpg" width="800" alt="Landing Page Mockups Desktop y Mobile">
  <br><em>Enlace a Figma: <a href="https://www.figma.com/design/ANY4VrfpB2hySc15nBdAhz/Sin-t%C3%ADtulo?node-id=0-1&t=k8B8SCaVRYBwmB9R-1">Ver Mockups AI-ToDu</a></em>
</p>

<div style="page-break-after: always"></div>

## 4.4. Web Applications UX/UI Design

El diseño de la aplicación web organiza las experiencias de los dos roles principales: el Dueño/Administrador (supervisión e indicadores) y el Operario de Almacén (registro rápido de movimientos).

### 4.4.1. Web Applications Wireframes

En el dashboard se prioriza la visualización de indicadores de inventario, ventas y rentabilidad. La distribución se adapta a dispositivos móviles para los operarios.

| Familia de vistas | Propósito | Historias relacionadas |
| :--- | :--- | :--- |
| **Acceso y cuenta** | Registro, inicio y cierre de sesión. | US01 |
| **Dashboard** | Consulta de inventario, ventas, mermas y rentabilidad. | US03 |
| **Inventario** | Consulta de productos, SKU, cantidades y estados. | US02, US04 |
| **Registrar entrada / salida** | Registro de nueva mercadería o despachos. | US02, US03 |
| **Notificaciones y Roles** | Avisos sobre stock bajo y administración de permisos. | US03, US05 |

### 4.4.2. Web Applications Wireflow Diagrams

Los wireflows representan la secuencia de pantallas y acciones que debe seguir cada usuario:

| Wireflow | Usuario y objetivo | Secuencia funcional |
| :--- | :--- | :--- |
| **W1** | **Admin/Operario:** Registrar entrada | Módulo Inventario → "Registrar entrada" → completar SKU → guardar → visualizar actualizado. |
| **W2** | **Admin:** Eliminar producto | Módulo Inventario → seleccionar ícono eliminar → confirmar mensaje → visualizar listado. |
| **W3** | **Admin/Operario:** Consultar ventas | Menú lateral → "Ventas" → consultar registro de transacciones. |
| **W4** | **Admin/Operario:** Consultar despachos | Menú lateral → "Despachos" → organizar y hacer seguimiento. |
| **W5** | **Admin:** Consultar reportes | Menú lateral → "Reportes" → consultar finanzas y compras. |
| **W6** | **Admin/Operario:** Notificaciones | Dashboard → ícono de notificaciones → revisar alertas de stock. |

<p align="center">
  <img src="Images/Wireflows-WebApp.jpg" width="800" alt="Wireflow Diagrams AI-ToDu">
  <br><em>Nota. Representación secuencial de las acciones W1 a W6.</em>
</p>

### 4.4.3. Web Applications Mock-ups

Los mock-ups presentan la propuesta visual final. Utilizan un menú lateral de navegación, tarjetas de resumen y tablas. Los estados del inventario se diferencian como “Óptimo”, “Alerta” y “Quiebre”.

<p align="center">
  <img src="Images/Mockups-WebApp.jpg" width="800" alt="Mockups Web App AI-ToDu">
</p>

### 4.4.4. Web Applications User Flow Diagrams

Las representaciones de decisiones complementan la secuencia de pantallas al incorporar las condiciones lógicas de AI-ToDu:
* El registro de una entrada válida actualiza la cantidad.
* No se permite registrar una salida mayor al stock disponible.
* Un producto en cuarentena no puede venderse ni despacharse.
* Las alternativas incluyen datos incompletos, SKU inexistente, stock insuficiente y errores de guardado.

<p align="center">
  <img src="Images/UserFlow-Diagrams.jpg" width="800" alt="User Flow Diagrams">
</p>

### 4.5. Web Applications Prototyping

El prototipo de AI-ToDu reúne las interfaces y conexiones de navegación para explorar la experiencia de usuario. Su evaluación comprueba la continuidad de las interacciones en computadoras y dispositivos móviles, simulando la experiencia de uso ágil.

<p align="center">
  <img src="Images/Prototype-Connections.jpg" width="800" alt="Prototipo Interactivo">
</p>

<div style="page-break-after: always"></div>

## 4.6. Domain-Driven Software Architecture

AI-ToDu adopta el enfoque de *Domain-Driven Design* (DDD) con el objetivo de organizar la solución según los procesos reales de gestión de las MYPES. El sistema se estructura en diferentes *Bounded Contexts*, encapsulando las reglas de negocio y facilitando la mantenibilidad técnica.

| Bounded Context | Descripción |
| :--- | :--- |
| **IAM** | Gestiona la autenticación, usuarios, roles y permisos de acceso. |
| **Warehouse & Inventory Management** | Administra productos, SKU, existencias, entradas, salidas y mermas (Core Domain). |
| **Sales & Commercial Transactions** | Gestiona ventas, productos vendidos y totales. |
| **Logistics & Dispatch** | Administra manifiestos y seguimiento de envíos. |
| **Reporting & Notifications** | Genera indicadores financieros y alertas de stock. |

### 4.6.1. Design-Level Event Storming

A través del EventStorming a nivel de diseño, se identificaron las interdependencias e integración entre los módulos:

| Origen — Evento | Destino — Comando | Descripción |
| :--- | :--- | :--- |
| **IAM:** User Authenticated | **Warehouse:** Register Movement | Un usuario autenticado puede registrar movimientos según permisos. |
| **Warehouse:** Merchandise Received | **Warehouse:** Update Inventory | La recepción de mercadería incrementa la cantidad disponible. |
| **Warehouse:** Low Stock Triggered | **Notifications:** Send Alert | El stock bajo genera una alerta para el usuario autorizado. |
| **Sales:** Transaction Created | **Warehouse:** Dispatch Merch. | Una venta confirmada solicita la salida de los productos. |

<p align="center">
  <img src="Images/DesignLevel-EventStorming.jpg" width="800" alt="Design-Level EventStorming">
  <br><em>Nota. Flujo de comandos, agregados y políticas de AI-ToDu.</em>
</p>

### 4.6.2. Software Architecture Context Diagram

El Diagrama de Contexto (Nivel 1 C4) ilustra el sistema central en su ecosistema operativo. Está liderado por el Dueño/Administrador y el Operario de Almacén. Se integra con plataformas externas como SUNAT API, Email Gateway (SendGrid) y Pasarelas de Pago.

```mermaid
flowchart TD
    %% Actors
    ADMIN(("<b>Dueño / Administrador</b><br/>[Person]<br/><i>Toma decisiones estratégicas, revisa<br/>rentabilidad y gestiona la MYPE</i>"))
    OPERATOR(("<b>Operario de Almacén</b><br/>[Person]<br/><i>Registra ingresos, salidas, mermas<br/>y consolida despachos físicos</i>"))
    
    %% Core System
    AITODU("<b>AI-ToDu System</b><br/>[Software System]<br/><i>Plataforma centralizada SaaS que unifica la gestión<br/>de inventario, ventas logísticas y alertas operativas</i>")
    
    %% External Systems
    SUNAT["<b>SUNAT API</b><br/>[Software System]<br/><i>Servicio gubernamental para validación<br/>y emisión de comprobantes</i>"]
    SENDGRID["<b>Email Gateway (SendGrid)</b><br/>[Software System]<br/><i>Servicio externo para envío de<br/>notificaciones preventivas</i>"]
    PAYMENT["<b>Pasarela de Pagos</b><br/>[Software System]<br/><i>Procesa el cobro recurrente<br/>de suscripciones SaaS</i>"]
    
    %% Relationships
    ADMIN -.->|"Supervisa métricas y<br/>administra cuenta"| AITODU
    OPERATOR -.->|"Registra el control de<br/>operaciones físicas"| AITODU
    
    AITODU -.->|"Valida transacciones<br/>fiscales (JSON/HTTPS)"| SUNAT
    AITODU -.->|"Delega envío de<br/>correos (HTTPS)"| SENDGRID
    AITODU -.->|"Delega cobros<br/>recurrentes (HTTPS)"| PAYMENT
    
    %% C4 Model Styling
    classDef person fill:#08427b,stroke:#052e56,color:#ffffff,stroke-width:2px
    classDef system fill:#1168bd,stroke:#0b4884,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    classDef external fill:#999999,stroke:#6b6b6b,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    
    class ADMIN,OPERATOR person
    class AITODU system
    class SUNAT,SENDGRID,PAYMENT external
```

### 4.6.3. Software Architecture Container Diagrams

El Diagrama de Contenedores (Nivel 2 C4) expone las unidades de ejecución y despliegue:
* **Landing Page:** Sitio estático (Vercel/Netlify).
* **Web Application (SPA):** Desarrollada con **Angular y TypeScript**, interfaz responsiva para operarios y gerentes.
* **Backend API:** Desarrollado en **Java 17 con Spring Boot** bajo arquitectura DDD. Procesa peticiones autenticadas vía JWT.
* **Database:** **PostgreSQL** para persistir el registro transaccional bajo garantías ACID.

```mermaid
flowchart TD
    %% Actors
    ADMIN(("<b>Dueño / Administrador</b><br/>[Person]"))
    OPERATOR(("<b>Operario de Almacén</b><br/>[Person]"))
    VISITOR(("<b>Visitante MYPE</b><br/>[Person]"))

    %% Boundary
    subgraph SYSTEM_BOUNDARY ["AI-ToDu Architecture"]
        direction TB
        LANDING("<b>Landing Page</b><br/>[Container: Vercel / Netlify]<br/><i>Servidor de archivos estáticos que entrega<br/>la página web promocional B2B.</i>")
        WEBAPP("<b>Web Application</b><br/>[Container: Firebase / Vercel]<br/><i>Servidor encargado de distribuir los<br/>artefactos estáticos (HTML/CSS/JS).</i>")
        SPA("<b>Single-Page Application</b><br/>[Container: Angular, TypeScript]<br/><i>App interactiva en el navegador que consume<br/>el Backend RESTful.</i>")
        API("<b>Backend API RESTful</b><br/>[Container: Java 17, Spring Boot]<br/><i>Procesa lógica de negocio DDD,<br/>auth JWT y expone servicios.</i>")
        DB[("<b>Database</b><br/>[Container: PostgreSQL]<br/><i>Almacena datos transaccionales bajo<br/>esquema Multi-Tenant y ACID.</i>")]
    end

    %% External Systems
    SUNAT["<b>SUNAT API</b><br/>[Software System]"]
    SENDGRID["<b>Email Gateway</b><br/>[Software System]"]

    %% Relationships
    VISITOR -.->|"Visita para conocer<br/>los planes"| LANDING
    ADMIN -.->|"Gestiona negocio y<br/>rentabilidad"| SPA
    OPERATOR -.->|"Controla inventario<br/>físico"| SPA
    
    SPA -.->|"Descarga bundle<br/>estático (HTTPS)"| WEBAPP
    SPA -.->|"Consume endpoints<br/>(JSON/HTTPS)"| API
    
    API -.->|"Lee/Persiste estado<br/>(JDBC/JPA)"| DB
    API -.->|"Valida facturación"| SUNAT
    API -.->|"Dispara notificaciones"| SENDGRID

    %% Styling
    classDef person fill:#08427b,stroke:#052e56,color:#ffffff,stroke-width:2px
    classDef container fill:#438dd5,stroke:#2e6295,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    classDef database fill:#438dd5,stroke:#2e6295,color:#ffffff,stroke-width:2px
    classDef external fill:#999999,stroke:#6b6b6b,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    classDef boundary fill:none,stroke:#444444,stroke-width:2px,stroke-dasharray: 5 5

    class ADMIN,OPERATOR,VISITOR person
    class LANDING,WEBAPP,SPA,API container
    class DB database
    class SUNAT,SENDGRID external
    class SYSTEM_BOUNDARY boundary
```

### 4.6.4. Software Architecture Components Diagrams

El Diagrama de Componentes (Nivel 3 C4) descompone el contenedor del **Backend API (Spring Boot)**. Muestra los módulos cohesivos: *IAM Module, Warehouse Module, Sales Module, Logistics Module* y la capa de *Shared Infrastructure* apoyada en **Spring Data JPA**.

```mermaid
flowchart TD
    %% External Containers
    SPA("<b>Single-Page Application</b><br/>[Container: Angular]<br/><i>Interfaz gráfica del usuario</i>")
    DB[("<b>Database</b><br/>[Container: PostgreSQL]<br/><i>Persistencia centralizada</i>")]
    EXTERNAL["<b>Sistemas Externos</b><br/>[Software Systems]<br/><i>SUNAT, SendGrid, etc.</i>"]

    %% Boundary
    subgraph API_BOUNDARY ["Backend API RESTful (Java / Spring Boot)"]
        direction TB
        IAM("<b>IAM & Security Module</b><br/>[Component: Spring Security, JWT]<br/><i>Gestiona identidad (Tenants) y<br/>autorización por roles.</i>")
        WAREHOUSE("<b>Warehouse Module</b><br/>[Component: Spring @Service]<br/><i>Reglas de dominio para inventario,<br/>SKUs y movimientos (Core).</i>")
        COMMERCIAL("<b>Commercial Module</b><br/>[Component: Spring @Service]<br/><i>Procesa transacciones de ventas<br/>y asociación con clientes.</i>")
        LOGISTICS("<b>Logistics Module</b><br/>[Component: Spring @Service]<br/><i>Gestiona manifiestos, asignación<br/>de choferes e incidencias.</i>")
        REPORTING("<b>Reporting & Alerts Module</b><br/>[Component: Spring @Service]<br/><i>Agrega métricas para el Dashboard<br/>y dispara alertas automáticas.</i>")
        JPA("<b>Shared Infrastructure</b><br/>[Component: Spring Data JPA]<br/><i>Capa de abstracción ORM para<br/>el mapeo objeto-relacional.</i>")
    end

    %% Relationships
    SPA -.->|"Peticiones HTTP con<br/>Bearer Token"| IAM
    
    IAM -.->|"Rutea auth"| WAREHOUSE
    IAM -.->|"Rutea auth"| COMMERCIAL
    IAM -.->|"Rutea auth"| LOGISTICS
    IAM -.->|"Rutea auth"| REPORTING
    
    COMMERCIAL -.->|"Valida y descuenta<br/>inventario físico"| WAREHOUSE
    
    WAREHOUSE -.->|"Solicita persistencia"| JPA
    COMMERCIAL -.->|"Solicita persistencia"| JPA
    LOGISTICS -.->|"Solicita persistencia"| JPA
    REPORTING -.->|"Consultas / Agregaciones"| JPA
    
    COMMERCIAL -.->|"Emite comprobantes"| EXTERNAL
    REPORTING -.->|"Notifica correos"| EXTERNAL
    
    JPA -.->|"Ejecuta Queries y<br/>Transacciones (JDBC)"| DB

    %% Styling
    classDef container fill:#438dd5,stroke:#2e6295,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    classDef component fill:#85bbf0,stroke:#5d82a8,color:#000000,rx:10px,ry:10px,stroke-width:2px
    classDef database fill:#438dd5,stroke:#2e6295,color:#ffffff,stroke-width:2px
    classDef external fill:#999999,stroke:#6b6b6b,color:#ffffff,rx:10px,ry:10px,stroke-width:2px
    classDef boundary fill:none,stroke:#444444,stroke-width:2px,stroke-dasharray: 5 5

    class SPA container
    class IAM,WAREHOUSE,COMMERCIAL,LOGISTICS,REPORTING,JPA component
    class DB database
    class EXTERNAL external
    class API_BOUNDARY boundary
```

<div style="page-break-after: always"></div>

## 4.7. Software Object-Oriented Design

Detallamos cómo los conceptos del DDD se traducen en código **Java**. El diseño orientado a objetos protege rigurosamente los invariantes encapsulando el estado.

### 4.7.1. Class Diagrams

Los Diagramas de Clases UML para los Bounded Contexts principales en Spring Boot (Java) son:
* **Warehouse Context:** La clase `InventoryItem` actúa como el Aggregate Root. Sus atributos se mantienen privados para evitar modificaciones externas directas. Exponemos métodos de dominio (ej. `updateConservationStatus`) que validan reglas de negocio.
* **Logistics Context:** La clase `ShipmentManifest` es el Aggregate Root. Contiene a `IoTTelemetry` como un *Value Object* inmutable sin ID propio.
* **Billing Context:** La clase `CommercialTransaction` almacena una referencia lógica (`linkedManifestId`) en lugar de un acoplamiento directo de objeto para mantener la independencia del módulo.

```mermaid
classDiagram
    %% ==========================================
    %% IAM / SAAS MODULE
    %% ==========================================
    namespace IamAndSaas {
        class Tenant {
            -UUID id
            -String name
            -String ruc
            -UUID subscriptionPlanId
            +changeSubscription(UUID planId) void
            +updateDetails(String name, String ruc) void
        }

        class SubscriptionPlan {
            -UUID id
            -String name
            -BigDecimal price
            -Integer maxUsers
        }

        class User {
            -UUID id
            -UUID tenantId
            -Integer roleId
            -String fullName
            -String email
            +assignRole(Integer roleId) void
        }

        class Role {
            -Integer id
            -String name
        }
    }

    %% ==========================================
    %% INVENTORY MODULE (CORE)
    %% ==========================================
    namespace Inventory {
        class InventoryItem {
            <<Aggregate Root>>
            -UUID id
            -UUID tenantId
            -UUID categoryId
            -String sku
            -Integer quantity
            -BigDecimal unitPrice
            +addStock(Integer amount) void
            +decreaseStock(Integer amount) void
            +updatePrice(BigDecimal newPrice) void
        }

        class Category {
            -UUID id
            -UUID tenantId
            -String name
        }

        class StockMovement {
            -UUID id
            -UUID inventoryItemId
            -UUID userId
            -String movementType
            -Integer quantity
            -String reason
        }
    }

    %% ==========================================
    %% COMMERCIAL MODULE
    %% ==========================================
    namespace Commercial {
        class Sale {
            <<Aggregate Root>>
            -UUID id
            -UUID tenantId
            -UUID customerId
            -UUID userId
            -BigDecimal totalAmount
            -String status
            -List~SaleDetail~ details
            +addDetail(UUID itemId, Integer qty, BigDecimal price) void
            +calculateTaxes() BigDecimal
            +confirmSale() void
        }

        class SaleDetail {
            -UUID id
            -UUID saleId
            -UUID inventoryItemId
            -Integer quantity
            -BigDecimal unitPrice
            +getSubtotal() BigDecimal
        }

        class Customer {
            -UUID id
            -UUID tenantId
            -String name
            -String contactInfo
        }
    }

    %% ==========================================
    %% LOGISTICS MODULE
    %% ==========================================
    namespace Logistics {
        class Dispatch {
            <<Aggregate Root>>
            -UUID id
            -UUID tenantId
            -UUID driverId
            -UUID userId
            -String status
            -List~DispatchSale~ dispatchSales
            +assignDriver(UUID driverId) void
            +completeDispatch() void
        }

        class DispatchSale {
            -UUID dispatchId
            -UUID saleId
        }

        class Driver {
            -UUID id
            -UUID tenantId
            -String name
            -String license
        }

        class DispatchIncident {
            -UUID id
            -UUID dispatchId
            -String description
            -LocalDateTime occurredAt
        }
    }

    %% ==========================================
    %% ALERTS MODULE
    %% ==========================================
    namespace Alerts {
        class Notification {
            -UUID id
            -UUID tenantId
            -UUID userId
            -String message
            -Boolean isRead
            +markAsRead() void
        }
    }

    %% Compositions (Aggregates)
    Sale *-- "1..*" SaleDetail : contains
    Dispatch *-- "1..*" DispatchSale : groups
    Dispatch *-- "0..*" DispatchIncident : records
    
    %% Associations
    Tenant "1" --> "*" User : has
    Tenant "1" --> "*" InventoryItem : owns
    SubscriptionPlan "1" --> "*" Tenant : grants
    Role "1" --> "*" User : assigns
    
    InventoryItem "1" --> "*" StockMovement : tracks
    Category "1" --> "*" InventoryItem : categorizes
    
    SaleDetail "0..*" --> "1" InventoryItem : references
    Customer "1" --> "*" Sale : makes
    
    Dispatch "1" --> "*" Driver : executes
    DispatchSale "*" --> "1" Sale : assigned_to
```

## 4.8. Database Design

El diseño en PostgreSQL sigue la filosofía de separación por Bounded Contexts, utilizando referencias lógicas blandas en lugar de Foreign Keys estrictas entre módulos separados para evitar el antipatrón "Big Ball of Mud".

### 4.8.1. Database Diagrams

Mapeado mediante **Spring Data JPA**, el ERD refleja:
* **Esquema WAREHOUSE:** Tabla `inventory_items` con llave primaria UUID. Enum de estados persistidos como VARCHAR.
* **Esquema LOGISTICS:** Tabla `shipment_manifests`. Atributos de Value Objects se aplana mediante la anotación `@Embedded`.
* **Esquema BILLING:** Tabla `commercial_transactions` incluye `linked_manifest_id` como referencia lógica al despacho.

```mermaid
erDiagram
    %% SaaS & Security Module
    TENANTS ||--o{ USERS : has
    SUBSCRIPTION_PLANS ||--o{ TENANTS : grants
    ROLES ||--o{ USERS : assigns

    %% Inventory Module
    TENANTS ||--o{ INVENTORY_ITEMS : owns
    TENANTS ||--o{ CATEGORIES : owns
    CATEGORIES ||--o{ INVENTORY_ITEMS : categorizes
    INVENTORY_ITEMS ||--o{ STOCK_MOVEMENTS : tracks
    USERS ||--o{ STOCK_MOVEMENTS : registers

    %% Commercial Module
    TENANTS ||--o{ SALES : generates
    TENANTS ||--o{ CUSTOMERS : manages
    CUSTOMERS ||--o{ SALES : makes
    USERS ||--o{ SALES : processes
    SALES ||--|{ SALE_DETAILS : contains
    INVENTORY_ITEMS ||--o{ SALE_DETAILS : included_in

    %% Logistics Module
    TENANTS ||--o{ DISPATCHES : organizes
    TENANTS ||--o{ DRIVERS : employs
    USERS ||--o{ DISPATCHES : creates
    DRIVERS ||--o{ DISPATCHES : executes
    DISPATCHES ||--|{ DISPATCH_SALES : groups
    SALES ||--o| DISPATCH_SALES : assigned_to
    DISPATCHES ||--o{ DISPATCH_INCIDENTS : records

    %% Alerts Module
    TENANTS ||--o{ NOTIFICATIONS : receives
    USERS ||--o{ NOTIFICATIONS : notified_by

    TENANTS {
        uuid id PK
        varchar name
        varchar ruc
        uuid subscription_plan_id FK
    }
    USERS {
        uuid id PK
        uuid tenant_id FK
        integer role_id FK
        varchar full_name
        varchar email
    }
    INVENTORY_ITEMS {
        uuid id PK
        uuid tenant_id FK
        uuid category_id FK
        varchar sku
        integer quantity
        numeric unit_price
    }
    STOCK_MOVEMENTS {
        uuid id PK
        uuid inventory_item_id FK
        uuid user_id FK
        varchar movement_type
        integer quantity
        varchar reason
    }
    SALES {
        uuid id PK
        uuid tenant_id FK
        uuid customer_id FK
        uuid user_id FK
        numeric total_amount
        varchar status
    }
    DISPATCHES {
        uuid id PK
        uuid tenant_id FK
        uuid driver_id FK
        uuid user_id FK
        varchar status
    }
```
