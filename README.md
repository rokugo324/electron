# ConaFormWordScanPDF
Esta aplicacion reliza un documento word a partir de un formulario, que se ve interrumpido por un espacio de subida de pdfs, esta app esta hecha en Laravel, emplea una bd de sqlite, usa la libreria PHPOffice para generar el word y usa Node.js para preparar el empaquetado en Electron
## Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

1. **Node.js**: Necesitarás tener Node.js instalado. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).

2. **npm**: npm es el administrador de paquetes de Node.js. Debería instalarse automáticamente cuando instalas Node.js.

3. **XAMPP**: Este proyecto requiere XAMPP para configurar un servidor web local y una base de datos. Puedes descargar XAMPP desde [apachefriends.org](https://www.apachefriends.org/).

## Configuración del Proyecto

1. **Clonar el Repositorio**: Comienza clonando este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
Instalar Dependencias de Node.js: Asegúrate de instalar las dependencias de Node.js en la carpeta raíz del proyecto:

    
    npm install
2. **Mover la Carpeta**: Mueve el contenido del proyecto a la raíz de tu servidor web local. En el caso de XAMPP, esto suele ser la carpeta htdocs en el directorio de instalación de XAMPP.

3. **Instalar Laravel y PHP**: Asegúrate de instalar Laravel y PHP siguiendo los pasos adecuados para tu sistema operativo. Puedes encontrar las instrucciones de instalación de Laravel en laravel.com.

4. **Configurar la Base de Datos**: Utiliza phpMyAdmin proporcionado por XAMPP para crear una nueva base de datos para tu proyecto. Actualiza la configuración de la base de datos en el archivo .env de Laravel con los detalles de tu base de datos.

45. **Ejecutar el Proyecto**: Una vez que hayas configurado todo, inicia el servidor web y accede a la aplicación a través de tu navegador web:

   
    http://localhost/nombre-del-repositorio/public

## Contribución
Si deseas contribuir a este proyecto, siéntete libre de abrir problemas (issues) y enviar solicitudes de extracción (pull requests).

## Licencia
Este proyecto está bajo la Licencia MIT.

**¡Disfruta explorando y trabajando en el proyecto! Si tienes alguna pregunta, no dudes en abrir un problema en este repositorio.

```bash
Asegúrate de reemplazar `tu-usuario` y `nombre-del-repositorio` con la información adecuada para tu repositorio.
