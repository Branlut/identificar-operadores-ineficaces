# Indentificar operadores ineficaces
## Descripción
-La empresa CallMeMaybe la cual provee un servicio de telefonia virtual busca desarrollar una función que brinde información sobre los operadores ineficaces los cuales tienen las siguientes características
- Gran cantidad de llamadas entrantes perdidas (internas y externas)
- tiempo de espera prolongado para las llamadas entrantes
- Numero reducido de llamadas salientes

## Objetivo
-Encontrar a los operadores ineficaces para que la gerencia pueda realizar los cambios pertinentes para mejorar el servicio

## Tecnologias
  - Python
  - vs code
  - panda
  - numpy
  - scipy
  - seabor
  - matplotlib

## Hipótesis
  ### Prueba llamadas entrantes y salientes

H0 = Las llamadas entrantes son iguales a las llamadas salientes

H1 = las llamadas entrantes son diferenctes de la llamadas salientes

se comprobo que si existe una diferencia entre las llamadas entrantes y salientes, por lo que podemos decir que los operadores estan tieniendo un flujo diferente de llamadas entrantes y salientes por lo que se podria identificar operadores que solo esten enfocando en una direccion de llamada.

### Comparacion tiempo de espera

H0: La duración promedio de espera es igual entre llamadas entrantes y salientes.

H1: La duración promedio de espera difiere entre llamadas entrantes y salientes.

los tiempo de espera son diferentes para llamadas entrantes y salientes, por lo que se podria identficar a operadores que esten demorando mas en unas llamadas(direccion de llamadas) que en otras por falta de preparacion o por que estan recibiendo demasiada llamadas.

## Conclusiones y recomendaciones
-Considerando que la tasa de llamadas perdidas normales puede ser entre un 2% a 5%, un 76% de los operadores estaria sobre este umbral por lo que por ejemplo tener mas operadores para probar si este numero disminuye

-El promedio de duracion de llamada por lo general es de 6 minutos y 10 segundos para este caso y tomaremos 8 minutos que es para garantizar la calidad de la llamada, aproximadamente un 33%  de los operadores estarian sobrepasando esto, por lo que estar vigilando por ejemplo los tiempos en silencio o verificar que el operador este haciendo el flujo para una gestion correctamente es esencial para disminuir la duracion de la llamada sin afectar la calidad del servicio

-Dentro de los planes los que sobrepasan el umbral son un 12% para el A, 11% para el plan B y un 10% para el C, por lo que hay que investigar el motivo de esto para los diferentes planes .

-El promedio de tranferiecia considerado bueno o aceptable es entre un 11% y 20%, aproximadamente un 18% de los operadores esta sobre esto por lo que mejorar el conocimiento con respecto a los servicios o mejorar el acceso a la informacion ayudaria a mejorar esta tasa.

-El tiempo promedio en el que el usuario abandona una llamada es de 2 minutos y 36 segundosm, por lo que dejar un tiempo de espera menor o igual a 2 minutos seria aceptable, con esto en mente aproximadamente un 7% de los operadores contemplando las llamadas entrantes contaron con un porcentaje mayor al tiempo definido, para ir mejorando se pordria verificar las colas de llamadas en relacion a la cantidad de operadores o talvez implementar soluciones de auto ayuda para que los usuarios no requieran llamar para cuestiones que puedan solucionar ellos.

-La cantidad de usuario por plan en los 3 meses que se poseen registros fue disminuyendo para los planes B Y C siendo que estos tenian la mayor cantidad de registros inicialmente y el plan A que tenia pocos subio considerablemente al final del ultimo mes, por lo que tomar caracteristicas de este plan como modelo para implementarlo en los otros y aumentar la cantidad usuarios en estos.
