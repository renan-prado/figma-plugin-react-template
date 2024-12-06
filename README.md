# Figma Plugin React Template

![figma-react](https://github.com/user-attachments/assets/cdb3e14f-2ecf-4d37-9fe3-8d83b6bf7f14)

This template contains the react example as shown on [Figma Docs](https://www.figma.com/plugin-docs/intro/), with some structural changes and extra tooling.

## Quickstart

- Run `yarn` to install dependencies.
- Run `yarn build:watch` to start webpack in watch mode.
- Open `Figma` -> `Plugins` -> `Development` -> `Import plugin from manifest...` and choose `manifest.json` file from this repo.

⭐ To change the UI of your plugin (the react code), start editing [App.tsx](./src/app/components/App.tsx).  
⭐ To interact with the Figma API edit [controller.ts](./src/plugin/controller.ts).  
⭐ Read more on the [Figma API Overview](https://www.figma.com/plugin-docs/api/api-overview/).

## Toolings

This repo is using:

- React + Webpack
- TypeScript
- Prettier precommit hook
