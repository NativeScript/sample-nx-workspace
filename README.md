## Nx workspace setup for multiple NativeScript apps

This sample demonstrates using NativeScript 8.1+ cli capabilities to manage multiple NativeScript apps within an [Nx workspace](https://nx.dev).

### Prerequisites

* node 15+/npm 7+ is recommended
* [environment setup for NativeScript](https://docs.nativescript.org/environment-setup.html)
* ensure latest NativeScript cli (8.1+) is installed:

```
npm i -g nativescript
```

### Run the apps:

```
// install dependencies for workspace
yarn

// run app a
nx run mobile-app-a:android
nx run mobile-app-a:ios

// run app b
nx run mobile-app-b:android
nx run mobile-app-b:ios
```

### Clean workspace anytime

```
yarn clean
```
