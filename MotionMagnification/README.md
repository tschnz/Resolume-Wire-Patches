# Motion Magnification

Real-time motion magnification of small subpixel movements in videos. 

Based on [EVM: Eulerian Video Magnification for Revealing Subtle Changes in the World](https://people.csail.mit.edu/mrub/evm/) but simplified to run on the GPU. Runs with 60FPS @2k on a half-way decent laptop with dedicated GPU.

*Avoid videos with shaky cameras and compression artifacts. Make sure video is playing at normal speed and your Resolume Arena composition is set to match your video framerate for best results.*

## Options
| Name              | Type  | Description                                                                                                                  |
| ----------------- | ----- | ---------------------------------------------------------------------------------------------------------------------------- |
| Amplification     | Float | Strength of the magnification effect                                                                                         |
| Output            | Int   | Options "Mixed" for the motion amplified output combined with the original input, "Motion" for only the motion image         |
| **Motion Range**  | Group | Amplify slow or fast movements                                                                                               |
| Slowest           | Float | The lower the value the slower the movements that will be amplified (**has to be smaller than "Fastest"**)                   |
| Fastest           | Float | Upper limit for the movements. Higher value means faster movements are amplified like noise                                  |
| **Boost Details** | Group | Amplify small or large things                                                                                                |
| LoD 1 (Low)       | Float | How much the lowest level of detail should be amplified (lower values mean larger things are amplified)                      |
| LoD 2             | Float | Level of detail 2 magnification                                                                                              |
| LoD 3             | Float | Level of detail 3 magnification                                                                                              |
| LoD 4             | Float | Level of detail 4 magnification (high chance for compression artifacts being amplified)                                      |
| LoD 5 (High)      | Float | How much the highest level of detail should be amplified (higher values mean smaller things like random noise are amplified) |

## Preview
<video width="800" controls src="https://github.com/user-attachments/assets/254bbe5a-d143-4f78-8301-f6c257fd4b45"></video>
