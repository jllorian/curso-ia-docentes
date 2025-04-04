---
layout: "two-cols-header"
title: "Riesgos y sesgos"
description: "Explorando los riesgos y sesgos en la generación de respuestas"
---
# **Explicabilidad**
versus la *interpretabilidad* y el **sesgo** y la **varianza**

> Un sistema con **[explicabilidad](https://www.ibm.com/es-es/cloud/learn/explainable-ai)** tiene herramientas que permiten comprender cómo se han alcanzado los resultados generados.

::left::

```mermaid {theme: 'default', alt: 'Construcción de Modelo Fundacional', scale: 0.60}
  flowchart TD
  A[Recolección de Datos]:::blue --> B{{Identificación de Patrones}}:::cyan
  B --> C[Creación de Modelo Fundacional]:::green
  C --> D[Introducción de Nueva Información]:::lime
  D --> E[Generación de Contenido]:::yellow

  classDef blue fill:#4285F4,color:white
  classDef cyan fill:#00BCD4,color:white
  classDef green fill:#4CAF50,color:white
  classDef lime fill:#8BC34A,color:white
  classDef yellow fill:#FFEB3B,color:black
```

::right::



<!--
# Datos entrenamiento desconocidos, así como proceso de selección de datos.
    Esto implica potencial existencia de sesgos entre clases.
# Proceso de entrenamiento desconocido
    No sabemos cómo han distribuido los pesos, que *features* han utilizado, etc.
# Proceso de inferencia opaco
    No sabemos cómo se efectua el proceso de inferencia, ni los patrones que se seleccionan en las redes neuronales del modelo.

La inferencia forma parte de un proceso en el que la IA analiza datos que no ha visto antes. Pero
se puede dar el caso de que la IA sí haya visto antes los datos que le mostramos. Estaríamos ante
una potencial situación de overfitting, donde el modelo ha aprendido a memorizar los datos de entrenamiento en lugar de generalizar patrones.
Esto puede llevar a resultados inesperados o erróneos.
-->

---
layout: "image-left"
image:
---
# Privacidad y seguridad

---
layout:
---
# Retos en la IA y las dimensiones de la IA responsable

---
layout: "center"
class: "text-center"
---
# Retrieval-Augmented Generation (RAG)
Generación a partir de información externa

**[Enriquezcamos]{style="color: rgb(44, 145, 179);"}** la ventana de contexto.

<div class="video-container">
    <Youtube id="T-D1OfcDW1M"/>
</div>

<style>
.video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 */
    height: 0;
    overflow: hidden;
    max-width: 100%;
}
.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
.video-container .youtube-embed {
    width: 100%;
    height: 100%;
}
.video-container .youtube-embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
</style>