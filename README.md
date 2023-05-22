# Propuesta Asignatura 

## Integrantes

- BURGOS ZURITA, Edison David
- SISALEMA RIOFRIO, Edwin Josue
- GARCÍA GONZÁLEZ, Demóstenes

## Descripción

Hemos generado un dataset ficticio con 100,000 ventas de una empresa que tiene
varias sucursales en Ecuador con los siguientes campos:

```
- Fecha de venta
- Tienda, objeto con identificador de tienda, nombre de tienda, ubicacion tienda (coordenadas)
- Total ($)
- Impuestos ($)
- Productos, arreglo de objetos con: id de producto, nombre producto, precio producto ($), descuento ($), impuestos ($), precio total ($)
- Comprador, objeto con: identificador de comprador, nombre comprador, telefono comprador, correo comprador
```

La empresa, es una empresa ficticia de venta de artículos para asados, donde se venden asadores de distintos tipos y algunos accesarios para asados.

## Desarrollo

Hemos utilizado Python para crear un dataset ficticio en JSON, el mismo crea artículos, categorías, distintas tiendas, compradores y genera 100,000 ventas ficticias aleatorias.

Para ejecutar el mismo y generar un nuevo dataset, solo debemos ejecutar:

```
python3 dataset_generator.py
```
