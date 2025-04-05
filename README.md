# Señales electromiográficas EMG
## Descripción 
La electromiografía de superficie (sEMG) es una técnica no invasiva que permite registrar la actividad eléctrica generada por los músculos durante la contracción voluntaria. Esta señal refleja la activación de unidades motoras y puede ser utilizada para evaluar el comportamiento muscular bajo diferentes condiciones, como la aparición de fatiga.
En esta práctica se busca evaluar experimentalmente el fenómeno de la fatiga muscular mediante el registro y análisis de señales EMG en el músculo del antebrazo, durante una contracción repetitiva y constante de 30 segundos. A lo largo de este tiempo, se observarán variaciones en la amplitud y el contenido frecuencial de la señal, características típicas del proceso de fatiga.
Para poder analizar la señal EMG, se implementa el uso de filtros digitales para eliminar el ruido. Además, se utiliza aventanamiento para dividir la señal en segmentos temporales sobre los que se aplica el análisis, permitiendo observar la evolución temporal de sus características. Finalmente, se realiza un análisis espectral mediante la Transformada Rápida de Fourier (FFT), con el fin de estudiar cómo cambia el contenido en frecuencia a lo largo del tiempo, lo cual puede indicar si hay fatiga muscular.

## Captura de la señal 
Para realizar la captura de la señal de EMG se realizó el siguiente procedimiento:
Utilizamos una Tarjeta De Adquisición De Datos DAQ NI el cual permite el registro de datos obtenidos a traves del módulo de electromiografía, se utilizó una frecuencia de muestreo de 1000 Hz debido a que la frecuencia máxima del EMG va hasta los 500 Hz y siguendo el criterio de Nyquist la frecuencia de muestreo debe ser el doble a la frecuencia máxima 




se utilizó un módulo de electromiografia AD8832 el cual captura y filtra la señal de los músculos 
 
