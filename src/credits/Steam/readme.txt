Place on map and use the first four arguments to change behavior.

First argument controls direction. 0 is up, 1 is down, 2 is forward. For best results,
down-pointing spawners should be placed 2 or 3 map units below the ceiling.

Second argument chooses if it's a constant spawner, or spawns in bursts. Burst spawners use the
third argument and play a different sound.

Third argument controls the frequency of the bursts (divided by 16. I.e, 128 will end up as 8).
This is only used by the second argument.

Fourth argument silences the spawner. 0 will play the sound, 1 will not.

SH: Made wider