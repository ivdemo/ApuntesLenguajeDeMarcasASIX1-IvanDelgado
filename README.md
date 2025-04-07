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
Para hacer un texto en **negrita** deberemos de escribir 2 asteriscos (*) o guiones bajos (_) tanto al incio com al final del texto para que funcione
```
        **Texto de prueba en negrita**
```
## 2.3 - Cursiva
Para hacer un texto en *cursiva* deberes de escribir 1 asterisco (*) o guion bajo(_) tanto al inico como al final del texto
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
Para mostrar un trozo de codigo deberemos de escribir 3 acentos abiertos ( ` ) al inicio y al final del codigo
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
    <p>**Este es el contenido del elemento**</p>
```
#### Elemento
El elemento es la suma del contenido mas las etiquetas de apertura y cierre, es el conjunto total.
### 3.1.2 - Atributos
Los atributos contienen informacion adicional del elemento.
Los atributos se incluyen dentro de la etiqueta de aperturo (lo que significa que no sera visible para el usuario)
```
    <p id="ATRIBUTO">
```
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
Para introducir imagenes en el codigo utilizaremos la etiqueta ```<img src="ubicacion">``` donde src (source) insertaremos la ubicacion de la imagen que queremos introducir.
### 3.3.3 - Enlaces
Para introducir enlaces utilizaremos la etiqueta ```<a href=URL></a>``` donde href sirve para insertar la direccion de la web a la que queremos enlazar.
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
# 4 - CSS
## 4.1 - Introducción a CSS
CSS (Cascading Style Sheets - Hojas de Estilo en Cascada) es un lenguaje utilizado para definir el estilo de los documentos HTML. Permite modificar la apariencia visual (colores, fuentes, márgenes, etc.) de los elementos de una página web.
## 4.2 - Tipos de CSS
### CSS en línea (inline) 
Dentro del propio elemento HTML.  
  ```html
  <h1 style="color: red;">Hola</h1>
  ```
### CSS interno
Dentro de la etiqueta `<style>` en el `<head>` del documento HTML.  
  ```html
  <style>
    h1 {
      color: red;
    }
  </style>
  ```
### CSS externo
En un archivo separado con extensión `.css` enlazado mediante la etiqueta `<link>`.  
  ```html
  <link rel="stylesheet" href="estilo.css">
  ```
## 4.3 - Selectores en CSS
### Selector universal  
  ```css
  * {
    margin: 0;
    padding: 0;
  }
  ```
### Selector de etiqueta  
  ```css
  h1 {
    color: blue;
  }
  ```
### Selector de clase  
  ```css
  .miClase {
    font-size: 18px;
  }
  ```
### Selector de id  
  ```css
  #miId {
    text-align: center;
  }
  ```
### Selector descendente  
  ```css
  div h1 {
    color: green;
  }
  ```

## 4.4 - Propiedades comunes de CSS
### Color y fondo  
  ```css
  color: red;
  background-color: yellow;
  ```
### Texto  
  ```css
  font-size: 16px;
  font-family: Arial;
  text-align: center;
  font-weight: bold;
  ```
### Caja y espaciado  
  ```css
  margin: 10px;
  padding: 5px;
  border: 1px solid black;
  ```
### Display y posición  
  ```css
  display: flex;
  position: relative;
  ```

## 4.5 - Modelo de Caja (Box Model)
El modelo de caja en CSS representa cómo se genera el espacio de los elementos en la página. Se compone de:  
### Contenido (Content)
Lo que contiene el texto o imagen.  
### Relleno (Padding)
Espacio interno entre el contenido y el borde.  
### Borde (Border)
El borde que rodea el padding y el contenido.  
### Margen (Margin)
Espacio externo entre el borde del elemento y otros elementos.  

## 4.6 - Jerarquía HTML para aplicar estilos
Ejemplo básico:  
```html
<div> <!-- Padre -->
  <h1>Hola</h1> <!-- Hijo -->
</div>
```


# 5 - Diseño Responsive

## 5.1 - ¿Qué es el diseño web responsive?

El diseño web responsive o adaptativo es una técnica que busca la correcta visualización de una misma página en distintos dispositivos, desde ordenadores hasta tablets y móviles.

## 5.2 - Media Queries

Media Query es una técnica de CSS3 que usa la regla `@media` para aplicar estilos solo si se cumple una condición.

```css
@media only screen and (max-width: 600px) {
   body {
      background-color: lightblue;
   }
}
```

Permiten que ciertas partes del diseño cambien completamente dependiendo del tamaño de la pantalla.

## 5.3 - Ejemplo con columnas

```css
/* Diseño de columnas */
.column-1 { width: 100%; float: left; }
.column-2 { width: 50%; float: left; }
.column-3 { width: 33.33%; float: left; }
.column-4 { width: 25%; float: left; }
.column-5 { width: 20%; float: left; }
.column-6 { width: 16.66%; float: left; }
.column-75 { width: 75%; float: left; }

@media only screen and (max-width: 600px) {
    .column-2 { width: 100%; }
    .column-3 { width: 100%; }
    .column-4 { width: 50%; }
}
```

## 5.4 - Orientación del dispositivo

```css
@media (orientation: landscape) {
  /* Estilos CSS */
}
```

##  5.5 - Condiciones múltiples

```css
@media only screen and (min-width:320px) and (max-width:480px) {
    /* Estilos CSS */
}
```

## 5.6 - Parámetros comunes en Media Queries

- `width`: anchura del navegador
- `height`: altura del navegador
- `device-width`: anchura del dispositivo
- `device-height`: altura del dispositivo
- `orientation`: `portrait` o `landscape`
- `resolution`: densidad de píxeles

Los prefijos `min-` y `max-` permiten establecer límites superior e inferior.

## 5.7 - Diseño Mobile First

Primero se define el estilo para móviles, y luego se sobrescriben para escritorio:

```css
/* Para móviles */
[class*="col-"] {
  width: 100%;
}

@media only screen and (min-width: 768px) {
  .col-1 { width: 8.33%; }
  .col-2 { width: 16.66%; }
  .col-3 { width: 25%; }
  .col-4 { width: 33.33%; }
  .col-5 { width: 41.66%; }
  .col-6 { width: 50%; }
  .col-7 { width: 58.33%; }
  .col-8 { width: 66.66%; }
  .col-9 { width: 75%; }
  .col-10 { width: 83.33%; }
  .col-11 { width: 91.66%; }
  .col-12 { width: 100%; }
}
```

## 5.8 - Metaetiqueta Viewport

Esta etiqueta se inserta en el `<head>` del HTML y define cómo se adapta la página a la pantalla:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### 5.8.1 - Atributos de la metaetiqueta Viewport

| Atributo          | Valores posibles                | Descripción |
|-------------------|----------------------------------|-------------|
| `width`           | Pixels o `device-width`         | Ancho de la página |
| `height`          | Pixels o `device-height`        | Alto de la página |
| `initial-scale`   | Número real ≥ 0.1               | Zoom inicial |
| `user-scale`      | `yes` / `no`                    | Permitir zoom al usuario |
| `minimum-scale`   | Número real ≥ 0.1               | Zoom mínimo permitido |
| `maximum-scale`   | Número real ≥ 0.1               | Zoom máximo permitido |
