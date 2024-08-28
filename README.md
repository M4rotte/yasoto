# Yet another SoX toy

This script generates SoX command lines from few inputs (sample file, tempo, length, effect chain, patterns) that play synchronized. It can optionnaly write those commands to some files which can be executed later to replay the audio.

Some examples are in the “tests” directory. They have hardcoded file path you’ll very probably have to adapt to where your audio samples are located. 

This is work-in-progress shit, there isn’t any option handling yet, only plain positionnal arguments. It is on purpose, because as far as I won’t have implemented all the things I want to, it’s simpler for me to keep things right.

I wonder what’s your hobbies or needs so you stumbled there! ^^ But now you’re here, it’d be nice to critisize or make some suggestions!

This Bash+SoX “bricolage” has been inspired by the great [Chuck](https://chuck.stanford.edu/) programming language, notably the concept of “now” object, and the marvelous *“now = T - (now % T)”* awesome idea.
