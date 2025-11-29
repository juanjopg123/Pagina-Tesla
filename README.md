# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

🚀 Estructura del proyecto

Dentro de tu proyecto Astro verás esta estructura:

/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json


Astro busca archivos .astro y .md dentro de src/pages/.
Cada archivo se convierte automáticamente en una ruta según su nombre.

La carpeta src/components/ es el lugar recomendado para tus componentes Astro, React, Vue, Svelte o Preact.

Los archivos estáticos (imágenes, íconos, etc.) deben ir en la carpeta public/.

🧞 Comandos

Ejecuta estos comandos desde la raíz del proyecto:

Comando	Acción
npm install	Instala todas las dependencias
npm run dev	Inicia el servidor de desarrollo en localhost:4321
npm run build	Compila tu sitio para producción en ./dist/
npm run preview	Previsualiza la compilación antes de desplegar
npm run astro ...	Ejecuta comandos de Astro como astro add o astro check
npm run astro -- --help	Muestra ayuda sobre la CLI de Astro