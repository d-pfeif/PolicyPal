# PolicyPal
This repository started from a [boilerplate](https://github.com/ixartz/React-Native-Boilerplate) and includes the following features:

- ⚡ [Expo](https://expo.dev) for mobile development
- ⚛️ [React Native](https://reactnative.dev) for building native apps using React
- 🔥 Type checking [TypeScript](https://www.typescriptlang.org)
- 💎 Integrate with [NativeWind](https://www.nativewind.dev), Tailwind CSS for React Native
- 📁 File-based routing with Expo Router
- 📏 Linter with [ESLint](https://eslint.org)
- 💖 Code Formatter with [Prettier](https://prettier.io)
- 🦊 Husky for Git Hooks
- 🚫 Lint-staged for running linters on Git staged files
- 🦺 Unit Testing with Jest and React Testing Library
- 🧪 E2E Testing with Detox
- 💡 Absolute Imports using `@` prefix
- 🗂 VSCode configuration: Settings, Tasks and extension for PostCSS, ESLint, Prettier, TypeScript, Jest

### Requirements

- Node.js 14+ and npm
- [iOS Simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Android Studio Emulator](https://docs.expo.dev/workflow/android-studio-emulator/)

Then, you can run locally in development mode with live reload:

```shell
npx expo start
# Or
npm run dev:ios
# Or
npm run dev:android
```

This will open the app in the iOS simulator or Android emulator.

### Testing

Testing is an important part of the development process and often the neglected one. This starter code comes up with Jest and React Testing Library for unit testing and Detox for E2E testing.

#### Unit Testing

To run the unit tests, run the following command:

```shell
npm run test
```

#### E2E Testing

To run the E2E tests, you first need to run the following command:

```shell
npm run e2e:prepare # Only need to run once
```

Then, you can run the following command to run the E2E tests:

```shell
npm run e2e:ios
# Or
npm run e2e:android
```
