# Realme 8 4G (RMX3085) TWRP device tree

This is a TWRP tree generated from [TWRP device tree generator](https://github.com/SebaUbuntu/TWRP-device-tree-generator) and some fiddling.

The Travis file is inspired by
[lopestom's](https://gist.github.com/lopestom/a5e6b690028cedd47d7e648a1035b358#12-create-a-file-named-travisyml-in-github-repo).
For now it's relying on the minimal TWRP manifest for Android 11 [over there](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp). Even at a
depth of 1 it's a humoungous tree to pull.
The build environment is [fr3akyphantom's droid-builder docker image](https://hub.docker.com/r/fr3akyphantom/droid-builder).

The ROM version used to extract a base recovery img from is `RMX3085export_11_A.19_2021081120010000`.

It's not guaranted to produce a functional TWRP recovery image at this point.
