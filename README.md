# workreap-react-files-dm-website


Android and IOS react app for digitalmarket.com

change version in android/app/build.gradle -> 'defaultConfig'

react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res/


and then run cd android && ./gradlew assembleRelease


keep file name - "workreap-app" in local pc

 