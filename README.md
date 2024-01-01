# Quake Weapon models (by Plague) optimized for VR

This is a VR weapon-pack for [QuakeSpasm-OpenVR](https://github.com/gameflorist/quakespasm-openvr).

It is based on the models by [Plague](https://members.optusnet.com.au/%7eplaguespak/).

The models were converted and animated for VR by Skizot.

Expansion pack weapons were added by codeflorist (by editing textures of Plague's existing weapons).

There is also a special package for usage with the [Alkaline](https://alkalinequake.wordpress.com/) mod.

## Usage with QuakeSpasm-OpenVR

To use them with QuakeSpasm-OpenVR, extract `pakz.pak` into your `id1` subfolder and rename it by changing the `z` to a number higher then the highest existing `pak`-file inside your `id1` folder. If you are using `pak` files from vanilla Quake this will be `pak2.pak`, and if you're using the Re-Release, it will be `pak1.pak`.

For the expansions, as as well as Arcane Dimensions, do exactly the same with the `hipnotic`, `rogue` and `ad` subfolders. There is also a special pack available for the Alkaline mod. Simply extract it into the `alk` subfolder.

You will notice, that the weapon offsets and scaling will be off. To switch to the correct offsets, access the `VR Options` in Quake's main menu and switch `Gun Model Offsets` from `Vanilla` to `Plague`. (Note that you will have to do that for each expansion/add-on you load, since Quake writes separate configs per mod.)
