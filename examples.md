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

Podémos ver este espacio y ejemplo [aquí](https://www.perplexity.ai/search/sabiendo-que-tenemos-4-horas-a-hNCJaPs4R5Wnz8plB4i9UA)

Files:
1. [Programación Didáctica Lengua 24-25 Extranjera: Inglés](https://educastur-my.sharepoint.com/personal/carmenys_educastur_org/_layouts/15/onedrive.aspx?ga=1&id=/personal/carmenys_educastur_org/Documents/web%20ies%20p%C3%BAblico/PROGRAMACIONES/INGL%C3%89S/PD_1_%20BACH_INGL%C3%89S.pdf&parent=/personal/carmenys_educastur_org/Documents/web%20ies%20p%C3%BAblico/PROGRAMACIONES/INGL%C3%89S)
Links:
1. https://iesdeluarca.es/

Haremos que la plataforma recupere el contenido de los textos leages y/o de la Consejería a través de internet.

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