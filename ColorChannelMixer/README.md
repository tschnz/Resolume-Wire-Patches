# Color Channel Mixer

Convert Red, Green, Blue, and Alpha channels into any other RGBA color separately.

"Weighted" makes sure color channels are never overexposed/clipped. For example with the Blue channel set to Green (RGBA -> RGGA) we dim the former Green and Blue channels so that the new Green channel stays between 0-1.

![Test image](img/CCM-colorwheel.png)

![Test image](img/CCM-frame.png)
