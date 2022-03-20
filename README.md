# Vite React Tauri Boilerplate

This repo is a simple boilerplate to create desktop apps using [Vite](https://vitejs.dev/), [React](https://reactjs.org/) and [Tauri](https://tauri.studio/).

## Setup

1. Install Tauri by following instructions for your recommended system: <https://tauri.studio/docs/getting-started/prerequisites>
2. Clone this repo and install dependencies using [PnPm](https://pnpm.io/) (recommended) or your preferred package manager.
3. Start the React server by running `pnpm dev` or `npm run dev` and do not close this session.
4. Start Tauri by running `pnpm tauri-dev` or `npm run tauri-dev` in a different terminal. The first run might take some time.
5. Make changes to your app and see them getting reflected!

## Building

1. To build your app, first build the react project using `pnpm build` or `npm run build`
2. Once the build is finished, then run `pnpm tauri-build` or `npm run tauri-build` to create an executable for your system. The first run might take some time.
