# enonic-app-demo-qbrick
## About
This is an app for the Enonic Market, and a demo on how to use the qbrick lib(see https://github.com/QbrickIPO/enonic-lib-qbrick)
This app enables use of qbricks video player in rich textfields and as a part on a page.

## Installing
You need to have Enonic 6.10.3 or above to use this app.
You can install this app directly from the Enonic Market(Look for Qbrick Integration Demo), or clone this project to build it yourself.

Once installed, add the app to your site and set your qbrick account ID. If you are not a customer of Qbrick, but want to see how this app works, use this ID in the settings: 2039052 

This account contains videos explaining the app and lib.

## Building
If you want to build the app yourself, please follow these instructions
Install git on you machine and open commandline and open the folder you want to install the app in:
```
git clone https://github.com/QbrickIPO/enonic-app-demo-qbrick

```
Once you have cloned the project, open the folder and build:
```
cd enonic-app-demo-qbrick
gradlew build
```

## Components
### Part Qbrick Video Player
This is a part you can insert anywhere on your site and it will by default show a videoplayer with the newest published video on your account. The part uses the libs custom selector, where you can search for videos on your account. There are 3 settings for playback:
* Automatic playback: If enabled, the video player will start playback as soon as the page is loaded. Defaults to false.
* Replay video when finished: If enabled, the video will start over once finished. Defaults to false
* Mute audio on playback: If enabled, the volume of the player will be set to 0. Default to false; volume = 1.

### Macro Qbrick Video Player
This is a macro you can insert in your rich textfields. The macro uses the libs custom selector, where you can search for videos on your account. There are 3 settings for playback:
* Automatic playback: If enabled, the video player will start playback as soon as the page is loaded. Defaults to false.
* Replay video when finished: If enabled, the video will start over once finished. Defaults to false
* Mute audio on playback: If enabled, the volume of the player will be set to 0. Default to false; volume = 1.

### Admin tool Qbrick Video Platform
This is a tool that ads a button to the admin interface that takes you to the Qbrick Video Platform. 
