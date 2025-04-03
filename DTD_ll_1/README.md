# DTD-ll
Ejercicio 1. Factura electrónica.
Diseña un documento XML que represente una factura electrónica para una transacción
comercial entre una librería y una biblioteca.
La factura debe contener la información del número y fecha de emisión, así como los
datos del emisor y el cliente. Además, debe incluir un detalle de los productos vendidos,
especificando el código del artículo, su tipo, descripción, cantidad y precio de venta por
unidad. Algunos productos pueden tener una oferta aplicada.
El documento debe estar validado mediante una DTD, el detalle es el siguiente:
• Elemento factura:
• Debe contener los elementos datos-emisor, datos-cliente y detallefactura.
• Tiene dos atributos obligatorios: numero y fecha.
• Elementos datos-emisor y datos-cliente:
• Ambos elementos deben contener los elementos nombre, cif y telefono.
• Elementos nombre, cif y telefono:
• Son elementos de texto simple (#PCDATA), es decir, solo pueden
contener caracteres de texto.
• Elemento detalle-factura:
• Debe contener uno o más elementos linea.
• Tiene un atributo obligatorio llamado importe.
• Elemento linea:
• Debe contener los elementos descripcion, cantidad y pvp.
• Tiene dos atributos obligatorios: codigo-articulo y tipo.
• codigo-articulo debe ser un identificador único (ID).
• tipo puede tomar los valores "Libro", "DVD" o "Varios".
• Elemento descripcion, cantidad y pvp:
• Son elementos de texto simple (#PCDATA).
• Elemento oferta:
• Es un elemento vacío que puede aparecer opcionalmente dentro del
elemento linea.