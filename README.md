# Práctica 8 - Cuenta de almacenamiento y Blob Storage

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 2 - Sesión 6

En esta práctica se creó una cuenta de almacenamiento para utilizar el recurso de Blob Storage de Azure.

-------------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

-------------------------------------------------------------

#### Pasos a seguir

1. Creamos un grupo de recursos de Azure.

2. En el buscador escribimos “Cuenta de Almacenamiento” y le damos en ‘Crear’. Llenamos los requisitos mínimos para poder crear cualquier recurso y nos aseguramos de que esté habilitado el acceso público desde todas las redes en el apartado de ‘Redes’ y que sea por enrutamiento de Microsoft. Le damos en ‘Revisar y Crear’ y en ‘Crear’.

![P8I1](https://github.com/AlbertoSF99/Practica-8/blob/main/Images/Sesi%C3%B3n%206%20-%20P8%2001.PNG)

![P8I2](https://github.com/AlbertoSF99/Practica-8/blob/main/Images/Sesi%C3%B3n%206%20-%20P8%2002.PNG)

3. Una vez creado la cuenta de Almacenamiento, nos dirigimos al recurso y en el apartado de ‘Contenedores’ le damos en ‘Contenedor’ para crear uno. Le damos un nombre al contenedor y en ‘Nivel de acceso público’ escogemos la opción de acceso y lectura anónimo para contenedores y le damos en ‘Crear’.

![P8I3](https://github.com/AlbertoSF99/Practica-8/blob/main/Images/Sesi%C3%B3n%206%20-%20P8%2003.PNG)

4. Entramos al contenedor y dentro de este le damos en ‘Cargar’. Abrirá el explorador de archivos y escogemos algún archivo para subir. Al hacerlo, aparecerá el archivo en el almacenamiento y se podrá abrir o ejecutar desde ahí.

![P8I4](https://github.com/AlbertoSF99/Practica-8/blob/main/Images/Sesi%C3%B3n%206%20-%20P8%2004.PNG)

***Información Adicional:*** El storage puede ejecutar páginas web que subamos, incluso estáticos, esto por medio de la habilitación de este en el apartado de ‘Sitio web estático’ del contenedor.
