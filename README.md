# TorToiSe 🐢
Si bien hay varias opciones para realizar TTS, actualmente (29/10/2022) hay pocas alternativas de código abierto que hagan generaciones de calidad y menos aún que te permitan replicar voces. Es por esto que quisimos hacer este repositorio para facilitar el uso de de TorToiSe, que permite exactamente esto.

De momento, no hemos encontrado mejor alternativa que esta. No obstante, pese a que no hemos hecho muchas pruebas y tampoco hemos profundizado en los descubrimientos de la comunidad, podemos notar a lo mínimo las siguientes 4 falencias:
- Sólo trabaja con texto y audio en inglés.
- El límite en la extensión del texto a ser leido es relativamente bajo.
- Tarda una cantidad significativa de tiempo en generar los audios.
- Incluso la mejor calidad está lejos de ser perfecta.

Cabe destacar que estos puntos son entendibles por el hecho de que este modelo fue entrenado por sólo una persona y con un dataset limitado. Por esta razón y viendo la rapidez con la que evoluciona el área, es de esperar que en pocos meses empecemos a ver modelos significativamente mejores.

Para facilitar el entendimiento del uso del modelo, incluimos un ejemplo usando la voz de Steve Jobs en este video: https://youtu.be/oeqPrUmVz-o
Las muestras usadas (libres de audio y anomalías) se pueden hallar en la carpeta "Voz de ejemplo" y también dejamos algunos ejemplos de textos en "Textos de ejemplo". De estos últimos, usamos el "Texto 3.txt" para el "Resultado de ejemplo.wav" (lo ejecutamos con la máxima calidad y tardó 35 minutos con 34 segundos).

Por lo demás, el notebook es bastante claro, así que no debería haber problemas con su uso. Eso sí, en caso de dudas o comentarios, siéntanse libres de realizar issues en este repositorio 😉👍
