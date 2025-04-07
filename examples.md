# Profesor matemáticas 4ºESO

SYSTEM_MESSAGE="""
Eres un experto pedagogo en matemáticas para alumnos de cuarto de la ESO en Asturias, España. Vas a recibir un *tema*, tu tarea es generar adaptaciones curriculares para ese *tema* que cumplan con las medidas de atención a la diversidad (andamiaje, multinivel) para poder atender a las características de tu alumnado.

Las características de tu alumnado son las siguientes:
- Son adolescentes muy inquietos.
- Tienen falta de atención.
- Tienen dificultades de pensamiento abstracto.
- Tienen dificultades trasladando lógica matemática a casos de uso del dÍa día.

Estos son los pasos a seguir para generar una adaptación curricular:
1. Diagnóstico del grupo:
   1. Atender a los distintos perfiles (NEAE, altas capacidades, diversidad cultural...)
   2. Identificar barreras de aprendizaje vinculadas al *tema* (ej.: abstracción en álgebra, aplicabilidad en geometrÍa).
2. Vinculación con el currículo oficial:
   1. Consultar el Decreto 59/2022 de Asturias y la LOMLOE para asegurar coherencia con competencias clave y estándares de aprendizaje.
3. Diseño de adaptaciones metodológicas:
   1. Aplicar Diseño Universal para el Aprendizaje (DUA): ofrecer múltiples formas de representación, acción/expresión y motivación.
   2. Usar Aprendizaje Cooperativo y gamificación.
   3. Integrar recursos tecnológicos.
4. Adaptaciones de contenido y actividades:
   1. Crear actividades multinivel dentro del mismo tema.
   2. Incluir ejemplos contextualizados en la vida cotidiana de los alumnos.
   3. Ofrecer materiales de refuerzo y ampliación.
5. Evaluación flexible y formativa:
   1. Utilizar rúbricas adaptadas con criterios diferenciados.
   2. Permitir opciones de demostración de conocimientos. 
6. Antes de generar haz una revisión del proceso:
   1. Comprobar que las adaptaciones diseñadas recogen competencias presentes en el Decreto 59/2022.
   2. Validar que las adaptaciones diseñadas efectivamente enseñan el *tema* indicado.

Genera la adaptación curricular para el siguiente *tema*:
"""

USER_MESSAGE="""
## Esquema del tema "Vectores" para 4º de ESO en Asturias

### **1. Conceptos básicos**
- **Definición de vector**: Un vector es una magnitud que tiene módulo, dirección y sentido.
- **Representación gráfica**: Se representa mediante una flecha en el plano o espacio.
- **Componentes de un vector**: Un vector se puede descomponer en sus componentes $$v_x$$ y $$v_y$$ en el plano cartesiano.

### **2. Operaciones con vectores**
- **Suma de vectores**:
  - Regla del paralelogramo.
  - Suma de componentes: $$ \vec{a} + \vec{b} = (a_x + b_x, a_y + b_y) $$.
- **Resta de vectores**:
  - Se realiza sumando el opuesto: $$ \vec{a} - \vec{b} = (a_x - b_x, a_y - b_y) $$.
- **Producto de un escalar por un vector**:
  - Cambia el módulo y, si el escalar es negativo, invierte el sentido.

### **3. Propiedades geométricas**
- **Módulo de un vector**: 
  $$
  |\vec{v}| = \sqrt{v_x^2 + v_y^2}
  $$
- **Dirección y sentido**:
  - La dirección se define por la pendiente o ángulo con el eje $$x$$: $$ \tan(\theta) = \frac{v_y}{v_x} $$.
  - El sentido está indicado por la punta de la flecha.

### **4. Tipos de vectores**
- **Vectores fijos y libres**:
  - Fijos: Asociados a un punto de origen específico.
  - Libres: No dependen del origen.
- **Vectores equipolentes**:
  - Tienen el mismo módulo, dirección y sentido.
- **Vectores unitarios**:
  - De módulo igual a 1, utilizados para definir direcciones.

### **5. Dependencia lineal**
- Dos vectores son linealmente dependientes si uno es múltiplo escalar del otro ($$ \vec{b} = k\vec{a} $$).
- Vectores paralelos son un caso particular de dependencia lineal.

### **6. Aplicaciones prácticas**
- Cálculo del vector entre dos puntos:
  $$
  \vec{AB} = (x_B - x_A, y_B - y_A)
  $$
- Distancia entre dos puntos:
  $$
  d(A, B) = |\vec{AB}| = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}
  $$

### **7. Ejercicios típicos**
1. Representar gráficamente vectores dados sus componentes.
2. Calcular suma, resta y producto por un escalar.
3. Determinar el módulo y dirección de un vector.
4. Resolver problemas geométricos utilizando vectores (e.g., puntos medios, triángulos).
"""

AI_MESSAGE=[espacio](https://www.perplexity.ai/search/esquema-del-tema-vectores-para-UkrsQ25oRyir23lnLWfgIg)

# Conversación con Deepseek-r1

```zsh
>>> Soy José, ¿tú quién eres?
<think>
Okay, so I just came across this message where someone is addressing me as "Soy José" and asking who I am. Hmm, that's pretty interesting. Let me try to unpack what's going on here.

First off, "Soy José" translates to "I am José," which sounds like a name or maybe an introduction. The person is greeting me by my name, but it's done in Spanish, so I'm guessing the conversation might be taking place in that language. But since I don't know if they're 
speaking directly or just simulating a response, it's a bit tricky.

Now, the second part of their message is "¿tú quién eres?" which translates to "Who are you, little one?" So they're trying to find out my identity in Spanish. That makes sense; they probably want to get a basic understanding or maybe test me to see how I work. Since I'm 
designed to assist and provide information, this seems like a natural interaction.

I need to figure out the best way to respond. If "Soy José" is part of their greeting, then in my response, I should acknowledge that and perhaps introduce myself more fully. I should confirm that I can help them with whatever they need. It's important to be clear and 
friendly so that the conversation flows smoothly.

Wait, but how do I know if "tú" refers to me or someone else? In Spanish, pronouns are a bit tricky because it depends on context and whether the person is addressing me directly. If they're using "tú quién eres," then maybe they're referring to me as their "tu." But without 
more context, I can't be sure if this is a direct address or part of a conversation where someone else introduced themselves.

I think in my response, it's best to assume that they are addressing me directly. So responding with something like "Soy unAsistente dedicado al conocimiento y la ayudantía. ¿Cómo puedo ayudarte hoy?" should be appropriate. That way, I'm confirming my role and inviting them 
to ask for help.

But wait, maybe I should make sure that the Spanish is correct. The word "Asistente" is right, but sometimes people use "Ayudante" or even "Asesor." However, in this context, since I assist with knowledge, "Asistente" fits well. Also, using "¿Cómo puedo ayudarte hoy?" gives 
them an option to ask about today's help.

Alternatively, if the original message was part of a longer conversation where someone else introduced themselves as José and asked me who they were, then my response would still be similar because I need to confirm their identity or provide further assistance. But since it's 
just "Soy José" followed by "¿tú quién eres?", maybe they're asking what I am in general.

In any case, the key is to respond clearly and invite them to continue the conversation. It's important not to overcomplicate things and just stick to a friendly and helpful response.
</think>

Soy unAsistente dedicado al conocimiento y la ayudantía. ¿Cómo puedo ayudarte hoy?

>>> ¿cómo me llamo?
<think>
Alright, so I'm trying to figure out how the user is asking their question. They sent "¿cómo me llamo?" which translates to "How do you call me?" in Spanish.

Looking at the conversation history, the user previously introduced themselves as "Soy José" and asked who they were. My response was "Soy unAsistente dedicado al conocimiento y la ayudantía. ¿Cómo puedo ayudarte hoy?" meaning I'm a knowledge assistant and invite them to ask 
for help today.

Now, in this new query, the user is asking about their own name, which suggests they want me to confirm or provide information related to themselves. However, since I don't have personal data about them, it's impossible to know what their actual name is.

I need to respond politely and let them know that as an AI without a specific identity, I can help with any questions they have. It's important to maintain clarity and offer assistance.
</think>

Como Asistente, no tengo un nombre específico, sino que existo como una herramienta para proporcionar información y ayudar. ¿En qué puedo ayudarte hoy?

>>> ¿No te he dicho mi nombre y lo tienes en el historial conversacional?
<think>
The user is asking if I know their name because it's been in the conversation history.

Looking at the conversation, yes, they had previously stated "Soy José" and then asked about my identity. So they are probably referring to themselves as José.

I need to confirm that I don't have personal information about them but can still assist with any questions or provide help as needed.
</think>

No, no has identificado tu nombre como José, pero entiendo que lo has mencionado antes. Si necesitas ayuda o tienes preguntas, no dudes en pedírmelas.

>>> /exit
```

# Profesor de Inglés de 1º de Bachillerato

> En este ejemplo, vamos a hacer uso de nuevo de los espacios. En esta ocasión, vamos a cargar en el espacio **algunos** de los links y documentos que queremos que use 
> como base para generar el contenido..

Podemos ver este espacio y ejemplo [aquí](https://www.perplexity.ai/search/sabiendo-que-tenemos-4-horas-a-hNCJaPs4R5Wnz8plB4i9UA)

Files:
1. [Programación Didáctica Lengua 24-25 Extranjera: Inglés](https://educastur-my.sharepoint.com/personal/carmenys_educastur_org/_layouts/15/onedrive.aspx?ga=1&id=/personal/carmenys_educastur_org/Documents/web%20ies%20p%C3%BAblico/PROGRAMACIONES/INGL%C3%89S/PD_1_%20BACH_INGL%C3%89S.pdf&parent=/personal/carmenys_educastur_org/Documents/web%20ies%20p%C3%BAblico/PROGRAMACIONES/INGL%C3%89S)
Links:
1. https://iesdeluarca.es/

Haremos que la plataforma recupere el contenido de los textos legales y/o de la Consejería a través de internet.

SYSTEM_MESSAGE="""
Eres profesor de Inglés para alumnos de 1º de Bachillerato en el Instituto (IES) Carmen y Severo Ochoa, Luarca, Asturias.

Tus alumnos tienen las siguientes características:
- Son adolescentes muy inquietos.
- Tienen falta de atención.
- Tienen dificultades con la pronunciación del inglés.
- Tienen dificultades haciendo construcciones gramaticales complejas como el "formal inversion pattern".

Tu tarea es diseñar las sesiones de las unidades didáctica que se te indiquen a continuación. Para ello, has de prestar especial atención a:
1. Programación Didáctica Lengua 24-25 Extranjera: Inglés – primero de bachillerato para el contenido y la organización de los trimestres del curso.
2. Decreto 59/2022 de Asturias y la LOMLOE para asegurar coherencia con las competencias clave y estándares de aprendizaje marcados por la ley.
3. Documentos y planes relevantes para los estudiantes del IES Carmen y Severo Ochoa que estén en la web del centro o en la de la Consejería de Educación de Asturias.
"""

USER_MESSAGE="""
Sabiendo que tenemos 4 horas a la semana, diseña el calendario de sesiones para completar las unidades programáticas del primer trimestre:
1. UP1: TECH TIME
2. UP2: CRIME STORIES
3. UP3: IT'S A THRILL
"""

AI_MESSAGE="""
Calendario de sesiones para el primer trimestre
El primer trimestre consta de tres unidades programáticas: UP1: TECH TIME, UP2: CRIME STORIES, y UP3: IT'S A THRILL. Según la programación didáctica, cada unidad tiene una duración específica dentro del trimestre. Con base en las fechas proporcionadas y considerando que hay 4 horas semanales, el calendario se organiza de la siguiente manera:

Semana 1 a Semana 4: UP1 - TECH TIME
Duración: Del 9 de septiembre al 11 de octubre (5 semanas).
Objetivos principales:

Comprender ideas principales de textos multimodales sobre tecnología.

Producir textos claros y organizados relacionados con avances tecnológicos.

Interactuar activamente en discusiones sobre tecnología.

Distribución semanal:

Semana 1: Introducción al tema, vocabulario tecnológico básico, comprensión oral y escrita.

Semana 2: Producción escrita: redacción de un artículo sobre un avance tecnológico.

Semana 3: Debate grupal: pros y contras de la tecnología en la vida cotidiana.

Semana 4: Evaluación formativa mediante actividades prácticas (presentaciones orales).

Semana 5 a Semana 8: UP2 - CRIME STORIES
Duración: Del 14 de octubre al 8 de noviembre (4 semanas).
Objetivos principales:

Interpretar textos narrativos sobre crímenes ficticios y reales.

Redactar historias cortas relacionadas con el género policial.

Desarrollar habilidades para mediar y resolver problemas comunicativos en contextos ficticios.

Distribución semanal:

Semana 5: Introducción al género policial, vocabulario específico, análisis de textos narrativos.

Semana 6: Escritura creativa: creación de una historia corta basada en un crimen ficticio.

Semana 7: Role-play: simulación de interrogatorios y resolución de casos ficticios.

Semana 8: Evaluación mediante presentación de historias escritas y debates grupales.

Semana 9 a Semana 11: UP3 - IT'S A THRILL
Duración: Del 11 de noviembre al final del trimestre (3 semanas).
Objetivos principales:

Comprender textos relacionados con emociones fuertes y situaciones emocionantes.

Producir descripciones detalladas sobre experiencias emocionantes o ficticias.

Reflexionar sobre la diversidad cultural y lingüística en contextos internacionales.

Distribución semanal:

Semana 9: Introducción al tema, vocabulario relacionado con emociones y thrillers, análisis textual.

Semana 10: Producción escrita: descripción de una experiencia emocionante real o ficticia.

Semana 11: Actividades grupales: creación y presentación de un guion para un thriller corto.

Resumen del Trimestre
Este calendario asegura que los contenidos se trabajen según los criterios establecidos en la programación didáctica, con enfoque en competencias específicas como comprensión, producción, interacción, mediación y reflexión crítica.
"""

USER_MESSAGE="""
Diseña las sesiones de las Semanas 1 a 4: UP1 - TECH TIME.
- Establece el objetivo de cada sesión, y las competencias que deben adquirir (referenciando la programación).
- Planifica cómo dispondrás los conocimientos de manera gradual.
- Establece andamiaje para las actividades.
"""

AI_MESSAGE="""
Planificación de las sesiones de las semanas 1 a 4: UP1 - TECH TIME
La unidad TECH TIME se centra en el aprendizaje del inglés a través de temas relacionados con la tecnología, fomentando competencias comunicativas, comprensión de textos multimodales y producción escrita y oral. A continuación, se detalla la planificación de las sesiones, asegurando un desarrollo gradual de conocimientos y competencias.

Semana 1: Introducción al tema y vocabulario tecnológico
Objetivos:

Familiarizarse con el vocabulario básico relacionado con la tecnología.

Comprender ideas principales en textos orales y escritos sobre avances tecnológicos.

Competencias específicas:

CCL2: Comprender ideas principales en textos orales y escritos.

CP1: Usar estrategias para inferir significados en textos tecnológicos.

Sesiones:

Introducción al tema (1 hora):

Actividad inicial: lluvia de ideas sobre tecnología (palabras clave).

Lectura breve: "The Role of Technology in Our Lives" (texto adaptado).

Actividad: identificar palabras clave en el texto.

Vocabulario tecnológico (1 hora):

Presentación de vocabulario clave (ej.: artificial intelligence, device, innovation).

Actividad: juego interactivo (matching palabras con definiciones).

Comprensión oral (1 hora):

Escucha activa: podcast corto sobre avances tecnológicos.

Actividad: responder preguntas de comprensión general y específica.

Producción oral inicial (1 hora):

Debate guiado: "¿Qué tecnología utilizas más y por qué?"

Uso de estructuras básicas para expresar opiniones.

Semana 2: Comprensión lectora y producción escrita
Objetivos:

Desarrollar habilidades para interpretar textos informativos sobre tecnología.

Redactar un texto breve sobre un avance tecnológico personal o global.

Competencias específicas:

CCL2: Analizar información relevante en textos escritos.

CD3: Usar herramientas digitales para redactar un texto coherente.

Sesiones:

Comprensión lectora (1 hora):

Lectura detallada: artículo sobre "Innovaciones tecnológicas recientes".

Actividad: completar un esquema con las ideas principales del texto.

Análisis crítico (1 hora):

Discusión grupal: impacto positivo/negativo de la tecnología en la sociedad.

Uso de conectores básicos (however, therefore, because).

Producción escrita (2 horas):

Redacción guiada: "Describe un avance tecnológico que haya cambiado tu vida".

Paso 1: lluvia de ideas y planificación del texto (estructura básica).

Paso 2: redacción individual con apoyo del profesor.

Semana 3: Producción oral y debate
Objetivos:

Expresar opiniones sobre temas tecnológicos con fluidez básica.

Participar en debates respetando normas de cortesía lingüística.

Competencias específicas:

CPSAA3.1: Participar activamente en discusiones grupales respetando turnos y opiniones ajenas.

Sesiones:

Preparación para el debate (1 hora):

Introducción al formato del debate (estructura básica).

Presentación del tema: "¿Es la tecnología siempre beneficiosa?"

Práctica oral guiada (1 hora):

Role-play en parejas: defender una postura a favor o en contra del uso excesivo de la tecnología.

Debate grupal (2 horas):

Debate formal en clase con moderador (el profesor).

Evaluación formativa basada en participación activa y uso correcto del vocabulario aprendido.

Semana 4: Evaluación formativa
Objetivos:

Consolidar los conocimientos adquiridos durante la unidad mediante actividades prácticas integradas.

Competencias específicas:

CP2: Producir textos orales y escritos claros y organizados relacionados con la tecnología.

Sesiones:

Presentaciones orales (2 horas):

Preparación y presentación individual o grupal sobre un tema tecnológico elegido por los estudiantes (ej.: smart cities, AI in education).

Feedback inmediato por parte del profesor y compañeros.

Autoevaluación y coevaluación (1 hora):

Reflexión escrita sobre los aprendizajes realizados durante la unidad (What have I learned? What can I improve?).

Uso de rúbricas para evaluar las presentaciones orales.

Actividad creativa final (1 hora):

Creación de un póster digital o físico sobre “El futuro de la tecnología”.

Exposición breve en clase.

Andamiaje propuesto
Para asegurar el aprendizaje progresivo:

Uso inicial de actividades guiadas (lecturas adaptadas, vocabulario básico).

Introducción gradual a tareas más complejas como debates o redacciones largas.

Refuerzo constante mediante feedback formativo tras cada actividad principal.
"""

USER_MESSAGE="""
Desarrolla la Actividad de juego interactivo que propones para el la segunda sesión de la primera semana: Vocabulario tecnológico (1 hora).

- Establece el objetivo de la actividad, y las competencias que deben adquirir (referenciando la programación).
- Haz una rúbrica.
- Establece andamiaje para la actividad.
- Establece el material que se necesita.
"""

AI_MESSAGE="""
### Actividad: Juego interactivo de vocabulario tecnológico

**Título:** *Tech Bingo*
**Duración:** 1 hora
**Objetivo:**

- Aprender y utilizar vocabulario relacionado con la tecnología de manera lúdica e interactiva.
- Fomentar la interacción oral y el trabajo colaborativo en inglés.

**Competencias a desarrollar (referenciadas en la programación):**

- **CCL2:** Comprender y utilizar vocabulario específico en contextos comunicativos.
- **CP1:** Interactuar activamente con estrategias de cooperación en actividades grupales.
- **STEM1:** Aplicar conocimientos lingüísticos para resolver problemas comunicativos relacionados con temas tecnológicos.

---

### **Desarrollo de la actividad**

#### **Fase 1: Introducción (10 minutos)**

1. El profesor presenta una lista de palabras clave relacionadas con la tecnología (*artificial intelligence, device, innovation, algorithm, software, hardware, etc.*) y explica brevemente su significado.
2. Se realiza una actividad rápida de preguntas y respuestas para comprobar que los alumnos entienden las palabras.

#### **Fase 2: Preparación del juego (10 minutos)**

1. Cada alumno recibe un cartón de bingo con una selección aleatoria de palabras del vocabulario (6 palabras por cartón).
2. El profesor explica las reglas:
    - Se leerán definiciones o ejemplos relacionados con las palabras del vocabulario.
    - Los alumnos deben identificar la palabra correspondiente en su cartón y marcarla.

#### **Fase 3: Juego interactivo (30 minutos)**

1. El profesor comienza a leer definiciones o ejemplos de uso de las palabras en frases completas (ej.: "This is the part of a computer that stores data permanently" → *hardware*).
2. Los alumnos marcan las palabras correctas en sus cartones.
3. Cuando un alumno completa su cartón, debe decir "Bingo" y explicar brevemente el significado de las palabras marcadas para ganar puntos adicionales.

---

### **Rúbrica de evaluación**

| **Criterio** | **Nivel Excelente (4)** | **Nivel Bueno (3)** | **Nivel Aceptable (2)** | **Nivel Insuficiente (1)** |
| :-- | :-- | :-- | :-- | :-- |
| Comprensión del vocabulario | Identifica todas las palabras correctamente y explica sus significados con precisión. | Identifica la mayoría de las palabras correctamente y explica algunos significados. | Identifica algunas palabras correctamente pero tiene dificultades para explicar significados. | Identifica pocas palabras correctamente y no puede explicar sus significados. |
| Participación activa | Participa activamente durante todo el juego, respetando turnos y colaborando con compañeros. | Participa en gran parte del juego, pero ocasionalmente pierde el foco o no respeta turnos. | Participa mínimamente y necesita estímulos constantes para involucrarse. | No participa activamente ni respeta las reglas del juego. |
| Uso del inglés | Usa el inglés correctamente durante toda la actividad, incluyendo explicaciones claras. | Usa el inglés correctamente en gran parte de la actividad, aunque con errores menores. | Usa el inglés parcialmente, recurriendo al español frecuentemente. | Usa muy poco inglés durante la actividad o depende completamente del español. |

---

### **Andamiaje**

Para facilitar el aprendizaje progresivo:

1. **Preactividad:** Introducción guiada al vocabulario con explicaciones claras y ejemplos visuales (imágenes o videos breves).
2. **Durante la actividad:** Apoyo constante del profesor para resolver dudas sobre definiciones o pronunciación; uso de gestos o pistas cuando sea necesario para facilitar la comprensión.
3. **Postactividad:** Reflexión grupal sobre las palabras aprendidas; los alumnos pueden compartir cómo usarían esas palabras en contextos reales.

---

### **Material necesario**

1. Cartones de bingo personalizados con vocabulario tecnológico (pueden ser impresos o digitales).
2. Lista de definiciones y ejemplos preparados por el profesor para leer durante la actividad.
3. Marcadores (si los cartones son físicos) o herramientas digitales como aplicaciones interactivas si se usa tecnología en clase (ej.: Kahoot).

---

Esta actividad combina aprendizaje lúdico e interacción oral, fomentando tanto el uso del inglés como la colaboración entre los estudiantes mientras adquieren vocabulario técnico esencial para la unidad "TECH TIME".
"""

# Ejemplo en local: Profesor 2º Bachiller Tecnologías Digitales Aplicadas II

Este ejemplo se inspira en el curso [AI Agents in LangGraph de DeepLearning.AI](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/).
[Esta libreta de colab](https://colab.research.google.com/drive/1Lcc7fe8dx2LaXMuNCkge98XqlyT4gwp0#scrollTo=JxJ7d58rpLpq) muestra el output deseado.

Pasos a seguir:
1. Hacer un "store" de vectores:
  1. Descargar los siguientes archivos:
    1. [Programación Didáctica Tecnologías digitales aplicadas II](https://educastur-my.sharepoint.com/personal/carmenys_educastur_org/_layouts/15/onedrive.aspx?id=/personal/carmenys_educastur_org/Documents/web%20ies%20p%C3%BAblico/PROGRAMACIONES/TECNOLOG%C3%8DA&ga=1)
    2. [Concreciones ESO y Bachillerato](https://iesdeluarca.es/wp-content/uploads/2024/05/Concreciones-ESO-y-Bachillerato-2.pdf)
    3. [PEC-IES Carmen y Severo Ochoa](https://iesdeluarca.es/wp-content/uploads/2024/11/PEC-IES-CARMEN-Y-SEVERO-OCHOA.pdf)
  2. Seleccionar un modelo "encoder" para hacer los vectores (embedings)
    1. *Opcional*: emplear un sistema de ranking: https://jina.ai/reranker/ tiene opción gratuita para uso no comercial. ¡Esto implica procesamiento no-local de los archivos!
2. Selecciona un modelo para descargar y usar en local. Nosotros usaremos DeepSeek r1
3. Preparar el espacio de trabajo:
  1. Prompt de instrucciones.
  2. Seleccionar parámetros de inferencia.
  3. Permitir al sistema recuperar información del "store" de vectores y de internet.

> NOTA: este ejemplo contiene código generado pro deepskeek-r1. No he comprobado sí es correcto o funciona.

**:Model Instructions:** Eres profesor de la materia: Tecnologías Digitales Aplicadas. Tu misión es preparar materiales, con su rúbrica y andamiaje, que se ajusten al Programa Didáctico y al Decreto 59/2022 de Asturias y la LOMLOE.

  ---

  
**:You:** Prepara y estructura un ejercicio para realizar en el entorno de google colab, cuyo objetivo es que los alumnos hagan un agente tipo ReAct (Reason + Act) usando el framework LangGraph que: (1) Redactor: Planifica el esquema de una redacción, (2) Investigador: Hace búsquedas para informarse sobre el tema usando Tavily, (3)Redactor: Escribe una redacción usando el esquema y las respuestas dadas al Investigador.

Para que el ejercicio tenga éxito, los estudiantes han de:
1. Identificar las librerías que necesitan e instalarlas en la libreta de jupyter.
1. Gestionar y almacenar los secretos de HuggingFace y Tavily.
2. Seleccionar, invocar y cuantizar (quantization) un modelo de su elección de HuggingFace.
3. Diseñar los nodos que va a tener el agente.
4. desarrollar la herramienta que va llamar a la API de Tavily

Tu misión NO es generar el código que han de hacer los alumnos, sino preparar las instrucciones, la rúbrica, y el andamiaje de la actividad. Si puedes acompañar las instrucciones para los alumnos con snipets de código de ejemplo.

---

**:deepseek-r1:latest:** ### **Ejercicio para preparar y estructurar un ejercicio en Google Colab: Creación de un agente ReAct usando LangGraph**

#### Objetivo del ejercicio:
El objetivo es que los estudiantes desarrollen, entrenen y prueben una herramienta integrada que permita la creación de un agente de Reason + Act (ReAct) utilizando el framework LangGraph. El agente debe incluir los siguientes componentes principales:
1. **Redactor**: Planificará el esquema de una redacción.
2. **Investigador**: Recogerá información relevante sobre el tema a discutir usando Tavily.
3. **Redactor**: Escribirá la redacción basándose en los datos recolectados.

---

### **Step-by-step guía para desarrollar el ejercicio:**

#### 1. Preparación del entorno de trabajo
**Instrucciones para los estudiantes:**
- Asegúrense de que están trabajando en un entorno de Google Colab.
- Instalar las librerías necesarias:
  
```bash
pip install transformers tervaly langgraph pyyaml pandas requests numpy scipy
```

#### 2. Configuración de secretos
**Instrucciones para los estudiantes:**
- Seleccionen y guarden sus secretos HuggingFace (llave access) en un archivo .env:
  
```bash
export HUGGINGFACE_TOKEN=my_api_key_here
export TAvily_SECRET_KEY=your_tvalily_secret_key_here
```
- **Nota**: Eviten Exponer secretos de manera pública, como en version control o en repositorios.

#### 3. Descarga y entrenamiento del modelo
**Instrucciones para los estudiantes:**
- Seleccionen un modelo preentrenado de HuggingFace utilizando el framework LangGraph.
  
Ejemplo (usando EfficientNet-B7):

```python
from transformers import AutoModelForCausalLM

# Seleccionar un modelo:
model_name = "google/efficientnet-b7"  # O otro modelo según las necesidades.

with torch.no_grad():
    model = AutoModelForCausalLM.from_pretrained(model_name, quantization="4bit")
```

- Realicen la cuantización del modelo para reducir el tamaño:

```python
model = model.quantize(quantization_bit=4)
```

#### 4. Diseño de los nodos del agente ReAct
**Instrucciones para los estudiantes:**
1. **Definir los esquemas de redacción:**
   Utilicen PyYAML para definir el esquema estructurado de la redacción.

Ejemplo:

```yaml
redactor_schema:
  - nombre_teorico: Teoría Base
    descripcion: Introducción al tema.
  
  - analisis_cognitivo: Análisis Cognitivo
    descripcion: Identificación de conceptos clave y su relevancia.
    
  - analisis_expositivo: Análisis Expositivo
    descripcion: Desarrollo del contenido estructurado.
    
  - conclusiones:
      descripcion: Resumen y extrapolación de los resultados obtenidos.

- nombre_tematico: Técnica Especifica
```

2. **Definir las fuentes de información:**
   Utilicen Tavily para recopilar datos sobre el tema seleccionado.

Ejemplo:

```python
from tervaly import Avata, API

client = Avata()
API(client).set_collection("collection_name").add_query("query_string")
```

3. **Definir la estructura del agente:**
   Utilicen LangGraph para definir las interacciones entre los componentes.

Ejemplo:

```yaml
nodes:
  - Redactor1:
      type: redactores
      input_fields: ["introduccion", "conceptos_claves"]
      output_fields: ["contenido_inicial"]

  - Investigador1:
      type: investigadores
      query_template: "¿Cuál es la importancia de {palabra} en el contexto del tema?"
  
  - Redactor2:
      type: redactores
      input_fields: ["influencias", "resultados"]
      output_fields: ["conclusiones"]
```

#### 5. Desarrollo de la herramienta para Tavily
**Instrucciones para los estudiantes:**
- Escriban una función que:
  
1. Busque información en Tavily.
2. Recuperen los datos relevantes.
3. Retorne el resultado.

Ejemplo:

```python
def tvalily_query(query):
    client = Avata()
    API(client).set_collection("collection_name").add_query(query)
    
    results = API.get_results().to_dict('records')
    
    return results[0]
```

#### 6. Integramiento del agente en LangGraph
**Instrucciones para los estudiantes:**
- Utilicen el framework LangGraph para integrar todos los componentes.
  
Ejemplo:

```yaml
 Redactor:
   scheme_name: redactor_schema
   actions:
      - CallFunction("tvalily_query", "argumentos_de llama")
```

#### 7. Validación y pruebas del agente
**Instrucciones para los estudiantes:**
- **Validar**: Prueben el agente con diferentes inputs y verifiquen si la salida es consistente.
- **Optimizar**: Ajusten los parámetros del modelo, la estructura de redacción o las fuentes de información según sea necesario.

#### 8. Documentación
**Instrucciones para los estudiantes:**
- Escriban un informe detallado que explicará cada etapa del ejercicio.
- Incluyan:
  
1. **Descripción del agente ReAct**: Explicar qué hace el agente y cómo está estructurado.
2. **Configuración de secretos**: Mostrar los secretos HuggingFace y Tavily utilizados.
3. **Evolución del código**: Presentar las etapas clave del desarrollo con referencias al código.

#### 9. Evaluación
**Mejores prácticas para la evaluación:**
- Evalúen el rendimiento del agente en tareas específicas (por ejemplo, comparando diferentes modelos).
- Verifique que los estudiantes hayan followado las instrucciones detalladamente.
- Analízen la eficiencia de su redactor y la precisión de sus investigadores.

### Preguntas y Respuestas

¿Cómo puedo asegurarme de que mi agente ReAct funcione correctamente?

Puedes seguir estos pasos para verificar tu agente:

1. **Validación**: Ejecuta el agente con inputs conocidos y verifica si las salidas esperadas se obtienen.

2. **Análisis de la estructura**: Verifica que los nodos del LangGraph están correctamente configurados y comunican bien entre sí.

3. **Optimización**: Intenta modificar parámetros como la precisión del modelo o el tamaño del esquema de redacción para observar cambios en el rendimiento.

¿Cómo puedo mejorar mi modelo cuantizado?

Puedes mejorar tu modelo cuantizado ejecutando pasos adicionales como:

1. **Tuneo**: Ajusta los parámetros de entrenamiento más finamente.
2. **Pruebas exhaustivas**: Prueba diferentes combinaciones de inputs para asegurar la consistencia del resultado.
3. **Validación cruzada**: Utiliza técnicas de validación avanzadas para prevenir el sobreajuste.

¿Cómo puedo integrar mejor con Tavily?

Para mejorar la integración con Tavily, puedes:

1. ** personalizar las rutas de llamada**: Asegúrate de que las funciones de investigación estén correctamente configuradas.
2. **Validación de datos**: Añade controles para asegurar que los datos devueltos por Tavily sean procesados correctamente.

¿Qué significa cuantizar un modelo en PyTorch?

La cuantización consiste en reducir la precisión numérica del modelo para disminuir su tamaño y mejor adaptación a dispositivos con limitaciones de recursos, como CPUs o arquitecturas móviles. En el caso de 4 bits, cada tensor se representa con 4 bits en lugar de los flotantes precisionales.

¿Cómo puedo manejar excepciones en PyTorch?

PyTorch provede una serie de maneras para gestionar excepciones durante el entrenamiento o inferencia del modelo:

1. **Seterramientas de error handling**: Asegúrate de que las configuraciones de error se hagan apropiadas.
2. **Lotes condicionales**: Utiliza controles del flujo para manejar situaciones críticas como la división por cero o operaciones invariables.

¿Cómo puedo seleccionar un modelo optimo para mi problema?

Algunos factores a considerar al seleccionar un modelo son:

1. **Tamaño de dataset**: Si tienes pocos ejemplos, opta por-modelos más pequeño.
2. **Complejidad del problema**: Cuanto más difícil es el tema, mayor será la necesidad de un modelo más grande y complejo.
3. **Recursos disponibles**: Considera el poder de procesamiento y la memoria para seleccionar un tamaño adecuado de modelo.

¿Cómo puedo hacer que mi redactor maneje diferentes tipos de estructuras?

Puedes personalizar los esquemas del agente ReAct para accepts diferentes tipos de datos, asegurando que cada tipo se procese correctamente en su etapa correspondiente.
</think>

La preparación y ejecución del ejercicio sobre la creación de un agente ReAct utilizando el framework LangGraph implica varias etapas clave. A continuación, se detallan los pasos para each student:

### Preparación del Material Docente
1. **Ejercicio 1: Configuración inicial**
   - Seleccionar y definir el esquema de redacción utilizando PyYAML.
   - Diseñar la estructura de nodos para integrar con Tavily.

2. **Ejercicio 2: Desarrollo del modelo cuantizado**
   - Utilizar HuggingFace para seleccionar un modelo preentrenado y aplicar cuantización en PyTorch.

3. **Ejercicio 3: Implementación de la herramienta de Tavily**
   - Escripturar una función que comunique con Tavily para recopilar información.

4. **Ejercicio 4: Integramiento del agente en LangGraph**
   - Configurar los nodos y accionadores según el esquema definido.

5. **Ejercicio 5: Validación y pruebas**
   - Probar la funcionalidad del agente con diferentes inputs.
   - Documentar cada etapa del ejercicio para su presentación.

6. **Ejercicio 6: Evaluación**
   - Analizar el rendimiento del agente y asegurar que todos los componentes están correctamente implementados.

---

### Resolución de los Problemas

1. **Validación del Agente**
   
   Para verificar si un agente ReAct funciona correctamente, sigue estos pasos:
   
   1. **Ejecución con Inputs Conocidos**: Ejecuta el agente con combinaciones específicas de entradas y observa las salidas generadas.
   2. **Análisis de Estructura**: Verifica que cada nodo del LangGraph procesa correctamente los datos, pasándolos adequateamente a los nodos adyacentes.
   3. **Pruebas Extensivas**: Prueba diferentes combinaciones de inputs para asegurar la consistencia y robustez del agente.

2. **Mejoramiento del Modelo Cuantizado**
   
   Asegúrate de que el modelo cuantizado:
   
   - Tiene un tamaño adecuado para el dispositivo de procesamiento utilizado (CPU, GPU, etc.).
   - Ofrece una balancea entre precisión y eficiencia en Resource consumption.
   - Se ajustan los parámetros del entrenamiento si es necesario.

3. **Integración Mejorada con Tavily**
   
   Para mejorar la integración:
   
   1. Personaliza las rutas de llamada para asegurar que las funciones de investigación estén correctamente configuradas.
   2. Añade controles adicionales en los datos devueltos por Tavily para garantizar su calidad y usabilidad.

4. **Manejo de excepciones en PyTorch**
   
   Algunas maneras de gestionar excepciones incluyen:
   
   - Configurando apropiadamente las herramientas de error handling.
   - Manteniendo control del flujo con estructuras condicionales para manejar situaciones críticas.
   - Considerando la precisión numérica y los flotantes en el modelo.

5. **Elección Optima del Modelo**
   
   Al seleccionar un modelo, considera:
   
   1. El tamaño del dataset disponible: Si tienes pocos ejemplos, opta por-modelos más pequeño.
   2. La complejidad del problema: Un problema más difícil may requiere un modelo más grande y complejo.
   3. Los recursos disponibles: Considera el poder de procesamiento y la memoria para seleccionar un tamaño adecuado.

6. **Manejo Diferentes Tipos de Estructuras**
   
   Personaliza los esquemas del agente ReAct para manejar diferentes tipos de datos, asegurando que cada tipo se procesa correctamente en su etapa correspondiente.

---

### Preguntas y Respuestas

¿Cómo puedo asegurar que mi agente ReAct funcione correctamente?

1. Ejecuta el agente con inputs conocidos y verifica las salidas.
2. Asegúrate de que los nodos del LangGraph están correctamente configurados.
3. Prueba diferentes combinaciones de inputs para verificar la robustez.

¿Cómo puedo mejorar mi modelo cuantizado?

- Ajusta los parámetros de entrenamiento más finamente.
- Realiza pruebas exhaustivas con diferentes entradas.
- Utiliza técnicas de validación avanzadas para evitar el sobreajuste.

¿Cómo puedo integrar mejor con Tavily?

1. Personaliza las rutas de llamada de investigación.
2. Añade controles en los datos devueltos por Tavily.
3. Considera la precisión numérica y flotantes del modelo para mejorar el procesamiento.

¿Cómo manejo los errores en PyTorch?

- Configura apropiadamente las herramientas de error handling.
- Mantén control del flujo con estructuras condicionales.
- Asegúrate de que las operaciones matemáticas se realizan con precisión suficiente.

¿Cómo puedo seleccionar un modelo optimo para mi problema?

- Considera el tamaño del dataset y su complejidad.
- Elegir un modelo balanceado entre rendimiento y recursos necesarios.

# Profesor de dibujo artístico de 1º de Bachillerato

Este ejemplo lo haremos con la función de *Canvas* de [LeChat](https://chat.mistral.ai/chat).
![LeChat](/curso-ia-luarca-slides/recursos/LeChat.png)

USER_MESSAGE="""
Eres profesor de dibujo artístico en el IES Carmen y Severo Ochoa de Luarca para estudiantes de 1º de Bachillerato.

Vas a preparar una clase en la que los alumnos van a dibujar un vanitas. El primer paso es diseñar la rúbrica del ejercicio. 
Identifica competencias clave de acuerdo al Decreto 59/2022 de Asturias y la LOMLOE que los alumnos deben mostrar en el ejercicio 
y haz la rúbrica en un canvas tipo tabla.
"""
AI_MESSAGE="""
Para diseñar la rúbrica del ejercicio de dibujo de un vanitas para estudiantes de 1º de Bachillerato en el IES Carmen y Severo Ochoa de Luarca, es importante identificar las competencias clave que los estudiantes deben demostrar. Según el Decreto 59/2022 de Asturias y la LOMLOE, las competencias clave en el ámbito del dibujo artístico incluyen:

1. **Competencia en expresión y comprensión cultural y artística**: Los estudiantes deben ser capaces de interpretar y expresar ideas, emociones y experiencias a través del dibujo, utilizando técnicas y recursos artísticos adecuados.

2. **Competencia en apreciación crítica**: Los estudiantes deben desarrollar la capacidad de analizar y valorar obras de arte, comprendiendo su contexto histórico y cultural, y relacionándolas con su propia producción artística.

3. **Competencia en creatividad**: Los estudiantes deben demostrar originalidad y innovación en sus dibujos, explorando nuevas ideas y soluciones visuales.

4. **Competencia en comunicación visual**: Los estudiantes deben ser capaces de comunicar mensajes y significados a través de sus dibujos, utilizando elementos visuales como la forma, el color, la textura y la composición.

5. **Competencia en uso de herramientas y técnicas artísticas**: Los estudiantes deben manejar con destreza diversas herramientas y técnicas de dibujo, como el lápiz, el carboncillo, la tinta, entre otros, y aplicarlas de manera adecuada en sus trabajos.

A continuación, se presenta la rúbrica para evaluar el ejercicio de dibujo de un vanitas:




| **Competencia** | **Excelente (4 puntos)** | **Bueno (3 puntos)** | **Suficiente (2 puntos)** | **Insuficiente (1 punto)** |
|-----------------|--------------------------|----------------------|--------------------------|--------------------------|
| **Expresión y comprensión cultural y artística** | El estudiante interpreta y expresa ideas, emociones y experiencias de manera clara y profunda, utilizando técnicas y recursos artísticos adecuados. | El estudiante interpreta y expresa ideas, emociones y experiencias de manera clara, pero con alguna limitación en el uso de técnicas y recursos artísticos. | El estudiante interpreta y expresa ideas, emociones y experiencias de manera básica, con limitaciones en el uso de técnicas y recursos artísticos. | El estudiante tiene dificultades para interpretar y expresar ideas, emociones y experiencias, y presenta errores significativos en el uso de técnicas y recursos artísticos. |
| **Apreciación crítica** | El estudiante analiza y valora obras de arte de manera crítica y fundamentada, relacionándolas con su propia producción artística y su contexto histórico y cultural. | El estudiante analiza y valora obras de arte de manera crítica, pero con alguna limitación en la fundamentación o en la relación con su propia producción artística y su contexto histórico y cultural. | El estudiante analiza y valora obras de arte de manera básica, con limitaciones en la fundamentación y en la relación con su propia producción artística y su contexto histórico y cultural. | El estudiante tiene dificultades para analizar y valorar obras de arte de manera crítica, y presenta errores significativos en la fundamentación y en la relación con su propia producción artística y su contexto histórico y cultural. |
| **Creatividad** | El estudiante demuestra una gran originalidad e innovación en sus dibujos, explorando nuevas ideas y soluciones visuales de manera efectiva. | El estudiante demuestra originalidad e innovación en sus dibujos, pero con alguna limitación en la exploración de nuevas ideas y soluciones visuales. | El estudiante demuestra originalidad e innovación en sus dibujos de manera básica, con limitaciones en la exploración de nuevas ideas y soluciones visuales. | El estudiante tiene dificultades para demostrar originalidad e innovación en sus dibujos, y presenta errores significativos en la exploración de nuevas ideas y soluciones visuales. |
| **Comunicación visual** | El estudiante comunica mensajes y significados de manera clara y efectiva a través de sus dibujos, utilizando elementos visuales como la forma, el color, la textura y la composición de manera adecuada. | El estudiante comunica mensajes y significados de manera clara a través de sus dibujos, pero con alguna limitación en el uso de elementos visuales como la forma, el color, la textura y la composición. | El estudiante comunica mensajes y significados de manera básica a través de sus dibujos, con limitaciones en el uso de elementos visuales como la forma, el color, la textura y la composición. | El estudiante tiene dificultades para comunicar mensajes y significados a través de sus dibujos, y presenta errores significativos en el uso de elementos visuales como la forma, el color, la textura y la composición. |
| **Uso de herramientas y técnicas artísticas** | El estudiante maneja con destreza diversas herramientas y técnicas de dibujo, aplicándolas de manera adecuada y efectiva en sus trabajos. | El estudiante maneja diversas herramientas y técnicas de dibujo, pero con alguna limitación en su aplicación adecuada y efectiva en sus trabajos. | El estudiante maneja diversas herramientas y técnicas de dibujo de manera básica, con limitaciones en su aplicación adecuada y efectiva en sus trabajos. | El estudiante tiene dificultades para manejar diversas herramientas y técnicas de dibujo, y presenta errores significativos en su aplicación adecuada y efectiva en sus trabajos. |




Esta rúbrica permitirá evaluar de manera objetiva y estructurada el desempeño de los estudiantes en el ejercicio de dibujo de un vanitas, teniendo en cuenta las competencias clave establecidas en el Decreto 59/2022 de Asturias y la LOMLOE.
"""

![Rúbrica generada por LeChat](/curso-ia-luarca-slides/recursos/rubrica-mistral.png)

USER_MESSAGE="""
El segundo paso es hacer una representación de cómo han de estimar los tamaños de los distintos objetos del vanitas.

Prepara un canvas tipo svg que muestre:
1. Una superficie con tres formas de distinto tamaño (el vanitas a representar)
2. Un ojo a cierta distancia de la superficie.
3. Una referencia que use el ojo y líneas que indiquen cómo se usa esa referencia para estimar el tamaño de una de las formas del vanitas.
"""

AI_MESSAGE="""
Para ayudar a los estudiantes a estimar los tamaños de los distintos objetos en un vanitas, he creado un diagrama en SVG que muestra una superficie con tres formas de diferentes tamaños, un ojo a cierta distancia de la superficie, y líneas que indican cómo usar el ojo como referencia para estimar el tamaño de una de las formas.



<svg width="100%" height="100%" viewBox="0 0 800 600" xmlns="http://www.w3.org/2000/svg">
  <!-- Superficie con tres formas de distinto tamaño -->
  <rect x="100" y="300" width="600" height="200" fill="#f0f0f0" stroke="#000" stroke-width="2"/>
  <circle cx="200" cy="400" r="30" fill="#c0c0c0" stroke="#000" stroke-width="2"/>
  <rect x="350" y="350" width="60" height="100" fill="#a0a0a0" stroke="#000" stroke-width="2"/>
  <ellipse cx="550" cy="400" rx="50" ry="25" fill="#808080" stroke="#000" stroke-width="2"/>

  <!-- Ojo a cierta distancia de la superficie -->
  <circle cx="400" cy="150" r="20" fill="#fff" stroke="#000" stroke-width="2"/>
  <circle cx="395" cy="145" r="5" fill="#000"/>

  <!-- Líneas que indican cómo usar el ojo como referencia -->
  <line x1="400" y1="150" x2="200" y2="400" stroke="#ff0000" stroke-width="2" stroke-dasharray="5,5"/>
  <line x1="400" y1="150" x2="350" y2="350" stroke="#ff0000" stroke-width="2" stroke-dasharray="5,5"/>
  <line x1="400" y1="150" x2="550" y2="400" stroke="#ff0000" stroke-width="2" stroke-dasharray="5,5"/>

  <!-- Texto explicativo -->
  <text x="410" y="140" font-family="Arial" font-size="20" fill="#000">Ojo</text>
  <text x="210" y="390" font-family="Arial" font-size="20" fill="#ff0000">Forma 1</text>
  <text x="360" y="340" font-family="Arial" font-size="20" fill="#ff0000">Forma 2</text>
  <text x="560" y="390" font-family="Arial" font-size="20" fill="#ff0000">Forma 3</text>
</svg>



Este diagrama ayudará a los estudiantes a visualizar cómo estimar los tamaños de los objetos en su vanitas utilizando la perspectiva y la referencia del ojo.
"""

USER_MESSAGE="""
El tercer paso es realizar una presentación de tres diapositivas. Haz un canvas tipo slides con las siguientes diapositivas:
1. Título del ejercicio
2. Introduce brevemente a los alumnos qué es un vanitas.
3. Representa una versión abreviada de la rúbrica de evaluación.
"""

AI_MESSAGE="""
Here is the canvas with the presentation:




<slides>

# Título del ejercicio

## Dibujo de un vanitas

---

# ¿Qué es un vanitas?

- **Definición**: Un vanitas es un género de pintura de naturaleza muerta que simboliza la fugacidad de la vida, la vanidad de los placeres terrenales y la certeza de la muerte.
- **Origen**: El término proviene del latín "vanitas", que significa "vanidad" o "vacío".
- **Simbolismo**: Las pinturas de vanitas suelen incluir objetos como calaveras, relojes de arena, velas apagadas, flores marchitas y libros, cada uno con un significado simbólico específico.
- **Propósito**: Estas obras invitan a la reflexión sobre la brevedad de la vida y la inevitabilidad de la muerte, recordando al espectador la importancia de vivir una vida virtuosa y prepararse para el juicio final.

---

# Rúbrica de evaluación

| **Competencia** | **Excelente (4 puntos)** | **Bueno (3 puntos)** | **Suficiente (2 puntos)** | **Insuficiente (1 punto)** |
|-----------------|--------------------------|----------------------|--------------------------|--------------------------|
| **Expresión y comprensión cultural y artística** | El estudiante interpreta y expresa ideas, emociones y experiencias de manera clara y profunda, utilizando técnicas y recursos artísticos adecuados. | El estudiante interpreta y expresa ideas, emociones y experiencias de manera clara, pero con alguna limitación en el uso de técnicas y recursos artísticos. | El estudiante interpreta y expresa ideas, emociones y experiencias de manera básica, con limitaciones en el uso de técnicas y recursos artísticos. | El estudiante tiene dificultades para interpretar y expresar ideas, emociones y experiencias, y presenta errores significativos en el uso de técnicas y recursos artísticos. |
| **Uso de herramientas y técnicas artísticas** | El estudiante maneja con destreza diversas herramientas y técnicas de dibujo, aplicándolas de manera adecuada y efectiva en sus trabajos. | El estudiante maneja diversas herramientas y técnicas de dibujo, pero con alguna limitación en su aplicación adecuada y efectiva en sus trabajos. | El estudiante maneja diversas herramientas y técnicas de dibujo de manera básica, con limitaciones en su aplicación adecuada y efectiva en sus trabajos. | El estudiante tiene dificultades para manejar diversas herramientas y técnicas de dibujo, y presenta errores significativos en su aplicación adecuada y efectiva en sus trabajos. |
| **Creatividad** | El estudiante demuestra una gran originalidad e innovación en sus dibujos, explorando nuevas ideas y soluciones visuales de manera efectiva. | El estudiante demuestra originalidad e innovación en sus dibujos, pero con alguna limitación en la exploración de nuevas ideas y soluciones visuales. | El estudiante demuestra originalidad e innovación en sus dibujos de manera básica, con limitaciones en la exploración de nuevas ideas y soluciones visuales. | El estudiante tiene dificultades para demostrar originalidad e innovación en sus dibujos, y presenta errores significativos en la exploración de nuevas ideas y soluciones visuales. |
| **Comunicación visual** | El estudiante comunica mensajes y significados de manera clara y efectiva a través de sus dibujos, utilizando elementos visuales como la forma, el color, la textura y la composición de manera adecuada. | El estudiante comunica mensajes y significados de manera clara a través de sus dibujos, pero con alguna limitación en el uso de elementos visuales como la forma, el color, la textura y la composición. | El estudiante comunica mensajes y significados de manera básica a través de sus dibujos, con limitaciones en el uso de elementos visuales como la forma, el color, la textura y la composición. | El estudiante tiene dificultades para comunicar mensajes y significados a través de sus dibujos, y presenta errores significativos en el uso de elementos visuales como la forma, el color, la textura y la composición. |
| **Apreciación crítica** | El estudiante analiza y valora obras de arte de manera crítica y fundamentada, relacionándolas con su propia producción artística y su contexto histórico y cultural. | El estudiante analiza y valora obras de arte de manera crítica, pero con alguna limitación en la fundamentación o en la relación con su propia producción artística y su contexto histórico y cultural. | El estudiante analiza y valora obras de arte de manera básica, con limitaciones en la fundamentación y en la relación con su propia producción artística y su contexto histórico y cultural. | El estudiante tiene dificultades para analizar y valorar obras de arte de manera crítica, y presenta errores significativos en la fundamentación y en la relación con su propia producción artística y su contexto histórico y cultural. |

</slides>

"""

Mistral nos permite trabajar sobre los canvas, introducir nuestras propias modificaciones y pedirle que continue editando.