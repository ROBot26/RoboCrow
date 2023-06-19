# RoboCrow
Found out a good friend has a fear of crows. So I decided to create an automated crow that would use a proximity sensor to detect his presence, light up glowing red eyes, and let out a crow caw. 
The crow itself will be 3D printed. The brains of the crow will be an arduino nano. The proximity sensor is an IR LED and IR sensor that I stole from a parallax BOE robotics kit.


The code uses the PCM arduino library by David Mellis to play back the crow voice.
The crow voice is from pixabay https://pixabay.com/sound-effects/croworraven1-6749/
I used audacity to get the WAV to an 8khz, monaudal, 8 bit file with apropriate normalization. I then used the windows encoding tool from the following to get the sound data in an array I could drop in my arduino sketch: https://highlowtech.org/?p=1963
