---
theme: seriph
# background image credit: moren hsu https://unsplash.com/@moren
background: https://cover.sli.dev
title: Introducción a la Inteligencia Artificial para Docentes
info: |
  ## Intruducción a la Inteligencia Artificial para Docentes
  Presentación desarrollada por [José María Llorián Álvarez](https://www.linkedin.com/in/llorian) para la formación en IA impartida en el IES Carmen y Severo Ochoa el 18 del 2 de 2025.

  Formación propuesta por el Centro del Profesorado y de Recursos de Avilés — Occidente.
author: José María Llorián Álvarez

class: text-center
css: ./style.css
drawings:
  presenterOnly: true
  persist: false

transition: slide-left
mdc: true
---

# Introducción a la Inteligencia Artificial para Docentes

IES Carmen y Severo Ochoa

18 de febrero de 2025

<!-- Dar las gracias a todos los participantes por unirse.
# Antes de comenzar:

  - ¿Han traído sus portátiles?
  - Que los enciendan ya que los vamos a usar
  - No se preocupen por tomar notas que les voy a pasar todos los materiales.
 -->
---
transition: fade-out
---

# José María Llorián Álvarez

¿Quién soy y qué hago aquí?

<br>
<img border="rounded" src="https://media1.tenor.com/m/4ho5rKl9UtYAAAAd/dog-doggo.gif" alt="meme dog maths" style="width: 150px; float: left; margin-right: 15px;">
<br>
<br>
<br>
<br>
<br>

<div v-click> <img src="./recursos/foto-profesional.jpg" alt="Foto profesional" style="border-radius: 75%; width: 80px; float: right;"> </div>


👋 ¡Hola! Soy un apasionado del **[aprendizaje]{style="color: rgb(44, 145, 179);"}** y la innovación.
He liderado el desarrollo de sistemas de búsqueda potenciados por IA y chatbots, creando experiencias que combinan tecnología y <span v-mark.circle.orange>creatividad.</span>

<br>
<br>
<div v-click="2">
  📍 Navia, Asturias, España  
  ✉️ josellorian@gmail.com | <a href="https://www.linkedin.com/in/llorian">LinkedIn</a>
</div>

<div class="slide-counter">
  <SlideCurrentNo />/<SlidesTotal />
</div>

---
transition: slide-up
---

# Nuestros objetivos para hoy:

<ul>
  <li v-click="1">🤓 <span v-mark.red="4"><b>Saber</b></span> qué es la IA a nivel general y el *GenAI* a nivel particular.</li>
  <li v-click="2">🧠 <span v-mark.red="5"><b>Aprender</b></span> a usar la IA de manera responsable.</li>
  <li v-click="3">🤖 <span v-mark.red="6"><b>Usar</b></span> la IA para elaborar adaptaciones para la atención a la diversidad, refinar material y generar documentos dentro un marco de criterios de evaluación y plan formativo.</li>
</ul>
<br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-up
---

# La relevancia de la IA en educación


<img
  v-click="[1,2]"
  src="./recursos/aprendizaje-personalizado.svg"
  alt="Aprendizaje personalizado"
  class="overlay-item"
/>
<img
  v-click="[2,3]"
  src="./recursos/automatizacion-tareas.svg"
  alt="Automatización de tareas"
  class="overlay-item"
/>
<img
  v-click="3"
  src="./recursos/inclusion-educativa.svg"
  alt="Inclusión educativa"
  class="overlay-item"
/>


<style>

.overlay-item {
  position: fixed;
  top: 50%;
  left: 50%;
  transform-origin: center;
  transform: translate(-50%, -50%);
  max-width: 90%;
  max-height: 80%;
  object-fit: contain;
  opacity: 0.9;
  transition: transform 0.3s ease, opacity 0.3s ease;
}

.overlay-item:hover {
  transform: translate(-50%, -50%) scale(1.1);
  opacity: 1;
}

.slidev-vclick-target {
  transition: all 800ms ease;
}

.slidev-vcklick-hidden {
  opacity: 0;
  transform: scale(0.8);
  pointer-events: none;
}

h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.slidev-layout {
  background-color: #121212 !important;
  color: #ffffff !important;
}
</style>
<!-- Esta slide muestra las ventajas del uso de la IA en educación. Pero de todo tipo de IA, como se verá más adelante, esta formación se enfoca en el uso de IA generativa.
 -->