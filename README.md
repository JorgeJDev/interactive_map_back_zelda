### Eng: My most recent personal project consists of an interactive map that meets all the requirements learned during my Full Stack bootcamp training. In the backend, I primarily use the combination of Node.js, Express, MongoDB, Express-Validator, and Firebase.  I also use the NPM package manager.

### Esp: Mi proyecto personal más reciente consiste en un mapa interactivo que cumple con todos los requisitos aprendidos durante mi formación en el bootcamp de Full Stack. En el backend, utilizo principalmente la combinación de Node.js, Express, MongoDB, Express-Validator y Firebase. También uso el gestor de paquetes NPM.

## Base de datos de entradas:

## Link al despliegue: https://backmapjorge.onrender.com

- Obtener todas las entradas:
````
- GET: https://backmapjorge.onrender.com/api/v1/entries
````  

- Obtener una entrada por ID:
````
- GET: https://backmapjorge.onrender.com/api/v1/entries/:id
```` 
- Obtener entradas por query search:
````
https://backmapjorge.onrender.com/api/v1/entries/?search=tower
````
- Crear una entrada:
````
- POST: https://backmapjorge.onrender.com/api/v1/entries
````  

- Editar una entrada por id:
````
- PUT: https://backmapjorge.onrender.com/api/v1/entries/:id
````
- Eliminar una entrada por id:
````
- DELETE: https://backmapjorge.onrender.com/api/v1/entries/:id
````  
-Eliminar todas las entradas de un usuario por id:
````
- DELETE: https://backmapjorge.onrender.com/api/v1/entries/user/
````  
## Base de datos de los usuarios:
- Obtener todos los usuarios:
````
- GET: https://backmapjorge.onrender.com/api/v1/users
````
- Obtener un usuario por ID:
````
- GET: https://backmapjorge.onrender.com/api/v1/users/:id
````
- Crear un usuario:
````
- POST: https://backmapjorge.onrender.com/api/v1/auth/register
````
- Editar un usuario por id:
````
- PUT: https://backmapjorge.onrender.com/api/v1/users/:id
````
- Eliminar un usuario por id:
````
- DELETE: https://backmapjorge.onrender.com/api/v1/users
````

## Endpoints de autentificación:

- Logear con un usuario:
````
- POST: https://backmapjorge.onrender.com/api/v1/auth/login
````
- Delogear con un usuario:
````
- GET: https://backmapjorge.onrender.com/api/v1/auth/logout
````
- Renovar token de usuario:
````
- POST: https://backmapjorge.onrender.com/api/v1/auth/renew
````
- Logout de un usuario:
````
https://backmapjorge.onrender.com/api/v1/auth/logout
````