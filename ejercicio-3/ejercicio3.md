<div align="center">

# Bases de Datos

## Práctica 1

# Ejercicio 3. Investigación

<br>

**Nombre:** Daniel Eduardo Lucero Peña y Fiorella Karina del Carmen Piccolo Amendola

**Profesor:** Gabriel Hurtado Avilés

**Grupo:** 3CV2

**ESCOM**

**Fecha:** 12/09/26

</div>

---

# Índice

1. **Introducción**

2. **Desarrollo**
   - 2.1. Dato, información y base de datos
   - 2.2. Características de una base de datos
   - 2.3. Archivos frente a bases de datos
   - 2.4. Usuarios de una base de datos
   - 2.5. Ciclo de vida de una base de datos
   - 2.6. Sistema gestor de una base de datos (SGBD)
   - 2.7. Arquitectura de tres niveles
   - 2.8. Modelo de datos

3. **Referencias**

---

# Introducción

Las bases de datos son herramientas fundamentales para almacenar, organizar y administrar grandes cantidades de información. Se utilizan en diferentes ámbitos, como universidades, empresas, hospitales y sistemas de comercio, donde es necesario consultar y actualizar información de manera rápida y organizada. Para que los datos puedan utilizarse correctamente, deben contar con mecanismos que permitan garantizar su disponibilidad, integridad, seguridad y acceso controlado.

El desarrollo de las bases de datos ha permitido sustituir métodos tradicionales de almacenamiento basados únicamente en archivos independientes. Actualmente, los Sistemas Gestores de Bases de Datos (SGBD) proporcionan herramientas para administrar la información, controlar el acceso de los usuarios y mantener la consistencia de los datos.

En esta unidad se estudian los conceptos fundamentales relacionados con las bases de datos, sus características, los usuarios que participan en su administración, su ciclo de vida, los sistemas gestores y los principales modelos de datos.

---

# Desarrollo

## 2.1. Dato, información y base de datos

Un dato representa un elemento que puede ser registrado y almacenado. Por sí mismo puede no tener un significado completo hasta que se relaciona con otros datos. La información surge cuando los datos son procesados y organizados de manera que adquieren significado y pueden utilizarse para obtener conocimiento o apoyar la toma de decisiones.

Una base de datos es una colección organizada de datos relacionados entre sí, diseñada para facilitar su almacenamiento, consulta, modificación y administración. De acuerdo con Elmasri y Navathe (2016), una base de datos representa información relacionada de manera que pueda ser utilizada por diferentes aplicaciones. Coronel y Morris (2019) señalan que permite administrar datos relacionados para satisfacer las necesidades de información de una organización.

El propósito de una base de datos no consiste únicamente en almacenar información, sino en organizarla para que pueda ser recuperada y utilizada eficientemente. Para ello se emplean sistemas gestores que proporcionan mecanismos de consulta, actualización, seguridad y control.

En síntesis, el dato constituye la unidad básica de información; cuando los datos son procesados y adquieren significado se convierten en información, mientras que una base de datos permite almacenar y relacionar conjuntos de datos de manera organizada.

---

## 2.2. Características de una base de datos

Las bases de datos poseen características que permiten administrar la información de manera eficiente y segura:

**Integración:** los datos se encuentran organizados como parte de un conjunto relacionado, evitando que cada aplicación tenga que mantener información completamente independiente.

**Persistencia:** la información permanece almacenada y puede ser utilizada posteriormente, incluso después de finalizar una aplicación.

**Redundancia controlada:** se busca reducir la duplicación innecesaria de datos, ya que una redundancia excesiva puede generar inconsistencias.

**Integridad:** los datos deben conservar su exactitud y cumplir las reglas establecidas para garantizar que sean válidos.

**Seguridad:** se establecen mecanismos para controlar quién puede consultar o modificar determinada información.

**Recuperación:** deben existir mecanismos que permitan recuperar la información ante errores o fallas.

**Concurrencia:** diferentes usuarios pueden acceder a los datos al mismo tiempo sin provocar inconsistencias.

**Independencia de datos:** permite modificar determinados aspectos de la estructura de almacenamiento sin tener que modificar todas las aplicaciones que utilizan los datos.

Estas características permiten que las bases de datos sean más confiables y flexibles que los sistemas basados únicamente en archivos independientes.

---

## 2.3. Archivos frente a bases de datos

Antes de la utilización generalizada de los SGBD, la información se almacenaba principalmente en archivos administrados directamente por las aplicaciones. Este método podía funcionar para sistemas pequeños, pero presentaba dificultades cuando aumentaba la cantidad de información o de usuarios.

Uno de los principales problemas era la redundancia de datos, debido a que una misma información podía almacenarse en diferentes archivos. Esto podía provocar inconsistencias cuando un dato era actualizado en un archivo pero no en los demás.

Otro problema era la dependencia entre los programas y los archivos. Si cambiaba la estructura de un archivo, frecuentemente era necesario modificar las aplicaciones que trabajaban con él.

Los sistemas gestores de bases de datos surgieron para solucionar estas dificultades. Un SGBD centraliza funciones como el almacenamiento, consulta, seguridad, integridad y recuperación de los datos, permitiendo que diferentes aplicaciones trabajen sobre una misma base de información.

---

## 2.4. Usuarios de una base de datos

En una base de datos participan diferentes tipos de usuarios, cada uno con responsabilidades específicas.

El diseñador de la base de datos se encarga de determinar qué información debe almacenarse y cómo deben relacionarse los datos. Su trabajo incluye definir la estructura de la base de datos de acuerdo con las necesidades del sistema.

El administrador de la base de datos (DBA) es responsable de administrar y supervisar el funcionamiento de la base de datos. Entre sus actividades se encuentran la seguridad, el control de accesos, el mantenimiento y la recuperación de información.

El programador de aplicaciones desarrolla los programas que permiten a los usuarios interactuar con la base de datos. Utiliza los mecanismos proporcionados por el SGBD para realizar operaciones sobre la información.

Finalmente, el usuario final utiliza las aplicaciones o herramientas disponibles para consultar, introducir o modificar información de acuerdo con los permisos que tenga asignados.

---

## 2.5. Ciclo de vida de una base de datos

El desarrollo de una base de datos sigue diferentes etapas que permiten planificar, diseñar, implementar y mantener el sistema.

**Planificación de la base de datos:** se establecen los objetivos generales y las necesidades que deberá cubrir.

**Definición del sistema:** se determinan los límites y características principales del sistema.

**Recolección y análisis de requisitos:** se identifican las necesidades de información de los usuarios y de la organización.

**Diseño de la base de datos:** se define la estructura de los datos. Comprende el diseño conceptual, lógico y físico.

**Selección del SGBD:** se selecciona el sistema gestor que se utilizará de acuerdo con las necesidades del proyecto.

**Diseño de aplicaciones:** se desarrollan las aplicaciones que permitirán a los usuarios trabajar con la base de datos.

**Prototipado:** se pueden crear versiones preliminares para comprobar el funcionamiento y validar los requisitos.

**Implementación:** se construye la base de datos y las aplicaciones correspondientes.

**Conversión y carga:** se incorporan los datos necesarios al nuevo sistema.

**Pruebas:** se comprueba que el sistema funcione correctamente y que cumpla con los requisitos establecidos.

**Operación y mantenimiento:** una vez puesto en funcionamiento, el sistema requiere supervisión, actualización y mantenimiento.

Estas etapas permiten desarrollar la base de datos de forma organizada y reducir problemas durante su implementación y operación.

---

## 2.6. Sistema gestor de una base de datos (SGBD)

Un Sistema Gestor de Bases de Datos (SGBD) es un conjunto de programas que permite crear, administrar, consultar y modificar bases de datos. Su función principal es proporcionar una interfaz entre los usuarios o aplicaciones y los datos almacenados.

Entre sus componentes principales se encuentra el procesador de consultas, encargado de interpretar y ejecutar las consultas realizadas por los usuarios. El administrador de almacenamiento controla la forma en que los datos son almacenados y recuperados. Por su parte, el administrador de transacciones coordina las operaciones para mantener la consistencia de la base de datos.

Las transacciones deben cumplir propiedades conocidas como ACID: atomicidad, consistencia, aislamiento y durabilidad. Estas propiedades permiten que las operaciones se ejecuten de forma confiable y que los datos mantengan un estado válido.

Los SGBD también proporcionan diferentes lenguajes para trabajar con la información. El DDL (Data Definition Language) permite definir estructuras de la base de datos; el DML (Data Manipulation Language) permite consultar y modificar los datos; el DCL (Data Control Language) se relaciona con los permisos y el control de acceso; y el control de transacciones permite administrar operaciones que deben ejecutarse como una unidad.

Los SGBD pueden clasificarse de acuerdo con diferentes criterios, como el modelo de datos utilizado, el número de usuarios que soportan o la distribución de los datos. Entre los sistemas utilizados se encuentran los basados en el modelo relacional y los sistemas NoSQL, que emplean diferentes estructuras para almacenar información.

El uso de un SGBD facilita la administración de grandes cantidades de información y proporciona mecanismos para garantizar la seguridad, integridad, recuperación y acceso concurrente a los datos.

---

## 2.7. Sistema de Base de Datos

Un sistema de base de datos comprende no solamente los datos almacenados, sino también los programas, usuarios y recursos que participan en su administración. Su funcionamiento puede comprenderse mediante diferentes niveles de abstracción.

El modelo ANSI/SPARC establece tres niveles principales. El nivel externo representa las vistas que tienen los diferentes usuarios sobre la información. El nivel conceptual describe la estructura lógica general de toda la base de datos. Finalmente, el nivel interno representa la forma en que los datos son almacenados físicamente.

La separación entre estos niveles permite establecer independencia de datos. La independencia lógica permite modificar la estructura conceptual sin afectar las vistas externas, mientras que la independencia física permite modificar aspectos del almacenamiento sin modificar la estructura lógica.

Los sistemas de bases de datos también pueden utilizar diferentes arquitecturas. Una arquitectura centralizada concentra los recursos principales en un sistema, mientras que una arquitectura cliente-servidor distribuye las funciones entre los clientes y el servidor de la base de datos.

Esta organización facilita la administración y permite separar las aplicaciones de los mecanismos utilizados para almacenar y administrar los datos.

---

## 2.8. Modelos de datos

Un modelo de datos proporciona una forma de representar la información y las relaciones existentes entre los datos. Su función es establecer los conceptos y estructuras necesarios para describir una base de datos.

Los modelos pueden clasificarse según su nivel de abstracción. El modelo conceptual representa la información desde una perspectiva general y cercana a las necesidades de los usuarios. El modelo lógico describe la estructura de los datos de acuerdo con el modelo utilizado por el SGBD. El modelo físico especifica cómo se almacenan los datos en el sistema.

También pueden clasificarse según la estructura que utilizan. El modelo jerárquico organiza los datos mediante una estructura semejante a un árbol. El modelo de red permite establecer relaciones más complejas entre los datos. El modelo relacional organiza la información mediante tablas formadas por filas y columnas, estableciendo relaciones entre ellas. El modelo orientado a objetos representa los datos mediante objetos y sus relaciones.

Además, existen diferentes modelos NoSQL, desarrollados para trabajar con estructuras que no necesariamente utilizan el esquema tradicional de tablas del modelo relacional. Estos pueden adaptarse a determinados tipos de aplicaciones y necesidades de almacenamiento.

La selección de un modelo de datos depende de las características del sistema, de la información que debe administrarse y de las necesidades de los usuarios. Por ello, comprender los diferentes modelos permite seleccionar una estructura adecuada para representar y administrar los datos de un sistema.

---

# 3. Conclusión

---

# 4. Referencias

Coronel, C., & Morris, S. (2019). *Database systems: Design, implementation, & management* (13th ed.). Cengage Learning.

https://soclibrary.futa.edu.ng/books/2019%20Database%20Systems%20Design,%20Implementation,%20and%20Management%20by%20Carlos%20Coronel%20Steven%20Morris%20(z-lib.org).pdf

Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of database systems* (7th ed.). Pearson.

https://ia802808.us.archive.org/8/items/fundamentosdesistemasdebasesdedatos/Fundamentos-de-Sistemas-de-Bases-de-Datos.pdf

Silberschatz, A., Korth, H. F., & Sudarshan, S. (2019). *Database system concepts* (7th ed.). McGraw-Hill.

https://www.mpgcamb.com/wp-content/uploads/2024/12/Abraham-Silberschatz-Henry-F.-Korth-S.-Sudarshan-Database-System-Concepts-McGraw-Hill-Education-2019.pdf

Watt, A., & Eng, N. (2014). *Database design* (2nd ed.). BCcampus.

https://opentextbc.ca/dbdesign01/open/download?type=pdf

Connolly, T., & Begg, C. (2015). *Database systems: A practical approach to design, implementation, and management* (6th ed.). Pearson.

https://www.academia.edu/41779665/Database_Systems_A_Practical_A_Thomas_Connolly

Referencias Ejercicio 4.
Fan Fan, W., Geerts, F., Li, J., & Ma, S. (2020). Multi-source data repairing powered by integrity constraints and source reliability. Information Sciences, 507, 386–403. https://doi.org/10.1016/j.ins.2019.08.044

Iqbal, A., Khan, S. U., Niazi, M., et al. (2024). Advancing database security: A comprehensive systematic mapping study of potential challenges. Wireless Networks, 30, 6399–6426. https://doi.org/10.1007/s11276-023-03436-z

Bakar, N. A., et al. (2023). Active learning with concept maps: Enhancing understanding of entity-relationship diagrams in database modeling. 2023 IEEE Frontiers in Education Conference (FIE). https://doi.org/10.1109/FIE58773.2023.10343471
