Ejercicio 2. Equipos NBA.
Diseña un documento XML que contenga información sobre equipos de la NBA,
incluyendo sus títulos, posición y quinteto titular.
Cada equipo debe ser identificado por su nombre y debe especificarse su conferencia
(división en la que está inscrito un equipo dentro de la NBA. La NBA está dividida en dos
conferencias principales: la Conferencia Este y la Conferencia Oeste). Además, se debe
detallar el número de títulos ganados por el equipo, su posición en la clasificación y el
quinteto titular
La DTD debe establecer las siguientes restricciones para la estructura y contenido del
documento XML:
• El elemento raíz debe ser EquiposNBA, que contiene uno o más elementos
equipo o nombre.
• El elemento nombre contiene el nombre de un equipo.
• El elemento equipo contiene la información detallada de un equipo, incluyendo
sus títulos, posición y quinteto titular.
• El elemento equipo tiene un atributo obligatorio llamado conferencia, que
especifica la conferencia a la que pertenece el equipo.
• Los elementos titulos, posicion y quinteto contienen información sobre los títulos
ganados, posición en la clasificación y quinteto titular de un equipo,
respectivamente.
• Elemento EquiposNBA:
• Este es el elemento raíz que contiene la información sobre los equipos
de la NBA.
• Puede contener una secuencia de elementos equipo o nombre.
• Elemento nombre:
• Contiene el nombre de un equipo de la NBA.
• Es un elemento de texto simple (#PCDATA).
• Elemento equipo:
• Contiene información detallada sobre un equipo, incluyendo sus títulos,
posición y quinteto titular.
• Tiene un atributo obligatorio llamado conferencia, que especifica la
conferencia a la que pertenece el equipo.
• Atributo equipo conferencia:
• Este atributo especifica la conferencia a la que pertenece el equipo (por
ejemplo, "este" u "oeste").
• Es un atributo de tipo CDATA (datos de caracteres).
• Elemento titulos:
• Contiene el número de títulos ganados por el equipo.
• Es un elemento de texto simple (#PCDATA).
• Elemento posicion:
• Contiene la posición del equipo en la clasificación.
• Es un elemento de texto simple (#PCDATA).
• Elemento quinteto:
• Contiene el quinteto titular del equipo.
• Es un elemento de texto simple (#PCDATA)