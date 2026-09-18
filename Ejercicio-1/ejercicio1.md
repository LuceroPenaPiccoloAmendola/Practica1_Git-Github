<div align="center">

# INSTITUTO POLITÉCNICO NACIONAL

## ESCUELA SUPERIOR DE CÓMPUTO

### BASES DE DATOS

<br>

# PRÁCTICA 1

## EJERCICIO 1

### Parte A y Parte B

<br>

**Nombres:**

Daniel Eduardo Lucero Peña  
Fiorella Karina del Carmen Piccolo Amendola

**Profesor:** Gabriel Hurtado Avilés

**Grupo:** 3CV2

**Fecha:** 05/09/26

</div>

---

# Índice

1. [Parte A](#parte-a)
   - [1. Introducción](#1-introducción)
   - [2. Desarrollo](#2-desarrollo)
     - [2.1 ¿Qué es un sistema de control de versiones?](#21-qué-es-un-sistema-de-control-de-versiones)
     - [2.2 Diferencia entre Git y GitHub](#22-diferencia-entre-git-y-github)
     - [2.3 Conceptos principales](#23-conceptos-principales)
     - [2.4 Flujo de trabajo basado en ramas](#24-flujo-de-trabajo-basado-en-ramas)
   - [3. Conclusión](#3-conclusión)
   - [4. Referencias](#4-referencias)
2. [Parte B](#parte-b)
   - [Evidencia 1: Git Log](#evidencia-1-git-log)
   - [Evidencia 2: Pull Request](#evidencia-2-pull-request)

---

# Parte A

## 1. Introducción

Hoy en día, varios proyectos de programación se hacen en equipo, por esta razón, es importante tener herramientas que permitan organizar trabajos y controlar los cambios que se realizan en los archivos. Si varias personas trabajan al mismo tiempo en un solo proyecto, pueden tener problemas como perder información, sobrescribir en el trabajo del otro o no saber quién hizo un cambio en específico.

Los sistemas controladores de versiones se utilizan para resolver estos problemas. Una de las herramientas más utilizadas es Git, ya que permite registrar los cambios de un proyecto. Además, compartir estos proyectos y colaborar con el equipo es más fácil con plataformas como GitHub, así como la importancia de revisar el código antes de colocarlo al proyecto principal.

---

## 2. Desarrollo

### 2.1 ¿Qué es un sistema de control de versiones?

Para empezar, un sistema de control de versiones es una herramienta que permite registrar y organizar los cambios que se realizan en los archivos de un proyecto. Es bastante útil cuando varias personas trabajan en el mismo proyecto, porque permite saber qué modificaciones realizó cada uno, cuándo se hicieron y recuperar versiones anteriores si algo no funciona.

También permite trabajar de manera más organizada y conservar un historial del proyecto.

---

### 2.2 Diferencia entre Git y GitHub

**Git no es lo mismo que GitHub.**

Git es un sistema de control de versiones que se instala en la computadora y sirve para registrar los cambios de un proyecto.

Por otro lado, GitHub es una plataforma en línea que permite almacenar repositorios de Git y colaborar con otras personas.

Por ejemplo, un equipo puede utilizar Git para controlar los cambios que cada uno hace en el código y usar GitHub para subir el proyecto, compartirlo con los demás integrantes y revisar los cambios antes de agregarlos al proyecto principal.

---

### 2.3 Conceptos principales

#### 1. Repositorio

Es el lugar en el que se encuentra un proyecto y su historial de cambios.

> **Ejemplo:** un repositorio puede tener todos los archivos de un programa que ejecuta operaciones matemáticas y guardar las diferentes versiones que se han creado.

---

#### 2. Confirmación o commit

Es un registro de los cambios realizados en un momento determinado.

> **Ejemplo:** luego de agregar una función para sumar dos números, se puede ejecutar un commit con el mensaje `Se agregó la función suma` y queda registrado el cambio.

---

#### 3. Rama o Branch

Es una versión independiente del proyecto que permite trabajar en una función o cambio sin impactar directamente la versión principal.

> **Ejemplo:** uno de los integrantes puede crear una rama llamada `login` para trabajar en el inicio de sesión, mientras que los demás siguen trabajando en otras partes del proyecto.

---

#### 4. Fusión o Merge

Se trata de unir los cambios hechos en una rama a otra.

> **Ejemplo:** si la función de inicio de sesión ya se realizó, se puede fusionar con la rama principal del proyecto.

---

#### 5. Conflicto de fusión

Esto ocurre cuando no se puede combinar automáticamente dos cambios porque diferentes personas cambiaron la misma parte de un archivo de maneras distintas.

> **Ejemplo:** si dos cambian la misma línea de código, Git marca un conflicto para que el equipo decida qué cambio mantener o cómo combinar ambos.

---

#### 6. Pull Request

Es una petición para añadir los cambios de una rama a otra, normalmente a la principal.

Antes de aceptarlo, los demás pueden revisar el código y hacer comentarios.

---

#### 7. Archivo `.gitignore`

Este se usa para indicar qué archivos o carpetas no deben incluirse en el repositorio.

> **Ejemplo:** puede usarse para evitar subir archivos temporales, personales o archivos que no son necesarios para el proyecto.

---

#### 8. Archivo README

Este tiene información importante sobre el proyecto como qué hace, instrucciones para instalarlo o qué necesita para funcionar.

Es como una guía para que otra persona lo pueda entender.

---

### 2.4 Flujo de trabajo basado en ramas

Este implica que cada integrante del equipo trabaja en una rama diferente para desarrollar una función o solucionar algún problema.

Después de terminar se crea un Pull Request para que los demás revisen los cambios. Si todo está bien, se combinan con la rama principal.

El código se revisa entre pares antes de fusionarse porque otra persona puede detectar errores que no se notaron. Además, se puede comprobar que el código sea claro y que funcione.

De esta manera se reducen los errores y se mejora la calidad del código.

---

## 3. Conclusión

En conclusión, los sistemas de control de versiones son una herramienta importante para llevar a cabo proyectos de programación de una manera más organizada, sobre todo cuando se trabaja en equipo.

Se pueden conservar registros de los cambios, recuperar versiones anteriores y evitar que el trabajo de un integrante afecte el de otros gracias a ellos.

Para finalizar, utilizar un flujo de trabajo basado en ramas y realizar revisiones en equipo ayuda a que un proyecto sea más ordenado, disminuye el riesgo a errores y permite que varias personas trabajen de manera simultánea en el mismo código sin interferir con el trabajo de los demás.

---

## 4. Referencias

1. Universidad San Gregorio. (s. f.). *Vista de Configuración de usuarios en GIT para grupos de desarrollo en entornos universitarios*.  
   https://revista.sangregorio.edu.ec/index.php/REVISTASANGREGORIO/article/view/66/19

2. Espol, R. T. (s. f.). *Revista tecnológica ESPOL - RTE*.  
   https://rte.espol.edu.ec/index.php/tecnologica/es/article/view/442/307

3. *Vista de LOS SISTEMAS DE CONTROL DE VERSIONES*. (s. f.).  
   https://revistas.udistrital.edu.co/index.php/vinculos/article/view/4134/5794

---

# Parte B

## Evidencias

La Parte B contiene las evidencias correspondientes al trabajo realizado durante la práctica con Git y GitHub.

---

## Evidencia 1: Git Log

La siguiente evidencia muestra el historial de commits realizado durante el desarrollo de la práctica.

<div align="center">

![Git Log](Parte%20B/E1B_GitLog.jpeg)

**Figura 1.** Historial de commits mediante Git Log.

</div>

---

## Evidencia 2: Pull Request

La siguiente evidencia muestra el Pull Request realizado para integrar los cambios de la rama del Ejercicio 1 con la rama principal del repositorio.

<div align="center">

![Pull Request](Parte%20B/E1B_PullRequest.jpeg)

**Figura 2.** Pull Request realizado en GitHub.

</div>

---

<div align="center">

## Fin del documento

**Práctica 1 — Ejercicio 1**

</div>