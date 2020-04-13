# [`react-native`](https://reactnative.dev/docs/environment-setup)

## react-native cli

- install react-native-cli

```sh
npm i -g react-native-cli
```

- init

```sh
npx react-native init awesome
```

- project start

```sh
cd awesome

npx react-native run-android
```

## expo-cli

- [`node 12 lts`](https://nodejs.org/ko/) install
- install expo-cli

```sh
npm install -g expo-cli
```

- init project

```sh
expo init expoawesome

  ----- Managed workflow -----
  blank                 a minimal app as clean as an empty canvas
  blank (TypeScript)    same as blank but with TypeScript configuration
  tabs                  several example screens and tabs using react-navigation
  ----- Bare workflow -----
  minimal               bare and minimal, just the essentials to get you started
  minimal (TypeScript)  same as minimal but with TypeScript configuration
```

- project start

```sh
cd awesome

yarn start
# you can open iOS, Android, or web from here, or run them directly with the commands below.

yarn android

yarn ios # requires an iOS device or access to a macOS for a simulator

yarn web
```
