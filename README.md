# Parula

Parula wrapper app that the user starts and which displays the UI and starts the AI background processes.

Based on Svelte, vite and Electron.

## Usage

Start with: `npm start`

> Vite builds the renderer and watches for changes. Meanwhile, electron starts up and loads the index.html file built.

Build with `npm run build`

> Vite statically builds the renderer into `src/renderer/dist`, then electron-builder packages up the build into an executable.

## Structure

* `src/index.js` - Electron entrypoint for app
* `src/renderer/index.html` - Renderer entrypoint for electron
