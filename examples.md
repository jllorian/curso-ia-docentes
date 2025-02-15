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