# Análisis de Pisada para Corredores con PDI

## Descripción del Proyecto
Este proyecto tiene como objetivo identificar el tipo de pisada en corredores (pronadora, supinadora o neutra) mediante técnicas de procesamiento digital de imágenes aplicadas a huellas plantares. La correcta identificación del tipo de pisada permite elegir el calzado adecuado y mejorar la técnica de carrera, promoviendo así un mejor rendimiento y la prevención de lesiones.

## Integrantes
- Tomás Lopera Duque
- Pedro Sierra Arbeláez

## Metodología
El análisis de huellas plantares se realiza utilizando las siguientes técnicas de procesamiento de imágenes:

1. **Preprocesamiento**: Aplicación de un filtro gaussiano, conversión a escala de grises.
2. **Detección de Bordes**: Implementación de algoritmos como Sobel, Laplace y Canny, siendo Sobel el más efectivo en nuestras pruebas.
3. **Segmentación**: Uso del Umbral de Otsu para separar la huella del fondo, aunque no se aplicó a todas las imágenes debido a variaciones en los resultados.
4. **Morfología Matemática**: Operaciones de dilatación y erosión para refinar la forma de la huella y eliminar detalles menores.

## Resultados
El proyecto incluye análisis detallados de imágenes de huellas en diferentes superficies (arena y moldes), donde se evalúa la efectividad de los métodos aplicados y se proporciona información sobre el tipo de pisada de cada muestra.

## Instalación
Para ejecutar el proyecto, sigue estos pasos:

1. Clona este repositorio:
```bash
git clone 

1. Instala las dependencias necesarias:

pip install -r requirements.txt
