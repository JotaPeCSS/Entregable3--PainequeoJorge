# Simulador de Tienda

## Descripción

Este es un simulador de tienda en línea que permite a los usuarios ver productos, añadirlos a un carrito de compras y realizar la compra. El carrito de compras se puede vaciar y confirmar la compra utilizando una alerta de SweetAlert2.

## Estructura del Proyecto

El proyecto se compone de los siguientes archivos:

- **index.html**: Documento principal HTML que estructura la tienda virtual.
- **styles.css**: Archivo de estilo CSS para el diseño de la tienda y el carrito de compras.
- **script.js**: Archivo JavaScript para cargar y mostrar los productos.
- **shoppingCart.js**: Archivo JavaScript para manejar las operaciones del carrito de compras.
- **data.json**: Archivo JSON que contiene los datos de los productos disponibles.
- **README.md**: Este archivo, que proporciona una guía sobre el uso del simulador de tienda.

## Funcionalidades

1. **Visualización de Productos**:
   - Los productos se cargan dinámicamente desde un archivo JSON.
   - Cada producto muestra una imagen, nombre y precio.
   - Los usuarios pueden añadir productos al carrito de compras.

2. **Carrito de Compras**:
   - Los productos añadidos al carrito se muestran en una lista.
   - Se puede aumentar o disminuir la cantidad de cada producto en el carrito.
   - Los productos pueden ser eliminados del carrito.
   - El carrito muestra el total de la compra.
   - Se puede vaciar el carrito y realizar la compra.

3. **Mensajes y Confirmaciones**:
   - Al vaciar el carrito, si está vacío, se muestra un mensaje informativo.
   - Al vaciar el carrito cuando contiene productos, se muestra una confirmación antes de proceder.
   - Al realizar una compra, se muestra una confirmación y un mensaje de agradecimiento.

## Instrucciones de Uso

1. **Abrir el Proyecto**:
   - Abre el archivo `index.html` en un navegador web para ver la tienda en línea.

2. **Interacción con Productos**:
   - Visualiza los productos en la tienda.
   - Haz clic en "Agregar al Carrito" para añadir productos al carrito.

3. **Gestionar el Carrito**:
   - Revisa el carrito de compras a la derecha.
   - Usa los botones para aumentar, disminuir o eliminar productos del carrito.
   - Haz clic en "Vaciar Carrito" para eliminar todos los productos del carrito (se pedirá confirmación si hay productos).
   - Haz clic en "COMPRAR" para confirmar la compra (se mostrará una alerta de confirmación).

