***

# Wipeout-Rewrite port for Dreamcast (updated 2025/10/13)

***
Wipeout-DC is a port of the Wipeout Rewrite project by Dominic Szablewski which can be found at:

https://github.com/phoboslab/wipeout-rewrite
***

***
This is the 9th bug-fix/update release for v2. It no longer requires custom KOS to be built.

If you have cloned/built Wipeout prior to 2025/10/13, you will need to grab a fresh copy of KOS `v2.2.1` tag from the official repo.

Current feature set includes: Extended draw distance, 16:9 anamorphic widescreen available,

reimplemented screen shake, restored PSX-original collision behavior, more.

Feature complete, almost 100% 60 FPS (100% is a strong guarantee), full music and sound,

VMU save/load for settings and high scores (6 blocks required), full input remapping support for Dreamcast controller.
***

## Download the disc image:

***
Go to the `Releases` section of the Github repo. A `7z` file is provided with `CDI`.

https://github.com/jnmartin84/wipeout-dc/releases/tag/v2.9

Note that playing in emulation is not supported. If you run into trouble and need a solution, buy a Dreamcast.

If you have a Dreamcast but you're using a GDEMU, you're also out of luck. I don't own one. I will never own one. I can't help.

If you file a Github issue related to emulation or GDEMU, I will close it without reading.
***

#### Default controls:

***
    dpad / analog stick up - nose down
    dpad / analog stick down - nose up
    dpad / analog stick left - turn left
    dpad / analog stick right - turn right
    L trigger - left air brake
    R trigger - right air brake
    A button - thrust / select
    X button - weapon
    Y button - view change

These may be changed in the controls menu, along with the sensitivty of the analog stick control.
***

##### Available video menu options
`Display` - `4:3` / `16:9 anamorphic`; standard aspect ratio or 16:9 for modern displays

`Texture Filtering` - `on` for bilinear filtering, `off` for point sampling.

***

#### Bonus menu

***

enable Rapier Class and bonus circuit.
***

### How to build

***
Setup Dreamcast compiler.

Clone KOS from the official repo. Check out the `v2.2.1` tag.

Build KOS.

From `wipeout-rewrite` repo directory, run `make` followed by `make cdi` or `make dcload` depending on how you are playing.

Data files are not provided. They can be extracted from the CDI file or the original data can be sourced and the music converted according to the notes in `HOWTO.md` .

Enjoy. - *jnmartin84*


***
***
***
