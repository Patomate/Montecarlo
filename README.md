# Montecarlo
En este repositorio guardare todo lo relacionado con mi proyecto de montecarlo de Ast. Computacional II 
Este documento ReadMe proporciona información sobre un código de modelado estelar que calcula y analiza las características de estrellas, incluyendo su masa, tiempo de vida, tipo de remanente, edades y fracciones. El código se ha desarrollado utilizando Python y las bibliotecas NumPy y Matplotlib.
## Resumen del Código

El código se divide en varias secciones, cada una de las cuales cumple una función específica. A continuación, se presenta un resumen de cada sección:

## Generación de Masas Aleatorias:
1. Genera masas aleatorias de estrellas en el rango de 0.08 a 100 masas solares.
2. Asigna exponentes de acuerdo con el rango de masas.
3. Calcula la variable y a partir de las masas y los exponentes.
4. Grafica un diagrama de dispersión log-log de masa estelar vs. y.

## Generación de Edades:
1. Crea una distribución de edades de estrellas a lo largo del tiempo (SFR constante, poco realista pero para simplicidad).
2. Grafica un histograma de edades de nacimiento de las estrellas.

## Cálculo de la Masa Final:
1. Calcula el tiempo de vida (main sequence) de cada estrella según su masa.
2. Clasifica las estrellas en diferentes tipos de remanentes (main sequence, white dwarf, neutron star, black hole) según su tiempo de vida y masa.
3. Grafica histogramas de masas finales de los diferentes tipos de remanentes.

## Análisis de Edades de Remanentes:
Grafica histogramas de edades de los diferentes tipos de remanentes.

## Fracciones de Remanentes:
1. Calcula las fracciones de estrellas en cada tipo de remanente.
2. Imprime las fracciones y la suma total.

## Uso del Código

Para utilizar este código, asegúrate de tener las bibliotecas NumPy y Matplotlib instaladas en tu entorno de Python. Luego, simplemente ejecuta el código en tu entorno de desarrollo preferido. El código generará visualizaciones de datos y proporcionará información sobre las fracciones de diferentes tipos de remanentes estelares.

Ten en cuenta que este código es un modelo simplificado de estrellas y puede no representar con precisión la realidad. Además, algunos valores y funciones son proporcionados por profesores o papers, lo que implica ciertas limitaciones.

Si deseas ajustar parámetros o personalizar el código para adaptarlo a tus necesidades, puedes modificar las secciones correspondientes del código.
Contribuciones y Agradecimientos

Este código fue desarrollado como parte de un proyecto de modelado estelar y se basa en conocimientos y datos proporcionados por profesores y publicaciones científicas. Se agradecen las contribuciones y la colaboración de la comunidad científica en la creación de este código.
Contacto

Si tienes preguntas o comentarios sobre el código o su uso, no dudes en ponerte en contacto con el desarrollador del código o el equipo de investigación detrás de él.

¡Disfruta utilizando este código de modelado estelar!
