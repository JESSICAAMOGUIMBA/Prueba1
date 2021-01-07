# ESCUELA POLITÉCNICA NACIONAL

* ING. JUAN PABLO ZALDUMBIDE 👨🏻‍🏫

#  LOGIN CON GMAIL USANDO IONIC & FIREBASE

INTEGRANTES DE GRUPO  👨‍💻👩‍💻 👨‍💻👩‍💻 👨‍💻
- Amoguimba Jessica
- Gómez Samanta
- Guaras Ahilton
- Ibujés Gabriel
- Mendoza Joel


# INTRODUCCIÓN # 📝

Este README contiene un explicativo del la aplicación de login con Gmail la misma que fue realizada en Ionic usando Angular y Firebase con autenticacion de Gmail.

## Acerca del proyecto ##
### Explicación ###


### Comandos usados
Ejecutaremos los siguientes comandos :
```
- Instalar ionic 
npm install -g @ionic/cli

- Ejecutar Ionnic
ionic serve
ionic serve -l

- Crear el servicio
ionic g service services/nombreservicio

- Instalar Firebase
npm install firebase @angular/fire --save

- Intalar Cordova
npm install -g ionic cordova

- Generar APK 
ionic cordova build android


```
## Credenciales 

- Firebase
![myimage-alt-tag](https://github.com/SamantaGomez/Authentication-Login/blob/main/imagenes/8.jpeg)

- API
	http://www.omdbapi.com/



## Funcionalidad del Proyecto :pencil2:

- Base de datos

| **Firebase Auth** :speech_balloon:| **Usuarios** :speech_balloon: | **Historial** :bust_in_silhouette: |
| ------------- | ------------- | ------------- | 
|![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/firebase%20auth.JPG) |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/firebase_users.JPG) |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/firebase_historial.JPG)  |![myimage-alt-tag]|

## Interfaces

- Usuario

La aplicación nos permitirá iniciar sesión, en el caso de contar con una cuenta previamente creada. Caso contrario deberemos crear una.
Se podrá buscar (películas, series, episodios) por título, además de visualizar la información de las películas.


| **login** :speech_balloon: | **register** :bust_in_silhouette: | **movies** :clapper:|**movies details** :scroll:|
| ------------- | ------------- | ------------- | ------------- |
|![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/login.JPG) |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/register.JPG)  |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/movies.JPG)  |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/movie_info.JPG) |

- Administrador

El administrador podrá ver el historial de usuarios, modificar y eliminar estos.

| **Users** :speech_balloon: | **Historial** :alarm_clock: |**Edit User** :black_nib:| **New User** :heavy_check_mark:|
| ------------- | ------------- | ------------- |------------- |
|![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/users.JPG) |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/historial.JPG)  |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/edit_user.JPG)  |![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/new_user.JPG)  |

## Código:
En la siguiente imagen se muestran las páginas creadas.
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/paginas.JPG) 

En el siguiente código se puede observar la conexión con la API
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/servicio%20pelis.JPG)


Esta imagen se puede apreciar la conexión con la Base de Datos.
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/credenciales_fire.JPG)

A continuación se describen los métodos de Autenticación, Registro y Cierre de Sesión.
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/firebase%20auth.JPG)


Esta fracción de código representa el método de búsqueda de películas.
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/movie_page.JPG)




Este código representa los métodos de Geolocalización, e Historial de películas buscadas por usuario. Para este método es necesario el Id del usuario ya que de esta forma se podrá guardar su historial de búsquedas.
![myimage-alt-tag](https://github.com/wendysoto/proyecto_finalTopicos/blob/master/images/movie_details.JPG)


## Video en Yotube :movie_camera:
 


### Referencias ###
    1. https://ionicacademy.com/ionic-4-app-api-calls/
    2. https://www.youtube.com/watch?v=REgMMe2fYKA
    3. https://www.nigmacode.com/ionic/Exportar-y-firmar-APK-en-Ionic
 	4. https://gradle.org/install/
 	5. https://ionicacademy.com/ionic-4-app-api-calls/
 	6. http://www.omdbapi.com/
   
