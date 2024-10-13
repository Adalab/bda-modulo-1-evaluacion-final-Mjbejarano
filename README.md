# Proyecto de Gestión de Inventario 

## Descripción
Este proyecto permite gestionar un inventario de productos y llevar un registro de clientes y sus compras. 

## Estructura del Proyecto
El proyecto está estructurado de la siguiente manera:
1. **Inventario**: Una lista que contiene productos, cada uno representado por un diccionario con `nombre`, `precio` y `cantidad`.
2. **Clientes**: Un diccionario que lleva el registro de los clientes, donde cada cliente tiene un `nombre`, `email` y un historial de `compras`.
3. **Ventas Totales**: Una variable que mantiene un registro del total de ventas realizadas en la tienda.

## Instalación
Para utilizar este proyecto, asegúrate de tener Python instalado en tu sistema. 

## Que podemos hacer en nuestro proyecto?

agregar_producto(nombre, precio, cantidad)

ver_inventario()

buscar_producto(nombre)

actualizar_stock(nombre, cantidad)

eliminar_producto(nombre)

calcular_valor_inventario()

realizar_compra()