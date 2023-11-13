# Curso completo de web scraping 2023 | Cree e implemente un rastreador de precios de comercio electrónico
![Raspado web](https://i.ibb.co/9yXKrRP/Thumbnail1.png)

## Introducción
Sumérgete en el web scraping y crea un rastreador de precios de comercio electrónico Next.js 13 en un solo video que te enseña cómo extraer datos, trabajos cron, envío de correos electrónicos, implementación y más.

## Conviértete en uno de los mejores desarrolladores de Next.js 13 en un solo curso
https://www.coderfull.pro

## Consigue el trabajo de programación de tus sueños en 6 meses
https://www.coderfull.pro


## Descripción general

Bienvenido al proyecto Pricewise, una solución integral para rastrear precios de productos en Amazon. Este proyecto está diseñado para extraer detalles del producto de Amazon, almacenar los datos en una base de datos MongoDB y enviar notificaciones por correo electrónico a los usuarios cuando hay cambios en los detalles del producto. El proyecto incluye una aplicación web con una interfaz fácil de usar que permite a los usuarios buscar productos, ver detalles del producto y suscribirse a actualizaciones de productos. La aplicación está construida con Next.js y Tailwind CSS e incluye varios componentes, como una página de inicio, una página de detalles del producto, una barra de navegación, una barra de búsqueda, una tarjeta de producto, una tarjeta de información de precios y un modal.

La lógica del lado del servidor se implementa con funciones sin servidor que manejan diversas tareas, como conectarse a la base de datos, recopilar detalles del producto, actualizar la información del producto y enviar notificaciones por correo electrónico. El proyecto también incluye varias funciones de utilidad para extraer información de páginas web y formatear números.

# Tecnologías y marcos

- Next.js: un marco de React para crear aplicaciones web. Se utiliza tanto para el frontend como para el backend de la aplicación.
- Tailwind CSS: un marco CSS de utilidad para crear rápidamente diseños personalizados. Se utiliza para diseñar la aplicación.
- TypeScript: un superconjunto de JavaScript escrito estáticamente. Se utiliza para escribir el código.
- Mongoose: una biblioteca de modelado de datos de objetos (ODM) para MongoDB y Node.js. Se utiliza para definir el esquema del producto e interactuar con la base de datos MongoDB.
- Nodemailer: un módulo para aplicaciones Node.js que permite enviar correos electrónicos fácilmente. Se utiliza para enviar notificaciones por correo electrónico a los usuarios.
- Axios: un cliente HTTP basado en promesas para el navegador y Node.js. Se utiliza para realizar solicitudes HTTP para extraer detalles del producto de Amazon.
- Cheerio: una implementación rápida, flexible y sencilla del núcleo jQuery diseñada específicamente para el servidor. Se utiliza para analizar la respuesta HTML de la página del producto de Amazon.
- React Responsive Carousel: un componente de carrusel liviano para React. Se utiliza para mostrar un carrusel de imágenes en la página de inicio.
- Google Fonts: una biblioteca de familias de fuentes con licencia gratuita. Se utiliza para definir los estilos de fuente en la aplicación.

# Instalación

Siga estos pasos para instalar y ejecutar el proyecto:

1. **Clonar el repositorio**

   Abra su terminal y ejecute el siguiente comando para clonar el repositorio:

   ```golpecito
   clon de git https://github.com/siendodev/pricewise.git
   ```

2. **Navegue al directorio del proyecto**

   ```golpecito
   cd en cuanto a precio
   ```

3. **Instalar Node.js**

   El proyecto requiere Node.js para ejecutarse. Si no lo tiene instalado, puede descargarlo desde [aquí](https://nodejs.org/en/download/).

4. **Instale los paquetes requeridos**

   El proyecto requiere la instalación de varios paquetes. Ejecute el siguiente comando para instalarlos:

   ```golpecito
   npm yo
   ```

5. **Instale las fuentes requeridas**

   El proyecto requiere que las fuentes "font-inter" y "font-spaceGrotesk" estén disponibles. Puede descargarlos desde [Google Fonts](https://fonts.google.com/).

6. **Configurar las variables de entorno**

   El proyecto requiere que se defina la variable de entorno MONGODB_URI. Puedes hacer esto en un archivo `.env` en la raíz de tu proyecto:

   ```golpecito
   MONGODB_URI=tu_mongodb_uri
   ```

7. **Inicia el servidor**

   Ejecute el siguiente comando para iniciar el servidor:

   ```golpecito
   inicio de ejecución de npm
   ```

Ahora debería poder acceder al proyecto en `http://localhost:3000`.

Tenga en cuenta que el proyecto requiere que el dominio "m.media-amazon.com" sea accesible para el manejo de imágenes. Si no puede acceder a este dominio, puede tener problemas con la carga de imágenes.