# Simulador-MAIA
Simulador para curso Inteligencia en Robots MAIA
Esta es una versión traducida al español y adaptada del simulador propuesto en https://github.com/paulodowd/GoogleColab_Simple2DSimulator desarrollado por: [Paul O'Dowd](https://www.bristol.ac.uk/people/person/Paul-O'Dowd-d54e9ad6-41de-4eef-81c6-1ee227ced8dc) y [Hemma Philamore](https://www.bristol.ac.uk/people/person/Hemma-Philamore-c3c8acb0-fcce-4792-9249-2efccb92145f).

### Bienvenido al cuaderno de ejercicios

Todas estas hojas de ejercicios están diseñadas para ser utilizadas de forma interactiva dentro de [Google Colab](https://research.google.com/colaboratory/). Puedes guardarlas en tu propio espacio de trabajo. Es posible que necesites una [cuenta de Google](https://www.google.com/account/about/) para hacerlo.

Estas hojas de ejercicios están diseñadas para proporcionar una introducción rápida al marco de pensamiento necesario al trabajar en robótica. Esto incluye:
- Desarrollar software de control que funcione de manera iterativa y sin interrupciones.
- Anticipar que, aunque es posible una muy buena solución para una tarea, esta puede volverse más compleja fácilmente.
- Comprender que la complejidad de una tarea, y por lo tanto las soluciones adecuadas, puede aumentar rápidamente.

Estas hojas de ejercicios te desafiarán a avanzar a través de una serie de tareas que se construyen sobre la anterior, con una complejidad creciente. Estas son:
1. Comportamiento de evitación de obstáculos.
2. Comportamiento de circunnavegación.
3. Navegación para mapeo (cobertura).
4. Seguimiento de otro robot con sensores ruidosos.

Estas hojas de ejercicios sirven como una breve introducción, por lo que tienes la libertad de ser creativo y explorar la naturaleza del espacio de problemas.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/TestSheet.ipynb) **Cuaderno de prueba:** Puedes verificar rápidamente si puedes acceder a Google Colab y a estos cuadernos de ejercicios haciendo clic en el botón a la izquierda.

<br><br>
## Información: Primeros pasos

Si nunca has usado Python o Google Colab antes, las siguientes hojas de ejercicios te ayudarán a comenzar:

### [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/01_Operators.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/01_Operators.ipynb) Python: Operadores  
Realizar cálculos básicos, comparar variables, y usar valores booleanos para formar declaraciones lógicas.

### [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/02_Control_Flow.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/02_Control_Flow.ipynb) Python: Flujo de Control  
Tomar decisiones dentro de un programa para dirigir su ejecución.

### [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/03_Loops.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/03_Loops.ipynb) Python: Bucles  
Repetir operaciones de forma controlada dentro de un programa.

### [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/intro.ipynb) Google Colab  
Colaboratory, o "Colab", permite escribir y ejecutar Python en el navegador, sin configuración, acceso gratuito a GPUs y fácil compartición.

### Jupyter / Anaconda:
Si no puedes acceder a Google Colab, puedes instalar Jupyter/Anaconda en tu computadora para ejecutar los archivos localmente. Necesitarás descargar los archivos de este repositorio de GitHub.  
[Instalar Jupyter/Anaconda](https://test-jupyter.readthedocs.io/en/latest/install.html)  
Un breve tutorial sobre cómo ejecutar estas hojas en Anaconda/Jupyter está [disponible aquí](https://github.com/paulodowd/GoogleColab_Simple2DSimulator/raw/main/anaconda_instructions.pdf).

<br><br>
## Tutorial Simulador

## [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet1_ObstacleAvoidance.ipynb) Ejercicio 1: Evitación de obstáculos

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/obs_avoidance.png?raw=true" width="350px">
    </td>
    <td>
      En este ejercicio encuentras un controlador para que el robot simulado tome decisiones y se desplace evitando obstáculos.
    </td>
  </tr>
</table>

<hr><br><br>

## [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet2_Circumnavigation.ipynb)  Ejercicio 2: Navegación entre obstáculos

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/c_navigation.png?raw=true" width="350px">
    </td>
    <td>
      En esta ejercicio encuentras comportamientos para que el robot simulado detecte obstáculos y navegue a su alrededor.
    </td>
  </tr>
</table>

<hr><br><br>

## [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet3_Mapping.ipynb) Ejercicio 3: Generación de mapas

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/mapping.png?raw=true" width="350px">
    </td>
    <td>
      Aquí combinaremos trabajos previos para registrar un mapa del entorno simulado, explorando de manera eficiente.
    </td>
  </tr>
</table>

<hr><br><br>

## [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet4_SensorNoise.ipynb) Ejercicio 4: Ruido de Sensores

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/Following.png?raw=true" width="350px">
    </td>
    <td>
      En esta ejercicio encuentras como tratar los desafíos del ruido en sensores reales utilizando un controlador para seguir otro robot.
    </td>
  </tr>
</table>

<hr><br><br>

## Ejercicio 5: ¡Explora!

Ahora puedes explorar los ejercicios anteriores y exteiendas la funcionalidad del simulador. Habrá soporte disponible durante la semana para cualquier pregunta relacionada.
