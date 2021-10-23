# UPduino Himax Adapter

The UPduino Himax adapter is sold by Lattice Semiconductor and manufactured by tinyVision.ai Inc.

The design was done in the Altium tool and is open sourced with permission from Lattice Semiconductor.

## Design Notes
This design improves significantly on the original design of the Himax shield in the following ways:
1. 4 Layer board with proper ground/power planes and good layout
2. Voltage translation for the Himax sensor. The original design ran the sensor I/O at 3.3V which is outside the specified range, potentially causing long term degradation to the part.
3. Added IR LED drivers. The camera sensor can be replaced with a sensor that has no IR cut filter and the IR LED's can be used to illuminate the scene for gesture detection as well as other applications.
4. Improved microphone location: The 2 microphones in the original design were placed very close to each other resulting in no real gain from 2 mics. By spacing these as far apart as possible, we can use these for interesting applications such as beam forming for noise reduction, direction of arrival etc.

## Support
tinyVision.ai can provide support for this board on a best effort basis only. Please reach out to your local Lattice FAE as well. We are available to consult if you would like to incorporate the design into your application.