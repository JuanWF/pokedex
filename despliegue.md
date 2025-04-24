# Pokédex Angular

Es una aplicación angular, creada por el desarrollador Keiler Mora, que simula un pokex y esta aplicación donde puede ser vista en vivo a traves del enlace https://keilermora.github.io/pokedex-angular/.
El proyecto fue desarrollado usando la librería de JavaScript [Angular](https://angular.io/) para crear la interfaz de usuario, en comunicación con la Api RESTful [PokéAPI](https://pokeapi.co/).

# Instalar & Ejecutar
1. Descargar el codigo fuente del proyecto de la carpeta **"sistemas-distribuidos\poke-dex-lab\source\pokedex-angular\pokedex-angular.zip"**
2. Descomprime el archivo **pokedex-angular.zip**
3. Luego de descomprimir el archivo, si estás usando sistema operativo Windows, ejecuta las siguientes teclas **"WIN + R"** y colocar el comando **"CMD"**
4. Dentro de la consola ejecuta el comando
		
        cd "sistemas-distribuidos\poke-dex-lab\source\pokedex-angular\"
5. Luego instala las dependencias del proyecto con el siguiente comando:
		
        npm install
6. Ejecuta el proyecto usando el comando:
    
        npm start
7. Abre cualquier navegador web y navega en la url http://localhost:4200/

## Crear y subir repositorio de github

1. En tu cuenta de github crearas un nuevo repositorio llamado **"pokedex"**
2. Estando en la consola donde esta la ruta del proyecto agregaras el repositorio de git con el siguiente comando:

		git remote add origin <link del repositorio>
		
3. iniciamos el repositorio:
		
		git init
4. y subimos los archivos:

		git push -u origin main

## crear aplicacion web statica en azure
1. ingresar al [portal Azure](https://portal.azure.com/#home)
2. Crear un recurso.
3. Buscar static web app y presionar crear.
4. Elegimos la suscripción azure for students.
5. Creamos un nuevo grupo de recursos con el nombre **"rg-pokedex-jdcp"**.
6. Nombre de la aplicacion es **"swa-pokedex-web-prod-jdcp"**.
7. Seleccionamos el plan gratuito.
8. Seleccionamos github y vinculamos la cuenta con azure.
9. Organizacion seleccionar **"<tu nombre de perfil de github>"**.
10. Repositorio **"pokedex"**.
11. Rama **"Main"**. 
12. Valores preestablecidos de compilación **"angular"**.
13. Ubicación de la aplicación:

		/
14. Ubicacion de salida ingresar:

		dist/pokedex-angular
15. presionar **"crear"**, static web app se encargara automaticamente build y el despliegue de la aplicacion.
16. Los cambios que se hagan en el repositorio se actualizaran en tiempo real en azure.

## Esta es la URL publica del despliegue de la aplicacion por azure

https://agreeable-bush-0b2fb3310.6.azurestaticapps.net



