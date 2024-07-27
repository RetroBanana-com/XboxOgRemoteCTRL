
# Xbox OG Remote CTRL

## Contents

 - [Kit Contents](#Kit Contents)
 - [FAQ](#FAQ)
 - [Usage](#Usage)
 - 

## FAQ

#### What is the Xbox OG Remote CTRL?

It is a device that allows you to turn on/off the original Xbox and open/close the disc drive using a web browser or a domotica system. The Xbox OG Remote CTRL is connected to the controls of the front panel, enabling you to turn it on/off via WiFi. No soldering or modifications to the case is needed. The device is press-fitted in the Xbox case.

#### For who is this product?

For lazy people like me that most of the time have a controller on the couch and don't want to stand up to turn on the Xbox but rather prefer to shout at Alexa/Google/Siri to turn on the original Xbox

#### Is a domotica system needed?

No, there is a web interface that allows you to toggle the Xbox and disc drive. This interface is mobile-friendly and accessible via http://xboxogremotectrl.local/. However, using a domotica system, you can more easily connect it to a voice assistant like Alexa/Google/Siri and create flows/scenes to include it in your current setup to turn on your television.

#### Does the device connect to the internet?

No, the device is only active on your local network and does not make calls to the internet. Firmware updates can be downloaded from our GitHub and need to be manually loaded from the web interface. 

#### Is there a Discord channel?

Yes, join us on https://discord.gg/FFCH2MpZ




## Usage

Via the mobile-friendly web interface you can toggle the xbox on http://xboxogremotectrl.local

Or you can setup your domotica system to make a GET request and use Alexa/Google/Siri to control it via voice.

Toggle Xbox: GET request to http://xboxogremotectrl.local/xboxToggle

Toggle disc drive: GET request to http://xboxogremotectrl.local/driveToggle

![alt text](https://i.imgur.com/HN90IPR.png)

