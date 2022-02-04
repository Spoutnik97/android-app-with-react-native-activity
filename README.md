# Intention

This repository is an example of a basic android application with 2 activities inside which I added a React Native activity.
The [React Native documentation](https://reactnative.dev/docs/integration-with-existing-apps) about it is not updated, so I tried to make it work for the latest React Native version (0.67.2).

I started from the [Android tutorial](https://developer.android.com/training/basics/firstapp/creating-project), then I added an Activity with a React Native View

# Usage

## Prerequisites

- [React Native environnement configured](https://reactnative.dev/docs/environment-setup):
  - yarn
  - node
- Android Studio installed
- Java SDK 11 downloaded

## Install

- Run `yarn install` in the root folder

## Launch the application

- run `yarn react-native run-android` to launch the android application
  It will:

1. launch the metro bundler to bundle your javascript code
2. build your android native code
3. install the builded application on your device or your simulator
4. launch the application

## Develope

You can modify the [index.js](./index.js) file to see your modification in real-time thanks to the hot-reload!
