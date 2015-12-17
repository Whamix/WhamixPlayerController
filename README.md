# WhamixPlayerController
Unity3D first person navigation controller script for Oculus Rift that reduces VR sickness by progressively aligning body to head direction.
To install simply add to OVR camera rig as a component. Turn off the default OVRPlayerController.
There are two primary controls:
  - AlignMaxRot detmerines how much the body is allowed to re-orient at each step. Higher values allow trade off a tighter turning radius for a more floaty feeling.
  - HeadAlign can be used to toggle off the effect.

