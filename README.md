# FCND - 3D Motion Planning
![Quad Image](./misc/enroute.png)


## Pasos requeridos en el trabajo practico

### Paso 1: Clonar el respositorio
```sh
git clone https://github.com/leoborgnino/FCND-Motion-Planning
```
### Paso 2: Testear que funcione correctamente el entorno
Abrir el simulador y en otra consola correr:  
```sh
source activate fcnd
python backyard_flyer_solution.py
```

### Paso 3: Se puede utilizar para el desarrollo el archivo motion_planning.py o Practico1.ipynb segun se quiera desarrollar con jupyter notebook o no. Tambien esta el archivo planning_utils.py que provee funciones desarrolladas en el trabajo anterior y el archivo colliders .csv que tiene el mapa 2.5D del entorno.

### Paso 4: Desarrollar los algoritmos de Planning

Para ello se debe:

- Cargar el mapa 2.5D
- Discretizar el entorno en un grid y en un grafo 
- Definir el estado inicial y el estado objetivo. 
- Realizar la búsqueda de los waypoints necesarios para llegar al objetivo con A star u otra técnica.
- Usar un método de colinealidad o ray tracing para eliminar los waypoints innecesarios, si se usa un grid.
- Retornar los waypoints en coordenadas ECEF para luego enviar comandos al drone y realizar la navegación.


