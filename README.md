
# react-native-local-hotspot

## Getting started

`$ npm install react-native-local-hotspot --save`

### Mostly automatic installation

`$ react-native link react-native-local-hotspot`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.drake.reactnative.RNLocalHotspotPackage;` to the imports at the top of the file
  - Add `new RNLocalHotspotPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-local-hotspot'
  	project(':react-native-local-hotspot').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-local-hotspot/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-local-hotspot')
  	```


## Usage
```javascript
import RNLocalHotspot from 'react-native-local-hotspot';

// TODO: What to do with the module?
RNLocalHotspot;
```
  