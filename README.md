#### ACCESOS A API CON JS

Ejemplos de accesos a API a través de JS.

## 📁airtable

Acceso a datos la aplicacion AIRTABLE

### Cómo importar datos desde un fichero CSV en la tabla Productos

1. Accede a tu base de datos en [Airtable](https://airtable.com/).
2. Crea una nueva tabla llamada **Productos**.
3. Haz clic en el menú de la tabla y selecciona **Importar datos**.
4. Elige la opción **CSV** y selecciona tu archivo `Productos.csv`.
5. Revisa que los campos se correspondan correctamente y confirma la importación.

###  config.js
Renombra el fichero config-sample.js por config.js y rellena las apikeys con los valores que hayas generado.


### Cómo obtener las claves API para la tabla Productos con permisos de lectura

1. Accede a tu cuenta en [Airtable](https://airtable.com/).
2. Ve al área de desarrolladores: haz clic en tu avatar (arriba a la derecha) y selecciona **Developer hub** o accede directamente a [Airtable Developer Hub](https://airtable.com/developers).
3. En la sección **API keys**, haz clic en **Create API key**.
4. Asigna un nombre descriptivo a la clave (por ejemplo, "Lectura Productos").
5. Selecciona los permisos de **read** (solo lectura) y elige la base de datos donde está la tabla **Productos**.
6. Guarda la clave generada y cópiala.
7. Utiliza esta clave en tu archivo de configuración JS (`sample.js`) para realizar peticiones a la API de Airtable con permisos de lectura.

> **Importante:** No compartas tu clave API públicamente y guárdala en un archivo seguro.







## 📁Open data euskadi

Open data de euskadi

## 📁github

Archivos para ver a api de github. Un unico nivel de profundidad

## 📁open-meteo




## 📁pokeapi

Buscador de pokemones generado por IA

## 📁 themoviedb - recorrer apis en JS

Para poder usar el buscador de peliculas hay que registrase en [themoviedb](https://www.themoviedb.org/) y obtener la API_KEY  y la ACCESS_TOKEN.

### 01-buscador.html
Examina en consola cualquier url a una api. Mostrando los niveles de anidación. Hay que acceder a la consola del inspector para ver los resultados.

### 02-peliculas.html
Buscador de peliculas a traves de la API themoviedb.org. 
Primero busca los  resultados de la primera página y luego nos permite ver los de una de las peliculas seleccionada. (En la consola se ven los creditos)

#### 03-api_key.html 

Acceso con api_key a traves de url

### 03-api_access_token.html

Acceso a traves de access_token en los headers (auth)

#### Mejoras propuestas
- mostrar los resultados paginados
- ver los resutados mas amigablemente
- ....


