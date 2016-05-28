
skin.CarPC-touch_carbon
=======================
Configuring this skin.

Usage
=======================
 - Install rasbian
 - apt-get update/upgrade etc
 - apt-get install kodi
 - run kodi as pi once to create .kodi in the home folder
 - cd /pi/.kodi/addons
 - git clone https://github.com/slacker247/skin.CarPC-touch_carbon.git
 - run kodi and go to settings -> apperance -> skin
 -- change it to CarPC-touch_carbon
 - install custom boot splash screen []
 - configure kodi to load on boot
 - install touch usb drivers

Changes
=======================
 - Change Navigation to Google Maps
 - Added bluetooth from osmc to settings
 - Re-arranged the main menu buttons, changed them to configurable through Favorites
 - Moved the power button to the lower bar, added power options
 - Moved the apps/programs button to the lower bar
 - Changed the middle logo to a generic one and added a bunch of car manufactures to select from
 - Changed the FM Radio UI
 - Add touch calibration or reconfigure it

Last Branch
=======================
skin_xbmc
Update 2.09.2015
- Fixed file manager and add button in home.

- update 27-09-20015
- added new page for connecting 3g. If you don't need -> Hide button from - Settings/Skin settings/settings buttons/
- This working only with sakis3g
- The buttons send commands :
- sudo /usr/bin/modem3g/sakis3g connect
- sudo /usr/bin/modem3g/sakis3g disconnect

- More info: http://raspberry-at-home.com/installing-3g-modem/

