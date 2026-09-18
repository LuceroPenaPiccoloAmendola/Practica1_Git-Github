<div align="center">



\# BASES DE DATOS



\## PRÁCTICA 1



\### EJERCICIO 5



<br>



\*\*Nombres:\*\*

Daniel Eduardo Lucero Peña

Fiorella Karina del Carmen Piccolo Amendola



\*\*Profesor:\*\* Gabriel Hurtado Avilés



\*\*Grupo:\*\* 3CV2



\*\*ESCOM\*\*



\*\*Fecha:\*\* 17/09/26



</div>



\---



\# Índice



1\. \[Introducción](#1-introducción)

2\. \[Entrevista de Levantamiento de Requerimientos](#2-entrevista-de-levantamiento-de-requerimientos)

3\. \[Requerimientos del Sistema](#3-requerimientos-del-sistema)

&#x20;  - \[3.1 Datos que el sistema debe almacenar](#31-datos-que-el-sistema-debe-almacenar)

&#x20;  - \[3.2 Funciones que el sistema debe cumplir](#32-funciones-que-el-sistema-debe-cumplir)



\---



\# 1. Introducción



Para conocer las necesidades del supermercado y determinar qué información debe manejar la base de datos, se realizó una entrevista con el dueño del establecimiento. Durante la entrevista se indagó principalmente sobre la gestión de productos, control de inventario, ventas, proveedores, empleados y clientes frecuentes.



\---



\# 2. Entrevista de Levantamiento de Requerimientos



> \\\*\\\*Participantes:\\\*\\\*  

> \\\* \\\*\\\*Consultores:\\\*\\\* Equipo de consultores de bases de datos.  

> \\\* \\\*\\\*Dueño:\\\*\\\* Encargado/Dueño del supermercado.



\---



\*\*Consultores:\*\* Buenos días. Somos un equipo de consultores de bases de datos y queremos conocer cómo funciona actualmente su supermercado para identificar qué información necesita almacenar y consultar.



\*\*Dueño:\*\* Claro, sin problema. Ahorita tenemos algunos problemas para llevar el control de nuestros productos y ventas.



\*\*Consultores:\*\* ¿Qué información necesitan guardar de cada producto?



\*\*Dueño:\*\* Necesitamos guardar el nombre del producto, código de barras, precio, marca, cantidad disponible y proveedor.



\*\*Consultores:\*\* ¿Cuántos productos manejan aproximadamente?



\*\*Dueño:\*\* Tenemos alrededor de 2,000 productos diferentes.



\*\*Consultores:\*\* ¿Cómo controlan actualmente la cantidad de productos disponibles?



\*\*Dueño:\*\* Se lleva un registro, pero algunas veces no está actualizado porque los productos entran y salen constantemente.



\*\*Consultores:\*\* ¿Con qué frecuencia necesitan consultar el inventario?



\*\*Dueño:\*\* Prácticamente todos los días, para saber qué productos están por agotarse.



\*\*Consultores:\*\* ¿Qué información sería importante conocer?



\*\*Dueño:\*\* Saber cuántas unidades tenemos de cada producto, cuáles están agotadas y cuáles necesitan ser surtidas.



\*\*Consultores:\*\* ¿Necesitan guardar información de los proveedores?



\*\*Dueño:\*\* Sí. Necesitamos saber qué proveedor proporciona cada producto y tener sus datos de contacto.



\*\*Consultores:\*\* ¿Qué datos necesitan guardar?



\*\*Dueño:\*\* Nombre del proveedor, teléfono, correo electrónico y dirección.



\*\*Consultores:\*\* ¿Qué necesitan registrar cuando se realiza una venta?



\*\*Dueño:\*\* Necesitamos saber qué productos se vendieron, cuántas unidades, el precio, la fecha y el total de la venta.



\*\*Consultores:\*\* ¿Con qué frecuencia consultan las ventas?



\*\*Dueño:\*\* Todos los días. También nos interesa saber las ventas de una semana, un mes o un tiempo determinado.



\*\*Consultores:\*\* ¿Necesitan relacionar las ventas con los empleados?



\*\*Dueño:\*\* Sí. Queremos saber qué empleado realizó cada venta.



\*\*Consultores:\*\* ¿Qué información necesitan guardar de los empleados?



\*\*Dueño:\*\* Nombre, número de empleado, puesto y teléfono.



\*\*Consultores:\*\* ¿Registran información de sus clientes?



\*\*Dueño:\*\* Sí, principalmente de los clientes que tienen una tarjeta o son clientes frecuentes.



\*\*Consultores:\*\* ¿Qué información necesitan guardar?



\*\*Dueño:\*\* Nombre, teléfono, correo y número de cliente.



\*\*Consultores:\*\* Esas serían todas nuestras preguntas, gracias por contestar.



\---



\# 3. Requerimientos del Sistema



A partir de la entrevista realizada con el encargado del supermercado, se establecieron los siguientes requerimientos formales para el diseño de la base de datos:



\## 3.1 Datos que el sistema debe almacenar



1\. \*\*Productos:\*\* Nombre, código de barras, precio, marca, proveedor y cantidad.

2\. \*\*Categorías:\*\* Nombre e identificador de la categoría.

3\. \*\*Proveedores:\*\* Nombre, teléfono, correo y dirección.

4\. \*\*Inventario:\*\* Producto, cantidad disponible y fecha de actualización.

5\. \*\*Ventas:\*\* Fecha, total, empleado que realizó la venta y cliente (cuando esté registrado).

6\. \*\*Detalle de venta:\*\* Productos vendidos, cantidad y precio de cada producto.

7\. \*\*Empleados:\*\* Nombre, número de empleado, puesto y teléfono.

8\. \*\*Clientes:\*\* Nombre, número de cliente, teléfono y correo electrónico.



\---



\## 3.2 Funciones que el sistema debe cumplir



1\. Registrar, consultar y actualizar la información de productos, proveedores, empleados y clientes.

2\. Controlar las existencias del inventario y actualizar las cantidades después de cada venta.

3\. Registrar las ventas y los productos incluidos en cada una.

4\. Consultar las ventas realizadas durante un día o periodo determinado.

5\. Identificar productos con pocas existencias o agotados.

6\. Consultar los productos más vendidos y las ventas realizadas por cada empleado.

7\. Consultar qué productos proporciona cada proveedor.

8\. Generar reportes que faciliten el control del inventario y ventas.



\---



<div align="center">



\*\*Fin del Ejercicio 5\*\*



</div>





\---



\## Evidencia: Modelo Entidad-Relación



<div align="center">



!\[Modelo Entidad-Relación del Ejercicio 5](E5\_ModeloER.png)



\*\*Figura 1.\*\* Diagrama del Modelo Entidad-Relación para la base de datos del supermercado.



</div>

