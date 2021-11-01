# LinearRegression_hyundai_Cruise_Ship_info
Ejercicio de regresion linear en jupyter notebook

El objetivo principal es el de tratar de realizar un modelo predictivo basado en la información proveniente del cliente.
También aprender a convertir datos reales al formato requerido por Spark MLlib.

EJERCICIO
Hemos sido contratados por Hyundai Heavy Industries para ayudarles a crear un modelo predictivo para algunos de sus barcos.
Nos piden viajar a sus cuarteles generales en Ulsan, Corea del Sur.
Hyundai Heavy Industries es uno de las empresas de manufacturas más grandes del mundo. Crear naves de gran calado e incluso cruceros.
La empresa requiere una estimación precisa de cuántos miembros de la tripulación son requeridos para una embarcación.
Actualmente están a punto de vender algunas embarcaciones para nuevos clientes y requieren una predicción sobre los miembros necesarios para dichas embarcaciones.
Nos proveen la siguiente información: 
  -Ship Name
  -Cruise Line
  -Age
  -Tonnage (1000s de toneladas)
  -Passengers (100s)
  -Length (100s de pies)
  -Cabins (100s)
  -Passenger Density
  -Crew (100s)

Nuestro trabajo es el de crear un modelo de regresión que ayude a predecir cuántos miembros de la tripulación serán requeridos para futuras embarcaciones.
En otras palabras, debemos pensar de toda la información brindada por la empresa, cuál será útil para predecir los valores en la columna Crew.
El cliente mencionó que han encontrado que distintas líneas de cruceros pueden diferir en cuanto a la cantidad de miembros requeridos. Es una característica importante a tener en consideración.
Sin embargo, el valor para la Cruise es una cadena de texto.
Como cualquier proyecto del mundo real, no existe una solución “100% correcta”.
Este ejemplo es muy abierto a la interpretación y se puede crear un modelo de múltiples maneras distintas.
