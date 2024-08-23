# Inteligencia Artificial

# Aprendizaje no-supervisado
Consiste en técnicas que se ajustan a los datos (observaciones). Estas técnicas permiten encontrar patrones o grupos en los datos. La técnica de agrupamiento básica es el algoritmo de las k-medias (k-means). En los siguientes links podemos encontrar demostraciones de este algoritmo
* [Visualizing k-means clustering](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
* [K-Means Clustering Demo](https://user.ceng.metu.edu.tr/~akifakkus/courses/ceng574/k-means/)

Podemos también analizar algoritmos mas sofisticados 
* [Projector - Google](https://projector.tensorflow.org/)
* [druidjs generator](https://observablehq.com/@john-guerra/druidjs-generator)

Para aterrizar el funcionamiento de estos algoritmos se proponen el siguiente taller de actividades:
* [Taller K-means](https://github.com/cgl-itm/HerramientasIA/blob/main/01_IA_Basico/TallerNoSupervisado.md)

# Aprendizaje supervisado
Es el tipo de aprendizaje mas empleado debido a su gran conjunto de aplicaiones. Requiere de datos de entrada y datos de salida. Se pueden distringuir 2 tipos, la clasificación y la regresión.

## Clasificación
La clasificacion es una tarea que consiste aprender la relacion entre una entrada y una salida. La entrada puede ser desde un valor escalar hasta una imagen, y la salida es la clase que tiene asignada la entrada. Por ejemplo, entra la `imagen de un gato`, y el clasificador debe devolver el valor de la clase `gato`.
* [ML Playground](https://ml-playground.com/)
* [SVM demo](https://greitemann.dev/svm-demo)
* [SkLearn models](https://www.stefanom.io/sklearn-classifiers-playground/) 

Para la tarea de clasificación se propone el siguiente taller
* [Taller Clasificación](https://github.com/cgl-itm/HerramientasIA/blob/main/01_IA_Basico/TallerClasificacion.md)
 
## Regresión
Esta tarea consiste en aproximar funciones `f(x)` donde `x` es la entrada y `f(x)` es la salida. Para entrenar estos métodos de regresión, se requiere una tabla con valores de `x` y valores de `f(x)`, con el fin que método aprenda a relacionar la entrada con la salida. <br>

Para la tarea de regresión se propone el siguiente taller:
* [Taller regresion](https://github.com/cgl-itm/HerramientasIA/blob/main/01_IA_Basico/TallerRegresion.md) 

# Aprendizaje por refuerzo
Esta tecnica busca tomar la mejor acción de acuerdo a un estado. En la siguiente figura
<img src="https://deepanshut041.github.io/Reinforcement-Learning/notes/00_Introduction_to_rl/images/intro_to_rl.png" alt="drawing" style="width:400px;"/> <br>
podemos observar que el `Agente` interactua con un `Ambiente` y dependiendo de las acciones que tome el agente se modifica el estado del ambiente. Para poder definir cual es la mejor acción para cada estado se basa en la premiación (`reward`).

Para analizar el funcionamiento del aprendizaje por refuerzo se propone el siguiente taller:
* [Taller Refuerzo](https://github.com/cgl-itm/HerramientasIA/blob/main/01_IA_Basico/TallerRefuerzo.md)

# Deep Learning
## Neural Netrowks
* [3D Visualization Number Classification](https://adamharley.com/nn_vis/mlp/3d.html)
* [Tensorflow - Playground](https://playground.tensorflow.org/)

## Convolutional Neural Networks
* [CNN Explainer](https://poloclub.github.io/cnn-explainer/)

## Generative Adversarial Networks
* [Generative Adversarial Networks - GANs](https://poloclub.github.io/ganlab/)

## Advanced Topics
* [Transformer Explainer](https://poloclub.github.io/transformer-explainer/)
* [Diffusion Explainer](https://poloclub.github.io/diffusion-explainer/)



# Explain any model
* [SHAP demo](https://poloclub.github.io/webshap/)
