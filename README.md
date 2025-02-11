# Curso IA Docentes
Work In Progress

Este repositorio contiene las diapositivas, PDFs y recursos empleados en la formación en IA para Docentes del IES Carmen y Severo Ochoa de Luarca, así como la bibliografía empleada en al elaboración de la formación.

El CPR (Dentro del Profesorado y de Recursos) del Occidente nos ha facilitado la siguiente información respecto a las necesidades formativas del centro (parafraseado):

> En el centro, el nivel de conocimiento sobre inteligencia artificial (IA) es variado, por lo que la formación debería adaptarse tanto a personas con conocimientos básicos como a quienes ya tienen experiencia. Las áreas de mayor interés incluyen el uso de herramientas gratuitas y libres para aplicaciones docentes, la evaluación del alumnado, la creación de proyectos y aspectos relacionados con la ética y regulación de la IA.
En cuanto a aplicaciones específicas, se valoran especialmente aquellas que faciliten la creación de materiales educativos, como presentaciones, así como herramientas como ChatGPT o generadores de imágenes (aunque estas últimas en menor medida). El objetivo principal de la formación sería aprender a optimizar el tiempo dedicado a la preparación de clases.

La formación ha sido, por tanto, diseñada como un *crash course*: los objetivos de la misma son:
- Que el claustro comparta un nivel común de conocimiento sobre la IA.
- Que el claustro pueda identificar y minimizar riesgos, empleando la IA dentro de un marco de privacidad y protección de datos.
- Que el claustro adquiera la capacidad de hacer uso de herramientas de IA generativa de manera efectiva mediante el uso de la ventana de contexto: prompts, historial, y documentos "incrustados" (*embeddings*).

## Contenido

Work In Progress

1. Portada
2. ¿Quién soy?
3. Tabla de Contenidos
4. La relevancia de la IA en educación
5. ¿Qué es la IA?
   1. IA, *ML*, *DL*, *GenAI* y *AGI*.
6. *GenAI*: ¿Cómo funciona?
   1. FMs y familias de modelos, *embeddings*, parámetros de inferencia y ventana de contexto.
7. Usando la ventana de contexto:
   1. *Prompts*: *system message vs user message*.
   2. *Prompts* efectivos, estrategias y tipos.
8. Riesgos y sesgos en GenAI
   1. ¿Cuáles conocen?
   2. Sesgos.
9. Reducción de riesgos: Recuperación aumentada (*RAG*)
10. Ética y regulación: uso responsable
11. El ~futuro~ presente: Agentes y flujos de trabajo
12. Herramientas de IA generativa:
    1.  En la nube versus herramientas en "local".
    2.  Empleando *RAG* la nube: Perplexity, GPTSearch y otros proveedores.
    3.  Empleando *RAG* en local: Ollama, LLMStudio y Msty.
        1.  Repositorios de modelos.
13. Casos de uso prácticos con buenas prácticas:
    1.  Crear o usar un repositorio de *prompts*
    2.  Incrustar criterios de evaluación y planes docentes.
    3.  Refinar material docente para atención a la diversidad.
    4.  Generar documentos finales listos para distribuir.
    5.  Usar agentes para tareas específicas.
14. Glosario interactivo
15. Material adicional y cómo acceder al curso

# Uso de Slidev
Este proyecto utiliza [Slidev](https://sli.dev/), una herramienta para crear presentaciones con Markdown.

## Requisitos previos
Asegurate de tener instalado:
- `Node.js` (versión LTS recomendada)
- `pnpm` como gestor de paquetes:
  ```bash
  npm install -g pnpm
  ```

## Comandos principales
Dentro de la carpeta `curso-ia-luarca-slides`, puedes usar los siguientes comandos:

### 1. Iniciar el servidor local
Para previsualizar las slides en tu navegador:
```bash
pnpm dev
```

Esto abrirá las slides en `http://localhost:3030`

### 2. Construir las slides
Para generar una versión estática lista para desplegar
```bash
pnpm build
```

Los archivos generados se guardarán en la carpeta `dist`.

### 3. Exportar a PDF
Si necesitas una versión PDF de las slides:
```bash
pnpm export
```

Esto generará un archivo PDF del proyecto.

## Estructurya del proyecto
- `slides.md`: archivo principal donde se definen las diapositivas.
- `components/`: componentes personalizados para enriquecer las slides.
- `pages/`: archivos adicionales que pueden ser importaddos en las slides.
- `dist/`: carpeta generada al construir las slides (no presente en el repo).

## Despliegue
El despliegue automático está configurado mediante GitHub Actions. Cada vez que realices un *push* a la rama `main`, las slides se publicarán automáticamente en [GitHub Pages](https://jllorian.github.io/curso-ia-docentes/)

## Recursos Adicionales
Para más información sobre Slidev, consulta la [documentación oficial](https://sli.dev/guide/)

# Licencia
Este proyecto está licenciado bajo los términos de [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Puedes usarlo, modificarlo y redistribuirlo siempre que atribuyas al autor original.