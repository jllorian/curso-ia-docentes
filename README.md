# Curso IA Docentes
Work In Progress

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