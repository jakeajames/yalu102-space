# yalu102-space

![Yalu logo](https://github.com/jakeajames/yalu102-space/raw/source-code/yalu102/Assets.xcassets/AppIcon.appiconset/Icon-App-60x60%403x.png)

A jailbreak for 10.0-10.2 pre-iPhone 7 64bit

## Credits:
- ![Luca Todesco](http://twitter.com/@qwertyoruiop) - jailbreak
- ![Marco Grassi](http://twitter.com/@marcograss) - jailbreak help
- Ian Beer - mach voucher exploit (extra_recipe)

## Supported Devices and iOS versions

| Device | Version |
|---------|----------|
| iPad Pro  | iOS 10.0.0 -> iOS 10.2 |
| iPhone 6S  | iOS 10.0.0 -> iOS 10.2 |
| iPhone SE  | iOS 10.0.0 -> iOS 10.2 |
| iPhone 5S  | iOS 10.0.0 -> iOS 10.2 |
| iPad Air| iOS 10.0.0 -> iOS 10.2 |
| iPad Mini 2| iOS 10.0.0 -> iOS 10.2 |
| iPhone 6  | iOS 10.0.0 -> iOS 10.2 |
| iPad Mini 3| iOS 10.0.0 -> iOS 10.2 |
| iPad Air 2| iOS 10.0.0 -> iOS 10.2 |
| iPad Mini 4 | iOS 10.0.0 -> iOS 10.2 |
| iPod touch (6G)  | iOS 10.0.0 -> iOS 10.2 |


If you are already on iOS 10.2 with an iPhone 7, **stay there**. The actual exploit behind this still works, but the KPP bypass does not.

## Compiling:

1. `git clone` the repo.
2. Open the repo in Xcode
3. Change the bundle ID, as shown [here](https://www.reddit.com/r/sideloaded/wiki/how-to-sideload#wiki_changing_the_bundle_identifier_and_team)
4. Include the IOKit headers, and add them to your search path.
5. Run the project.

## Warnings

This jailbreak is a work in progress. Some things do not work, but most things do.

Do not install things that are untested.

**AppSync and other unsupported and untested software will probably throw your device into a bootloop or do other bad things.** Do not open an issue complaining that your device has been bootlooped because you installed other software. You have been warned.

## Installing

> DO NOT DOWNLOAD THIS SOFTWARE FROM OTHER SOURCES OTHER THAN THESE LINKS UNDER ANY CIRCUMSTANCE. IT IS VERY EASY TO BACKDOOR THIS SORT OF SOFTWARE TO CONTAIN MALWARE. PLEASE BE EXTREMELY CAREFUL. THESE MIRRORS ARE TRUSTED, BUT STILL CHECK THE SHA1.

* Download the pre-compiled version from the table below.
* [Check the SHA1 hash](http://onlinemd5.com) of the downloaded file (optional but recommended).
* Install using [Cydia Impactor](http://www.cydiaimpactor.com/).
* Open the application and follow instructions.


| Version | Download 
|---------|----------
| 3.0  | [Link](https://github.com/jakeajames/yalu102-space/raw/source-code/yaluspace.ipa)


## Contributing

Create a fork of the repository, make your changes and then create a pull request.
Please be sure to check if the pull request has been made before, before creating a new one. Note, any pull requests adding IOKit headers will be closed. Please respect copyright laws, and do not distribute / download IOKit headers from unofficial sources: they are bundled legally with macOS SDK

