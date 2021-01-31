# Youtube livestream translator
Well, this is a Python script which also uses **FFMPEG**. We translate using Google Translator. We also use Google's speech recognition. Currently works **only on Windows**.
For now it sucks, since it doesn't do any threading.

## Requierements
*Tested on Python 3.6.8. I don't know if it works on other versions of Python. Package versions below are the confirmed ones on which I tested the software.*
### Required modules:
- pafy 0.5.5
- requests 2.25.0
- json 2.0.9
- SpeechRecognition 3.8.1
- googletrans 4.0.0-rc.1
- cutlet 0.1.17
**You will also need ffmpeg, which you can download from here, or their website.**

## How to use
- Download the script
- Install the modules
- Open it in the cmd/powershell/git (any terminal, remember that it has to be on Windows)
- Copy and paste the Youtube Channel ID of the person who is streaming.
- Enter the input language (use a language code, for example *"ja"*, which stands for Japanese)
- Enter the destination language (also use a language code, for example *"en"*, which stands for English)
*After these steps, the script should start trying to detect the speech and to translate it. If you get an python exception saying **invalid source language**, then the language code you've provided was incorrect.*

## Additional info
The script is still in pre-alpha version. In the future, I plan on doing things in threads, stop the duplicate sentences,words problem, and many more. I also may make a gui for this script in the future.
