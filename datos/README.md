
-----------------------------------------------------

## Estos datos fueron obtenidos de la base de datos de producción de Plastic Omnium puebla y bajo ninguna circunstancia deberán ser compartidos sin el permiso de los autores o la empresa.

-----------------------------------------------------


# Contenidos:
### Los datos con iniciales ColCons, contienen los consumos de los 16 robots que se encuentran en funcionamiento en la línea de pintura. Además, conservan detalles de fabricación de cada pieza como hora de fabricación y referencia a los códigos de productos, estos son los tipos de datos que deberán tener las columnas para suinterpretación:


Nombre | Tipo
--- | ---
Fecha | datetime64
Label_ID | int64
Skid | int64
Job_ID | int64
Color_ID | int64
Product_ID | int64
Primer_ID | int64
Clear_ID | int64
Resin_R1_PR | float64
Resin_R2_PR | float64
Hardener_R1_PR | float64
Hardener_R2_PR | float64
Resin_R1_BC | float64
Resin_R2_BC | float64
Resin_R3_BC | float64
Resin_R4_BC | float64
Resin_R5_BC | float64
Resin_R6_BC | float64
Resin_R1_CC | float64
Resin_R2_CC | float64
Resin_R3_CC | float64
Resin_R4_CC | float64
Hardener_R1_CC | float64
Hardener_R2_CC | float64
Hardener_R3_CC | float64
Hardener_R4_CC | float64
CO21 | float64
CO22 | float64


### Los datos en las tablasClear, Colores, Primers, Product y Typescontienen los detalles de los códigos de producto, como los nombres, abreviaturas y demás.Estas tablas pueden ser utilizadas para relacionar los contenidosdentro de ColCons para un mejor entendimiento.

### Los datos que comienzan con Names_Clear, contienen los headers de todas las tablas antes mencionadas, ya que los archivos originales no los contienen, en la primera columna se encuntra el número de la columnay en la segunda el nombre que les corresponde. 


