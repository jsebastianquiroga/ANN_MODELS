# ANN_MODELS

El presente taller es desarrollado para la clase de aprendizaje de maquina.

Se crearán algunos datos randomicos, y se generara una red neural paso a paso, posteriormente se importará el modelo disponible en la libreria de Sklearn, para comprar sus resusltados.

***PRESENTADO POR*** :</P>
**JUAN SEBASTÍAN QUIROGA**

Fue generado un modelo sin libreria y se comparo con los resultados obtenidos mediante sklearn.

Los cuales fueron evaluados mediante un data set proveniente de kaggel. https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling?resource=download

Este modelo busca predecir el churn, de unos clientes en 4 paises distintos.

Es información financiera, son 10000 observaciones con 18 variables de estas.

Se importa de un csv, ya que es el formato que se descarga del link relacionado.

Este data set, tiene 4 variables identificadoras, como lo son el apellido, el numero de la fila, el id del cliente, por eso se removeran.

Se divide esta matriz entre los predictores y la variable de respuesta, x, y. 
