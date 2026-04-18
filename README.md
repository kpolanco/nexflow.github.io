# NexFlow CRM
Bienvenido al repositorio del sitio web de **NexFlow CRM** (`nexflow.nexgencloudware.com`), la solución integral de gestión empresarial desarrollada por NexGen Cloudware para optimizar la operación de negocios mediante automatización, control y análisis en tiempo real.

------------------------------------------------------------------------
## Descripción
Este sitio corresponde al **landing page oficial de NexFlow CRM**,
diseñado para presentar las funcionalidades, beneficios y propuesta de valor del sistema.

El portal está enfocado en comunicar cómo NexFlow CRM permite a las empresas gestionar de forma centralizada:

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

El sitio está construido como una **Single Page Application (SPA)** optimizada para marketing digital, generación de leads y presentación de producto.

------------------------------------------------------------------------
## Características
-   **Diseño responsivo**
    Adaptado para escritorio, tablet y dispositivos móviles, garantizando una experiencia fluida en cualquier pantalla.

-   **Estilo moderno NexGen**
    Basado en la identidad visual de NexGen Cloudware con una paleta en tonos púrpura:
    -   Primario: `#5B21B6`
    -   Secundario: `#7C3AED`
    -   Acento: `#A855F7`
    -   Oscuros: `#2E1065`, `#1A0540`

-   **Secciones dinámicas**
    Landing estructurado en bloques reutilizables como:

    -   Hero (presentación principal)
    -   Beneficios
    -   Funcionalidades
    -   Casos de uso
    -   Planes / pricing
    -   Testimonios
    -   Call To Action (CTA)
    -   Formulario de contacto

-   **Optimización SEO**
    Incluye meta tags, Open Graph y estructura optimizada para motores de búsqueda.
-   **Integración con formularios**
    Permite captación de leads mediante formularios conectados a servicios backend o correo electrónico.
-   **Animaciones y experiencia de usuario**
    Transiciones suaves, efectos visuales y navegación intuitiva.

------------------------------------------------------------------------
## Estructura del Proyecto
    src/
     ├── app/
     │    ├── components/
     │    │    ├── layout/        # Header, footer, navegación
     │    │    ├── pages/         # Páginas principales (home, product, contact)
     │    │    ├── sections/      # Secciones reutilizables del landing
     │    │    └── shared/        # Componentes reutilizables (botones, cards, etc.)
     │    ├── services/           # Servicios para integración con APIs
     │    ├── models/             # Interfaces TypeScript
     │    └── utils/              # Utilidades generales
     ├── public/
     │    ├── images/             # Imágenes del sitio
     │    ├── icons/              # Íconos
     │    ├── banners/            # Banners y backgrounds
     │    └── logos/              # Logos de NexFlow y NexGen

------------------------------------------------------------------------
## Cómo Publicar
### GitHub Pages
1.  Clona el repositorio:
    ``` bash
    git clone https://github.com/tu-usuario/nexflow.github.io.git
    ```

2.  Genera el build del proyecto:
    ``` bash
    ng build --configuration production
    ```

3.  Despliega en GitHub Pages:
    ``` bash
    npx angular-cli-ghpages --dir=dist/nexflow-landing
    ```

4.  Configura en GitHub:
    -   **Settings → Pages**
    -   Branch: `gh-pages`

5.  Configura el dominio:
    -   `nexflow.nexgencloudware.com`

------------------------------------------------------------------------
## Tecnologías
-   Angular (SPA)
-   TypeScript
-   SCSS
-   Bootstrap (grid system)
-   PrimeNG / PrimeFlex
-   HTML5
-   GitHub Pages / Firebase Hosting

------------------------------------------------------------------------
## Objetivo del Sitio
El landing page de NexFlow CRM tiene como propósito:
-   Presentar el producto de forma clara y atractiva
-   Comunicar su propuesta de valor
-   Generar leads comerciales
-   Servir como punto de entrada para clientes potenciales
-   Posicionar NexFlow como solución tecnológica empresarial

------------------------------------------------------------------------
## Licencia
© 2026 NexGen Cloudware. Todos los derechos reservados.
