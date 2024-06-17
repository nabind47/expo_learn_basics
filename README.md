# [EXPO LEARN](https://docs.expo.dev/tutorial/introduction/)

```sh
npx expo install expo-dev-client
```

```sh
npx expo start
```

```sh
eas init
```

```sh
eas build:configure
eas build --platform android --profile development
```

> **_For Android, the development build must be in the `.apk.` While the default Android format is `.aab`, which is ideal for Google Play Store distribution, it cannot be installed on devices or emulators. To create a `.apk` In `eas.json`, make sure that `developmentClient` is set to `true` under `build.development` profile. Then, run the `eas build command` with android as the platform and development as the build profile._**
