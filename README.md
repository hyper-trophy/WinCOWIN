# VaccASSIST
Automate you vaccine slot booking process on CO-WIN. 

## INSTALLATION
1. Download VaccASSIST.crx and save it in your computer.
2. Right click and extract to VaccASSIST. (note that "mainifest.json" file shoud be immediately inside this folder)
3. Open Extensions page by clicking on the menu icon (three dots) at the top right of Chrome, point to “More Tools,” then click on “Extensions.” 
4. Check "Developer mode" checkbox in the top right-hand corner.
5. Choose "load unpacked" and choose VaccASSIST folder where you have extracted it.
6. It should be installed by now.

## OPTIONS
* Only 18+: It will alert you if there are any slots for for age category of 18+. If disable it will alert for any open slots.
* Fast-forward: If enabled, during refreshing, if any free slot is available, it will play alert beep, automatically click on that slot and will choose Slot time as specified in extension, the only thing you need to do is put in captcha and submit.
  * pros: You will save time of clicking on free slot and choosing time slot.
  * cons: as it will open free slot as soon as it is availabe, make sure that the vaccination center is accessible by you.  

## USAGE
1. open https://selfregistration.cowin.gov.in/ and login.
2. Choose schedule and schedule now.
3. Choose search by district (This extension will only work for District search).
4. Select state and district.
5. Now click on VaccASSIST extension and choose options (see Options sections for more information).
6. click on start. The list will refreshed every couple of second, if slots open (according to option you have chosen) it will produce beep and alert you.
