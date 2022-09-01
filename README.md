# hotword_detector_2
The easy-to-use online activation word detection service

## About
This is a very simple python program that detects hotwords. It is not even close to be as accurate as e.g. snowboy and it does need (a fast) internet connection, but it is insanely easy to use and there's no need to do any configuration before running. It uses SpeechRecognition to detect specific words: if it detects the hotword, it returns 1, else, 0 (there's also an option where it calls a function when a hotword is detected). The interesting thing about this module is that it automatically adjusts the time needed to detect the word based on the length of the hotword choosen. For example, you'd take longer to say 'Parastratiosphecomyia' (genus of an insect) than to say 'hi'.

## Requirements:
To run the python script you'll need to install SpeechRecognition. To do that, type:
`pip3 install SpeechRecognition`
