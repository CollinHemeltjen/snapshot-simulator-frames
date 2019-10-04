# snapshot-simulator-frames
A replacement for the standard (fastlane) snapshot iPhone frames.

I made screenshots of all the current used iPhone simulator frames. And added the offsets to be compatible with the fastlane snapshot integration.

## How to use
- Clone or download this repo
- Add to ~/.fastlane/frameit
- Change the Framefile.json to contain:
  ```"device_frame_version": "snapshot-simulator-frames"```
- Done, your frameit will now use the simulator frames instead of the facebook ones.
