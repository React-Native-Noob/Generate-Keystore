
## Debug Keystore :-
```
cd android/app/

keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000
```

## Release Keystore :-

```
cd android/app

keytool -genkeypair -v -keystore my-upload-key.keystore -alias my-key-alias -keyalg RSA -keysize 2048 -validity 10000

```
Reference :- https://reactnative.dev/docs/signed-apk-android
