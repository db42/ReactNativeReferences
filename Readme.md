# React Native references and notes for iOS

### Background
These are the list of references I've found useful while working with React Native. It's been just a couple of weeks since I started RN and I plan to continue updating this document.

### React Native Debugging
Expo offers multiple ways to debug your React native apps. Use shake gesture in your expo app to see the debug options. This works both on iOS simulator and an actual device.

**Using Chrome  debugger**

Tap on `Debug JS Remotely` from debug options. This should open up a Chrome tab with the URL http://localhost:19001/debugger-ui.

In this tab, all the support offered by Chrome developer console is available for your react native application. Breakpoint, console logs, network request logs are all supported. Only missing support is you won't be able to do `inspect element`.

**GUI/Element Inspector**

Use `Toggle Element Inspector` from expo debug options to enable to GUI inspector inside your app.

### React Native Layout

- [Introduction to Flexbox for React Native](https://facebook.github.io/react-native/docs/flexbox)

- [Game to get more familiarity with Flexbox](https://flexboxfroggy.com/)

