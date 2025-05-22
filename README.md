# Trabajo Práctico - Validaciones, Funciones y DOM
## Objetivo:
Aplicar conocimientos de JavaScript para validar formularios, utilizar funciones reutilizables y manipular el DOM.
---
## Consignas:
### 1) Agregar al sitio un formulario con los siguientes campos:
- **Nombre** (entrada de texto)  
- **Correo electrónico** (ingrese tipo email)  
- **Asunto** (selecciona con 3 opciones)  
- **Mensaje** (área de texto)  
- **Botón de envío**
---
### 2) Funciones

#### - Función `validarEmail`
Cree una función llamada `validarEmail(email)` que verifique si un correo electrónico es válido con una expresión regular simple (contenga `@` y `.`).

#### - Función `calcularDescuento`
Cree una función que reciba un precio y un porcentaje de descuento, y devuelva el precio final. Probarla con 3 valores distintos.

```javascript
function calcularDescuento(precio, porcentaje) {
  // ...
}
```
### 3) Manipulación del DOM
#### - Contador de caracteres
Agregar un textarea y un párrafo debajo que diga “0 caracteres”. Cada vez que el usuario escriba en el textarea, actualizar el contador.
#### - Cambiar estilo de una caja al pasar el mouse
Agregar un div con una clase caja (tamaño 200px x 200px, fondo gris claro). Cuando el usuario pase el mouse sobre la caja, cambiar el fondo a azul. Cuando salga, volver al color original.

```
elemento.addEventListener('mouseover', () => { ... });
```
```
elemento.addEventListener('mouseout', () => { ... });
```
