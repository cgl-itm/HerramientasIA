# Aprendizaje Supervisado
Es una de la tecnicas mas usada del aprendizaje automatico. Las tecnicas de Aprendizaje Supervisado se entrenan a partir de datos etiquetados (Regresion y Clasificación). La clasificación consiste en identificar una clase de una señal (audio), una imagen (objetos o poses). <br>

Para comprender mejor el funcionamiento del Aprendizaje Supervisado se propnen un conjunto de mini proyectos para realizar en grupos. Se utiliza las plataformas Teachable Machines de Google y Edge Impulse.

## Teachable Machines - Google
Es una plataforma que permite subir bases de datos de Imagenes, Poses o Sonidos. A partir de estos datos se entrena un modelo de Deep Learning predefinido empleando Transfer Learnig. La base de datos es el principal insumo para estos modelos predefinidos. Para esta plataforma se proponen los siguientes mini proyectos: <br>

Los proytectos con imagenes se realizaran usando el modelo de imagen estandar de la plataforma Teachable Machines.

1. Clasificacion de Lenguaje de Señas: Consiste entrenar el clasificador para que identifique 3 clases diferentes de señas. Condiciones:
   * Seleccionar 3 señas diferentes, ver [video](https://www.youtube.com/watch?v=EOcVvy1mcYI). 
   * Cada estudiante del subgrupo debe tomarse 10 fotos realizando cada seña. Entonces por seña se tendran 20 fotos (10 de cada estudiante).
   * Subir las imagenes a cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.

2. Clasificacion de Posturas: Consiste entrenar el clasificador para que identifique 3 clases de posturas diferentes. Considere este [tutorial](https://medium.com/@warronbebster/teachable-machine-tutorial-head-tilt-f4f6116f491) como guia. Condiciones:
   * Seleccionar 3 posturas diferentes. 
   * Cada estudiante del subgrupo debe tomarse 10 fotos realizando cada postura. Entonces por postura se tendran 20 fotos (10 de cada estudiante).
   * Subir las imagenes a cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.

3. Clasificación commandos de voz: Sabias que Alexa, Siri y OK Google funcionan clasificando el audio en textos. Para este mini proyecto los estudiantes deben construir una base de datos silbando, aplaudiendo y chasquear los dedos. A partir de los audios construir un clasificador que indique cuando comando fue pronunciado. Usar este [tutorial](https://medium.com/@warronbebster/teachable-machine-tutorial-snap-clap-whistle-4212fd7f3555) para comprender los pasos a seguir.
Condiciones:
   * Seleccionar 3 comandos de voz diferentes, y una clase adicional para el ruido. 
   * Cada estudiante del subgrupo debe grabar 10 audios de cada comando. Entonces por comando se tendran 20 audios (10 de cada estudiante).
   * Subir los audios a cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.    

4. Clasificación de tipos de musica: Para este mini proyecto los estudiantes deben construir una base de datos a partir de diferentes audios con 3 tipos de musica diferentes (rock, pop, metal, salsa, regueton). A partir de los audios construir un clasificador que indique que tipo musica esta sonando. Usar este [tutorial](https://medium.com/@165498/teachable-machine-project-a-variation-of-classic-rock-music-9e0caf12bded) para comprender los pasos a seguir.
Condiciones:
   * Seleccionar 3 audios de musica diferentes, y una clase adicional para el ruido. 
   * Subir los audios a cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.   

## Proyectos con Edge Impulse 
1. Clasificacion de señales de acelerometros: El proyecto consiste entrenar un clasificador de imagenes que identifique 3 tipos diferentes de imagenes. Usar este [tutorial](https://docs.edgeimpulse.com/docs/tutorials/end-to-end-tutorials/image-classification) para comprender los pasos a seguir. Condiciones:
   * Construir una base de datos con tres objetos (botella, lapicero, billetera, etc). Las imagenes son de un solo objeto por clase. 
   * Cada estudiante del subgrupo debe tomarse 10 fotos de cada objeto. Entonces por clase o objeto se tendran 20 fotos (10 de cada estudiante).
   * Subir las imagenes de cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.

2. Detección de objetos: Para este mini proyecto los estudiantes deben construir una base de datos a partir de fotos o imagenes que contengan objetos. Luego se entrenara un modelo de aprendizaje supervisado para que detecte los objetos. Usar este [tutorial](https://docs.edgeimpulse.com/docs/tutorials/end-to-end-tutorials/object-detection/object-detection) para comprender los pasos a seguir.
   * Construir una base de datos con tres objetos (botella, lapicero, billetera, etc). Las imagenes pueden contener varios objetos. 
   * Cada estudiante del subgrupo debe tomar 20 fotos de los objetos. Entonces por clase o objeto se tendran 40 fotos (20 por cada estudiante).
   * Subir las imagenes de cada clase y entrenar el modelo. Verificar su desempeño.
   * Hacer una presentación donde se describar la base de datos, como entrenaron el modelo y la evaluación del desempeño. Realizar una demostración en la clase.
