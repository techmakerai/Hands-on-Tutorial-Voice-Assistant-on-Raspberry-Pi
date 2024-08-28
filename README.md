# Hands-on-Tutorial-Voice-Assistant-on-Raspberry-Pi
A hands-on tutorial to build a voice assistant with Google Gemini on Raspberry Pi

Following the YouTube video below to learn more about this project:    
https://youtu.be/uV6hJQcuW4w


Here is a schematic of the Raspberry Pi and LEDs    
<img src="https://github.com/techmakerai/Hands-on-Tutorial-Voice-Assistant-on-Raspberry-Pi/blob/main/schematic.png" width="720"/>
 
## Hardware:
1. Raspberry Pi (https://amzn.to/4bmstJa)
2. microSD card (https://amzn.to/4ay0HbY)
3. Audio amplifier (https://amzn.to/3JjPWy9)
4. Mini speaker (https://amzn.to/3TB9Pp3)     
5. USB Microphone (https://amzn.to/3HGGSCA) 
6. (optional) LEDs and resistors (https://amzn.to/3Jg4Yoz)
7. (optional) Breadboard (https://amzn.to/3V3ruWY)
8. uni SD Card Reader (https://amzn.to/3yYhwze) 

## Update and Upgrade the Raspberry Pi OS 

```console
sudo apt update
sudo apt upgrade
```


## Install a Firewall for the Raspberry Pi   

```console
sudo apt install ufw
sudo ufw allow ssh
sudo ufw enable
```

## Install Python and Pip
```console 
sudo apt install python3 python3-pip python3-venv
```

## Create Python Virtual Environment in the home directory 
```console 
python3 -m venv .venv
```

## Install Packages for Processing Audio Data
```console  
sudo apt install portaudio19-dev python3-pyaudio flac espeak 
```
## Create a Project Folder 
```console  
mkdir projects
cd projects
mkdir va
cd va 
```

## Activate Python Virtual Environment 
```console 
source ~/.venv/bin/activate
```  

## Install Python Packages 
You will need to install the following packages to run this code: 

```console
pip install -q -U google-generativeai
pip install speechrecognition gtts pygame gpiozero
```

## Run the Python Code
```console 
python gva7_led.py
``` 



\* As a participant in the Amazon Associate Program, we earn from qualifying purchases.  
