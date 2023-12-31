# Alastria Prototype Ionic App

Example mobile application to implement Alastria user stories

## Starting 🚀

These general instructions will allow you to get a copy of the project running on your local machine for development and testing purposes. For instructions for specific operating systems, see:
* [Docker](doc/install_docker.md)
* [Ubuntu 16.04 LTS](doc/install_ubuntu1604.md)

Clone the project:
```
git clone https://github.com/alastria/alastria-wallet.git
```

## Installation 🔧

### Requirements
* Node.js 10+
* Yarn / Npm
* Ionic 5.2.1 / Angular 8.2.14
* Android SDK / iOS SDK
* Cordova 9.0.0+
* Barcode Scanner

```
yarn install
```
or
```
npm install
```

### Run application in browser
```
yarn start:browser
```
or
```
npm run start:browser
```

### Run application in emulator or in mobile debug mode
```
yarn start:android:device
```
or
```
npm run start:android:device
```

### Android apk build
```
yarn start:android
```
or
```
npm run start:android
```

The app supports Android version 9, later versions are not supported.

## Deeplinks
To access the application through a deeplink you can access this link to see examples: https://codepen.io/samuelsan95/pen/poJwmrY