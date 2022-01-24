# Degrees of Lewdity - Light And Dark
Adds more wholesome features to Degrees of Lewdity, and more violence such as combat phases and murder.

# How to build

Optional Prerequisites

Install Tweego and remember the path where it was installed.
Add path to tweego.exe (e.g. C:\Program Files\Twine\tweego-2.1.0-windows-x64) to Windows Path environment variable.


Changing the build version and type

Open 01-config\sugarcubeConfig.js.
Edit the window.StartConfig object to the relevant config type.

Normal Build - enableImages needs to be true and enableLinkNumberify needs to be true.
Text Only Build - enableImages needs to be false and enableLinkNumberify needs to be true.
Android Build - enableImages needs to be true and enableLinkNumberify needs to be false.



version is optional between release versions but will be displayed on screen in several places and stored in the saves made.

debug is optional and will only effect new games.


Compiling the html

Run compile.bat or compile-watch.bat.
Open Degrees of Lewdity VERSION.html.


Build Android version (.apk)
?
