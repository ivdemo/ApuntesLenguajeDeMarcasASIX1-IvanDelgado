# ApuntesLenguajeDeMarcasASIX1-IvanDelgado

# 1 - Github
## 1.1 - Acceder a github
1. Acceder a github.com.
2. Registrarse/Iniciar sesion con tu cuenta.
## 1.2 - Creacion de repositorios
1. Acceder a tu perfil
2. Seleccionar la pestaña "Repositories"
3. Hacer clic en "New" para crear el repositorio
4. Rellenar la informacion sobre el repositorio
## 1.3 - Instalacion de git
1. Buscar git en google
2. Acceder al enlace de "Download for Windows"
3. Seleccionar la version de instalador acorde a nuestro sistema operativo.
### 1.3.1 - Diferentes comandos utiles para git
1. "git init" --> Reiniciar el repositorio
2. "git clone 'URL del repositorio'" --> Clonar el repositorio de github a local
3. "git branch" --> Seleccionar raiz
4. "git add" --> Preparar contenido para hacer comit
5. "git commit -m 'Mensaje comit'" --> Hacer comit con mensaje
6. "git push" --> Publicar commit en github
## 1.4 - Clonacion de repositorio
1. Copiar la url del repositorio desde github
2. Abrir un cmd desde la ubicacion donde queremos clonar el repositorio
3. Utilizar el comando "git clone" seguido de la URL del repositorio
4. Ahora ya podremos trabajar localmente en el repositorio
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
# 3 - HTML
## 3.1 - Introduccion a HTML
HTML es el lenguaje mas importante de Internet dado que sin HTML no se veria nada en el navegador.
HTML define la estructura y el contenido de las paginas web mediante etiquetas, es muy adaptable, tiene estructura logica y es facil de entender.
### 3.1.1 - Elementos
#### Etiqueta de apertura
Consiste en el nombre del elemento cerrado por los simbolos de menor y mayor que (<>) al inicio y al final. Este nos indica donde comienza el elemento.
```
    <p>
```
#### Etiqueta de cierre
Es igual que la etiqueta de apertura , excepto que se le añade una contra barra (/) antes del nombre de la etiqueta.
```
    </p>
```
#### Contenido
Es la informacion que se encuentra entre las etiquetas de apertura y cierre.
```
    <p id="CONTENIDO">
```
#### Elemento
El elemento es la suma del contenido mas las etiquetas de apertura y cierre, es el conjunto total.
### 3.1.2 - Atributos
Los atributos contienen informacion adicional del elemento.
Los atributos se incluyen dentro de la etiqueta de aperturo (lo que significa que no sera visible para el usuario)
## 3.2 - Estructura basica de HTML
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
    
    </body>
    </html>
```
- ```<!DOCTYPE html>```: Indica el tipo de documento.
- ```<html></html>```: Encierra todo el contenido de la pagina entera.
- ```<head></head>```: Contenedor para el contenido que no queremos que se vea en la pagina.
  - ```<meta></meta>```: Añade metainformacion a la pagina.
  - Descripcion de la pagina
  - Palabras clave
  - ```<title></title>```: Establece el titulo de la pagina. Este es el que aparece en la pestaña del navegador.
  - Icono
  - Enlaces con otros ficheros
  - Codigo CSS
- ```<body></body>```: Contenedor para el contenido que queremos mostrar en la pagina.
## 3.3 - Etiquetas basicas de HTML
### 3.3.1 - Rutas
#### Ruta absoluta
Esta ruta especifica la ubicacion completa del archivo en la web, comenzando por el dominio.
#### Ruta relativa
Esta ruta especifica la ubicacion del archivo basandonos desde nuestra ubicacion actual.
### 3.3.2 - Imagenes
Para introducir imagenes en el codigo utilizaremos la etiqueta "<img src="ubicacion">" donde src (source) insertaremos la ubicacion de la imagen que queremos introducir.
### 3.3.3 - Enlaces
Para introducir enlaces utilizaremos la etiqueta "<a href=URL></a>" donde href sirve para insertar la direccion de la web a la que queremos enlazar.
## 3.4 - Formularios
### 3.4.1 - Etiquetas de Formularios
#### Form
Se utiliza para crear formularios y asi permitir que el usuario envie datos.
- Atributos:
  - action: URL donde se enviaran los datos del formulario.
  - method: metodo de envio de datos.
  - enctype: Metodo de codificacion de datos antes de enviar.
  - target: Indica donde se debe de mostrar la informacion del formulario.
#### Input
Se utiliza para crear campos interactivos dentro del formulario.
- Atributos:
  - type: Tipo de entrada que se debe mostrar.
    - radio: Boton de opcion, se agrupa con otros de mismo nombre.
    - checkbox: Casilla de verificacion, permite seleccionar varias.
  - id: Identificador unico para el campo.
  - name: Nombre del campo.
  - value: Valor predeterminado del campo.
  - placeholder: Texto que aparece en el campo cuando esta vacio.
  - required: Indica que el campo debe de ser rellenado antes de enviar el formulario.
  - disabled: Desactiva el campo.
  - readonly: Solo permite leer el campo.
#### Textarea
Sirve para crear un area de texto donde los usuarios pueden escribir texto.
- Atributos:
  - name: Nombre de control que se usara al enviar el formulario.
  - id: Identificador del elemento.
  - rows: Numero de lineas visibles en el area de texto.
  - cols: Numero de caracteres visibles en una linea.
  - placeholder: Texto que aparece en el area cuano esta vacia.
  - required: Se debe de completar el campo antes de enviar.
  - readonly: El campo solo permite leer.
  - disabled: Desactiva el campo.
#### Select
Sirve para describir el contenido de un menu desplegable.
#### Option
Sirve para describir las opciones del menu.
#### Fieldset
Sirve para agrupar elementos que tengan algo en comun dentro de un formulario.
#### Legend
Nos da un titulo para el grupo
#### Button
Sirve para crear botones interactivos en el formulario.
