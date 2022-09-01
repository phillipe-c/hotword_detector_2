# hotword_detector_2
The easy-to-use online activation word detection service (Mid 2021 release)

## About
This is a very simple python program that detects hotwords. It is not even close to be as accurate as e.g. snowboy and it does need (a fast) internet connection, but it is insanely easy to use and there's no need to do any configuration before running. It uses SpeechRecognition to detect specific words: if it detects the hotword, it returns 1, else, 0 (there's also an option where it calls a function when a hotword is detected). The interesting thing about this module is that it automatically adjusts the time needed to detect the word based on the length of the hotword choosen. For example, you'd take longer to say 'Parastratiosphecomyia' (genus of an insect) than to say 'hi'.

## Requirements:
To run the python script you'll need to install SpeechRecognition. To do that, type:
`pip3 install SpeechRecognition`

## License
LEAP/LISA License

Copyright (c) 2022, Phillipe Caetano. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, 
are permitted provided that the following conditions are met:

1. Phillipe Caetano must allow the redistribution and use in source and binary 
   forms, with or without modification of the software in a written permission 
   letter before the redistribution.

2. Phillipe Caetano can modify, remove, and add conditions in and out of this 
   license at any time, previously or after the written permission, and the 
   license of the redistributed software must immediately be modified to match 
   the new license.

3. In case of granted permission from Phillipe Caetano in the written permission 
   letter, the following conditions must be met:

   3.1. Redistributions in source and in binary form must reproduce the above 
        copyright notice, this list of conditions from topic 1 and below including 
        topic 1, and the following disclaimer in the documentation and/or other 
        materials provided with the distribution

   3.2. All advertising materials mentioning features or use of this software must 
        display the following acknowledgement: This product includes software 
        developed by Phillipe Caetano

   3.3. Neither the name of Phillipe Caetano nor the names of its contributors may 
        be used to endorse or promote products derived from this software without 
        specific prior written permission.

THIS SOFTWARE IS PROVIDED BY PHILLIPE CAETANO AS IS AND ANY EXPRESS OR IMPLIED WARRANTIES, 
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A 
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL PHILLIPE CAETANO BE LIABLE FOR ANY 
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT 
NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; 
OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, 
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE 
USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
