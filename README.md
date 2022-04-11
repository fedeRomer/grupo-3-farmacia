# grupo-3-farmacia

![Diagrama de Proceso - GRUPO C](https://user-images.githubusercontent.com/60818032/162754430-61ad010a-6fdd-4943-a01d-1d0c4c6c2afd.png)
![Eventos Especiales](https://user-images.githubusercontent.com/60818032/162754443-8003d698-326a-4c3a-9549-bfdfce445135.png)



# Objetivo
Lograr que el proceso de dispensación de medicación de la farmacia cumpla con las normas establecidas por el Hospital Austral (que todos los pisos tengan la medicación de todos los pacientes en forma completa y antes de las 16 horas).

# Definición del problema
La farmacia no logra cumplir con las normas del Hospital ya que normalmente los carros van incompletos por falta de medicación y/o fuera de horario.  

# Alcance
El proceso de dispensación de la farmacia comienza desde que las indicaciones médicas ingresan por sistema y el farmacéutico es capaz de visualizarlas y validar dichas indicaciones. Una vez validadas, son enviadas para su posterior preparación. Cuando el proceso de preparación finaliza, la medicación es entregada al servicio de enfermería en su respectivo piso.

# Variables de decisión
## Cantidad de recetas.
## Cantidad de técnicos.
## Cantidad de farmacéuticos.
## Cantidad de medicamentos.


# Variables de referencia
## Tiempo promedio que demora el farmacéutico en validar las recetas.
## Tiempo promedio que demoran los técnicos en preparar las recetas.



El Hospital Universitario Austral es una prestigiosa institución argentina dedicada a atender a los pacientes, la asistencia, docencia e investigación médica. El Hospital cuenta con una farmacia propia, dentro del hospital, que es la encargada de entregar la medicación de cada uno de los pacientes de los diferentes pisos con los que cuenta el hospital, entre otras diversas tareas.

La problemática más importante de la farmacia es que no logra cumplir con las normas establecidas por el hospital respecto al horario y las condiciones de entrega de la medicación de los pacientes. Esto conlleva quejas y reportes de parte del personal de enfermería y médico, que producen conflictos y un mal servicio a quien más lo necesita, los pacientes hospitalizados.

El proceso comienza cuando el farmacéutico es capaz de visualizar en el sistema las indicaciones médicas. Una vez que las puede visualizar, ya puede comenzar a validar dichas indicaciones para ver si están bien hechas. A medida que van llegando las indicaciones, los farmacéuticos pueden filtrar en el sistema por piso. Esto permite darle prioridad a las recetas más urgentes, como por ejemplo, las recetas de la terapia intensiva. 

En caso de que el farmacéutico detecte un error en la indicación médica, se pone en contacto con el médico y le informa del error. El farmacéutico no puede indicar ni modificar las indicaciones médicas, únicamente puede validar, por lo que se ve obligado a contactarse con el médico para que modifique el error.

Cuando las indicaciones médicas de un piso están correctas, las envían por sistema al Kardex para que los técnicos puedan comenzar a preparar la medicación de cada paciente del piso enviado. Una vez que las indicaciones médicas figuran en el monitor del Kardex, el técnico las ejecuta de manera manual y comienza a preparar la medicación para luego ser entregada. 

En caso de que no haya stock físico de la droga, el Kardex imprime un listado con los medicamentos que están en las recetas pero no se encuentran dentro de la máquina. En esta situación, se busca en el depósito de farmacia o, en caso de que el depósito de farmacia no tenga,  se solicita la droga al depósito general del hospital. 
En caso de que la droga sea de la clase: Estupefaciente, Electrolito, Psicotrópico, Venta bajo receta, Jarabe o Alimentación: el Kardex lo notifica en el mismo listado anterior. En este caso, se busca en los armarios especiales que hay para estos tipos de droga y se colocan en la bolsa de los pacientes.





Una vez que el técnico finaliza con la preparación de la medicación, el cadete se encarga de subir todo dentro de un tupper cerrado con precinto. Cuando el cadete arriba al piso en cuestión, controla con una auxiliar de enfermería que esté toda la medicación completa. Si falta algo, el cadete lo anota en una planilla para luego ser enviado. Cuando termina de hacer el control bolsa por bolsa de todos los pacientes del piso, vuelve a farmacia con la medicación que sobro del día anterior.



# Eventos especiales  y lógicas
### ¿Las indicaciones médicas son correctas?
### ¿Están todas las drogas en el Kardex?
### ¿El piso está completo?


# Variables aleatorias, Parámetros y relación entre ellos
### Cantidad de pacientes hospitalizados.
### Cantidad de medicación indicada en cada paciente.

# Elementos del simulador
- Entidades
- Atributos
- Variables
- Recursos
- Colas
- Eventos
