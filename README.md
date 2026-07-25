# BBVA Data Challenge 2023
En el año 2023, el BBVA realizó un datathon en el cual participé donde, debido a que carecía de los conocimientos suficientes no pude resolverlo adecuadamente. Actualmente, quise retomar este reto y presentar mi propuesta de solución. 

## Descripción
Se requiere desarrollar un modelo predictivo que nos ayude a identificar a los clientes que abandonarán el segmento objetivo del banco.

Por diversas razones como inactividad, reducción de saldos activos o pasivos, cancelación de productos o mal comportamiento, dejan de estar en el segmento objetivo del banco. Existen 5 motivos a predecir, por lo tanto, el problema de ese año es multiclase.

## Evaluación
La métrica de la evaluación será el F1-score. (Considerar average = 'macro')

## Datos disponibles
- **customers.csv** - Contiene datos sociodemográficos; también, de tenencia de productos y ofertas en el banco.
- **balances.csv** - Contiene los datos de los saldo de crédito del Reporte Crediticio Consolidado.
- **liabilities.csv** - Datos de los saldos de ahorro de los clientes.
- **movements.csv** - Posee los datos de las compras realizas con la tarjeta del banco en 4 rubros de comercios.
- **digital.csv** - Posee los datos de la navegación de los clientes en las plataformas digitales del banco.
- **universe_train.csv** - Listado de clientes con la etiqueta del motivo del abandono del segmento objetivo.
- **universe_test.csv** - Listado de clientes a quienes hay que predecir el motivo del abandono del segmento objetivo.
- **sample_submission.csv** - Ejemplo del archivo de envío.
- **Diccionario de datos.xlsx** - Diccionario de los datos.

![image](https://www.bbva.com/wp-content/uploads/2018/01/DataChallenge3-1024x360.jpg)

