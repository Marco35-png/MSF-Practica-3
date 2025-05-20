
# Modelado de Sistemas Fisiológicos. Práctica 3: Sistema cardiovascular [Perez19212423]

## Autor
Perez Chavez Marco Antonio

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: marco.perez193@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita eliminar el error entre la entrada [Pa(t)] y la salida [Pp(t)] de un circuito RLC de segundo orden.

## Actividades
1. Calcular analíticamente la función de transferencia del sistema cardiovascular.
2. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
3. Construir el diagrama de bloques como se indica en el diagrama 5.8.
4. Diseñar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para sintonizar los valores últimos para cada una de las ganancias
kP, kI y kD.
5. Ilustrar el cambio de la presión sobre la distensibilidad arterial [Pp(t)]
en respuesta a la presión arterial de entrada Pa(t). Utilice la función de entrada Uniform Random Number con la siguiente configuración: mín = -0.2V; max = 1 V; seed = 106; Sample time = 0.5
6. Determinar la respuesta a la funciÛn en el intervalo t2 [0,15](segundos) en Python, Simulink y Multisim en lazo abierto y en lazo cerrado con el controlador.
7. Elaborar el diagrama biolÛgico del sistema con BioRender.com.
8. Discutir los resultados obtenidos en la experimentación in silico y elaborar el reporte de la práctica.


## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.
