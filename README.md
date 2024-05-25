# desarrolloia
Desarrollo de Sistemas de Inteligencia Artificial 
TECNICATURA SUPERIOR EN INNOVACIÓN CON TECNOLOGÍAS 4.0

SISTEMAS DE DESARROLLO DE INTELIGENCIA ARTIFICIAL

##SEGUNDO AÑO - COLOQUIO
-----------
# Tensorflow - Optimización de modelos de deep learning con Adam para aplicaciones en la industria 4.0
----------
Alumno: Raúl Moreno

Docente: Cr. Sol del Valle Figueroa

22 de Noviembre de 2023

-----------------------------
### Introducción
El aprendizaje profundo y el uso de redes neuronales están transformando la industria 4.0. Para entrenar estos modelos se requieren algoritmos de optimización eficientes. Uno de los más utilizados es Adam (Adaptive Moment Estimation), que combina las ventajas del momento y RMSProp.

En este trabajo se presenta el uso de Adam para entrenar modelos en TensorFlow/Keras, utilizando como caso práctico la clasificación de imágenes del conjunto de datos MNIST.

Sse desarrolla un ejemplo práctico paso a paso, posteriormente se discuten aplicaciones en la industria 4.0 como detección de anomalías, mantenimiento predictivo y automatización de procesos.

### Desarrollo
La industria 4.0 trae consigo la automatización inteligente a través de tecnologías como el internet de las cosas (IoT), big data, robótica avanzada y aprendizaje automático.

Dentro del aprendizaje automático, las redes neuronales profundas están demostrando un gran potencial para resolver problemas complejos en una variedad de dominios, donde entrenar estos modelos profundos y robustos representa un desafío computacional.

Los algoritmos de optimización juegan un rol crítico, permitiendo encontrar los parámetros óptimos para minimizar la función de pérdida del modelo. Uno de los más populares es Adam (Adaptive Moment Estimation), que combina las ventajas del momentum y el método RMSProp. Adam permite entrenar modelos rápidamente incluso con grandes cantidades de datos.

### Caso Practico: Clasificación de dígitos escritos a mano
Para demostrar el uso de Adam, desarrollaremos una red neuronal para clasificar imágenes de dígitos escritos a mano del conjunto de datos MNIST. MNIST contiene 70,000 imágenes en escala de grises de 28x28 píxeles de dígitos manuscritos de 0 a 9.

El objetivo es entrenar un modelo que reciba las imágenes y prediga el dígito correcto.
