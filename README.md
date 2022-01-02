# Hyperion case for DIY SlimeVR!

The Hyperion is one of the smallest and slimmest cases yet for your DIY SlimeVR Trackers. <br>
With it's completely Toolless design and tolerances fine tuned specifically for FDM 3D Printers.<br>
The Hyperion is both easy to print and assemble!<br>
Every part is carefully though out and snaps together with ease.<br>
The Hyperion also offers support for various Battery sizes and types.<br>

## Index
- [Components](#Components)
- [Compatibility](#Compatibility)
- [Versions](#Versions)
- [Printing](#Printing)
- [Assembly](#Assembly)
- [Links](#Links)
- [License (MIT)](#License)

## Components

For the Hyperion you will need the following components:<br>

- [TP4056](https://www.aliexpress.com/item/32649780468.html)
- [MPU6050](https://www.aliexpress.com/wholesale?SearchText=MPU6050)
- [Wemos D1 Mini](https://www.aliexpress.com/wholesale?SearchText=D1+mini)
- [SS12D00G3 (switch)](https://www.aliexpress.com/wholesale?SearchText=SS12D00G3)
- [Battery](https://docs.slimevr.dev/components-guide.html) (*804040 is what the docs suggest 503759 is smaller and usually higher capacity*)
    - [804040](https://www.aliexpress.com/item/33021202630.html)
    - [503759](https://www.aliexpress.com/item/1005003257130562.html)
- [40mm straps](https://www.aliexpress.com/item/1005002350231996.html)<br>

*These straps are from the docs and are merely 25mm wide, the Hyperion is designed to fit up to 40mm straps for extra stability.*

## Compatibility

The Hyperion case offers compatibility for various battery types.<br>
For example: the 503759 supports any battery that is equal to or smaller than 5x37x59mm<br>
So if your battery is not a 503759 or 804040 but it is smaller than either one it will work!<br>
You might have to fill up the space a little bit to prevent the battery from sliding around.
A good example would be a 503450, which would fit just fine.<br>

###### But what about the BNO08X? <br>
Sadly as of now it is virtually impossible to get a BNO chip at a reasonable price.<br>
For that reason i'm sorry to say that this case does not ***yet*** officially support the BNO08X chips.<br>
If it does fit please let me know through Discord I am Smeltie#1999 on the [Official SlimeVR Discord server](https://discord.gg/SlimeVR)<br>
<br>
![Imgur](https://i.imgur.com/Uzk8tyqt.png)

## Versions

As you may notice there are a lot of different .STL files included in this project.<br>
This is because the Hyperion supports multiple Battery sizes and AUX/extensions.<br>
The names of the files indicate what the parts are for or what features they incorporate.<br>
To clarify some of the terminology:<br>
If the file name includes the following then:<br>

*- AUX*: This part has an opening for a ribbon/JST cable to an Extension.<br>
*- 503759*: This means the part is meant for batteries that are 5x37x59mm (or smaller)<br>
*- 804040*: This means the part is meant for batteries that are 8x40x40mm (or smaller)<br>
*- Slime*: This part has the SlimeVR logo on it, mostly for the lid.<br>
*- Blank*: This part has no print or logo on it, mostly for the lid.<br>


### So which parts do i need?
Ofcourse this is totally dependant on the battery you chose.<br>
In total you will have to print at least 4 components which are:<br>
Case, Tray, lid and Switch.<br>


So for example, you bought a 503739 (or smaller) battery.<br>
You would need the following:<br>
*- Case_503759.stl*<br>
*- Tray_503759.stl*<br>
*- Lid_503759.stl*<br>
*The switch in this case is universal and not dependant on battery size!*
<br>


### If you want to have a tracker that uses a AUX/Extension module beware<br>
For those you would need the following:<br>
*- Case_503759_AUX.stl*<br>
*- Lid_503759_AUX.stl*<br>
*The tray is not dependant on the AUX/Extension feature.*


## Printing
It is heavily suggested to print these components on an FDM 3D printer such as the Ender 3.<br>
This is because all the tolerances have been adjusted to accommodate a wide variety of FDM printers.<br>
Personally I printed my parts on a slightly modified Ender3 V2 using E-Sun PLA+ (gray).<br>

In terms of the printing itself, these parts don't need any support.<br>
Orientation wise the case, tray and switch can be printed as is.<br>
The lid you might want to turn 180 degrees so the flat side is against the bed:.<br>

![Imgur](https://i.imgur.com/Qy82Dcqm.png)

#### The Switch
As you might have guessed the switch is a little small and harder to print.<br>
However it is doable with the right settings!<br>
*- Bed Temperature* - 70c<br>
*- Initial layer speed* - 10mm/s<br>
*- Printing speed* - 20mm/s<br>
*- infill* - 0%<br>
*- layer height* - 0.08mm<br>
*- Location on the buildplate* - Close to the front or back not in the middle.<br>
*- build plate adhesion* - Brim<br>

![Imgur](https://i.imgur.com/j43d2Gm.png)<br>

*These settings worked well for me, they might not work for everyone*<br>
*Especially layer height might be challenging for some printers*<br>
*Just take your time and take it slow, i've printed more than a handfull now*<br>
*The reason i say don't print in the middle is because on many printers that's a low spot, and this would hinder the adhesion needed to keep this little part stuck down.*<br>


## Assembly



## Links



## License