## PROYECTO 3 - Modelo de Serie de tiempo

#### LISTA PENDIENTES:  
- [X] Arreglar estética graficos Acamica 
- [X] Arreglar Textos y titulares
- [X] Producir visualizacion final; predicciones y serie general
- [ ] Analizar probelma de serie defasada (1 dia)

> Problema de serie defasada: Al producir las estructuras se elimina implicitamente un dia, con los arreglos en numpy con lo cual al intentar graficar el eje x con las fechas crudas (de `diario.cantidad_pasos.index[-92:]`) el resultado difiere, por un dia, de los volumenes que tiene `y_test` y no se pueden usar en el mismo grafico. Es un detalle, pero es un error.

##### Posibles Mejoras:  
- [ ] Lista de feriados, incorporar atributo
- [ ] Analizar Incorporar test `adfuller` de estacionariedad /tendencia

##### Innecesarios - Investigar:
- [ ] Porque `::-1` reindexa mal: `dd[f'split_{i}_rein'] = df.reindex(index=(res.index[::-1]))`
- [ ] Ver si sacando tendencia aproximo estacionalidad manualmente
- [ ] Obtener Index de fila como atributo, como agregarlo como string a una nueva columna (como +ROW(...) de Excel)



## PROYECTO 4 - Modelo de Serie de tiempo
- [ ] Hacer modelo Forecast completo 