# ProShop eCommerce

> Este eCommerce fue construido siguiendo un proyecto de un antiguo curso que compre a principios de este año. Terminar el curso de Backend de Coderhouse me ayudo a entender mejor algunas partes, pero aún tengo mucho por aprender y mejorar.

![screenshot](https://github.com/bradtraversy/proshop_mern/blob/master/uploads/Screen%20Shot%202020-09-29%20at%205.50.52%20PM.png)


### Env Variables

Para que todo funcione bien se deberá crear un archivo .env en la carpeta raíz con los siguientes datos.

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Instalar dependencias (frontend & backend)

```
npm install
cd frontend
npm install
```

### Ejecución

```
# Ejecutar frontend (:3000) y backend (:5000)
npm run dev

# Ejecutar backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Base de datos

Por defecto el sitio no contará con ningún artículo, puede usar los siguientes comandos para importar datos al sitio

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

### Usuarios

Para probar el sitio, se dejan algunos usuarios con las credenciales necesarias

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```
