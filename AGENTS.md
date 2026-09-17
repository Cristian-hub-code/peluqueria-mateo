# AGENTS.md

## Descripcion

Peluqueria Mateo es un sitio web estatico en espanol para presentar trabajos de peluqueria y dirigir a los visitantes hacia la agenda de citas. El proyecto usa Astro con JavaScript y CSS sin framework de UI.

## Estructura

- `src/pages/index.astro`: pagina principal y marcado de la interfaz.
- `src/styles/base.css`: estilos globales, variables de color y layout.
- `src/scripts/main.js`: comportamiento del boton de agenda ejecutado en el navegador.
- `public/`: archivos estaticos que deban copiarse sin procesar al build.
- `package.json`: scripts y dependencia de Astro.

## Comandos

- `npm install`: instala las dependencias.
- `npm run dev`: inicia el servidor de desarrollo.
- `npm run build`: genera la compilacion de produccion en `dist/`.
- `npm run preview`: sirve localmente la compilacion generada.

## Convenciones

- Mantener el contenido visible en espanol.
- Preferir componentes y paginas Astro antes que introducir un framework de frontend.
- Mantener el JavaScript del navegador pequeno y encapsulado en `src/scripts/`.
- Usar las variables CSS existentes para colores y tipografia antes de agregar valores globales nuevos.
- No guardar secretos ni archivos generados en el repositorio.
- Evitar cambios no relacionados con la interfaz o el flujo de agenda.

## Validacion

Antes de entregar cambios, ejecutar `npm run build`. Para cambios de comportamiento del navegador, comprobar tambien el flujo del boton de agenda en `npm run dev`.
