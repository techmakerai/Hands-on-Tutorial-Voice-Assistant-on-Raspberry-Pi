# Hands-on-Tutorial-Voice-Assistant-on-Raspberry-Pi
A hands-on tutorial to build a voice assistant with Google Gemini on Raspberry Pi

Following the YouTube video below to learn more about this project: 
https://youtu.be/uV6hJQcuW4w


Here is a schematic of the Raspberry Pi and LEDs    
<img src="https://github.com/techmakerai/Google-Gemini-Voice-Chatbot-on-Raspberry-Pi/blob/main/PaspberryPiSchematic.jpg" width="720"/>

## Materials 

1. Raspberry Pi (https://amzn.to/4bmstJa)
2. microSD card (https://amzn.to/4ay0HbY)
2. Audio amplifier (https://amzn.to/3JjPWy9)
3. USB Microphone (https://amzn.to/3HGGSCA) 
4. Mini speaker (https://amzn.to/3TB9Pp3)    
5. (optional) LEDs and resistors (https://amzn.to/3Jg4Yoz)     

## Set System Environment Variables 

GOOGLE_API_KEY=(API key from Google)   
PYGAME_HIDE_SUPPORT_PROMPT=hide

## Install Python and Packages 
You will need to install the following packages to run this code: 

```console
pip install -q -U google-generativeai
pip install speechrecognition gtts pygame gpiozero
```
   
If you have Python 3.12 or newer, also install the "setuptools" package,       

```console
pip install setuptools
```    

You may need to create a Python virtual environment first.        

\* As a participant in the Amazon Associate Program, we earn from qualifying purchases.  
