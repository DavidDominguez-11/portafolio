---

# David Domínguez - Portafolio de Desarrollador Web

---

¡Hola! Soy **David Domínguez**, y este repositorio es mi **carta de presentación personal y profesional** en el mundo del desarrollo web. Aquí demuestro las habilidades y conocimientos adquiridos y perfeccionados a lo largo de mi formación, así como mi dedicación a la **calidad del código** y la **estética de la interfaz**.

Este portafolio no solo presenta mis proyectos, sino que también es una muestra práctica de mi dominio en las **tecnologías web más relevantes** que hemos explorado. Entiendo que cada detalle, desde la elección de las herramientas hasta la implementación de las funcionalidades y la experiencia de usuario, es crucial al evaluar un perfil para roles en el área web.

Los proyectos que verás aquí son una combinación de los **labs desarrollados durante el curso** y algunas **iniciativas personales**, todos ellos diseñados para respaldar mis conocimientos y mi capacidad para construir soluciones web robustas y visualmente atractivas.

### Puedes ver el portafolio desplegado y en acción aquí: **https://calicheoficial.lat/DavidDom/portafolio/**

¡Espero que disfruten explorando mi trabajo tanto como yo disfruté creándolo!

## Tecnologías Demostradas

Este portafolio está construido con un stack de tecnologías web moderno y eficiente, cuidadosamente seleccionado para optimizar tanto el **rendimiento** como la **experiencia de desarrollo**:

* **Astro**: Utilizado por su enfoque en el **rendimiento web**, generando sitios estáticos ultrarrápidos y optimizados para el contenido. Esto demuestra mi entendimiento de la importancia de la velocidad de carga y la **SEO** en aplicaciones web.
Decidí usar Astro ya que a diferencia de frameworks basados en JavaScript como React, Astro prioriza la hidratación selectiva (Islands Architecture), enviando menos JavaScript al navegador por defecto. Esto resulta en una mejor Core Web Vitals, una experiencia de usuario más fluida y al ser contenido muy estático me parece la mejor opción. 
* **Tailwind CSS**: Implementado para asegurar una **estética cuidada** y un **diseño responsivo**. Su enfoque de utilidad-primero refleja mi habilidad para desarrollar interfaces de usuario personalizadas y mantener la **consistencia visual** sin sacrificar la agilidad.
* **Bun**: Empleado como *runtime* y *toolkit* principal, lo que subraya mi familiaridad con herramientas de desarrollo de última generación. Su eficiencia en la instalación de dependencias y la ejecución de scripts es un reflejo de mi búsqueda por **flujos de trabajo optimizados**.

## Estructura del Proyecto

Este proyecto sigue una estructura limpia y modular, facilitando la **legibilidad, mantenibilidad y escalabilidad**, aspectos cruciales en cualquier equipo de desarrollo:

```text
daviddominguez-11-portafolio/
└── portafolio-dev/
    ├── public/                 # Contenido estático servido directamente (ej. favicon, imágenes optimizadas).
    ├── src/
    │   ├── assets/             # Recursos multimedia y activos no procesados directamente por Astro.
    │   ├── components/         # Módulos reutilizables para construir la interfaz de usuario. Cada componente encapsula su lógica y presentación.
    │   ├── data/               # Fuentes de datos en formato JSON para contenido dinámico (contacto, experiencia, proyectos, tecnologías), demostrando separación de concerns.
    │   ├── layouts/            # Plantillas maestras que definen la estructura base de las páginas, asegurando consistencia en el diseño.
    │   ├── pages/              # Las rutas principales del sitio web, donde se orquestan los componentes y datos para formar las vistas finales.
    │   └── styles/             # Hojas de estilo globales y específicas, gestionadas con Tailwind CSS para un diseño eficiente.
    ├── astro.config.mjs        # Configuración principal de Astro, incluyendo integraciones como Tailwind CSS.
    ├── package.json            # Define el proyecto, sus dependencias y los scripts de desarrollo/producción.
    ├── bun.lock                # Asegura la **reproducibilidad de las dependencias** en cualquier entorno de desarrollo o despliegue.
    ├── postcss.config.cjs      # Configuración de PostCSS para transformaciones CSS.
    ├── tailwind.config.cjs     # Configuración personalizada de Tailwind CSS, extendiendo la paleta de diseño.
    └── tsconfig.json           # Configuración de TypeScript, confirmando el uso de un tipado estricto para un código más robusto y menos propenso a errores.
```

---
