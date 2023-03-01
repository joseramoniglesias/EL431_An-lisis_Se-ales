# EL431_Analisis_Senales
## Objetivos de la asignatura
## Conocer y manejar métodos de análisis generales como lo son las Transformadas de Fourier y Laplace.
## Reconocer las características de funcionamiento, análisis y diseñoo de sistemas con elementos no lineales que no varían en el tiempo.
## Introducir el estudio y manejo de señales dentro del conocimiento de sistemas de transmisión de información.
## Contenido básico
## 1. Conceptos básicos
## a) Señales y sistemas. Tipos de señales. Tipos de sistemas. Proopiedades de los sistemas. El tiempo como variable continua. El tiempo como variable discreta.
## b) Sistemas LTI discretos y continuos. Suma e integral de convolución. Propiedades de los sistemas LTI.
## 2. Modelos de entrada/salida
## a) Ecuaciones diferenciales y de diferencia. Sistemas LTI causales descritos por ecuaciones diferenciales y de diferencias.
## 3. Análisis de señales
## a) Representación de señales periódicas continuas y discretas en series de Fourier. Propiedades de la serie continua de Fourier. Propiedades de la serie discreta de Fourier. Relación de Parseval.
## b) Transformada de Fourier de señales continuas y discretas. Propiedades y parejas de transformadas. Transformada inversa de Fourier.
## c) Solución de sistemas caracterizados por ecuaciones diferenciales lineales con coeficientes constantes mediante la transformada de Fourier.
## 4. Análisis de sistemas dinámicos
## a) Transformada Z y Transformada de Laplace. Propiedades y parejas de transformadas. Transformadas inversas Z y de Laplace. Transformadas inversas por expansión en fracciones parciales. Solución de E.D. lineales mediante transformadas (discreto y continuo).
## b) Respuesta de entrada cero y de estado cero. Respuesta transitoria y estacionaria. Respuesta al escalón y al impulso. Funciones de transferencia. El caso de primer orden (discreto y continuo). El caso de segundo orden (discreto y continuo). Estabilidad de sistemas LTI continuos y discretos.
## c) Sistemas realimentados simples. Tipo de sistema y error de estado estacionario. Criterio de estabilidad de Routh-Hurwitz. 

## Curso de Analisis de Señaes 2023-1

## Planificación del Curso por Días

## Semana 1
### Clase 01 Vi 17-Feb-2023:
* Presentación de la materia: motivación, objetivos, metodología, evaluación.
* Señales continuas y discretas [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_Se%C3%B1ales_continuasydiscretas.pdf) 
### Clase 02 Sab 18-Feb-2023:
* Transformaciones de la variable independiente [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_Senales_Tiempo_Continuo.pdf)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_IntroNumpy_SyS.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Par_Impar.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Se%C3%B1ales_Periodicas_Aperiodicas.ipynb)

##  Semana 2
### Clase 03 Vie 24-Feb-2023:
* Señales exponenciales y sinusoidales [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_SenaleExponencialesSinusoidales.pptx)
### Clase 04 Sab 25-Feb-2023:
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Sistemas_Ideales.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Se%C3%B1ales_Exponenciales_Sinusoidales.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Se%C3%B1ales_estandar.ipynb)

## Semana 3
### Clase 05 Vie 03-Mar-2023:
* Sistemas LTI [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_SistemasLTI.pdf)
* Espacios vectoriales [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_Espacios%20Vectoriales.pdf)
* taller en clase [PDF](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS_Taller%20Se%C3%B1ales%20Y%20sistemas.pdf)
### Clase 06 Sab 04-Mar-2023:
* Representación de Señales [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Presentaciones/AS01_Representacion%20de%20senales.pdf)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS_Lineales_EspaciosVectoriales.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Sistemas_LTI_Convolucion.ipynb)
* Trabajo en clase [Python](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap01_Introducci%C3%B3n/Pit%C3%B3n/AS01_Convolucion_Discreta.ipynb)

## Semana 4
### Clase 7 Vie 10-Mar 2023:
* Introducción al modelamiento de sistemas, Sistemas LIT causales descritos por ecuaciones diferenciales y de diferencia [PPTX](https://github.com/joseramoniglesias/EL431_Analisis_Senales/blob/main/Clases/Cap02_Introducci%C3%B3n%20a%20los%20sistemas%20lineales%20continuos%20y%20discretos/Presentaciones/AS02_ModelamientoLTICausales.pdf)
* Trabajo en clase [Python]
### Clase 8 Sáb 11-Mar 2023:
* Taller y ejercicios en clase [PDF]

## Semana 5
### Clase 9 Vié  17-Mar 2023:
* Definición de las Series de Fourier en Tiempo Continuo y Discreto [PPTX]
* Trabajo en clase [Python]
### Clase 10 Sab 18-Mar 2023:
* Taller y ejercicios en clase [PDF]

## Semana 6
### Clase 11 Vie 24-Mar 2023:
* Primer Parcial.
### Clase 12 Sab 25-Mar-2023:
* Primer Parcial.

## Semana 7
### Clase 13 Vie 31-Abr 2023:
* Transformada continua de Fourier, Transformada discreta de Fourier. Muestreo en el dominio de la frecuencia y la reconstrucción de señales en el tiempo discreto.
* La transformada discreta de Fourier (DFT)
* Trabajo en clase [Python]

### Clase 14 Sab 1-Abr 2023:
* Taller y ejercicios en clase [PDF] 

## Semana 8
### Clase 15 Vier 14-Abr 2023:
* Propiedades de la transformada de Fourier I
* Trabajo en clase [Python]

### Clase 16 Sab 15-Abr 2023:
* Taller y ejercicios en clase [PDF]

## Semana 9
### Clase 17 Vie 21-Abr 2023:
* Propiedades de la transformada de Fourier II. Representación de la magnitud-fase de la transformada de Fourier. Representación de la magnitud-fase de la respuesta en frecuencia de sistemas LTI. [PPTX]
* Trabajo en clase [Python]

### Clase 18 Sab 22-Abr 2023:
* Taller y ejercicios en clase [PDF]
 
## Semana 10
### Clase 19 Vie 28-Abr 2023:
* Transformadas de Laplace y Z, region de convergencia (ROC), propiedades de la ROC, transformadas inversas [PPTX]
* Trabajo en clase [Python]

### Clase 20 Sab. 29-Abr-2023:
* Taller y ejercicios en clase [PDF]

## Semana 11
### Clase 21 Vie. 5-Mayo-2023:
* Segundo Parcial.
### Clase 22 Sab. 6-Mayo-2023:
* Segundo Parcial.

## Semana 12
### Clase 23 Vie. 12. Mayo-2023:
* Propiedades de las transformadas  de Laplace y Z, análisis de SLIT usando transformadas, transformadas unilaterales, solución de ecuaciones diferenciales y de diferencia. [PPTX]
* Trabajo en clase [Python]
### Clase 24 Sab. 13-Mayo-2023:
* Taller y ejercicios en clase [PDF]

## Semana 13
### Clase 25 Vie. 19-Mayo-2023:
* Introducción al análisis de sistemas dinámicos lineales, sistemas de primer y segundo orden. [PPTX]
* Trabajo en clase [Python]

### Clase 26 Sab. 20-Mayo-2023:
* Taller y ejercicios en clase [PDF]

## Semana 14
### Clase 27 Vie. 26-Mayo-2023
* Muestreo [PPTX]
* Trabajo en clase [Python]

### Clase 28 Sab. 27-Mayo-20232:
* Taller y ejercicios en clase [PDF]

## Semana 15
### Clase 29 Vie. 2-Jun-2023:
* Avances Presentaciones de Proyecto Final
### Clase 30 Sab. 3-jun-2023:
* Avances Presentaciones de Proyecto Final

## Semana 16
### Clase 31 Vie. 9-Jun-2023:
* Presentación Proyecto Final

### Clase 32 Sab. 10-Jun-2023:
* Presentación Proyecto Final
_______________________________________________________

Actualizado el 19-01-2023

