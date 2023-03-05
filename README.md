# anims
Create ASCII art animations for your terminal window

*Note*: this is now hosted at [Codeberg](https://codeberg.org/JBanana/anims)

This is a little framework to make it (relatively) easy to make animations of things crossing your terminal window.
Several examples are provided, and it's not too hard to make your own:

1. put all these files in a directory somewhere (e.g. by cloning this git repo)
2. make a new Bash script in the same place
3. define a printToBuffers function that generates a frame when given a position (see samples for how to do this)
4. source the `anim` file
5. (optional) override functions defined in `anim`
6. call `animate`

There are some helper scripts:
- ranim - plays one random animation
- anims - plays all the animations in a random order

The `muybridge*` sample animations are based on work by the Victorian photographer, Edweard Muybridge, who used multiple cameras to take a series of photos of moving objects.
He famously proved that a horse's hooves all leave the ground at once while galloping.
He took many sequences of shots of people and animals moving, and althought they are separate still photos, they work like the frames of a moving image.

The other samples are hand crafted ASCII art animation.
