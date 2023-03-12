### Error: EACCES: permission denied, mkdir '/usr/lib/node_modules/sass'

<hr>

El error que estás viendo es un error de permisos de instalación de Sass en Node.js. La causa del error es que el usuario actual no tiene los permisos necesarios para instalar Sass en el directorio global de Node.js. Para solucionar el error, se necesitan permisos de administrador

![imagenDeErrorSass](/media/errorSass.png)

Sol.

```sh
sudo npm install -g sass
```
