# Wire Patches

This is a private collection of [Resolume](https://resolume.com/) Wire patches. Something between case studies and actually useful stuff. 

## Legal Disclaimer

Everything is under **GPL-3** license which means you may use it commercially. However, if you use this as a base for another patch, it has to fall under GPL-3, too. You are **not allowed to sell** derivative work based on these patches but open source it and give back to the community.

For more info see https://www.tldrlegal.com/license/gnu-general-public-license-v3-gpl-3

## Patches

### Color Channel Mixer (Effect)

Turns R, G, B channels into any other color while it's possible to preserving overall luminance. Basically a base vector rotation in color space.

![Test image](ColorChannelMixer/img/CCM-colorwheel.png)

### Interactive Game of Life (Effect)

Cellular automaton simulating Conway's Game of Life. Input can be used as seed and the input movement influences the simulation.

![Game of Life simulation](InteractiveGameOfLife/img/gol_preview.gif)

### Laplace Pyramid Reconstruction (Effect)

Creates a 5 layer Laplace pyramid from the input and then reconstructs the original image from it. Useful for learning about image pyramids and multi-scale image processing.

![Laplace Pyramid](LaplacePyramidReconstruction/img/LaplacePyramid0.png)

### Motion Magnification (Effect)

Real-time motion magnification of small subpixel movements in videos. 

![Preview of Motion Magnification patch](MotionMagnification/img/momag_preview.gif)


### Physarum (Effect)

Particle system simulating the behavior of *Physarum polycephalum* (slime mold). Particles can bee steered by an input image. 

![Wire logo recreated with physarum patch](Physarum/img/Physarum_thumbnail-still.png)

### Unsharp Masking Balanced (Effect)

Unsharp Masking / Sharpening effect but with Threshold for noise reduction and Balance to control the amount of darkening vs brightening around edges.

![Preview of Unsharp Masking Balanced patch](UnsharpMaskingBalanced/img/unsharp_mask_preview.png)