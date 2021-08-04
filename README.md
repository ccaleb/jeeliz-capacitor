# Jeeliz Capacitor Example

This project takes a demo based on jeelizFaceFiler/demos/canvas2D from the [jeelizFaceFilter](https://github.com/jeeliz/jeelizFaceFilter) repo, and wraps it in a native app using [CapacitorJS](https://capacitorjs.com/).

## Project setup
```
npm install
```

### Running within a local web browser on desktop
```
npm run start
```

Launch browser and enter 'localhost' into address bar.

### Running within web browser on device
```
npm run start
```

Launch browser on mobile device and enter development computer's IP address into address bar.

### Building app on Android
```
npx cap add android
npx cap open Android
```

Within Android Studio add the following permissions to app/manifests/AndroidManifest.xml:

```
<uses-feature android:name="android.hardware.camera" android:required="false" />
<uses-feature android:name="android.hardware.camera.front" android:required="false" />
```

Connect an Android device to your computer.
From Android Studio, select the Run > Run App drop-down menu.

### Building app on iOS
```
npx cap add ios
npx cap open ios
```

Build and deploy your app to an iOS 14.5 device.


### Capacitor: Get started easily
See [Capacitor: Get started easily](https://capacitorjs.com/).
