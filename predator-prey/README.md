# Simulación de poblaciones de liebres y zorros
Este código simula las poblaciones de liebres y zorros en un ecosistema, con el objetivo de estudiar cómo interactúan y evolucionan ambas poblaciones a lo largo del tiempo.

La simulación se basa en los siguientes parámetros y variables:

## Parámetros
- `weeks`: cantidad de semanas que dura la simulación.
- `time_interval`: incremento de tiempo en semanas.
- `terrain_capacity`: capacidad del terreno para alimentar liebres.
- `rabbits_population`: cantidad inicial de liebres.
- `foxes_population`: cantidad inicial de zorros.
- `rabbits_growth_rate`: tasa de crecimiento de liebres.
- `foxes_survival_rate`: tasa de supervivencia de zorros.
- `foxes_population_increase`: tasa de crecimiento de la población de zorros.
- `hunting_encounters_rate`: tasa de mortalidad de los zorros por cada encuentro de caza.



## Variables
- `current_terrain_capacity`: capacidad actual del terreno para alimentar liebres.
- `rabbit_population_increase`: aumento en la población de liebres en una semana.
- `foxes_surviving_population`: cantidad de zorros que sobreviven cada semana.
- `hunting_encounters`: cantidad de encuentros de caza entre zorros y liebres cada semana.

## Instalación

Este proyecto contiene el archivo predator-prey.ipynb, que es un notebook de Jupyter. Para ejecutar el notebook, es necesario crear un entorno virtual y instalar los paquetes necesarios.

```sh
# Entrar a la carpeta del proyecto.
$ cd predator-prey

# Crear un entorno virtual.
$ python -m venv env

# Activar el entorno virtual.
$ source env/bin/activate

# Instalar los paquetes necesarios.
$ pip install -r requirements.txt
```

El archivo requirements.txt contiene los siguientes paquetes:
- matplotlib
- jupyter

## Ejecución
Asegurate de que estás en la carpeta del proyecto y el entorno virtual está activo. Ejecuta el siguiente comando para abrir Jupyter.

```sh
$ jupyter notebook
```

## Desactivar el entorno virtual
Cuando hayas terminado de trabajar en el proyecto, desactiva el entorno.

```sh
$ deactivate
```