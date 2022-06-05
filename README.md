# TFG

Pasos para poder descargar el repositorio y usar la página web.

Lo primero que hay que hacer es descargar el repositorio en zip, y descomprimirlo. Luego abrir la carpeta descomprimida de TFG en Visual Studio Code, y usaremos en la consola de comandos un npm i boostrap @supabase/supabse-js y npm i ngx-toastr, para instalar todas las dependecias, que aparecen en el package.json, que hacen que se produzca un funcionamiento correcto de la página.

![image](https://raw.githubusercontent.com/Aitor-tercero/TFG/main/TFG/src/assets/images/readme1.png)

Después de tener instaladas todas las dependencias nos vamos al archivo environments.ts para cambiar la variable publickey y url por la del usuario con su base de datos en Supabase.

![image](https://raw.githubusercontent.com/Aitor-tercero/TFG/main/TFG/src/assets/images/readme2.png)

Después de esto lo único que debemos hacer es ejecutar en la terminal el comando ng serve, para ejecutar la página web en nuestro buscador http://localhost:45850/.

Ahora ya tendremos la página web funcionando en nuestro navegador.

![image]https://raw.githubusercontent.com/Aitor-tercero/TFG/main/TFG/src/assets/images/readme3.png
