# ENSAYO Nº2

## Pregunta 1

    Al afirmar que el enfoque de BD es de naturaleza autodescriptiva significa que:

Seleccione una:

a) La base de datos además de contener datos posee un catálogo que describe dichos datos (metadatos)

b) Las aplicaciones definen la estructura de los datos con los que trabajan.

c) El sistema operativo es el único que administra directamente los archivos en los que están los datos.

d) La base de datos almacena los datos relacionados de manera permanente.

    Retroalimentación
    BD = DATOS + METADATOS

    El Catálogo del Sistema contiene metadatos: descripción de la estructura de la BB

---

    La respuesta correcta es: La base de datos además de contener datos posee un catálogo que describe dichos datos (metadatos)

---

## Pregunta 2

    ¿Cuál es el principal objetivo del SGBD (sistema gestor de bases de datos)?

Seleccione una:

a) Diseñar bases de datos, y proporcionar un lenguaje de manipulación de datos para el administrador de la base de datos.

b) Proporcionar una forma administrar el almacenamiento y recuperación de información de una base de datos práctica y eficiente desde su nivel más alto al más bajo en abstracción.

c) Proteger los datos de la base de datos y mantener la definición de los datos (metadatos).

d) Crear las aplicaciones de software para compartir datos a los usuarios de manera clara y simple.

    Retroalimentación
    La administración de la BD que permiten el almacenamiento, modificación y extracción de la información en una base de datos.

---

    La respuesta correcta es: Proporcionar una forma administrar el almacenamiento y recuperación de información de una base de datos práctica y eficiente desde su nivel más alto al más bajo en abstracción.

---

## Pregunta 3

    Respecto de las transacciones de datos es correcto afirmar :

Seleccione una:

a) Cualquier cambio realizado por la transacción no garantiza que se conserve debido a fallos en la base de datos.

b) El cambio que realiza una transacción debe completarse en su totalidad o no modificar nada en absoluto.

c) El cambio que realiza una transacción puede afectar los cambios de otras transacciones que se estén ejecutando al mismo tiempo sobre la base de datos

d.) Cualquier cambio aplicado por una transacción se mantendrá aunque no respete las restricciones del esquema de datos.

    Retroalimentación
    ATOMICIDAD : El cambio que realiza una transacción debe completarse en su totalidad o no modificar nada en absoluto.

    Las demás afirmaciones contradicen las demás propiedades ACID

---

    La respuesta correcta es: El cambio que realiza una transacción debe completarse en su totalidad o no modificar nada en absoluto.

---

## Pregunta 4

    ¿Cuál es el elemento que tiene un control centralizado de las operaciones de protección, ingreso, modificación, eliminación y recuperación de datos de la base de datos?

Seleccione una:

a) Sistema gestor de base de datos

b) Sistema operativo

c) Aplicaciones de usuario

d) Antivirus

    Retroalimentación
    Un software específico llamado DBMS (Data Base Management System) en español SGBD (Sistema de Gestión de Bases de Datos).

---

    La respuesta correcta es: Sistema gestor de base de datos

## Pregunta 5

    Muchos usuarios no tienen conocimiento del nivel en el cual se almacenan los datos con los que trabajan, ni tampoco del funcionamiento y lenguaje que se ejecuta en el sistema operativo para comunicarse con el hardware.

Lo anterior corresponde al nivel de abstracción :

a) Lógico

b) Físico

c) De Vistas

d) Elemental

    Retroalimentación
    Nivel físico: El nivel más bajo de abstracción describe cómo se almacenan realmente los datos. En el nivel físico se describen en detalle las estructuras de datos complejas de bajo nivel

---

    La respuesta correcta es:
    Físico

## Pregunta 6

    Cuando se tiene un sistema en el cual cada aplicación es dueña de sus propios archivos, aunque eso signifique usar mucho espacio de almacenamiento debido a la imposibilidad de compartir los archivos con todas las aplicaciones.

    Estamos hablamos de:

Seleccione una:

a) Una ventaja del enfoque de las BD

b) Una ventaja del enfoque tradicional

c) Una desventaja del enfoque de las BD

d) Una desventaja del enfoque tradicional

    Retroalimentación
    La respuesta correcta es: Una desventaja del enfoque tradicional

## Pregunta 7

    Cuando el Administrador de la Base de Datos (DBA) necesita mejorar la estructura de la los datos que se almacenan en la base de datos accede a este nivel para identificar qué datos hay en la base de datos física. De esta manera el SGBD permite al DBA trabajar de manera simple con estructuras físicas que en la realidad son muy complejas.

Lo anterior corresponde al nivel de abstracción :

a) Lógico

b) Físico

c) De Vistas

d) Elemental

    Retroalimentación
    • Nivel lógico: El siguiente nivel más alto de abstracción describe qué datos se almacenan en la base de datos y qué relaciones existen entre esos datos. La base de datos completa se describe así en términos de un número pequeño de estructuras relativamente simples. Aunque la implementación de estructuras imples en el nivel lógico puede involucrar estructuras complejas del nivel físico, los usuarios del nivel lógico no necesitan preocuparse de esta complejidad. Los administradores de bases de datos, que deben decidir la información que se mantiene en la base de datos, usan el nivel lógico de abstracción.

---

    La respuesta correcta es:
    Lógico

## Pregunta 8

    ¿Qué es una base de datos?

Seleccione una:

a) Corresponde a las estructuras de almacenamiento de información que son importantes para una organización.

b) Un sistema de archivos donde se guardan los datos repartidos por la organización; no están relacionados entre sí.

c) Un software que captura datos necesarios para tomar alguna decisión importante para la organización.

d) Corresponde a un software que permite gestionar los datos que están al interior y exterior de la organización.

    Retroalimentación
    Es un almacén de información en forma de datos de diferentes tipos ubicados en archivos relacionados.

---

    La respuesta correcta es: Corresponde a las estructuras de almacenamiento de información que son importantes para una organización.

## Pregunta 9

    Se define como el conjunto de programas que maneja todo el acceso a la base de datos. También se le conoce como un conjunto de datos relacionados entre sí y un conjunto de herramientas de software (y/o hardware) para tener acceso a esos datos. Finalmente, se le entiende como un conjunto de programas que son usados para definir, procesar y administrar la BD y sus aplicaciones.

Seleccione una:

a) Sistema operativo

b) Sistema gestor de bases de datos

c) Sistema de almacenamiento secundario

d) Sistema de información de datos

    Retroalimentación
    La respuesta correcta es: Sistema gestor de bases de datos

---

## Pregunta 10

    El sistema de base de datos está conformado por:

Seleccione una:

a) El sistema gestor de base de datos con todos los software que lo incluyen

b) Sistema gestor de base de datos y software de aplicaciones/consultas

c) La base de datos, y el sistema gestor de base de datos

d) La base de datos, el sistema gestor de base de datos y software de aplicaciones/consultas

    Retroalimentación
    BD + SGBD + Software de Aplicación/Consultas

---

    La respuesta correcta es: La base de datos, el sistema gestor de base de datos y software de aplicaciones/consultas

## Pregunta 11

    Analiza el siguiente caso: “En un colegio existen dos archivos que contienen los datos de los alumnos del colegio. La directora detecta que en uno de los archivos aparecen cinco alumnos con estado de “exalumno” y en el otro archivo aparecen como alumnos de 3° medio”. Según lo descrito el problema detectado es:

Seleccione una:

a) Irrelevancia

b) Redundancia

c) Restricción

d) Inconsistencia

    Retroalimentación
    La respuesta correcta es: Inconsistencia

---

Pregunta 12

    ¿Cual de las siguientes alternativas NO representa un inconveniente del enfoque tradicional de archivos?
    Seleccione una:

a) La inconsistencia de los datos era muy común en los datos de la organización.

b) Es flexible a los cambios de requerimientos de los sistemas de la organización.

c) Escasa posibilidad de compartir los datos de la misma organización.

d) La redundancia de los datos pertenecientes a la organización.

    Retroalimentación
    Es inflexible : Dificultad del enfoque para enfrentar cambios, debido a que no es sencillo adaptarse a nuevos requerimientos que no hayan sido considerados en el diseño inicial, como por ejemplo: nuevos reportes, documentos, etc.

    Esto genera una lenta evolución del sistema de información, que frustrará a los usuarios que saben que existen los datos, pero que no pueden obtener la información que necesitan.

---

    La respuesta correcta es: Es flexible a los cambios de requerimientos de los sistemas de la organización.

## Pregunta 13

    Cuando los datos han sido procesados de manera de entregar al usuario un mensaje que aumenta su conocimiento nos referimos a:

Seleccione una:

a) Base de datos

b) Sistema de información

c) Gestor de base de datos

d) Información

    Retroalimentación
    La respuesta correcta es: Información

## Pregunta 14

    “La capacidad de las bases de datos de permitir a las aplicaciones compartir la información de un mismo origen, y además que es posible desarrollar nuevas aplicaciones independientemente del lenguaje de programación que se conecten a la base de datos”

    Lo anterior corresponde a:

Seleccione una:

a) Una ventaja del enfoque de las BD

b) Una desventaja del enfoque de las BD

c) Una desventaja del enfoque tradicional

d) Una ventaja del enfoque tradicional

    Retroalimentación
    La respuesta correcta es: Una ventaja del enfoque de las BD

## Pregunta 15

    En el enfoque de base de datos los datos son organizados de una manera lógica que permite definir las relaciones entre ellos, tal que un usuario pueda fácilmente relacionar un dato con otro.

    De lo anterior podemos afirmar:

Seleccione una:

a) Verdadero porque el enfoque de base de datos no permite el acceso a múltiples usuarios.

b) Falso porque el enfoque de base de datos genera inconsistencia de datos

c) Verdadero porque el enfoque de base de datos integra los datos evitando la separación de éstos.

d) Falso porque el enfoque de base de datos descentraliza los datos

    Retroalimentación
    Corresponde a la propiedad de la integración de los datos

---

    La respuesta correcta es: Verdadero porque el enfoque de base de datos integra los datos evitando la separación de éstos.

## Pregunta 16

    De las siguientes características NO es una ventaja de las BD

Seleccione una:

a) Mínima redundancia de datos

b) Independencia de los datos

c) Inconsistencia de datos

d) Facilitar el desarrollo de aplicaciones

    Retroalimentación
    Consistencia de datos es una ventaja. Bajo este enfoque, cuando se produce una actualización de datos se realizan modificaciones en todos los registros donde estos se encuentran

---

    La respuesta correcta es: Inconsistencia de datos

## Pregunta 17

    De acuerdo con la visión de los datos, ¿Cuál es el nivel de complejidad que muestra solo las partes de los datos que son de interés para usuarios?

a) Vista lógica

b) Vista física

c) Vista externa

d) Vista conceptual

    Retroalimentación
    La vista externa muestra aquella porción de los datos que es de interés para cada grupo de usuarios según sus intereses.

---

    La respuesta correcta es: Vista externa

## Pregunta 18

    Es un lenguaje para especificar los datos y que se concentra en dar la estructura a la base de dato, por ejemplo, crear tablas o modificar la estructura de dichas tablas:

Seleccione una:

a) Lenguaje de definición de datos

b) Lenguaje unificado de modelamiento

c) Lenguaje de una aplicación

d) Lenguaje operativo de datos

    Retroalimentación
    La respuesta correcta es: Lenguaje de definición de datos

## Pregunta 19

    ¿Cuál de las siguientes funciones NO puede hacer el Sistema Gestor de Base de Datos?

Seleccione una:

a) Control de acceso a los datos

b) Soporta un lenguaje de alto nivel

c) Maneja información no persistente

d) Soporta un modelo de datos

    Retroalimentación
    Manejar información persistente. La información permanece entre diferentes ejecuciones de un programa

    La respuesta correcta es: Maneja información no persistente

## Pregunta 20

    Un programador o un usuario con más experiencia en el manejo de datos que necesita realizar consultas u operaciones sobre la base de datos trabajan con lenguajes de alto nivel que facilita la interacción con el sistema de base de datos.
    Este nivel les permite acceder de manera simple a las estructuras de datos reales, sin preocuparse de su complejidad y centrándose en obtener la información deseada.

Lo anterior corresponde al nivel de abstracción :

a) Lógico

b) Físico

c) De Vistas

d) Elemental

    Retroalimentación
    • Nivel lógico: El siguiente nivel más alto de abstracción describe qué datos se almacenan en la base de datos y qué relaciones existen entre esos datos. La base de datos completa se describe así en términos de un número pequeño de estructuras relativamente simples. Aunque la implementación de estructuras imples en el nivel lógico puede involucrar estructuras complejas del nivel físico, los usuarios del nivel lógico no necesitan preocuparse de esta complejidad. Los administradores de bases de datos, que deben decidir la información que se mantiene en la base de datos, usan el nivel lógico de abstracción.

---

    La respuesta correcta es:
    Lógico

## Pregunta 21

    Analiza el siguiente caso: ”El gerente de ventas de una empresa necesita tener un listado de información con los clientes que no han efectuado compras en los últimos 7 meses. Lamentablemente esta información no es suministrada por el actual sistema, y debe pedir al DBA que le proporcione dicha información de manera urgente”.

    Según lo descrito el problema detectado es:

Seleccione una:

a) Acceso concurrente

b) Seguridad de accesos

c) Dificultad de acceso

d) Atomicidad

    Retroalimentación
    La respuesta correcta es: Dificultad de acceso

## Pregunta 22

    De acuerdo con la visión de los datos, ¿Cuál es el nivel de complejidad que describe qué datos se almacenan y cómo se relacionan en la BD mediante un modelo de datos?

a) Lógico

b) Físico

c) Vistas

d) Definido

    Retroalimentación
    Es el nivel lógico o conceptual

---

    La respuesta correcta es: Lógico

## Pregunta 23

    El nombre indicado para señalar a un conjunto de registros, todos con los mismos campos es:

Seleccione una:

a) Dato

b) Archivo

c) Campo

d) Registro

    Retroalimentación
    La respuesta correcta es: Archivo

---

## Pregunta 24

    Este niveles de abstracción de una base de datos es el menos abstracto, y el que está más cerca del almacenamiento real. En este nivel se explican de manera específica las estructuras de datos complejas de bajo nivel, como la organización de archivos, modos de acceso, índices y punteros, bloqueo de registros, etc.

Lo anterior corresponde al nivel de abstracción :

a) Lógico

b) Físico

c) De Vistas

d) Elemental

    Retroalimentación
    Nivel físico: El nivel más bajo de abstracción describe cómo se almacenan realmente los datos. En el nivel físico se describen en detalle las estructuras de datos complejas de bajo nivel

    La respuesta correcta es:
    Físico

---

## Pregunta 25

    Este elemento corresponde a un módulo de programa que conecta los datos de bajo nivel (físico) con las aplicaciones y consultas. Permite acceder de manera simple con el gestor de archivos.

    Lo anterior corresponde a :

Seleccione una:

a) gestor de almacenamiento

b) procesador de consultas

c) aplicaciones de usuario

d) almacenamiento en disco

    Retroalimentación
    Un gestor de almacenamiento es un módulo de programa que proporciona la interfaz entre los datos de bajo nivel en la base de datos y los programas de aplicación y consultas emitidas al sistema. El gestor de almacenamiento es responsable de la interacción con el gestor de archivos

---

    La respuesta correcta es:
    gestor de almacenamiento
