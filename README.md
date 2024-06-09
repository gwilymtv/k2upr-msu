## Overview

This is an MSU music pack for use with The Legend of Zelda: A Link to the Past
featuring music from [Unrealistic Project
Roadmap](https://lapfox.bandcamp.com/album/unrealistic-project-roadmap) by
Kitsune² (Halley Labs).

## Usage

These are track definitions only. You'll need the FLAC
files from the album to generate the SNES-compatible audio.

To generate the audio on Windows or Linux, just grab
[msupcm++](https://github.com/qwertymodo/msupcmplusplus) and put it in a folder
with `tracks.json` and all the album FLAC files. Run msupcm and it should
generate all the necessary `k2upr-*.pcm` files using this `tracks.json` as
input.

Then it's just a matter of using them with the game, which will require patching
in MSU-1 support.

Randomizers typically support MSU-1 automatically. For that, the Archipelago
project has a good [MSU-1 Setup
Guide](https://archipelago.gg/tutorial/A%20Link%20to%20the%20Past/msu1/en). I'll
defer to that guide as it heavily depends on your setup.

If you're not using a randomizer, you'll have to research how to patch MSU-1
support in yourself. I haven't done it so I can't help you there. 

## Notes

These definitions should be considered incomplete. I've done a couple of
playthroughs (here's a [Twitch livestream of
one](https://www.twitch.tv/videos/2167426238)) and I'm happy with the results
but there's some missing tracks ("You're So Moonish..." is used as a placeholder
as there's no "game over" music in ALTTP), some volume inconsistencies, and some
lazy track / cut / loop choices. After all, there's more tracks in the original
game than the album, so while it's not a perfect fit I've had fun with it all
the same. All I wanted was to fight Gannon to "Battle Against an Inscrutable
Machine" and I got that.

I'm sharing this as-is because I may not find time to polish it any further. If
you wish to tweak it more, msupcm++ has a [JSON
schema](https://github.com/qwertymodo/msupcmplusplus/blob/master/configs/schema)
to describe the available options and the [ALttPR Wiki Soundtrack
page](http://alttp.mymm1.com/wiki/Soundtrack) is a great reference resource for
the original tracks themselves.
