# ApuntesLenguajeDeMarcasASIX1-IvanDelgado

# 1 - Github
## 1.1 - Acceder a github
1. Acceder a github.com.
2. Registrarse/Iniciar sesion con tu cuenta.
## 1.2 - Creacion de repositorios
1- Acceder a tu perfil
2- Seleccionar la pestaña "Repositories"
3- Hacer clic en "New" para crear el repositorio
4- Rellenar la informacion sobre el repositorio
## 1.3 - Instalacion de git
1- Buscar git en google
2- Acceder al enlace de "Download for Windows"
3- Seleccionar la version de instalador acorde a nuestro sistema operativo.
### 1.3.1 - Diferentes comandos utiles para git
1- "git init" --> Reiniciar el repositorio
2- "git clone 'URL del repositorio'" --> Clonar el repositorio de github a local
3- "git branch" --> Seleccionar raiz
4- "git add" --> Preparar contenido para hacer comit
5- "git commit -m 'Mensaje comit'" --> Hacer comit con mensaje
6- "git push" --> Publicar commit en github
## 1.4 - Clonacion de repositorio
1- Copiar la url del repositorio desde github
2- Abrir un cmd desde la ubicacion donde queremos clonar el repositorio
3- Utilizar el comando "git clone" seguido de la URL del repositorio
4- Ahora ya podremos trabajar localmente en el repositorio
# 2 - Markdown
## 2.1 - Encabezados
El uso de encabezados es una forma de poder organizar y estructurar un documento.
Para crear estos encabezados utilizaremos las almoadillas (#). Cuantas mas pongamos mas pequeño sera el encabezado empezando por un minimo de 1 y un maximo de 6.
```
    # Encabezado nivel 1
    ## Encabezado nivel 2
    ...
    ###### Encabezado nivel 6
```
## 2.2 - Negrita
Para hacer un texto en negrita deberemos de escribir 2 asteriscos (*) o guiones bajos (_) tanto al incio com al final del texto para que funcione
```
        **Texto de prueba en negrita**
```
## 2.3 - Cursiva
Para hacer un texto en cursiva deberes de escribir 1 asterisco (*) o guion bajo(_) tanto al inico como al final del texto
```
    *Texto de prueba en cursiva*
```
## 2.4 - Listas ordenadas y desordenadas
Para crear una lista ordenada deberemos de escribir un numero segido de un punto (1.) al inicio del texto.
1. Primer apartado
   1. Primer subapartado
   2. Segundo subapartado
2. Segundo apartado
3. Tercer apartado

En cambio, para crear una lista desordenada deberemos de escribir un guion (-) o asterisco (*) al inicio del texto
* Primer apartado
- Segundo apartado
* Tercer apartado
## 2.5 - Mostrar codigo en un repositorio
Para mostrar un trozo de codigo deberemos de escribir 3 acentos abiertos (`) al inicio y al final del codigo
```
    ```
    Texto de prueba para mostrar codigo
    ```
```
## 2.6 - Como poner links
Para colocar un enlace deberemos de escribir el siguiente codigo y copiar y pegar la URL
```
    [Texto del enlace](URL del enlace "Texto emergente al colocar el cursor encima")
```
## 2.7 - Como poner imagenes
Para colocar una imagen deberemos de subir la imagen a nuestro repositorio y seguidamente escribir el siguiente codigo con la URL de la imagen en github
```
    ![Texto alternativo cuando no carga imagen](URL de la imagen "Texto emergente al colocar el cursor encima")
```
## 2.8 - Crear tablas
Para crear tablas utilizaremos las pipes (|) para delimitar las columnas y pondremos una segunda linea con guiones para delimitar el espacio de cada columna. Ademas como detalle podremos poner dos puntos (:) a los laterales de cada columna de guiones en funcion de como queramos alinear el texto
```
    |Columna 1|Columna 2|Columna 3|
    |---------:|:-----------------:|:---------|
    |Texto 1|Texto 2|Texto 3|
    |Primer ejemplo|Segundo ejemplo|Tercer ejemplo|
```