Project to work through phonegap-nfc issue #132

Plugins are installed and committed to the repo

    $ cordova plugin add com.chariotsolutions.nfc.plugin
    $ cordova plugin add com.chariotsolutions.toast.plugin
    $ cordova plugin add org.apache.cordova.vibration
    $ cordova plugin add org.apache.cordova.dialogs

Platforms are not committed and must be added

    $ cordova platform add android

Plug in a device and run the code

    $ cordova run
