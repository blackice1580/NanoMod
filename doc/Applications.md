# Applications

## Provided Applications

The applications provided by NanoMod will be
* magic-mounted as system applications when installed as Magisk Module
* directly installed as system applications when installed in System Mode

Full list of provided applications
* Adaway [> F-Droid](https://f-droid.org/packages/org.adaway)
* Amaze (File Manager) [> F-Droid](https://f-droid.org/packages/com.amaze.filemanager)
* AnySoftKeyboard [> F-Droid](https://f-droid.org//packages/com.menny.android.anysoftkeyboard)
* BeHe Keybarod [> F-Droid](https://f-droid.org/packages/com.vlath.keyboard/)
* (Simple) Calendar [> F-Droid](https://f-droid.org/packages/com.simplemobiletools.calendar)
* Face Slim (Facebook client) [> F-Droid](https://f-droid.org/packages/org.indywidualni.fblite)
* (Simple) Gallery [> F-Droid](https://f-droid.org/packages/com.simplemobiletools.gallery)
* K-9 Mail [> F-Droid](https://f-droid.org/packages/com.fsck.k9)
* Kernel Adiutor [> GitHub](https://github.com/Grarak/KernelAdiutor)
* KeyPassDroid (Password Safe) [> F-Droid](https://f-droid.org/packages/com.android.keepass)
* Lightning (Browser) [> F-Droid](https://f-droid.org/packages/acr.browser.lightning)
* MPV (Video Player) [> GitHub](https://github.com/mpv-android/mpv-android)
* New Pipe (YouTube client) [> F-Droid](https://f-droid.org/packages/org.schabi.newpipe)
* Oandbackup (App backup and restore) [> F-Droid](https://f-droid.org/packages/dk.jens.backup)
* Odyssey (Audio player) [> F-Droid](https://f-droid.org/packages/org.gateshipone.odyssey)
* OpenCamera [> F-Droid](https://f-droid.org/packages/net.sourceforge.opencamera)
* OpenKeyChain [> F-Droid](https://f-droid.org/packages/org.sufficientlysecure.keychain)
* OpenLauncher [> F-Droid](https://f-droid.org/packages/com.benny.openlauncher)
* OpenWeatherMap Weather Provider [> GitHub](https://github.com/LineageOS/android_packages_apps_OpenWeatherMapProvider)
* OpenVPN [> F-Droid](https://f-droid.org/packages/de.blinkt.openvpn)
* Orbot [> Guardian Project](https://guardianproject.info/apps/orbot/)
* Orfox [> Guardian Project](https://guardianproject.info/apps/orfox/)
* QKSMS [> F-Droid](https://f-droid.org/packages/com.moez.QKSMS)
* Substratum (App) [> GitHub](https://github.com/substratum/substratum)
* Termux [> F-Droid](https://f-droid.org/packages/com.termux)
* Twidere (Twitter client) [> F-Droid](https://f-droid.org/packages/org.mariotaku.twidere)
* XDA Labs [> XDA](https://forum.xda-developers.com/android/apps-games/labs-t3241866)
  * source not (yet) available
* Yahoo Weather Provider [> GitHub](https://github.com/LineageOS/android_packages_apps_YahooWeatherProvider)

## Alter provided Applications

You can control what applications to install using the file

`.nanomod-apps`

on your device, in one of the following directories

* `/sdcard` (internal storage)
* `/persist`
* `/external_sd` (TWRP path to SD Card (if any))
* directory containing the zip file
* `/data` (fallabck)

All applications listed in that file will be installed. See the [default settings](.nanomod-apps), which are used when no `.nanomod-apps` configuration file was found. 

Alternatively you can also use the Setup Wizard instead of manual creation of the configuration file (if you've got an arm/arm64 device).

The syntax is pretty simple:

* one app per line
* name must be an exact match

applications managed by other setup variables (F-Droid, microG, PlayStore) are not effected by this file.
