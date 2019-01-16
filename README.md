# Guia de fundamentos de bases de datos en Platzi
Una guía sobre el curso de  "Fundamentos de bases de datos" en Platzi.

# 1. Propósito general de las Bases de Datos 
Las Bases de Datos nacieron con el propósito de almacenar información importante. Comenzaron (obviamente) en papel.
Podríamos imaginar una Base de Datos clásica con el clásico formato de carpetas organizadas con rótulos en estantes.
La forma de Bases de Datos tradicional sirven para almacenar en el tiempo. Pero son ineficientes a la hora de dar con la información.

Dadas las imperfecciones humanas y el avance de la tecnología. Las Bases de Datos empezaron a ser parte de los computadores.

Los datos por sí solos no representan nada. Es al momento de crear el reporte en el que los datos pueden convertirse en información importante.

¿Cómo han evolucionado las Bases de Datos?

### Historia de las Bases de Datos

1950-1960: Maquinas tabuladoras, tarjetas perforadas y cintas magnéticas.

1960-1979: Modelos jerárquicos, discos duros, modelo de data relacional, transacciones en tiempo real.

Un disco duro tiene información persistente, o sea que perdura en el tiempo.

1970-1980: SQL, Sistemas SQL comerciales, bases de datos paralelas y distribuidas, bases de datos orientadas a objetos.

SQL es un estándar, la mayoría de los comandos básicos, en cualquier tipo de datos que sea SQL deben funcionar (MariaDB, MySQL, etc).

1980-1990: Data mining, data warehouse, e-commerce.

2000-Actualidad: XML, administración automatizada, analytics, big data, No SQL, InMemory, Scale Out, Systems of Engagement.

# 2. Tipos de Bases de Datos y sus aplicaciones en la industria

Las bases de datos existen en casi todos lados.

### Tipos.
**Bases de datos relacionales**: Este tipo de base de datos se diferencia porque trabaja con un conjunto de tablas y se manipula de acuerdo con el modelo de datos relacional.

**Bases de datos no relacionales**: En este tipo de base de datos aunque todas se denominan NoSQL, en realidad hay diferentes tipos:

Bases de datos relacionales: Este tipo de base de datos se diferencia porque trabaja con un conjunto de tablas y se manipula de acuerdo con el modelo de datos relacional.
Bases de datos no relacionales: En este tipo de base de datos aunque todas se denominan NoSQL, en realidad hay diferentes tipos:
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