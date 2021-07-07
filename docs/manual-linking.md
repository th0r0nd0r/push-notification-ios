# Manual linking

- Add the `.xcodeproj` to your project
```
node_modules/@react-native-community/push-notification-ios/ios/PushNotificationIOS.xcodeproj
```

- Add the following to `Link Binary With Libraries` phase
```
libCrispyPushNotificationIOS.a
```

More info on manual linking, [here](https://reactnative.dev/docs/linking-libraries-ios).
