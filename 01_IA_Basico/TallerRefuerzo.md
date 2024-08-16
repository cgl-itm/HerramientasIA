# Taller Aprendizaje por refuerzo
Para las actividades propuestas en esta sección, utilizaremos la aplicación
- [Reinforcement Learning Playground](https://alazareva.github.io/rl_playground/)
  
En esta aplicación permite probar diferentes esquemas de aprendizaje como SARSA, Q-learning y Dyna-Q. El ambiente 
tiene 54 estados, correspondientes a las celdas en el laberinto. Se pueden tomar 4 acciones (arriba, abajo, izquierda y derecha).
El agente recibe una recompensa de -0.01 sí intenta salirse del mapa o atravesar un muro. Recibe una recompensa de +10
sí llega a su objetivo.

La idea es resolver el laberinto siguiente una de estas tres rutas
<img src="https://raw.githubusercontent.com/cgl-itm/HerramientasIA/main/assets/RLMaze01.png" alt="drawing" style="width:400px;"/> <br>
El agente no sabe cual es la solución, y al comienzo seleccionada de manera aleatoria las acciones, hasta empezar a recibir las recompensas.

1. Ejecutar la simulación para cada método de aprendizaje.
2. Ordenar de mejor a peor el desempeño de cada método de acuerdo a las soluciones encontradas.
