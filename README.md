## Instalación de dependencia y ejecución.

1. Ejecutar "npm install".
2. 
   a. Ejecutar "npm start" la aplicación se ejecutará con el comando "node server.js".
   b. Ejecutar "npm run dev" la aplicación se ejecutará con el comando "nodemon server.js".

## Probar el programa en Heroku  

URL https://proyecto-final-nodejs-36535.herokuapp.com/

1. Tener el programa POSTMAN instalado.
2. Importar la colleción "Proyecto_Final_NodeJS_36535.postman_collection.json".
3. En la sección "variable" de la colleción ingresar un value en EMAIL y un value en PHONE (formato: +54.... u otro prefijo) para probar los end points.
4. Una vez importada la colleción en la request de LOGIN, NEW CART colocar email en el JSON.
5. Realizar el registro de un nuevo usuario con sus respectivos datos.
6. Realizar el login con las credeciales correspondientes.
7. Crear un nuevo carrito con el email correspondiente.
8. Realizar el checkout con el id de un carrito.
9. Realizar una consulta al perfil para obtener los datos del usuario.
