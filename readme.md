# Repositorio template para el taller en RIIAA 2021: "Introducción a las redes, su predicción usando redes neuronales".

## La presentación consistira de las siguiente partes:

1. IntroduccionGraficasRedes.pdf (en el folder presentation). Se introducen conceptos básicos de redes-grafos
2. 1_Redes_ModelosEpi.ipynb (en el folder notebooks). Donde se complementa el capítulo anterior con el módulo Networkx y se introduce a los modelos epidemiológicos en redes de contactos y su simulación
3. 2_RNN.ipynb  (en el folder notebooks). Se presentan los conceptos básicos de redes neuronales recurrentes (RNN), en particular las redes LSTM, y se comentan varios ejemplos. Finalmente se menciona uno de los usos de las predicciones obtenidas con RNN.

## Instrucciones para estudiantes

En el taller utilizaremos Colab y para las redes neuronales utilizaremos pytorch.

Cosas para preparar
* Una laptop.
* Este repositorio de GitHub clonado y actualizado antes del taller.
* Un sentido aventurero en los datos.
* Un ambiente Python 3.7+ con Anaconda (ver opciones 1 y 2 abajo).

En el taller, parte del material está en *notebooks* de Jupyter con  código ejecutable.  Los *notebooks* se pueden crear y ejecutar en la nube vía Google Colab.

### Google Colab
[Colab](https://colab.research.google.com) es un servicio de Google para ejecutar *notebooks* en la nube. Provee ambientes de Python 2 y 3 con CPUs, GPUs y TPUs. ¡Y es gratis! Solo necesitas tener una cuenta de Google o crear una.

Recomendamos que elijas un ambiente con Python 3 y GPU. Para activarlo:
* Abre el menú `Entorno de ejecución`
* Elige la opción `Restablecer todos los entornos de ejecución...` .
* Vuelve a abrir `Entorno de ejecución`
* Elige `Cambiar tipo de entorno de ejecución`
* Selecciona Python 3 como `Tipo de ejecución` y GPU de la lista de `Acelerador por hardware`

La siguiente captura de pantalla ilustra este proceso.

![](media/escoge_acelerador.png)

En [Colab](https://colab.research.google.com) puedes crear un nuevo *notebook*, subir uno existente desde tu computadora o importarlo de Google Drive o GitHub.

