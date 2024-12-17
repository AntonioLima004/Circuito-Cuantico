# Circuito Cuántico en Python

## Descripción

Este proyecto implementa un circuito cuántico utilizando Python. El circuito está diseñado para demostrar principios fundamentales de la computación cuántica, como la superposición y el entrelazamiento. Se utiliza la librería `qiskit` para construir y simular el circuito.

## Requisitos

Antes de ejecutar el código, asegúrate de tener instalados los siguientes requisitos:

- Python 3.8 o superior
- Qiskit (se puede instalar con `pip install qiskit`)
- Matplotlib (para la visualización de resultados, se instala con `pip install matplotlib`)

## Instalación

1. Clona este repositorio en tu computadora:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd circuito_cuantico
   ```

3. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Ejecuta el script principal para simular el circuito cuántico:
   ```bash
   python circuito_cuantico.py
   ```

2. Observa los resultados en la consola y, si está habilitada, una representación gráfica de las probabilidades cuánticas.

## Circuito

El circuito implementa las siguientes operaciones:

1. **Puerta Hadamard (H):** Coloca al qubit en superposición.
2. **Puerta CNOT:** Entrelaza dos qubits, creando un estado entrelazado.
3. **Medición:** Colapsa el estado cuántico y registra los resultados en clásicos.

## Ejemplo de Resultados

- Estado final simulado: |00>, |01>, |10>, |11> con diferentes probabilidades dependiendo de las puertas utilizadas.
- Representación gráfica de las probabilidades (histograma).

## Estructura del Proyecto

```
.
├── circuito_cuantico.py   # Archivo principal con la implementación del circuito
├── README.md              # Documentación del proyecto
├── requirements.txt       # Dependencias del proyecto
└── resultados/            # Directorio para almacenar los resultados generados
```

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama con tu función o mejora:
   ```bash
   git checkout -b mejora-nueva-funcion
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -m "Agregada nueva función"
   ```
4. Envía un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más información.

## Contacto

Para cualquier duda o sugerencia, puedes contactarme a través de [correo electrónico](jose.antonio.la.2004@gmail.com).
