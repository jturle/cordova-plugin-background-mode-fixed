## ChangeLog

#### Version 0.7.7

- Trying to fix Cordova 9 install (remove windows engine references)

#### Version 0.7.5

- Fixed onactivate call
- Merged new Android permissions

#### Version 0.7.4

- Fixed iOS 12.2 crashes
- Merged original repository Android source updates

#### Version 0.7.3

- fixed iOS crashes
- Check if screen is off on Android
- Wake-up device on Android
- Unlock device on Android

#### Version 0.7.2 (02.02.2017)

- Fixed app freeze on iOS using wkwebview-engine
- Websocket sample in SampleApp

#### Version 0.7.1 (30.01.2017)

- Bug fixes for iOS9 and Android
- Allow app to be excluded from recent list on Android

#### Version 0.7.0 (27.01.2017)

- **Features**
- Support for tAmazon FireOS
- Support for the browser platform
- Ability to configure icon and color on Android
- Allow app to move to foreground on Android
- Allow app to move to background on Android
- Allow app to override back button behaviour on Android
- New events for when the mode has been enabled/disabled
- **Improvements**
- Various enhancements and bug fixes for all platforms
- Support for latest platform and OS versions
- Multi line text on Android
- Multiple listeners for same event
- Compatibility with cordova-plugin-geolocation
- Compatibility with cordova-plugin-crosswalk-webview
- Compatibility with cordova-plugin-wkwebview-engine
- New sample app
- **Fixes**
- Silent mode issues on Android
- Lock screen issues on Android
- Callback not called on Android
- Notification shows app info with cordova-android@6
- Other apps audio interruption on iOS
- **Changes**
- Deprecate event callbacks
- Notification not visible by default on lock screen
- Remove ticker property on Android
- Remove unexpected back button handler
- Remove support for wp8 platform

#### Version 0.6.5 (29.02.2016)

- Published on npm
- Updated dependency ID for the device plug-in

#### Version 0.6.4 (03.03.2015)

- Resolve possibly dependency conflict

#### Version 0.6.3 (01.01.2015)

- [feature:] Silent mode for Android

#### Version 0.6.2 (14.12.2014)

- [bugfix:] Type error
- [bugfix:] Wrong default values for `isEnabled` and `isActive`.

#### Version 0.6.1 (14.12.2014)

- [enhancement:] Set default settings through `setDefaults`.
- [enhancement:] New method `isEnabled` to receive if mode is enabled.
- [enhancement:] New method `isActive` to receive if mode is active.
- [bugfix:] Events caused thread collision.

#### Version 0.6.0 (14.12.2014)

- [feature:] Android support
- [feature:] Change Android notification through `configure`.
- [feature:] `onactivate`, `ondeactivate` and `onfailure` callbacks.
- [___change___:] Disabled by default
- [enhancement:] Get default settings through `getDefaults`.
- [enhancement:] iOS does not require user permissions, internet connection and geo location anymore.

#### Version 0.5.0 (13.02.2014)

- **retired**

#### Version 0.4.1 (13.02.2014)

- Release under the Apache 2.0 license.
- [enhancement:] Location tracking is only activated on WP8 if the location service is available.
- [bigfix:] Nullpointer exception on WP8.

#### Version 0.4.0 (10.10.2013)

- Added WP8 support<br>
  The plugin turns the app into an location tracking app _(for the time it runs in the background)_.

#### Version 0.2.1 (09.10.2013)

- Added js interface to manually enable/disable the background mode.

#### Version 0.2.0 (08.10.2013)

- Added iOS (>= 5) support<br>
  The plugin turns the app into an location tracking app for the time it runs in the background.
