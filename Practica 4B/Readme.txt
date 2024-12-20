Practica 4B: En esta practica se realiza un análisis de señales moduladas por PM.

En el punto 1 se analizaron 4 casos, 2 para modulación de banda estrecha y 2 para modulación de banda ancha. Para ambos casos se analizó la señal modulada en el osciloscopio identificando el comportamiento de la misma y de su envolvente, con esta medida se calculó el valor de la potencia de la envolvente. Luego de esto se analizaron las señales moduladas en el espectrómetro midiendo su potencia y su ancho de banda.
Como ejemplo, para uno de los casos (KpAm=0.05), la evidencia de medida es la siguiente: 
https://github.com/Sebaskr6/GNURADIO_LABCOMUIS_2024_2_B1B_G2/blob/main/Practica%204B/P1/KpAm=0.05%20Espectrometro.jpg?raw=true  
https://github.com/Sebaskr6/GNURADIO_LABCOMUIS_2024_2_B1B_G2/blob/main/Practica%204B/P1/KpAm=0.05%20Osciloscopio.jpg?raw=true

En el punto 2 se realizo el análisis de una señal modulada en PM y sus coeficientes de Bessel, en este punto debíamos hacer la medida para dos casos, en donde KpAm o B sea mayor que 10, Se escogieron los casos B=12,B=13.
Para el caso de B=KpAm=12, como ejemplo para anexar a este github, las medidas fueron las siguientes:
https://github.com/Sebaskr6/GNURADIO_LABCOMUIS_2024_2_B1B_G2/blob/main/Practica%204B/P2/Potencia0-5KpAm=12.jpg?raw=true  
https://github.com/Sebaskr6/GNURADIO_LABCOMUIS_2024_2_B1B_G2/blob/main/Practica%204B/P2/Potencia4-9KpAm=12.jpg?raw=true

Un resumen de lo realizado fue, calcular los coeficientes de bessel para B=13 y B=12 con Matlab, se añadieron estos datos a la tabla, luego se ajustó el coeficiente en el PC para B=13 y B=12 , y se observo la señal en el Espectrometro. Teniendo en cuenta que los coeficientes de Bessel estan en las frecuencias Fc+nFm, se midieron los picos de potencia en estas frecuencias hasta n=9 (Se puede evidenciar en las imagenes en el directorio P2) y se añadieron estos picos en dBm a la tabla, la tabla hizo el resto. Cabe aclarar que para cuando el coeficiente teorico es negativo, ajustamos el signo del coeficiente practico, pues al estar despejado de la formula dada en este punto, puede ser negativo o positivo. Tambien se ajustó la formula para calcular la potencia que estaba en la tabla, pues faltaba multiplicar por un 2. Es importante aclarar que la tabla está en: https://docs.google.com/spreadsheets/d/1uUCnBHitW6KdjmyM7DuH9b-YKht6OC3gM7rC0kKbwDk/edit?usp=sharing

Cabe aclarar que el análisis más profundo de esta practica se encuentra en el Moodle, y las evidencias completas se encuentran en cada carpeta de este directorio.
