

![proyecto aprendizaje automatico](https://github.com/darioverdun/PROYECTO-DETECCION-DE-FALLA/assets/143291888/c83333df-6054-4f25-8a1e-ec91b6a3a1f2)




Descripción del Dataset y Origen 

Nombre del Dataset: Base de datos de fallas de maquinaria. 

Cantidad de Instancias y Características: Cada archivo CSV contiene alrededor de 250,000 filas y 8 columnas. Las características incluyen:
1.	Señal del tacómetro de la columna 1, que permite estimar la frecuencia de rotación. (Tipo de datos: Numérico)
2.	Acelerómetro de soporte colgante de las columnas 2 a 4 (dirección axial, radial tangencial). (Tipo de datos: Numérico)
3.	Acelerómetro de rodamiento saliente de las columnas 5 a 7 (dirección axial, radial tangencial). (Tipo de datos: Numérico)
4.	Micrófono de columna 8. (Tipo de datos: Numérico) 

Origen del Dataset: https://www02.smt.ufrj.br/~offshore/mfs/page_01.html 

Los datos provienen del Simulador de fallas de maquinaria (MFS) de SpectraQuest, Alineación-Equilibrio-Vibración (ABVT). Este simulador se utiliza para simular diferentes estados de fallas en maquinaria. El dataset comprende archivos CSV que representan series de tiempo multivariadas adquiridas por sensores en el MFS. Especificaciones del Banco Experimental:
 • Motor: 1/4 CV CC. 
• Rango de frecuencia: 700-3600 rpm. 
• Peso del sistema: 22 kg. 
• Diámetro del eje: 16 mm. 
• Longitud del eje: 520 mm. 
• Rotor: 15.24 cm. 
• Distancia de rodamientos: 390 mm. Sistema de Adquisición de Datos: 
• Sensores IMI industriales, acelerómetros modelo 601A01 y modelo 604B31. 
• Tacómetro analógico Monarch Instrument MT-190.
 • Micrófono Shure SM81.
 • Módulos de adquisición analógica de 4 canales NI 9234 de National Instruments. 

Preprocesamiento:
 No hay información faltante en los datos. Las etiquetas de clase no están directamente etiquetadas dentro de los archivos CSV, pero se pueden inferir a partir de la estructura de las carpetas. Cada carpeta dentro de la base de datos corresponde a un peso de desbalance específico (por ejemplo, 6g, 10g, etc.), y los archivos dentro de cada carpeta representan mediciones de ese peso particular de desbalance.
Además, la base de datos está compuesta por:
•	Base de datos de funcionamiento normal:
o	Cantidad de archivos: 28
o	Cada archivo representa una medición del motor en funcionamiento normal.
o	Cada medición contiene 8 columnas como se describe en la descripción del dataset.
o	Cada archivo contiene alrededor de 250,000 filas de datos.
•	Bases de datos de desbalance:
o	Cantidad de bases de datos: 7 (una por cada nivel de desbalance)
o	Niveles de desbalance: 6g, 10g, 15g, 20g, 25g, 30g, 35g
o	Cada base de datos contiene 4 archivos, uno por cada nivel de desbalance.
o	Cada archivo tiene las mismas 8 columnas que las mediciones de funcionamiento normal.
o	Cada archivo contiene alrededor de 250,000 filas de datos.
