# Parameter-Space-Explorer
Alternative Version of Latent-Space-Explorer. The user can map output parameter values from the neural network to arbitrary parameters in Ableton Live Set.

## Dependencies

1. Fluid Corpus Manipulation -> FluCoMa Max Package. You can download it directly from the Max Package Manager.

2. Jasch Objects -> Max Package downloadable from Max Package Manager.

## Setup

1. Load m4l device into an audio track.
2. Load the parameter-space-model-01.json file via the LoadModel Button inside of the device.
3. Check auto and predict buttons.
4. Route an audio signal into the device. Input parameters should move/adjust accordingly.
5. If model is correctly loaded, output parameters should also move automatically.
6. Now you can map each output parameter to one ableton live effect parameter of your choice
