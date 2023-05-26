INFORME SOBRE EL ANALISIS DEL DATASET "AccidentesAviones.csv"
Diosa Medina


Los accidentes aéreos constituyn eventos que ocurren inesperadamente a causa de diversos factores, tales como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento de las aeronaves y de las pistas de aterrizaje, fallas en la gestión del tráfico aéreo, así como problemas de diseño y/o fabricación de las aeronaves, entre las que tenemos: aviones comerciales, aviones privados, helicópteros, planeadores y globos aerostáticos. Estos accidentes producen como consecuencia, daños físicos a las personas o a las propias aeronaves.


Según Javier Gimeno (2018), la aviación en sus comienzos se basaba en el método ensayo-error, por lo que los accidentes eran algo a lo que el inicialmente reducido sector aeronáutico estaba acostumbrado; pues no cumplía la función  de transportar pasajeros que realiza actualmente. Con el desarrollo de la tecnología, los materiales y el gran número de experimentos tanto satisfactorios como fallidos, muchos de ellos provenientes del sector militar, la aeronáutica se desarrolló y comenzó a expandirse al ámbito del transporte de pasajeros. Pero, como ocurre en la actualidad, el miedo a volar y la sensación de falta de seguridad del viajero eran comunes. Sin embargo, el número de accidentes aéreos anuales, o bien se ha mantenido entorno a un valor determinado o ha ido disminuyendo a lo largo de los años.


El investigador norteamericano David Huntzinger P.H.D. de la Boeing Company, afirma que la estadística nos ha mostrado que en el período de los años 1950 a 1970, ocurrieron accidentes aéreos aproximadamente en una frecuencia de 20 por cada millón de salidas. Después de esa época, al comenzar los diferentes planes de seguridad aérea (incluyéndose principalmente los cursos de Factores Humanos para tripulaciones), los accidentes disminuyeron notablemente hasta estabilizarse aproximadamente en una cantidad de 3 por cada millón de salidas. Aún así, al aumentar la flota de aviones comerciales en el espacio aéreo durante la última década, se calcula que tendremos aproximadamente 1 accidente por semana durante los próximos 10 años, estadística que tendrá que necesariamente ser evaluada cuidadosamente para tratar de disminuirla con los diferentes programas establecidos.


La recopilación y el análisis sistemático de los datos de accidentes pueden ayudar a los investigadores a identificar patrones, tendencias y factores contribuyentes que podrían llevar a mejorar la seguridad aérea. Es por esto que la Organización de Aviación Civil Internacional (OACI) como parte de su misión, ha decidido llevar a cabo un proyecto de data analytics para analizar los accidentes aéreos de aviones en todo el mundo. El objetivo del proyecto es recopilar, analizar y visualizar datos relevantes sobre accidentes aéreos para identificar patrones y tendencias en la seguridad de la aviación civil.


Como analista de datos y contribuyendo con la OACI, he realizado un ETL, un EDA y un análisis de datos del dataset suministrado "AccidentesAviones.csv", cuyos detalles se presentan en el notebook "Lab_2.ipynb". En este dataset se ha encontrado gran cantidad de datos faltantes que se trataron según se indica en el ETL realizado con Pandas. En el EDA se encontró que las variables numéricas todas son asimétricas positivas porque contienen valores outliers, los cuales no se eliminaron ya que al consultar en internet sobre los citados accidentes, se corroboró que son datos reales, además para no perder información relevante en otros campos del dataset. El análisis de las variables categóricas mostró aspectos interesantes como que la mayor cantidad de accidentes la tienen aviones que no aparecen registrados por la OACI, por lo menos en el dataset; que la mayor cantidad de accidentes corresponde a vuelos de entrenamiento, vuelos de paseo, vuelos de prueba, es decir, vuelos no comerciales; que la mayor cantidad de accidentes también corresponde a vuelos que no tienen registrada su ruta, ¿podría esto interpretarse como que fueron cambiados de ruta a última hora?. También se observa en el gráfico de líneas, que con el correr de los años se ha incrementado la brecha entre el número de personas a bordo y el número de personas fallecidas, indicándonos que la seguridad ha ido incrementándose. 


El resultado final del proyecto es un dashboard interactivo que permite a los usuarios explorar los datos y obtener información sobre accidentes específicos, en el cual se presentan los hallazgos obtenidos de la información analizada.


Dentro de este trabajo, con el fin de entender los datos y alinearlos con los objetivos de la OACI, se visualiza en el dashboard los siguientes KPIs:

- Reducir en 5% la tasa de mortalidad a nivel anual,
- Aumentar en 5% el índice de supervivencia a nivel anual,
- Aumentar en 5% la razón de supervivencia a mortalidad a nivel anual,
- Reducir en 5% la tasa de accidentalidad del operador a nivel anual.


Espero que este informe y este dashboard proporcionen información valiosa a la OACI, a la industria de la aviación civil, a los reguladores gubernamentales y otros interesados en la seguridad de la aviación.


Documentos consultados:

https://riunet.upv.es/bitstream/handle/10251/110595/GIMENO%20-%20ACCIDENTES%20DE%20AVIACI%C3%93N.%20AN%C3%81LISIS%20CAUSAL%20%282012-2016%29.pdf

https://semae.es/wp-content/uploads/Tema13.pdf