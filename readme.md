# Be careful when using it because you can't revert it
Make sure to make a clone of your ragdoll to always have the characterJoint version of it saved.
## This is a joint converter that converts character joint of an object into configurable joints
This is mainly used for ragdolls, if you want to do active ragdoll for exemple.
## If you want it to change on play only and then goes back to characterJoint :
Just delete the editor part (line 2 to 18)
And change ConvertJoint() to Start()
