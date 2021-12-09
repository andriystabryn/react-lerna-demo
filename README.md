# Lerna: React + React Native

## Available Scripts


### `yarn`
Install all dependences 

### `npx lerna bootstrap`
Link all packages

### `cd packages/web-app && yarn start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `cd packages/NativeApp && yarn ios`

Launches the ios app

## Shared package

Here is one shared folder `@root/shared`.
It is imported in mobile and web apps `import library from '@root/shared';`