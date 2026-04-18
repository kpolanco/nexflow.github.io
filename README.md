# NexFlow CRM
Bienvenido al repositorio del sitio web de **NexFlow CRM** (`https://nexflow.nexgencloudware.com/`), la solución integral de gestión empresarial desarrollada por NexGen Cloudware para optimizar la operación de negocios mediante automatización, control y análisis en tiempo real.

------------------------------------------------------------------------
## Descripción
Este repositorio contiene **únicamente los archivos binarios compilados del landing page de NexFlow CRM**, generados a partir del proyecto Angular y destinados a ser publicados en el dominio oficial:  **https://nexflow.nexgencloudware.com/**

Su propósito es servir como repositorio de despliegue para alojar la versión productiva del sitio web, facilitando la publicación continua mediante **GitHub Pages** o cualquier mecanismo de hosting estático.

El landing page de **NexFlow CRM** está diseñado para presentar las funcionalidades, beneficios y propuesta de valor del sistema, permitiendo comunicar de forma clara cómo la plataforma ayuda a las empresas a gestionar de manera centralizada:
-   Clientes y contratos
-   Citas y agenda operativa
-   Ventas y control financiero
-   Inventario y productos
-   Sucursales y empleados
-   Promociones y planes
-   Control de gastos y conciliaciones
-   Dashboards analíticos en tiempo real
-   Automatización de procesos
-   Integración con asistentes inteligentes (IA)

------------------------------------------------------------------------
## Características del Sitio
-   **Repositorio de despliegue** Contiene exclusivamente el resultado compilado (`dist/`) del proyecto Angular.
-   **Publicación estática** Preparado para publicarse en hosting estático bajo el dominio: `https://nexflow.nexgencloudware.com/`
-   **Diseño responsivo** Compatible con escritorio, tablet y dispositivos móviles.
-   **Identidad visual NexFlow** Implementa la línea gráfica oficial del ecosistema NexFlow y NexGen Cloudware.
-   **Optimización SEO** Incluye estructura optimizada para motores de búsqueda y generación de leads.

------------------------------------------------------------------------
## Estructura del Repositorio
``` plaintext
/
├── assets/              # Recursos estáticos generados por Angular
├── browser/             # Archivos compilados del build
├── favicon.ico          # Ícono del sitio
├── index.html           # Punto de entrada del portal
└── 404.html             # Página de soporte para rutas estáticas
```

Este repositorio **no contiene código fuente Angular**, únicamente el contenido compilado listo para producción.

------------------------------------------------------------------------
## Identidad Visual de NexFlow CRM
El sitio utiliza la paleta oficial de colores de **NexFlow CRM**, definida mediante variables CSS:
``` css
:root {
  --nf-primary:       #5B21B6;
  --nf-secondary:     #7C3AED;
  --nf-accent:        #A855F7;
  --nf-light:         #C4B5FD;
  --nf-dark:          #2E1065;
  --nf-darker:        #1A0540;

  --nf-grad-primary:  linear-gradient(135deg, #5B21B6 0%, #7C3AED 50%, #A855F7 100%);
  --nf-grad-hero:     linear-gradient(135deg, #1A0540 0%, #2E1065 40%, #4C1D95 100%);
  --nf-grad-cta:      linear-gradient(135deg, #7C3AED 0%, #A855F7 100%);
  --nf-grad-card:     linear-gradient(135deg, rgba(91,33,182,0.15) 0%, rgba(168,85,247,0.1) 100%);

  --body-font-family: 'Poppins', sans-serif;
  --body-font-size:   1.125rem;
  --body-font-weight: 400;
  --body-line-height: 1.5;

  --hero-title-font-size:    3.875rem;
  --hero-title-font-weight:  700;
  --hero-subtitle-font-size: 1.25rem;

  --header-height: 80px;
}
```

### Colores principales
-   **Primary:** `#5B21B6`
-   **Secondary:** `#7C3AED`
-   **Accent:** `#A855F7`
-   **Dark:** `#2E1065`
-   **Darker:** `#1A0540`

### Tipografía
-   **Fuente principal:** `Poppins`
-   **Uso:** títulos, contenido y elementos de navegación

------------------------------------------------------------------------
## Flujo de Publicación
Los archivos publicados en este repositorio se generan desde el proyecto fuente Angular mediante:
``` bash
ng build --configuration production
```

Posteriormente, el contenido compilado se publica en este repositorio para ser desplegado en:
``` bash
https://nexflow.nexgencloudware.com/
```

------------------------------------------------------------------------
## Tecnologías Utilizadas
-   Angular (build compilado)
-   HTML5
-   CSS3
-   JavaScript
-   GitHub Pages / Hosting estático

------------------------------------------------------------------------
## Objetivo del Repositorio
Este repositorio tiene como finalidad:
-   Almacenar la versión compilada del portal NexFlow CRM
-   Facilitar la publicación continua del sitio web
-   Mantener una versión estable del landing page en producción
-   Servir como punto de despliegue para el dominio oficial

------------------------------------------------------------------------
## Licencia
© 2026 NexGen Cloudware. Todos los derechos reservados.