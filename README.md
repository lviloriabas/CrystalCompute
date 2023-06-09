# CrystalCompute
# Programa de cuantificación de granos en microscopías ópticas de metales

Este programa está escrito en Jupyter Notebooks y está diseñado para realizar la cuantificación de granos en imágenes de microscopías ópticas de metales. Utiliza técnicas de procesamiento de imágenes en Python para identificar y contar los granos presentes en las muestras.

![Ejemplo de resultados](ejemplo.png)

## Librerías utilizadas
El programa hace uso de las siguientes librerías de Python:

1. **Numpy**: Se utiliza para el manejo eficiente de matrices y cálculos numéricos.
2. **OpenCV**: Proporciona herramientas para el procesamiento de imágenes, incluyendo filtrado, segmentación y detección de bordes.
3. **clEsperanto**: Es una biblioteca de Python para procesamiento de imágenes basada en OpenCL, que permite ejecutar algoritmos en GPU para acelerar el procesamiento.
4. **scikit-image**: Proporciona una amplia variedad de algoritmos para el procesamiento de imágenes, incluyendo segmentación y medición de objetos.
5. **Matplotlib**: Se utiliza para generar visualizaciones de los resultados obtenidos, como gráficos y diagramas.

## Funcionalidades principales

El programa ofrece las siguientes funcionalidades principales:

1. **Carga de imágenes**: Permite cargar imágenes de microscopías ópticas de metales en formato de imagen común, como JPEG o PNG.
2. **Preprocesamiento de imágenes**: Aplica técnicas de preprocesamiento a las imágenes cargadas, como filtrado y mejora del contraste, para mejorar la calidad de la imagen y facilitar la detección de granos.
3. **Segmentación de granos**: Utiliza algoritmos de segmentación para separar los granos de fondo y otros objetos en la imagen. Esto permite identificar y aislar los granos de interés.
4. **Conteo de granos**: Realiza el conteo de los granos presentes en la imagen segmentada, utilizando técnicas de análisis de objetos.
5. **Visualización de resultados**: Genera visualizaciones de los resultados obtenidos, como gráficos de distribución de tamaño de los granos o imágenes con los granos detectados resaltados.

## Requisitos del sistema

El programa requiere tener instalado Jupyter Notebooks, Python 3.x y las siguientes librerías:

- Numpy
- OpenCV
- clEsperanto
- scikit-image
- Matplotlib

## Uso del programa

1. Asegúrese de tener instaladas todas las dependencias mencionadas anteriormente.
2. Ejecute el Jupyter Notebooks en su entorno de desarrollo de Python.
3. Cargue una imagen de microscopía óptica de metal en el formato adecuado.
4. Cambie las variables de configuración a su gusto (img, it_er, it_dil y M)
5. Visualice y analice los resultados obtenidos utilizando las celdas de código y salida de Jupyter Notebooks.
6. Repita los pasos anteriores para otras imágenes si es necesario o para obtener una correcta segmentación de los granos.
