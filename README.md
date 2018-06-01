
# react-native-call-blocking

## Getting started

`$ npm install react-native-call-blocking --save`

### Mostly automatic installation

`$ react-native link react-native-call-blocking`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-call-blocking` and add `RNCallBlocking.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCallBlocking.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCallBlockingPackage;` to the imports at the top of the file
  - Add `new RNCallBlockingPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-call-blocking'
  	project(':react-native-call-blocking').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-call-blocking/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-call-blocking')
  	```

## Usage
```javascript
import RNCallBlocking from 'react-native-call-blocking';

// TODO: What to do with the module?
RNCallBlocking;
```
  