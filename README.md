![logo](https://i.imgur.com/jinBPJU.png "logo")

# SXLoader
A modified version of [NXLoader](https://github.com/DavidBuchanan314/NXLoader) Launch SX OS or other Fusée Gelée payloads from stock Android

Heavily based on [Fusée Gelée](https://github.com/reswitched/fusee-launcher/) and [ShofEL2](https://github.com/fail0verflow/shofel2). [fusee.bin](https://github.com/ktemkin/Atmosphere/tree/poc_nvidia/fusee) is bundled as a default payload

## Note: Any proprietary payloads are neither tested nor supported by this software.

## [Get the APK release](https://github.com/annson24/SXLoader/releases)

## HOWTO:
- Launch the app.
- Plug in your Switch. (On my Galaxy S8, I used a cheap Type-A to C cable, and an A-to-C OTG)
- Put the Switch into RCM mode. (Note: your switch will power on by itself when plugged in, be sure to hold VOL+).
- Grant permission to the app to access the USB device.
- Enjoy!

Note: The app does not need to be running in order to launch the payload. The phone can even be locked!

## FAQ:
- Did you made tis?: Yes...No. DavidBuchanan314 made NXLoader, which SXLoader was heavily based, I mean even this description is only modified to satisfy SXLoader. Most of the credits should go to him.
- Why use this over a web-based launcher?: No internet required, and can auto-launch even if your phone is locked. Plug and play!
- Will it brick my phone/switch?: Hopefully not, but I an certainly not responsible if it does!
- Does it need root?: Nope!

## TODO:
- Nothing, we just wait for an update with NXLoader

For anyone who wants to look at the exploit source, the magic happens [here](https://github.com/annson24/SXLoader/blob/master/app/src/main/java/io/github/annson24/sxloader/PrimaryLoader.java).
