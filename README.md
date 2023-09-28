# CALCULADORA HTML

Calculadora desarrollada en lenguaje html, usando css y JavaScript.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Explicación](#explicación)
- [Uso](#uso)
- [Características](#características)

## Instalación
Descarga proyecto zip.

```shell
git clone https://github.com/KevinMMF23/CALCULADORA-HTML.git
```
## Explicación 
Esta línea busca en el documento HTML un elemento con la clase "display". En este caso, se está buscando el elemento que muestra el resultado en la calculadora.
```shell
document.querySelector(".display");
```
Esto busca todos los elementos button en el documento y los almacena en una lista llamada buttons. En otras palabras, obtiene todos los botones en la calculadora.
```shell
const buttons = document.querySelectorAll("button");
```
Esto obtiene el texto que está dentro del botón que se acaba de hacer clic y lo almacena en la variable buttonText. Por ejemplo, si haces clic en el botón "7", buttonText contendrá "7".
```shell
buttonText = button.textContent;
```
Esto es un bucle que recorre todos los botones en la lista buttons. Para cada botón, ejecuta el código dentro de las llaves { ... }. En otras palabras, se está configurando un "escuchador" para cada botón.

```shell
buttons.forEach((button) => { ... }: 
```
Esta línea agrega un "escuchador" a cada botón para el evento de clic. Cuando se hace clic en un botón, se ejecuta el código dentro de las llaves { ... }. Esto permite que la calculadora reaccione cuando se hace clic en los botones.
```shell
button.addEventListener("click", () => { ... } 
```
## Características
- Sencillo de usar.
- Desarrollado en visual studio code con los lenguajes antes mencionados.

## Uso
El uso de esta página es muy sencillo, es el uso que le hemos dado a cualquier
tipo de calculadora, en este caso es una sencilla.
Seleccionamos los numeros que necesitemos y luego un operador matemático.







