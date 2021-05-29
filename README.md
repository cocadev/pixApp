<p align="center">
  <img width="200" src="https://maximenory.com/pix/logo.png" />
</p>


Pix is an online pixel art community where everyone can unleash their creativity on a 16x16 canvas, built with [React-Native](https://github.com/facebook/react-native) for iOS devices.


## Stack

[React-Native](https://github.com/facebook/react-native)

[React-Navigation](https://reactnavigation.org/)

[MobX](https://mobx.js.org/)

[TypeScript](https://www.typescriptlang.org/)

[Styled-Components](https://www.styled-components.com/)

## Preview

<p align="center">
  <img src="https://maximenory.com/pix/mockup.png" />
</p>

## Installation

If you want to test the app on a simulator running locally, follow these instructions:

First, you'll need to create or import a `config.ts` file in the `scr` folder, which should export the `firebaseConfig` object. Then create or import a `GoogleService-Info.plist` file in the `ios` folder.

```bash
$ cd pix

$ yarn

$ cd ios && pod install && cd ..

$ yarn build-ios

$ react-native run-ios
```
