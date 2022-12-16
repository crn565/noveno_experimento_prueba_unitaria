# noveno_experimento_prueba_unitaria
noveno_experimento_prueba_unitaria

Se analizan las medidas de  10 dispositivos conectados a tres ozm's con pruebas  unitarias de 1 minuto por dispositivo. 

No se tienen en cuenta los transitorios de tension corriente o potencia  dado que esta circunstancia se considerara en el quinto experimento

Las medidas se realizaron el dia 17/12/2022 entre las 12:13 y las 12:24 en el laboratorio de Electrotecnia de la Escuela Politécnica Superior de la Universidad de Almeria.

Los dispositivos analizados,  asi como su orden es el siguiente:

 - 1 mains
 - 2 electric_furnace
 - 3 microwave
 - 4 television
 - 5 kettle
 - 6 vacuum_cleaner
 - 7 electric_space_heater
 - 8 electric_shower_heater
 - 9 fan
 - 10 fridge
 - 11 freezer

En este repositorio se adjunta el dataset generado (DSUAL) en formato HDFS5

NOTA:  Los ficheros  4,6 y 7 deberian filtrarse con objeto de eliminar los picos de potencia activa con valores negativos, es decir en caso de obtener valores de potencia negativa  deberiamos  hacer las potencia reactivas y aparente cero , ademas la intensidad tambien la deberiamos hacer cero  y el coseno de fi o factor de potencia uno.  

