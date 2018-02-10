# handson-voice-kit
google voice kit Hands-On
# Make your Raspberry Pi speak with Google Voice Kit  

![](https://statics3.seeedstudio.com/seeed/file/2017-10/bazaar597923_aiyk1.jpg)  

>_"Our goal with AIY Projects has always been to make artificial intelligence open and accessible 
for makers of all ages,"_- Bill Rutledge, director of AIY Projects at Google

## Introduction

The Google AIY Voice Kit,that can be built as a voice recognition kit using the Google Assistant on Raspberry Pi.It can be made capable of various tasks, including detecting hotwords, understanding natural language and responding to voice commands.

**The best part of the Google Voice Kit is that it does not require any soldering for its functioning!!!!!**

The Google AIY Voice Kit contains the same Voice HAT accessory board, microphone board,Plastic standoffs,Speaker,Arcade-style push button,4-wire button cable,5-wire daughter board cable,two cardboard frames  
![materials](https://user-images.githubusercontent.com/35935951/35828458-80398bb8-0ae5-11e8-9ab8-952d869e945e.jpg)
                     

## Get all the hardware

In addition with the Google Voice Kit Raspberry Pi 3,SD card,screwdriver,tape is required to make this project.

## Set up your Hardware
* Place the two standoffs into the two yellow (near the edge of Raspberry Pi 3).    
_NOTE: Make sure that they are fixed completely into place._    
       ![rpi1](https://user-images.githubusercontent.com/35935951/35770502-4628645c-0942-11e8-8aa2-bc96b72f6693.png)   ![rpi2 - copy](https://user-images.githubusercontent.com/35935951/35770431-4c69bf4c-0941-11e8-8fca-603717e0eccb.png)  

* Take your Voice HAT accessory board and attach it to the Raspberry Pi 3 box header. Voice HAT should be placed such that I/O pins of Raspberry Pi 3 as well as that of Voice HAT line up with each other. Gently push the Voice HAT and snap them together.   
 ![pic3](https://user-images.githubusercontent.com/35935951/35770508-4c226fa6-0942-11e8-95ba-4e659982e582.png)   ![pic4](https://user-images.githubusercontent.com/35935951/35770457-9c9df262-0941-11e8-9ed5-bf64eee6f8ff.png)  
  
* Insert the speaker’s red wire into the “+” terminal on the Voice HAT blue screw connector and the black wire into the “-” terminal. Now screw the wires in place with a screwdriver.  
                ![pic5](https://user-images.githubusercontent.com/35935951/35770626-cad4552e-0944-11e8-98c6-9489821c7276.png)  
                
* Get the 4-wire button cable, it has a white plug on one end and four wires (blue, red, white, black) having metal contacts on the other end. Insert the plug into the white connector label as “Button” on the Voice HAT board.  
![pic6](https://user-images.githubusercontent.com/35935951/35770725-801441aa-0946-11e8-963f-67e719a38325.png)  

* Find the Voice HAT Microphone board and the 5-wire daughter cable from kit. Insert the 5-wire plug into the Microphone board.  
  ![pic7](https://user-images.githubusercontent.com/35935951/35770762-66ca8eba-0947-11e8-8e6e-b3b3f0e014c1.png)  
  
* Plug the Microphone board to the Voice Hat board using the white connector labelled “Mic”.  
 ![pic8](https://user-images.githubusercontent.com/35935951/35770764-78b7991a-0947-11e8-9826-e949a0148e75.png)  
 
* Now it’s turn to build the box. Take the larger cardboard piece with holes on one side. Fold along the creases as shown in the picture. It will be the outer frame.  
  ![pic9](https://user-images.githubusercontent.com/35935951/35770638-fae74dfc-0944-11e8-9522-43c0f2449c6a.png)  
  
* Take the other cardboard piece that will build the inner frame to hold the hardware. Fold the flaps labelled 1 and 2 along the creases. The flap above the 1 and 2 folds has a U-shaped cutout. Push it out.  
![pic10](https://user-images.githubusercontent.com/35935951/35770947-0971079a-094b-11e8-9963-9adc957e7399.png) ![pic11](https://user-images.githubusercontent.com/35935951/35770968-5deeb68c-094b-11e8-873f-80ed38c26781.png)  

* Then fold the rest of the flaps outward The U-shaped flap should lay flush with the box side.    
![pic12](https://user-images.githubusercontent.com/35935951/35771076-e0b2b04a-094c-11e8-933b-48c904d5249a.png)  
  
* Take the speaker and slide it into the U-shaped pocket on the cardboard frame as shown.  
![frame-5](https://user-images.githubusercontent.com/35935951/35827340-9ef73694-0ae1-11e8-86ef-757f6f3b8d09.jpg)  

* Turn the cardboard frame around. Take the Raspberry Pi  attached to Voice HAT board and slide the it into the bottom of the frame below flaps 1 and 2.The USB ports on the Pi should be kept away from the cardboard frame.   
![frame-6](https://user-images.githubusercontent.com/35935951/35827811-69ad1858-0ae3-11e8-928b-07321029eac5.jpg)  

* Take the outer cardboard frame and find the side with the seven speaker holes. Slide the inner cardboard frame having hardware, into the outer cardboard frame, keeping the speaker on the holes side of the frame. Gently place the Raspberry Pi board at the bottom of the box.  
![pic15](https://user-images.githubusercontent.com/35935951/35771086-f91a21d6-094c-11e8-8c12-26842e603bce.png) ![pic16](https://user-images.githubusercontent.com/35935951/35771090-201fd9b0-094d-11e8-88a5-5b36a6aad573.png)  

* Take the arcade button and set it into the top of your cardboard box.   
![pic17](https://user-images.githubusercontent.com/35935951/35827521-530c031c-0ae2-11e8-82d6-4cc6717c2f63.png)  

* On the other side, screw on the washer. Connect the four coloured wires with metal contacts connected to the Voice HAT board to this 
  push button. Connect the wires in the positions indicated by the image.  
      * Blue: bottom left  
      * Red: bottom right  
      * Black: top right  
      * White: top left  
      ![pic18](https://user-images.githubusercontent.com/35935951/35827511-4ce861e2-0ae2-11e8-8a65-082eb8e57577.png)![pic19](https://user-images.githubusercontent.com/35935951/35827804-61502f38-0ae3-11e8-920e-ea83629d4cdb.png)  

* Attach the microphone board to the cardboard using tape.   
![pic20](https://user-images.githubusercontent.com/35935951/35827488-3f257aea-0ae2-11e8-86b9-27c861369d35.png)  

## Set up your device
1. Get an SD card(minimum of 8 GB)  
2. Get the Voice Kit SD image<https://aiyprojects.withgoogle.com/voice#assembly-guide-1-get-the-voice-kit-sd-imag>    
3. Write the image to an SD card using Etcher.io<https://etcher.io/>  
![1_tyypl1a4izzphbyxatk62w 1](https://user-images.githubusercontent.com/35935951/36050436-8c6cc3f8-0e0c-11e8-9e34-3a3825d9cc2e.png)

### Booting up your device
   1. Connect the Raspberry Pi to peripherals USB Keyboard, USB Mouse and HDMI Monitor.  
   ![screenshot 52](https://user-images.githubusercontent.com/35935951/36050686-7a696d36-0e0d-11e8-9077-28c38c2a50db.png)  
   2. Insert your SD card (having Voice Kit SD image).  
   3. Plug in the power supply (into the slot just next to where HDMI Monitor is connected),  
      the Raspberry Pi will begin booting up.  
      ![screenshot 42](https://user-images.githubusercontent.com/35935951/36048400-2197262e-0e05-11e8-8777-aa7c5121d9fd.png)
   
### Connecting to Google Cloud Platform
   Open web browser and go to <https://console.cloud.google.com>  
   1. Sign into Google Cloud Platform using your Google account and then enable the API.  
      Go to Home->Dashboard->Create Project( give any name )  
      ![screenshot 44](https://user-images.githubusercontent.com/35935951/36049241-1398d88a-0e08-11e8-953e-8cf4de31fc72.png)  

   2. Go to Cloud Console->enable the Google Assistant API.   
   ![screenshot 49](https://user-images.githubusercontent.com/35935951/36049272-2d9beb3c-0e08-11e8-8ed0-6d148f01056f.png) ![screenshot 50](https://user-images.githubusercontent.com/35935951/36049279-358b4e8c-0e08-11e8-882b-17c0940d9e18.png)  
   3. Go to Cloud Console->API Manager->Credentials->Create Credentials.Choose create an OAuth 2.0 client.  
   ![screenshot 46](https://user-images.githubusercontent.com/35935951/36049250-1f74eda6-0e08-11e8-8002-f2adc4c4cea0.png) ![screenshot 47](https://user-images.githubusercontent.com/35935951/36049253-22b9b92e-0e08-11e8-9bd7-35df65b15473.png)

   _NOTE:If this is your first time creating a client ID, you’ll need to configure your consent screen by clicking Configure consent     screen. You’ll need to name your app._  
   4. A new window will appear. Click OK.  
      In the Credentials list, find your new credentials and click the download icon on the right.  
      ![screenshot 48](https://user-images.githubusercontent.com/35935951/36049261-27d5835c-0e08-11e8-9935-24a0a8c14863.png)  
   5. Find the JSON file you just downloaded (client_secrets_XXXX.json) and rename it to assistant.json.   
      Then move it to /home/pi/assistant.json  
   6. Go to the Activity Controls panel.  
      NOTE:Keep in mind to log in with the same Google account as before.  
   7. Turn on the following:  
      -	Web and app activity  
      -	Device information  
      -	Voice and audio activity  

### Use your device
#### Start the ASSISTANT LIBRARY DEMO APP  

Start the assistant library demo app by double-clicking "Start dev terminal" on the Desktop and enter  

`src/examples/voice/assistant_library_demo.py`  
To start a conversation with the Google Assistant, say "Okay, Google" or "Hey Google". When you are done, press Ctrl-C to end the application.  

#### START THE ASSISTANT GRPC DEMO APP
Double-click "Start dev terminal" on the Desktop and enter  

`src/examples/voice/assistant_grpc_demo.py`  

Unlike the assistant library demo, this demo does not support hotword detection. To ask Google Assistant a question, press the arcade button and speak. When you are done, either press the arcade button and say "goodbye", or simply press Ctrl-C to end the application.

### Do Somethimg more

Add a new voice command to kit

```"""A demo of the Google CloudSpeech recognizer."""

import os

import aiy.audio
import aiy.cloudspeech
import aiy.voicehat


def main():
    recognizer = aiy.cloudspeech.get_recognizer()
    recognizer.expect_phrase('turn off the light')
    recognizer.expect_phrase('turn on the light')
    recognizer.expect_phrase('blink')
    recognizer.expect_phrase('repeat after me')

    button = aiy.voicehat.get_button()
    led = aiy.voicehat.get_led()
    aiy.audio.get_recorder().start()

    while True:
        print('Press the button and speak')
        button.wait_for_press()
        print('Listening...')
        text = recognizer.recognize()
        if text is None:
            print('Sorry, I did not hear you.')
        else:
            print('You said "', text, '"')
            if 'turn on the light' in text:
                led.set_state(aiy.voicehat.LED.ON)
            elif 'turn off the light' in text:
                led.set_state(aiy.voicehat.LED.OFF)
            elif 'blink' in text:
                led.set_state(aiy.voicehat.LED.BLINK)
            elif 'repeat after me' in text:
                to_repeat = text.replace('repeat after me', '', 1)
                aiy.audio.say(to_repeat)
            elif 'goodbye' in text:
                os._exit(0)


if __name__ == '__main__':
    main()
```

















                
                
