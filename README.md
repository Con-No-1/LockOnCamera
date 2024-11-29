# LockOnCamera
Lock-on Camera &amp; Miscellaneous Tools 

Lock-on-Camera Instructions:
Add the actor compotent "AC_LockOnCamera" to the player blueprint.
Add the actor component "AC_LockOnTarget" to the target you want the players camera to lock onto.

You can choose the lock on type on the AC_LockOnCamera component, you can choose from snap and interpolate.
If you choose interpolate, you can set the interpolation speed (the speed at which the camera points towards the target.

You can disable the camera from locking onto a target by setting AC_LockOnTarget's "Enabled" boolean to false. This will make the player's camera revert to normal.

The camera will always prioritise the closest target to the player.
