# Unreal-1st-Person-Camera

This is a full project consisting mainly of blueprint modification of the third person content pack. The purpose is to give a more realistic real-time walking / running animation.

This is the output: https://youtu.be/tspDNO9z9ek

You can also record the movement to an animation track in sequencer with the take recorder, then key in the amount of camera lag as a track. That's what I did in the above video - with the whip pan near the end having a much lower lag than during the walking.

I have also set up a Metasounds footstep blueprint graph in the anim blueprint which can be populated by your favourite footstep sounds.

Press the left mouse button to run, then the right to return to walking.

--------

Note that quick horizontal movement causes an issue due to the camera lag + how quick the full-body animation turns. Will try and fix and commit at a later date.
