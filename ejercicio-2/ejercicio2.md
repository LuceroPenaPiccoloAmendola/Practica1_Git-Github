<div align="center">



\# BASES DE DATOS



\## PRÁCTICA 1



\### EJERCICIO 2



\### Parte A



<br>



\*\*Nombres:\*\*  

Daniel Eduardo Lucero Peña  

Fiorella Karina del Carmen Piccolo Amendola



\*\*Profesor:\*\* Gabriel Hurtado Avilés



\*\*Grupo:\*\* 3CV2



\*\*ESCOM\*\*



\*\*Fecha:\*\* 06/09/26



</div>



\---



\# Índice



1\. \[Introducción](#1-introducción)

2\. \[Desarrollo](#2-desarrollo)

&#x20;  - \[2.1 Contenedores y máquinas virtuales](#21-contenedores-y-máquinas-virtuales)

&#x20;  - \[2.2 Conceptos principales de Docker](#22-conceptos-principales-de-docker)

&#x20;  - \[2.3 Importancia de los volúmenes](#23-importancia-de-los-volúmenes)

3\. \[Conclusión](#3-conclusión)

4\. \[Referencias](#4-referencias)



\---



\# 1. Introducción



Los contenedores se han convertido en herramientas importantes para el desarrollo e instalación de aplicaciones, porque permiten crear ambientes de trabajo aislados y fáciles de transportar entre equipos distintos. Docker es una de las tecnologías más usadas para trabajar con ellos.



Un contenedor, a diferencia de una máquina virtual, no necesita ejecutar un sistema operativo completo. Por lo tanto, utiliza menos recursos y puede iniciar más rápido.



Para entender cómo funcionan es necesario conocer algunos conceptos básicos, como imagen, volumen, puerto publicado y contenedor. También es importante entender qué pasa con los datos si no se utiliza un volumen, ya que esto puede llevar a que se pierda información cuando se elimina un contenedor.



\---



\# 2. Desarrollo



\## 2.1 Contenedores y máquinas virtuales



Un contenedor es un entorno ligero que ejecuta una aplicación con sus dependencias compartiendo el núcleo del sistema operativo anfitrión, lo que le permite iniciar en segundos y ocupar poco espacio.



En contraste, una máquina virtual simula una computadora completa con su propio sistema operativo y un hipervisor, por lo que requiere más espacio (gigabytes) y tiempo de arranque, aunque ofrece un nivel de aislamiento más fuerte.



\---



\## 2.2 Conceptos principales de Docker



A continuación, se presentan algunos de los conceptos principales relacionados con Docker:



\### 1. Imagen



Es un paquete que tiene los elementos necesarios para crear y ejecutar un contenedor.



\### 2. Contenedor



Es una imagen que está funcionando. Por ejemplo, una imagen de PostgreSQL se puede usar para crear un contenedor que funcione con una base de datos.



\### 3. Volumen



Es un espacio de almacenamiento administrado por Docker que permite conservar información independiente del ciclo de vida del contenedor.



\### 4. Puerto publicado



Este permite que un servicio en funcionamiento dentro del contenedor sea accesible desde fuera de este.



\---



\## 2.3 Importancia de los volúmenes



El volumen es indispensable cuando una aplicación necesita mantener datos, aunque el contenedor sea eliminado.



Si no se declara un volumen, los datos que se escriban dentro de la capa de almacenamiento quedan asociados a ese contenedor. Estos pueden usarse con normalidad mientras el contenedor exista, pero si se elimina, esa información deja de estar disponible.



Por esta razón, los volúmenes permiten conservar los datos de manera independiente al ciclo de vida del contenedor.



\---



\# 3. Conclusión



En conclusión, en este trabajo se aprendió que los contenedores son herramientas útiles para ejecutar aplicaciones de forma más rápida y con menor uso de recursos que una máquina virtual.



También se conoció cómo funcionan sus elementos principales, como los volúmenes, ya que permiten conservar los datos, aunque sean eliminados los contenedores.



Por estas razones, saber utilizar correctamente Docker no solo ayuda a ejecutar aplicaciones, sino también a poder mantener la información segura y organizada.



\---



\# 4. Referencias



1\. Entornos y contenedores | 2.1. Introducción. (s. f.).  

&#x20;  https://eines-informatiques.recursos.uoc.edu/entornos-y-contenedores/es/2-1-introduccion/



2\. Vista de Uso de contenedores para la construcción de productos de software. (s. f.).  

&#x20;  https://cuadernos.tic.unam.mx/index.php/cua/article/view/15/36



3\. Google Cloud.  

&#x20;  https://cloud.google.com/discover/containers-vs-vms?hl=es



\---



<div align="center">



\*\*Fin de la Parte A\*\*



</div>



---

# Parte B

## Evidencia 1: Conexión con la base de datos

En esta evidencia se muestra la conexión con la base de datos realizada durante el desarrollo del ejercicio.

<div align="center">

![Conexión con la base de datos](Parte%20B/E2B_Cap_ConexionBd.jpeg)

**Figura 1.** Conexión con la base de datos.

</div>

---

## Evidencia 2: Prueba de persistencia

En esta evidencia se muestra la prueba de persistencia realizada para comprobar el comportamiento de los datos.

<div align="center">

![Prueba de persistencia](Parte%20B/E2BCap_PruebaPersistencia.jpeg)

**Figura 2.** Prueba de persistencia.

</div>

---

<div align="center">

**Fin del Ejercicio 2**

</div>

