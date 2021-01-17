## Proyecto 3 - Modelo de Serie de tiempo

#### LISTA PENDIENTES:  

- [X] Arreglar estética graficos Acamica 
- [X] Arreglar Textos y titulares
- [ ] Hacer modelo final Parte C


##### Posibles Mejoras:  

- [ ] Lista de feriados, incorporar atributo
- [ ] Analizar Incorporar test `adfuller` de estacionariedad /tendencia


##### Innecesarios - Investigar:
- [ ] Porque `::-1` reindexa mal: `dd[f'split_{i}_rein'] = df.reindex(index=(res.index[::-1]))`
- [ ] Ver si sacando tendencia aproximo estacionalidad manualmente
- [ ] Obtener Index de fila como atributo, como agregarlo como string a una nueva columna (como +ROW(...) de Excel)