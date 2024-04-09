# Hazrat Ali
# Software Engineer 

# FireBase Setup ( React Native)

# Using npm
npm install --save @react-native-firebase/app

# Using Yarn
yarn add @react-native-firebase/app

# Dependency

project.ext {
  set('react-native', [
    versions: [
      // Overriding Build/Android SDK Versions
      android : [
        minSdk    : 19,
        targetSdk : 33,
        compileSdk: 33,
      ],

      // Overriding Library SDK Versions
      firebase: [
        // Override Firebase SDK Version
        bom           : "32.8.0"
      ],
    ],
  ])
}