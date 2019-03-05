# DTWSpells-Murphy
# How to Use
## Setup
- Download microbit-sendXYZ.hex on the microbit that is going to go on your wand
- Download microbit-receieveXYZ.hex on the microbit plugged into your computer
- download wand_to_osc2.py on your computer
## How to run
- open 3Spells.wekproj
- run wand_to_osc2.py with python3 wand_to_osc2.py
- Run and do the spells!
## Your names.
 Bridget Murphy
## What your goal is (i.e. what problem you are trying to solve).
 I wanted to create a wirless wand that I could use to train wekinator to recognize simple harry potter spells.
## How you approached the problem, including
### Sensors used
Accelerometer on microbit (XYZ)
### Feature extractor approach (if you tried several ways to do this, document your work)
I began using only one microbit because I had trouble with the wireless microbit solution last project, but was eventually able to get the wirless working. It ended up being a problem with transferring the hex files. When I was downloading just the hex files from github it was corrupting them somehow. When I downloaded the whole folder as a zip it worked.
## ML model structure - what you did and why, including results from experiments you tried along the way
I used DTW with 4 different classes. Based on the demos from Thursday I knew it would be a good idea to create a no spell sort of class to reduce noise and that worked quite well for me. My other 3 classes were the spells Incendio, Wingardium Leviosa, and Mimblewimble respectively. All 3 spells are fairly accurate, and that is demonstrated in the demo video.
## Ideas about how other might improve upon your work
I would like to include a fun output with some animation that shows the spell you are doing or maybe use the microbit LEDS to create that effect.

## For Reference
Look at spelllistnytf-2.jpg to find the spell motions to use!
Youtube Demo: https://youtu.be/ZGnSxulMtpw
