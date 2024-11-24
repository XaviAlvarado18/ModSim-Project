# ModSim-Project
Project #01 - Modeling and Simulation course

# Simulación del Mundial de Qatar 2022

Este proyecto utiliza un enfoque probabilístico basado en técnicas de Monte Carlo para simular los resultados de los partidos del Mundial de Qatar 2022. El objetivo principal es modelar el comportamiento de los equipos a lo largo de las fases de grupos y eliminatorias, para estimar las probabilidades de victoria de cada selección.

## Descripción del Proyecto

El modelo utiliza las siguientes características principales:
1. **Base de datos**: Se parte de un archivo CSV con información sobre los equipos, sus grupos y sus puntuaciones históricas.
2. **Simulaciones**: Cada enfrentamiento es simulado utilizando diferencias relativas en puntaje, ajustadas con un factor probabilístico.
3. **Fases del torneo**: Se implementan todas las fases del torneo, desde la fase de grupos hasta la final.
4. **Resultados**: Los datos generados permiten calcular las frecuencias de victoria de cada equipo y observar el desempeño promedio en múltiples simulaciones.

## Estructura del Código

### Cargar y Preparar Datos
El archivo `SimulacionQATAR2022.csv` contiene la información inicial. Se carga utilizando la biblioteca `pandas`.

### Simulación de Enfrentamientos
Se define una función que utiliza un modelo probabilístico para determinar el ganador de un enfrentamiento entre dos equipos, basado en sus puntajes respectivos.

### Progresión del Torneo
Las siguientes etapas son simuladas:
- **Fase de grupos**: Todos los equipos enfrentan a los otros equipos de su grupo.
- **Fases eliminatorias**: Desde los octavos de final hasta la final, se simulan enfrentamientos directos.

### Resultados

- Modelación de MonteCarlo

![image](https://github.com/user-attachments/assets/929aa270-acde-4703-a2ed-5fa9654ff195)
![image](https://github.com/user-attachments/assets/82f44a56-7afa-4679-b3fa-d90e258e209d)
![image](https://github.com/user-attachments/assets/bb341913-8486-4a97-ba85-98b191ddb78f)
![image](https://github.com/user-attachments/assets/a54cf084-5dae-41cc-89e7-5bb0f39dd7d6)
![image](https://github.com/user-attachments/assets/7425cfd4-3fd6-4b7f-8e34-21d6c2464af6)
  
- Cadenas de Markov

![image](https://github.com/user-attachments/assets/8ca74e50-e5e4-460d-9b5a-07baffa228a2)
![image](https://github.com/user-attachments/assets/46bc17be-b745-47b1-ba14-7d4f3d908b09)
![image](https://github.com/user-attachments/assets/d449baab-8301-4502-a716-934158f83d4a)
![image](https://github.com/user-attachments/assets/e44a695c-ecb7-4022-a679-d7baca24c336)
![image](https://github.com/user-attachments/assets/db0f20d5-a2e8-4fc4-891a-f58e77ccd519)
