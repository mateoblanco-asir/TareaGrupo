# ¿Qué es un SSG?

Un generador de sitios estáticos (SSG) es una herramienta que genera un sitio web HTML a traves de archivos de texto plano y plantillas de diseño


## Comparativa de Frameworks: Jekyll vs. Hugo vs. Astro

### 1. Jekyll
Es el generador de sitios estáticos pionero del ecosistema open-source (basado en Ruby), utilizado principalmente en blogs personales, páginas de proyectos pequeños y documentación sencilla integrada con repositorios.

-**Ventajas:**
 1.  Integración nativa y gratuita con GitHub Pages.
 2.  Cuenta con ya con miles de plantillas listas.

-**Desventajas:**
 1.  En webs grande tarda en compilar
 2.  Complejidad en la instalacion con Ruby

### 2. Hugo
Es un generador estático optimizado y escrito en Go, utilizado principalmente en blogs masivos, portales de noticias con miles de artículos y plataformas de documentación empresarial gigante.

-**Ventajas:**
1.  Compila en milisegundos 
2.  Instalacion sencilla sin dependencias externas

-**Desventajas:**
1.  Su sistema de plantillas es compleja
2.  Entorno muy técnico y difícil de personalizar desde cero.

### 3. Astro
Es un framework moderno basado en JavaScript enfocado en el rendimiento, utilizado principalmente en portafolios interactivos, webs corporativas y sitios de e-commerce que combinan partes estáticas con dinámicas.

-**Ventajas:**
1.  Comprime imágenes por defecto y genera formatos modernos automáticamente
2.  Permite combinar componentes de React, Vue o Svelte.

-**Desventajas:**
1.  Ecosistema de plugins más pequeño por ser una tecnología nueva.
2.  Requiere dominar el desarrollo Frontend moderno 

![image](SSG.jpg)

---

## Información Adicional

-  [Vídeo explicativo sobre SSG](https://www.youtube.com/watch?v=osWfEtbP_sk)

-  **Información sobre los CMS:** [Gestión de Contenidos](./cms.md "Ir a CMS")


### ¿Cómo funciona un SSG? (corrección)

Un SSG (Static Site Generator o generador de sitios estáticos) es una herramienta que permite crear páginas web estáticas automáticamente a partir de contenido, plantillas y recursos.

Su funcionamiento se divide en varios pasos:

1. **Contenido:** Se escribe el contenido de la página, normalmente utilizando archivos Markdown u otros formatos.
2. **Plantillas:** Se preparan diseños que definen cómo se mostrará el contenido en la página web.
3. **Generación:** El SSG combina el contenido con las plantillas y genera los archivos finales.
4. **Publicación:** Los archivos generados, como HTML, CSS y JavaScript, se suben a un servidor para que los visitantes puedan acceder a la web.

De esta forma, las páginas ya están preparadas antes de que el usuario las visite, por lo que el servidor no necesita generarlas cada vez que alguien accede.

Algunos ejemplos de SSG son Jekyll, Hugo y Astro.

### Comparación entre un SSG y la creación manual de páginas HTML

1. **Creación manual de HTML:** El desarrollador escribe directamente el código HTML de cada página. Si hay varias páginas con el mismo diseño, debe repetir parte del código.
2. **Uso de un SSG:** El desarrollador crea plantillas y añade el contenido por separado. Después, la herramienta genera automáticamente las páginas HTML.

| Característica | HTML manual | SSG |
|---|---|---|
| Creación | Se escribe el HTML de cada página. | Las páginas se generan automáticamente. |
| Diseño | Se repite el código cuando hay varias páginas. | Se utilizan plantillas reutilizables. |
| Actualización | Hay que modificar manualmente los archivos. | Se modifica el contenido y se vuelve a generar la web. |
| Organización | Puede complicarse cuando hay muchas páginas. | Se separa el contenido del diseño. |
| Dificultad | Es sencillo para páginas pequeñas. | Requiere aprender a utilizar y configurar la herramienta. |



