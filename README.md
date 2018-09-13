The notch popularized by the iPhone X is officially called "cutout" by Google. So I will go by this term.
I guarantee no correctness of this list. Almost all of this was gathered by searching for images/articles.

## Usage

- Only on [Android Pie (9.0/API 28) onwards](https://developer.android.com/guide/topics/display-cutout/) that the cutout API is available. Which you will have an option to auto-letterbox the cutout and more. Currently many devices that feature the cutout starts from Android Oreo which does not have the API. You can use this database to match with programatically retrieved model number if the device has a cutout.
- You can get the status bar height [since Lollipop](https://developer.android.com/reference/android/support/v4/view/WindowInsetsCompat#getsystemwindowinsettop) (API 22) so it is possible to letterbox these devices based on that height before Android Pie. [Only after Pie API 28](https://developer.android.com/reference/android/view/WindowInsets#getDisplayCutout()) of course that the new method to get the cutout is available. (It can provide the exact `Rect` of the cutout area, so you can also avoid the cutout by other means than letterboxing.)
- Thus, in the future when a cutout devices came with Android Pie by default it would not be necessary to be in this CSV. We will be in this pain for just a while I believe.
- According to Google it is possible for a device to has up to 2 cutouts on the short edges. The position is not necessary in the center but can be in a corner of the short edge. This list does not tell you what kind of cutout the phone has. (Even though you can almost safely assume that most phones in this list will have 1 centered cutout at its top shorter edge.)

## How to contribute

If a new device with a cutout is introduced and you don't find it here, you can edit the CSV. Many of the data here was from [Google's Google Play supported devices CSV](http://storage.googleapis.com/play_public/supported_devices.csv). Please search for that phone's name and append it here instead of manually typing the metadata if it is available.

You can add the device even if it came with Android P by default.

## Need help

These phones have a notch but I don't know its correct model number and metadata. Someone with the actual device needs to debug this and put in the CSV correctly.
Additionally if you are too lazy to put in the CSV but found a new device you can put them here.

- Oppo R15
- Oppo R15 Pro
- Oppo F7
- Vivo V11
- Vivo V11i
- Sharp Aquos R2
- Doogee V
- Doogee X70
- Ulefone Armor 5
- Ulefone X

## License

This database is on [public domain (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/).