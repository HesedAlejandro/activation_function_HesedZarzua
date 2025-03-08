# Funciones de Activación en Redes Neuronales

Este proyecto implementa y visualiza funciones de activación comunes utilizadas en redes neuronales: ReLU, Sigmoid, Tanh y Leaky ReLU. 

## Estructura del Proyecto

```
activation_function_HesedZarzua/
|-- src/
|   |-- relu.py         # Implementación y visualización de ReLU
|   |-- sigmoid.py      # Implementación y visualización de Sigmoid
|   |-- tanh.py         # Implementación y visualización de Tanh
|   |-- leaky_relu.py   # Implementación y visualización de Leaky ReLU
|-- main.py            # Ejecuta y muestra las funciones de activación
|-- requirements.txt   # Dependencias necesarias
|-- README.md          # Documentación del proyecto
```

## Instalación

Clona este repositorio y navega a la carpeta del proyecto:

```bash
git clone https://github.com/tu_usuario/activation_function_HesedZarzua.git
cd activation_function_HesedZarzua
```

Instala las dependencias necesarias:

```bash
pip install -r requirements.txt
```

## Uso

Ejecuta el script principal para visualizar las funciones de activación:

```bash
python main.py
```

Este script ejecuta las funciones de activación definidas en `src/` y muestra sus respectivas gráficas.

## Explicación de Archivos

- `relu.py`: Implementa la función ReLU y su derivada. Genera una gráfica con ambas funciones.
- `sigmoid.py`: Implementa la función Sigmoid y su derivada. Genera una gráfica con ambas funciones.
- `tanh.py`: Implementa la función Tanh y su derivada. Genera una gráfica con ambas funciones.
- `leaky_relu.py`: Implementa la función Leaky ReLU y su derivada. Genera una gráfica con ambas funciones.
- `main.py`: Importa y ejecuta todas las funciones para mostrar sus representaciones visuales.

## Notas

- Asegúrate de que `src/` esté correctamente referenciado en `main.py` para evitar errores de importación.
- Puedes modificar los valores de `alpha` en `leaky_relu.py` para ver su impacto en la función.
