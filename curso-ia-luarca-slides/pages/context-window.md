---
class: px-20
---
# *GenAI* ¿Cómo funciona?

<MessageBox 
  type="system" 
  title="Mensaje del sistema" 
  icon="../recursos/icon/systemIcon.svg"
  :click-step="1"
>
  Eres un <span v-mark.underline.orange=2>experto pedagogo</span> en lengua castellana para estudiantes de ESO españoles. <span v-mark.underline.orange=3>Diseña y expone tres niveles de andamiaje para la siguiente tarea formativa</span>:
</MessageBox>

<MessageBox 
  type="user" 
  title="Mensaje del usuario" 
  icon="../recursos/icon/userIcon.svg" 
  :click-step="5"
>
  "Periodistas por un día"
  Los estudiantes asumen el rol de periodistas para crear un reportaje sobre las variedades lingüísticas de su ...
</MessageBox>

<MessageBox 
  type="ai" 
  title="Mensaje de la IA" 
  icon="../recursos/icon/iaIcon.svg" scale
  :click-step="7"
  is-code
>
   Tablas de sustitución para estructurar oraciones: "El titular debe ser ____"...
</MessageBox>

<Arrow v-click="[4,5]" x1="850" y1="70" x2="780" y2="110" color="#2196F3" width="2" arrowSize="1" two-way: false />
<p v-click="[4,5]" class="absolute top-8 right-12 opacity-50 transform -rotate-10">ponemos el modelo en un estado</p>

<Arrow v-click="[6,7]" x1="111" y1="270" x2="210" y2="300" color="#4CAF50" width="2" arrowSize="1" two-way: false />
<p v-click="[6,7]" class="absolute left-10 bottom-65 opacity-50 transform -rotate-25">le damos la tarea</p>

<!--
- Un modelo de IA generativa por tanto tiene un "modo de pensar", que se ha desarrollado en base a los datos con los que ha sido entrenado. En la ventana de contexto, nosotros le damos nueva información, que en teoría no ha visto antes, para que haga el proceso de inferencia.
- En la ventana hay un system message que sitúa al modelo en un estado, como explicamos antes, los FMs son capaces de adaptarse automáticamente a nuevas tareas o contextos. En nuestro caso queremos que ese estado este ligado al mundo de la docencia. Podemos indicarle que es un profesor de enseñanza secundaria o un especialista en pedagogía de cierta material. Y queremos que en su estado haga cierta tarea: digamos elaborar andamiaje para los materiales que le demos.
- Ese system message se introduce delante del user message, lo que coloquialmente llamamos prompt, cada vez que lancemos un prompt, ese system message se añade delante.
- Las respuestas que infiera la IA, también se añadirán a la ventana de contexto, asociadas al system message, y user message que las generó, creando un historial en al conversación.

Es importante ser conscientes del historial que estamos construyendo al interactuar con la IA, por dos razones:
- La ventana de contexto es limitada
- Estamos condicionando su respuesta: no responde a nuestro último mensaje de manera aislada, sino que infiere qué debe de generar en base a nuestro último mensaje, el system message que se añade al mismo y todo el historial que hemos generado en nuestra conversación.-->