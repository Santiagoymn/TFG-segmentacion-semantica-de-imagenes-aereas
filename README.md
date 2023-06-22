# TFG-segmentacion-semantica-de-imagenes-aereas

En este repositorio se encuentran cuatro carpetas distintas, en ellas se encuentra lo siguiente:

## Entrenamientos
En esta carpeta se encuentran los distintos ficheros Jupyter con los que se han llevado a cabo los distintos entrenamiento, por ello, existen cuatro ficheros Jupyter siendo estos:

#### TFG - Dataset Rural con ResNetUNet.ipynb. Se trata del fichero en donde se encuentra el código desarrollado para llevar a cabo el entrenamiento del dataset rural utilizando como arquitectura ResNetUNet.
#### TFG - Dataset Rural con DeepLabV3.ipynb. Se trata del fichero en donde se encuentra el código desarrollado para llevar a cabo el entrenamiento del dataset rural utilizando como arquitectura DeepLabV3.
#### TFG - Dataset Urbano con ResNetUNet.ipynb. Se trata del fichero en donde se encuentra el código desarrollado para llevar a cabo el entrenamiento del dataset urbano utilizando como arquitectura ResNetUNet.
#### TFG - Dataset Urbano con DeepLabV3.ipynb. Se trata del fichero en donde se encuentra el código desarrollado para llevar a cabo el entrenamiento del dataset urbano utilizando como arquitectura DeepLabV3.

## Data augmentation
En esta carpeta se encuentra un fichero Jupyter llamado:

#### TFG - Flip para data Augmentation en dataset urbano.ipynb. Se trata del fichero Jupyter que contiene el pequeño script con el que se ha hecho data augmentation a las imágenes del dataset urbano.

## Comparativas
En esta carpeta se observará como existen dos fichero Jupiter, los cuales han sido creados para llevar a cabo distintas comparativas acerca de los valores proporcionados por los entrenamientos. Los ficheros que se encuentran en este carpeta se llaman:

#### TFG - Gráficas comparativas de IOU.ipynb. Este fichero contine el código y los valores de la métrica IOU para visualizar en forma de gráficas los distintos valores para las clases y de forma global en las arquitecturas ResNetUNet y DeepLabV3 tanto para los primeros entrenamientos, como para los entrenamientos definitivos.
#### TFG - Tabla comparativa de los valores de las arquitecturas.ipynb. Contiene el código que muestra en uns misma tabla los valores obtenidos para las distintas métricas tanto para la arquitectura ResNetUNet como para DeepLabV3. Para ello, se cargan desde los ficheros CSV en donde han sido almacenados los valores para cada arquitectura

## Transfer learning
En esta carpeta se encuentran dos ficheros Jupiter llamados:

#### TFG - Transfer learning urbano.ipynb. Se encuentra el código para ejecutar el transfer learning para mejorar las prediciones de las imágenes urbanas. Hay dos posibles modelos en los que partir este transfer learning, uno de ellos es con todas las clases del dataset rural y la otra posibilidad es partiendo del modelo rural pero con las clases que no se encuentran en el dataset urbano puestas como la clase clutter. En el propio fichero se encuentran ambas posibles opciones a elegir
#### TFG - Transfer learning urbano y rural.ipynb. Se encuentra el código para ejecutar el transfer learning para mejorar las prediciones tanto de las imágenes urbanas como las rurales. Hay dos posibles modelos en los que partir este transfer learning, uno de ellos es con todas las clases del dataset rural y la otra posibilidad es partiendo del modelo rural pero con las clases que no se encuentran en el dataset urbano puestas como la clase clutter. En el propio fichero se encuentran ambas posibles opciones a elegir


