# SpeechRecognitionGame
This repository contains simple game made with unity and speech recognition API.

The project utilize google's speech recognition API to translate voice of user into text, sent back to game to be used later.<br>
This project use **[plugin](https://github.com/oshoham/UnityGoogleStreamingSpeechToText)** to be the API between unity and google's cloud to use speech recognition from google.
Shout out to **[oshoham](https://github.com/oshoham)** the creator of said plugin.

# How to use this project
Open this project in Unity editor and you may edit the project or build it into game and try.<br>

# Important
This project utilize Google's speech recognition which mean you need to have key file to access said service, Otherwise the game will be unable to recognize sound.<br>
Please refer to doc or **[plugin repository](https://github.com/oshoham/UnityGoogleStreamingSpeechToText)** for more info.

# How to play
This game has 2 methods of controlling, keyboard control and voice recognizing.<br>
In the gameplay, player will control character to collect box and attempt to earn score.
Player can move by hit keyboard control or use voice command to make character act according to player's word.<br>

When player collide with box, a window that show the word in the middle of screen and timer will show up.
Your objective is to say that word correctly in time.
If you say it either incorrectly or too late, you will miss a score for that box.<br>

After you collect all box a screen that display scores will show up, with option to proceed to next stage, repeat, or go back.
