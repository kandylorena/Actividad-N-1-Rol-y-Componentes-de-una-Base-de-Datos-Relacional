1. El rol de una base de datos
• Explica con tus palabras cuál es el rol de una base de datos relacional dentro de una empresa u
organización.
R// Es la fuente mas segura que tiene la empresa de mantener su datos, poder utilizarlos de  forma confiada de que los datos son realmente fidedignos y que todo lo que en ella hay es por que son reales, puede hacer consultas, informes reportes.

• Menciona 3 ejemplos concretos de uso (por ejemplo: sistema de ventas, gestión de usuarios,
inventario).

Contro de recursos humanos y pagos
Control financiero y reportes
El contro de inventario

2. Características de un RDBMS
• Define qué es un RDBMS y nombra al menos 3 características que lo diferencian de otros tipos de
sistemas de almacenamiento.
Es un software creado para crear, actualizar. es organizado en tablas, la vuelve relacional al momento de de conecgtarse entre si las tablas por medio de un identificar  llave.
Relaciones mediantes llaves, PRIMARY KEY Y FOREIGN KEY
Normalizacion de datso (evitar redundancia)
transacciones seguras si no termina la transaccion la deshace


• Menciona 3 RDBMS ampliamente usados en la industria y en qué contextos se suelen utilizar.
*PostgreSQL  de codigo abierto mas avanzado y potente, capacidad para manejar datos complejos
    -se usa mucho en Analisis de datos, ciencia de datos y sistemas geograficos

*MYSQL es uno de los mas populares en desarrollo web. es famoso por der rapido en operaciones de lectura(mostrar informacion al usuario)
    -Paginas web, E-commerce y blogs

*Oracle database es conocido por su incfreible potencia y por ser capaz de manejar bases de datos de tamaños monstruosos, destaca por su seguridad avanzada y capacidad de recuperacion ante desastres.
    -Bancos, gobiernos y multinacionales.

3. Herramientas y objetos
• ¿Qué herramientas gráficas y de línea de comandos se pueden usar para consultar bases de datos?
Menciona al menos dos.
De linea de comandos:
    psql 
    MySQL
Graficas:
    pgAdmin
    MySQL wORKBENCH

• Describe brevemente qué función cumple cada uno de estos objetos dentro de una base de datos:
• Tabla: Objeto fundamental de almacenamiento, organiza la informacion en filas y columnas
• Vista: no guarda datos propios, muestra el resultado de una consulta guardada. Permite simplificar consultas o proteger datos sensibles.
• Índice: estructura oculta que acelera la bsiqueda de datos, dice exactamente en que posicion esta.
• Llave primaria: es el identificador unico e irrepetible de cada fila en una tabla, garantiza que no existan registros repetidos, no puede ser not null.
• Llave foránea: Es la que crea vinculo entre dos tablas, relacion una fila de una tabla con la llave primaria de otra.