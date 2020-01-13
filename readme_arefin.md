 type null >readme_arefin.md

 works in cmd only not in powershell.

 https://docs.nativebase.io/docs/GetStarted.html



 Setup with React Native
**react-native init AwesomeNativeBase**
cd AwesomeNativeBase
Copy
Install NativeBase

npm install native-base --save
Copy
Install Peer Dependencies
The peer dependencies included from any npm packages does not automatically get installed. Your application will not depend on it explicitly.

react-native link
Copy
You've successfully setup NativeBase with your React Native app. Your React Native app is ready to run on iOS and Android devices.

Check out the NativeBase KitchenSink an example of NativeBase components implementation. Here's the source code for NativeBase KitchenSink

**package.json file**

```json

{
  "name": "AwesomeNativeBase",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "android": "react-native run-android",
    "ios": "react-native run-ios",
    "start": "react-native start",
    "test": "jest",
    "lint": "eslint ."
  },
  "dependencies": {
    "react": "16.9.0",
    "react-native": "0.61.5"
  },
  "devDependencies": {
    "@babel/core": "^7.8.0",
    "@babel/runtime": "^7.8.0",
    "@react-native-community/eslint-config": "^0.0.6",
    "babel-jest": "^24.9.0",
    "eslint": "^6.8.0",
    "jest": "^24.9.0",
    "metro-react-native-babel-preset": "^0.56.4",
    "react-test-renderer": "16.9.0"
  },
  "jest": {
    "preset": "react-native"
  }
}


```