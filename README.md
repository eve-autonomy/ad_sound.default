# autonomous_driving_sound

## Overview
This is a default package of sound files for [ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager/).

Users can place your own sound files in a user-defined directories under sub-directory `wavs`.
Since this repository is a template, it contains only the `default` directory.

Sound file names in config have to be aligned with those file names in the `default` directory.

## List of supported files
See the [parameter description for ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager#parameter-description).

## Extensibility of this package
This package is a set of template default sounds.
If you want to use your own sound files, please see the following steps;
1. Fork this repository.
1. Create a new directory in the [wavs](#/wavs) directory and insert the new audio file in it.
1. Change the value `lang`, which works as a new directory name in [launch arguments of ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager#launch-arguments).
