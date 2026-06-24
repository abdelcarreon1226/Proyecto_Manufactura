# Proyecto_Manufactura
Este proyecto consiste en analizar datos simulados de una empresa para evaluar la calidad de produccion de distintas maquinas en una empresa manufacturera

# Objetivo del proyecto 
Analizar datos de producción de una fábrica para identificar áreas de mejora operativa, respondiendo preguntas clave del negocio mediante visualizaciones estadísticas e interactivas.

# Dudas del Negocio 
1. ¿Qué línea genera más scrap?
2. ¿Qué turno genera más scrap?
3. ¿Qué línea tiene el mayor tiempo promedio de ciclo?
4. ¿Qué máquinas presentan los mayores tiempos promedio de ciclo?
5. ¿Las máquinas más antiguas generan más scrap?

# Dataset 
El data set contiene datos obtenidos de kaggle contiene informacion de id de maquinas, turnos, horas trabajadas entre otros datos para llegar a un analisis sobre el funcionamiento de la fabrica para mejorar el rendimiento. 
-link de el dataset : https://www.kaggle.com/datasets/williamsewell/manufacturing-quality-decisions

# Herramientas
- Python
- Pandas
- Matplotlib
- Power Bi

# Conclusiones
- **Line_D** es la línea más crítica: mayor volumen de scrap (73 unidades)
  y mayor tiempo promedio de ciclo (36.6 min).
- **El turno day** genera más scrap (111 unidades), duplicando al turno
  nocturno (55 unidades).
- **MC126 y MC150** son las máquinas con mayor tiempo de ciclo promedio
  (~37.5 min).
- La antigüedad de la máquina **no es el factor determinante** del scrap;
  otros factores como turno y línea tienen mayor influencia.
