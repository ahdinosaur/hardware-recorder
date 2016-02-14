# hardware recorder

## idea

what if it was easy to record and upload audio and video of your last meeting?

## why?

i recently recorded two open space sessions from the recent Enspiral retreat using my poor phone recorder and my static server, yet got a very positive response from those who were or weren't present who valued the recording being available. i reckon we'd receive value if we reduce the barrier for recording audio and video of our various workshops, meetings, presentations, etc, so we more of what we do is available asynchronously and remotely.

## how?

here's a potential design:

- beaglonebone
- usb hub
- usb webcam
- usb microphone
- usb wifi dongle
- [lcd cape](http://www.seeedstudio.com/depot/7-LCD-Cape-for-Beagle-Bone-Black-Touch-Display-p-1697.html)
- 3d printed case (which allows attachment to tripod)
- standard camera tripod

setup beaglebone to boot to an electron app using debian and minimal [window manager](https://github.com/ahdinosaur/webkit-window-manager).

must be able to:

- connect to local wifi
- setup audio / video recording profiles
- start audio / video recording using a profile
- browse recordings
- setup upload targets
- upload recording to target
- ? browse to web page (over local mdns) to interact using another device
- ? choose usb microphone from list of available devices
- ? choose usb webcam from list of available devices
