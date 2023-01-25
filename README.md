## expo-router@1.0.0-rc2 / React Native 0.71.1

This repo demonstrates integration of `expo-router` with a new React Native project generated with `npx react-native` init with `react-native@0.71.1`.

You can see the steps in each commit:

- Initialize app: `npx react-native init`
- Install Expo Modules API: `npx install-expo-modules@latest`. Also changed entry point name to `main`.
- Install `expo-router`: followed these steps https://expo.github.io/router/docs/ & also installed `react-native-gesture-handler`.
- Lastly, I changed the scripts for `ios` and `android` to use Expo CLI instead of React Native CLI.

## How to run

- Clone the repository
- Run `yarn`
- Run `yarn ios`