# whatsapp-button

Whatsapp Button, es un componente custom para agregar un botón que nos redirige a whatsapp.


## Configuración

### Paso 1 - Configuración Básica

Crear un nuevo repositorio usando el template de GitHub react-app-template.

### Paso 2 - Clonación del repositorio

Clone este repositorio en sus archivos locales para poder comenzar a trabajar en él de manera efectiva.

Luego, acceda al directorio del repositorio usando su terminal.

## Paso 3 - Editar el Manifest.json

Configurar el Manifest.json basado en el siguiente ejemplo:

```json
{
  "vendor": "itgloberspartnercl",
  "name": "whatsapp-button",
  "version": "0.0.1",
  "title": "WhatsApp Button Component",
  "description": "Component button for WhatsApp that will receive a phone, a logo and a message",
  "builders": {
    "react": "3.x",
    "messages": "1.x",
    "docs": "0.x",
    "store": "0.x"
  },
}
```
## Paso 4 - Instalar apps necesarias

Acceda a la carpeta React por medio de el comando cd react, una vez ubicado en esta carpeta ejecute el comando yarn install el cual instalara todas las dependencias necesarias para la ejecución de el componente.

Una vez terminada la instalación verifique que hayan quedado instalados los archivos de node-modules.

## Paso 5 - Ejecute un preview de la tienda

Una vez realizadas las configuraciones necesarias de el componente  ejecutar el comando vtex link dentro de el proyecto, de esta forma se vinculara nuestro componente custom a nuestro proyecto base. Si no hay ningun error la terminal mostrara la siguiente información: info: App linked successfully

## Dependencies

```json
{
 "itgloberspartnercl.whatsapp-button": "0.x"
}
```
