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

<div class= "text-container">
    <p v-click="1" class="text-container_traning_data">
        Datos de entrenamiento <span style="color: rgb(44, 145, 179);">desconocidos</span>
    </p>
    <p v-click="2" class="text-container_traning">
        Proceso de entrenamiento <span style="color: rgb(44, 145, 179);">desconocidos</span>
    </p>
    <p v-click="3" class="text-container_inference">
        Proceso de inferencia <span style="color: rgb(44, 145, 179);">opaco</span>
    </p>
</div>
<br>
<div v-click="2" class="image-container">
    <img src="../recursos/bias-variance.png" alt="Riesgos y sesgos">
</div>


<!--
# Datos entrenamiento desconocidos, así como proceso de selección de datos.
    Esto implica potencial existencia de sesgos entre clases.
# Proceso de entrenamiento desconocido
    No sabemos cómo han distribuido los pesos, que *features* han utilizado, etc.
# Proceso de inferencia opaco
    No sabemos cómo se efectúa el proceso de inferencia, ni los patrones que se seleccionan en las redes neuronales del modelo.

La inferencia forma parte de un proceso en el que la IA analiza datos que no ha visto antes. Pero
se puede dar el caso de que la IA sí haya visto antes los datos que le mostramos. Estaríamos ante
una potencial situación de *overfitting*, donde el modelo ha aprendido a memorizar los datos de entrenamiento en lugar de generalizar patrones.
Esto puede llevar a resultados inesperados o erróneos.

Varianza ≈ ruido en los datos
Sesgo ≈ error sistemático en los datos

**Interpretability** is a feature of model transparency. Interpretability is the degree to which a human can understand the cause of a decision.
**Interpretability** is the access into a system so that a human can interpret the model’s output based on the weights and features.


**Explainability** is how to take an ML model and explain the behavior in human terms. With complex models (for example, black boxes), 
you cannot fully understand how and why the inner mechanics impact the prediction. However, through model agnostic methods (for example, partial dependence plots, 
SHAP dependence plots, or surrogate models) you can discover meaning between input data attributions and model outputs. With that understanding, 
you can explain the nature and behavior of the AI/ML model.

-->

---
layout: "image-left"
image:
---
# Privacidad y seguridad

---
layout: "two-cols"
---
# Retos en la IA y las dimensiones de la IA responsable

::right::

<div class="image-container">
    <img src="https://explore.skillbuilder.aws/files/a/w/aws_prod1_docebosaas_com/1743804000/InIXiZi6tTNf46TuRw14HQ/tincan/1795780_1731946240_o_1id00k8mrapu1j8e1un5ctcr6nb_zip/assets/Responsible%20AI%20core%20dimensions.png" alt="Retos en la IA y las dimensiones de la IA responsable">
</div>

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