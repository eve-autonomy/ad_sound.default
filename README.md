# autonomous_driving_sound

## Overview
This is a package for managing parameters to make [ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager) easier to use.

Users can place and use user-defined directories in `wavs` directory.
Since this repository is a template, it contains only the `default` directory.

The list of names of sound files managed in the use-defined directory should be aligned with those in the `default` directory.

## List of supported files
See the [parameter description for ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager#parameter-description).

## Extensibility of this package
This package is a template as a parameter configuration.

If you want to change sound files in this package and use it, follow the steps below.
1. Fork this repository to create a new one.
1. Create a new directory in the [wavs](#/wavs) directory and insert the new audio file in it.
1. Change the value `lang`, which works as a new directory name in [launch arguments of ad_sound_manager](https://github.com/eve-autonomy/ad_sound_manager#launch-arguments).
