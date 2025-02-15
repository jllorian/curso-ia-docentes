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