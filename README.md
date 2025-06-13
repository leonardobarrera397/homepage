👋 Mi Página de Inicio Retro 2000s
¡Bienvenido al repositorio de Mi Página de Inicio Retro 2000s! Este proyecto es una aplicación web personal diseñada con una estética nostálgica inspirada en la era digital de principios de los años 2000. Combina un diseño profesional con un toque retro, ofreciendo un acceso rápido y visual a tus herramientas web más frecuentes.

🚀 Descripción General
Esta página de inicio está construida como una aplicación de React y utiliza Tailwind CSS para una estilización eficiente y responsiva. Su propósito principal es servir como un portal centralizado donde puedes organizar y acceder rápidamente a tus aplicaciones y servicios en línea más utilizados, todo ello envuelto en una interfaz que te transportará de vuelta al cambio de milenio.

✨ Características Destacadas
Diseño Retro Auténtico: Una estética cuidadosamente elaborada para evocar la sensación de los sitios web de los años 2000, con paletas de colores específicas, tipografías clásicas y efectos visuales de la época.

Construido con React: Desarrollado como una aplicación de página única (SPA) utilizando el moderno framework React, lo que facilita la modularidad, escalabilidad y mantenimiento del código.

Estilización con Tailwind CSS: Todas las clases de utilidad de Tailwind CSS se utilizan para aplicar estilos, garantizando un diseño responsivo y un desarrollo ágil sin necesidad de escribir CSS personalizado extenso.

Iconos Interactivos: Enlaces visuales representados por iconos claros e interactivos para tus herramientas web más frecuentes, mejorando la usabilidad.

Completamente Responsivo: La interfaz se adapta perfectamente a diferentes tamaños de pantalla, desde dispositivos móviles hasta escritorios.

🛠️ Tecnologías Utilizadas
React: Biblioteca de JavaScript para construir interfaces de usuario.

Vite: Herramienta de construcción rápida para el desarrollo frontend.

Tailwind CSS: Framework CSS de utilidad para un diseño rápido y personalizable.

Font Awesome: Librería de iconos (referenciada a través de CDN en el HTML).

⚙️ Configuración del Proyecto
Para ejecutar este proyecto localmente, sigue estos pasos:

Clona el Repositorio:

git clone https://github.com/tu-usuario/nombre-del-repositorio.git
cd nombre-del-repositorio

Instala las Dependencias:
Si ya tienes un proyecto Vite con React, simplemente instala las dependencias:

npm install # o yarn install

Si estás creando un nuevo proyecto Vite:

npm create vite@latest nombre-del-proyecto -- --template react
cd nombre-del-proyecto
npm install

(Asegúrate de que react y react-dom estén en tus dependencias).

Configura Tailwind CSS:
Asegúrate de que Tailwind CSS esté configurado correctamente en tu proyecto Vite con React. Puedes seguir la Guía de instalación de Tailwind CSS con Vite.

Añade Font Awesome (CDN):
Asegúrate de que la siguiente línea esté incluida en la sección <head> de tu archivo public/index.html:

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

🚀 Ejecución del Proyecto
Una vez que las dependencias estén instaladas y Tailwind CSS configurado, puedes iniciar la aplicación:

npm run dev # o yarn dev

Esto abrirá la aplicación en tu navegador predeterminado, generalmente en http://localhost:5173/ (o un puerto similar).

📝 Personalización
Herramientas: Edita el array tools en src/App.jsx (o src/App.tsx si usas TypeScript) para añadir, modificar o eliminar los enlaces a tus herramientas web.

Información Personal: Actualiza "Tu Nombre" en el pie de página.

Colores y Estilos: Ajusta los colores y las propiedades de Tailwind CSS en la configuración tailwind.config.js si deseas modificar aún más la estética retro.

🤝 Contribuciones
Las contribuciones son bienvenidas. Si tienes sugerencias para mejorar el diseño o la funcionalidad, no dudes en abrir un issue o enviar un pull request.

¡Disfruta de tu viaje al pasado con esta página de inicio!
