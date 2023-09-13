#                       **PROYECTO INDIVIDUAL Nº2



### Descripción

Tomando en cuenta la importancia de los siniestros viales y sus victimas, se nos solicita la elaboración de un proyecto de análisis de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para ello, nos disponibilizan un dataset( [Buenos Aires Data - Siniestros viales](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales))  sobre homicidios en siniestros viales ocurridos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato *xlsx* y contiene dos hojas llamadas: **hechos** y **víctimas**. Además,  incluye otras dos hojas adicionales de diccionarios de datos, que sirve como mayor entendimiento de la data compartida.

## Preprocesamiento de Datos

Para la limpieza de datos, dentro de un notebook, se observo el formato de los mismos, se observo la cantidad de nulos y porque estaban ahí, se eliminaron los campos con ID igual. Algunos campos que no eran del tipo de dato adecuado a los registros también se modificaron. Luego, se procedió a unir el dataset de hechos con el de victimas, ya que ambos se relacionaban con un numero de ID, y se guardo uno nuevo con los datos unificados en formato xlsx. 

Una vez unidos los datos, mediante bibliotecas como matplotlib, entre otras, dentro del mismo notebook  se analizaron algunos datos, se buscaron patrones, estadísticas y ver el comportamiento de los datos. Luego se crearon 3 KPI, el primero consistía en disminuir la tasa de homicidio en siniestros viales un 10%, el segundo en reducir la tasa de mortalidad de motociclistas en siniestros viales un 7%, y un tercero, que consiste reducir las victimas de la comuna que mas posee. Los mismos se incluirán en el posterior Dashboard, estos se guardaron en 3 xlsx.

## Dashboard

Mediante Power bi se crea un Dashboard interactivo que consta de 3 paginas. En el mismo, se incluye un separador de años que muestra incidentes por comuna, la evolucion a traves de los años, donde fueron los mismos, quienes fueron los participantes y demas. Ademas tambien se da informacion sobre las victimas, ya sea genero o rol de las mismas. También el dashboar incluye los 3 KPI con los resultados favorables o no que tuvieron los mismos.

El sistema se basa en una similitud del coseno para calcular la similitud de los juegos mediante los géneros y etiquetas.



## Repositorio

El siguiente repositorio contiene, un notebook llamado Proyecto Individual N2 con el análisis de los datos, una carpeta llamada Data con el dataset de Hechos_Victimas y los 3KPI en formato xlsx Y un documento de Power Bi llamado dashboar.  

