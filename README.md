# First Electron App

## Installation
- `npm install`
- run - `npm start`

## Steps To Replicate
- `npm init -y`
- `npm i --save-dev electron`
- Change package.json main - `"main": "main.js"`
- Change package.json start script - `"start": "electron ."`
- (can npm start here)
- Import Electron forge to your app folder
  - `npm install -D @electron-forge/cli`
  - `npx electron-forge import`
- Create a distributable
  - `npm run make`
- Include author in `package.json` or build will fail in `npm run make`