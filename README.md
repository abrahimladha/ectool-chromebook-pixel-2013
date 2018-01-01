# ectool-chromebook-pixel-2013

This is the binary file for ectool for the Chromebook Pixel 1st gen from 2013.
It has the codename link. I tried to compile this myself from the chromiumos
project, but the data for link is no longer in the master branch and to
get other branches was a non trivial task with the chromiumos development
enviroment for just a single utility. Instead I found an old copy of chromiumos
for this laptop (version 57) and mounted it as a filesystem and just copied it
from there. With this, you can control your fanspeed, control your lightbar,
get backlight, battery, and thermal information. All the good stuff. The
ectool-samus-git from the AUR is for the 2015 model of the chromebook pixel,
and does not fully work. It can control fans, but not the lightbar, and some
other stuff. 
