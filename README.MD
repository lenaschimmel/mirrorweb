# mirrorweb ↺ qǝʍɹoɹɹᴉɯ
This simple app lets you use one Android device simultaniously by two people sitting opposite each other.

<p align="center">
  <img src="https://lenaschimmel.de/static/mirrorweb/screenshot01.png" width="360" height="640" alt="Screenshot of this website viewed with mirrorweb"/>
</p>

The qǝʍɹoɹɹᴉɯ app features two webviews within a single activity, with the "upper" one rotated by 180 degrees. Both can be operated independently. One user can use the default back button of the device, the other one has a back button in the action bar.

Currently qǝʍɹoɹɹᴉɯ does not even have an address bar. So how to open a web page? When opening a URL (http or https) from a non-browser-app, you can choose mirrorweb like you would choose any other browser. Or you can use the "share" action from your regular browser and share the URL with mirrorweb.

## Apk download
You can download the first alpha release of qǝʍɹoɹɹᴉɯ [here](https://lenaschimmel.de/static/mirrorweb/mirrorweb.apk).

## Development note
This app was coded quickly and dirtily in about one hour. It's based on Android Studio's `FullScreenActivity` but since something was broken with that, some of the code was commented out.
