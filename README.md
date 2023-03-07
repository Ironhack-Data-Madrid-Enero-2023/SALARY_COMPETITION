# SALARY_COMPETITION

Lo primero es que en la competición no sale mi nombre sino salgo como 'wolves of the mountain'.

Para este proyecto he hecho varios intentos en el jupyter notebook y el valor de RMSE que menos me salía ha sido el que he subido a KAGGEL.
Dentro del proyecto que menos valor me daba he realizado ciertos cambios. Primeramente he eliminado las columnas 'salary', 'salary_currency' ya que ya tenemos una columna con todo junto por lo que estas columnas son inservibles.

Después he pasado de las columnas categoricas a numericas usando distintos metodos. Por ejemplo para las columnas que tienen menos value_counts he creado un diccionario asignandoles valores 1,2,..... para las otras he usado label encoder(sabiendo que esto me podría generar sesgos)

Una vez hecho esto defino la X y la y, normalizo y spliteo. Aplico Lazy predict para que me dé una idea de que modelo predictivo puede ser el más eficiente. En este caso no era el mejor que me indicaba Lazy por lo que he ido probando el cual he encontrado que era Poison.

Realizado dicho modelo aplico el evaluador RMSE y subo los datos a KAGGEL. Observo que la diferencia entre lo obtenido en Jupyter y Kaggel no difiere en demasia , es decir lo tengo overfitted pero poco por lo que considero que está relativamente bien ajustado.





