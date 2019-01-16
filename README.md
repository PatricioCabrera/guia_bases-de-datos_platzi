# GUIA DE FUNDAMENTOS DE BASES DE DATOS EN PLATZI
**Una guía sobre el curso de  "Fundamentos de bases de datos" en Platzi.**

# 1. Propósito general de las Bases de Datos 
Las Bases de Datos nacieron con el propósito de almacenar información importante. Comenzaron (obviamente) en papel.
Podríamos imaginar una Base de Datos clásica con el clásico formato de carpetas organizadas con rótulos en estantes.
La forma de Bases de Datos tradicional sirven para almacenar en el tiempo. Pero son ineficientes a la hora de dar con la información.

Dadas las imperfecciones humanas y el avance de la tecnología. Las Bases de Datos empezaron a ser parte de los computadores.

Los datos por sí solos no representan nada. Es al momento de crear el reporte en el que los datos pueden convertirse en información importante.

¿Cómo han evolucionado las Bases de Datos?

### Historia de las Bases de Datos.

1950-1960: Maquinas tabuladoras, tarjetas perforadas y cintas magnéticas.

1960-1979: Modelos jerárquicos, discos duros, modelo de data relacional, transacciones en tiempo real.

Un disco duro tiene información persistente, o sea que perdura en el tiempo.

1970-1980: SQL, Sistemas SQL comerciales, bases de datos paralelas y distribuidas, bases de datos orientadas a objetos.

SQL es un estándar, la mayoría de los comandos básicos, en cualquier tipo de datos que sea SQL deben funcionar (MariaDB, MySQL, etc).

1980-1990: Data mining, data warehouse, e-commerce.

2000-Actualidad: XML, administración automatizada, analytics, big data, No SQL, InMemory, Scale Out, Systems of Engagement.

# 2. Tipos de Bases de Datos y sus aplicaciones en la industria.

*Las bases de datos existen en casi todos lados. Y sirven de manera increíble.*

### Tipos.
**Bases de datos relacionales**: Este tipo de base de datos se diferencia porque trabaja con un conjunto de tablas y se manipula de acuerdo con el modelo de datos relacional.

**Bases de datos no relacionales**: En este tipo de base de datos aunque todas se denominan NoSQL, en realidad hay diferentes tipos:
- Bases de datos “Clave” – “Valor”: Es el modelo de NoSQL más popular y sencilla en cuanto a funcionalidad.
- Bases de datos “Documentales”: Este tipo es el más versátil ya que guarda información como un documento generalmente de tipo JSON o XML.
- Bases de datos “En grafo”: La información representada en este tipo de bases de datos se realiza en forma de nodos de un grafo y sus relaciones con las aristas del mismo.
- Bases de datos “Orientadas a Objetos”: En este tipo de bases de datos la información se representa mediante objetos de igual forma que lo hacen los lenguajes de programación orientados a objetos.

### Ejemplos.
- Un gran ejemplo son las empresas de aerolíneas. Donde se guardan todos los datos sobre vuelos y pasajeros.
- Las universidades, donde hay cantidad de estudiantes, notas, cursos y contenidos.. Etc.
- El sistema bancario. Los bancos trabajan con sistemas muy robustos que operan a tiempo real. Deben soportar transacciones de un sistema personal a el de otros.
- El retail. Cualquier tipo de negocio grande utiliza Bases de Datos para manejar inventarios y registrar todas las transacciones.
Algunos utilizan instancias de Bases de Datos separadas en una misma arquitectura para ofrecer otros servicios. Como los datos con reviews de usuarios.
- Manufactura. La manufactura maneja inventarios contando la cantidad de componentes y herramientas. Las Bases de Datos son útiles para alertar cuando quedan pocos suministros de algo en específico.
- Empresas. Donde se almacenan datos de los empleados. Rendimiento, salarios, familias habilidades.

# 3. Vision general de los datos.

Un dato es algo que me va a permitir describir un objeto. Como la capacidad de un vaso, tamaño, color...
Un dato puede ser un número, una palabra, adjetivo, característica, imágen, transacción, estadística o código.

**Recordar:** *Los datos como tal, no representan nada. A no ser que los explotemos o consultemos de manera correcta.* Son algo que perdura en el tiempo, para llevar un registro.

Un dato puede ser un usuario registrado. Podrás imaginar que el registro de un nuevo usuario como tal no significa nada, o casi nada.
Los datos de muchos usuarios podrían ser usados para generar información, un gráfico por ejemplo.

### Tres niveles de abstracción.

- **Conceptual:**
Lo primero que tengo que hacer para diseñar una base de datos es tener los conceptos sobre qué voy a diseñar.
Tendremos 2 objetos importantes. Entidades y relaciones.
 - Entidad: Las entidades son objetos o abstracciones de un objeto, que poseen características.
 - Relación: Una relación es como se comportan esos objetos con respecto a otros objetos.

Ejemplo de relación. Tenemos una entidad que puede ser items en una tienda. Los items tienen un código de barra, cantidad, nombre, dimensión y color.
Estos items tienen un carrito de compras, cuyo carrito tiene un código y un usuario asociado. Un monto de transacción y una forma de pago.
Un item puede estar en muchos carritos, un carrito puede tener muchos items.

Lo importante es modelar de manera **conceptual** lo que quiero hacer basado en esos objetos.

- **Lógico:**
Tendremos generalmente un diagrama lógico que me va a resolver dudas de consistencia que genere en un modelo conceptual. Evitando que cree loops y que haya consistencia en los datos.

- **Físico:**
Será como lo va a ver mi base de datos. Tiene mucho que ver con la parte inicial. Cada Base de Datos tiene sus tipos de datos puntuales.
Es aquí donde llevamos nuestra estructura general a la forma requerida por el sistema de gestión de bases de datos que elegimos para nuestro proyecto.