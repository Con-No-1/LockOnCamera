# LockOnCamera
Lock-on Camera &amp; Miscellaneous Tools 

Lock-on-Camera Instructions:
Add the actor compotent "AC_LockOnCamera" to the player character blueprint.
The player character must have a 3rd person camera with a spring arm.

Add the actor component "AC_LockOnTarget" to the any actors you want the player's camera to lock onto.

The camera will always prioritise the closest target to the player.

LOCK ON CAMERA CONFIG:
ENUM: Lock On Type: The type of target tracking you want the camera to do.
FLOAT: Interpolate Speed: The speed the camera rotates if using interpolation mode.

LOCK ON TARGET CONFIG:
BOOL: Enabled: Set whether the lock on camera is enabled on this actor.
BOOL: Auto-Enable by Distance: Set whether the lock on camera is enabled on this actor. Setting "Enabled" to true or false will still override the auto-enable functionality.
FLOAT: Auto-Enable Distance: Distance to player to auto-enable, if "Auto-Enable by Distance" is true.
BOOL: Override Lock on Type: Override the "Lock on Type" of  AC_LockOnCamera.
ENUM: Lock on Type: The type of target tracking you want the camera to do, if "Override Lock on Type" is true.
BOOL: Override Interpolation Speed: Override the "Interpolation Speed" of  AC_LockOnCamera.
FLOAT: Interpolation Speed: The speed the camera rotates if using interpolation mode, if "Override Interpolation Speed" is true.
