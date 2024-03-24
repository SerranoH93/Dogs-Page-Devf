# PROYECTO FINAL DEVF
---


## **📌 OBJETIVOS**

-  Construir una Single Page Application utlizando las tecnologías: **React**, **Redux**, **Node**, **Express** y **Sequelize**.
-  Poner en práctica recursos básicos de estilos y diseño.
-  Afirmar y conectar los conceptos aprendidos en la carrera.
-  Aprender mejores prácticas.



## **⚠️ IMPORTANTE**

Es necesario contar minimamente con la última versión estable de NodeJS y NPM. Asegúrate de contar con ella para poder instalar correctamente las dependecias necesarias para correr el proyecto. Actualmente las versiónes necesarias son:

-  **Node**: 12.18.3 o mayor
-  **NPM**: 6.14.16 o mayor

Para verificar que versión tienes instalada:

```bash
node -v
npm -v
```

---


## **📋 PARA COMENZAR...**

1. Deberás forkear este repositorio para tener una copia del mismo en tu cuenta personal de GitHub.

2. Clona el repositorio en tu computadora para comenzar a trabajar. Este repositorio contiene un **`BoilerPlate`** con la estructura general del proyecto, tanto del servidor como del cliente. El boilerplate cuenta con dos carpetas: **`api`** y **`client`**. En estas carpetas estará el código del back-end y el front-end respectivamente.

3. Debes tener instalado **PostgreSQL 15.5 o superior** para poder levantar la base de datos.

4. En la carpeta **`api`** deberás crear un archivo llamado: **`.env`** que tenga la siguiente forma:

   ```env
       DB_USER=usuariodepostgres
       DB_PASSWORD=passwordDePostgres
       DB_HOST=localhost
   ```

5. Reemplazar **`usuariodepostgres`** y **`passwordDePostgres`** con tus propias credenciales para conectarte a postgres. Este archivo va ser ignorado en la subida a github, ya que contiene información sensible (las credenciales).

6. Adicionalmente será necesario que crees, **desde psql (shell o PGAdmin)**, una base de datos llamada **`dogs`**. Si no realizas este paso de manera manual no podrás avanzar con el proyecto.

7. Para instalar las dependendencias, en las capetas **`api`** y **`client`** se debe usar el comando para instalar.

```bash
npm install
```

8. Para inicializar el servidor, en la carpeta **`api`** se usa el siguente comando:

```bash
npm start
```
Podrás ver el siguiente mensaje en tu terminal.

``` 
[0] 
[0] > server@1.0.0 server
[0] > nodemon index.js
[0]  
[0] [nodemon] 2.0.22
[0] [nodemon] to restart at any time, enter `rs`
[0] [nodemon] watching path(s): *.*
[0] [nodemon] watching extensions: js,mjs,json
[0] [nodemon] starting `node index.js`
[0] Server listening on port 3001

```

Esto significa que el servidor ya está corriendo en tu computadora en el puerto 3001. Es decir que podrás acceder a ella desde la URL **`http://localhost:3001`**. Para poder comunicarte con esta API deberás dejar la terminal levantada.

9. Para inicializar el cliente en la carpeta **`client`** se usa el siguiente comando:

```bash
npm run dev
```

Podrás acceder a ella normalmente desde la URL **`http://localhost:5173`**. 