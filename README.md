# ytmous-app
This is a standalone webview [ytmous](https://github.com/Yonle/ytmous) client that point to https://ytmous.herokuapp.com. 

## Notice
At installation, Google will prompt a security issue like **__Blocked by Play Protect__** with a reason `Play Protect does not recognize this app's developer`. Just tap **__Install Anyway__** to install ytmous frontend client to your android devices. This is common problem & nothing bad will happend to you.

I'm not recommend you to use this for daily use. Some function like **__Download__**, **__Background Playing__** support is seems forbidden due to cordova limits for webview-only app. So please use [ytmous](https://github.com/Yonle/ytmous) on your browser instead. Thank you for understanding.

## Building
```bash
cordova platform add android
cordova build --no-telemetry
```
