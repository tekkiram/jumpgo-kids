#JumpGo Kids [![Build Status](https://travis-ci.org/JTechMe/JumpGo-Kids.svg?branch=master)](https://travis-ci.org/JTechMe/JumpGo-Kids)
####The internet made safer!
#![](ic_launcher_small.png)
####Download
* [Download APK from here](https://github.com/JTechMe/JumpGo-Kids/releases)

* [Download from Google Play](https://play.google.com/store/apps/details?id=com.jtechme.jumpgokids)

####Master Branch
* [![Build Status](https://travis-ci.org/JTechMe/JumpGo-Kids.svg?branch=master)](https://travis-ci.org/JTechMe/JumpGo-Kids)

####Features
* Parental Controls
 * Parental Login screen for Parental Controls
 * Internet Content Filter
 * Ad Filter
 * History that can't be erased by the child

* Bookmarks

* Multiple search engines (Google, Bing, Yahoo, StartPage, DuckDuckGo, etc.)

* Google search suggestions

* Orbot Proxy support and I2P support

## Development checklist
- [x] Parental Controls
 - [x] Website Blacklist
 - [ ] Website Whitelist option
 - [x] Ad Filter
 - [x] Login Screen
- [ ] Child Safe Search
- [x] Kid Theme
 - [x] Browser Colors
 - [x] Reading Mode Colors
 - [ ] Tab Drawer Colors
 - [ ] Bookmarks Drawer Colors
 - [ ] Updated Button Icons
- [ ] Bonus Game Mode

####Permissions

* ````INTERNET````: For accessing the web

* ````WRITE_EXTERNAL_STORAGE````: For downloading files from the browser

* ````READ_EXTERNAL_STORAGE````: For downloading files from the browser

* ````ACCESS_FINE_LOCATION````: For sites like Google Maps, it is disabled by default in settings and displays a pop-up asking if a site may use your location when it is enabled

* ````ACCESS_NETWORK_STATE````: Required for the WebView to function by some OEM versions of WebKit

####The Code
* Please contribute code back if you can. The code isn't perfect.
* Please add translations/translation fixes as you see need

####Contributing
* Contributions are always welcome
* If you want a feature and can code, feel free to fork and add the change yourself and make a pull request
* PLEASE use the ````dev```` branch when contributing as the ````master```` branch is supposed to be for stable builds. I will not reject your pull request if you make it on master, but it will annoy me and make my life harder.
  * Find the ````dev```` branch at [https://github.com/JTechMe/JumpGo-Kids/tree/dev](https://github.com/JTechMe/JumpGo-Kids/tree/dev)
* Code Style
    * Standard Java camel case
    * Member variables are preceded with an 'm'
    * Use 4 spaces instead of a tab (\t)

####Setting Up the Project
Due to the inclusion of the netcipher library for Orbot proxy support, importing the project will show you some errors. To fix this, first run the following git command in your project folder (NOTE: You need the git command installed to use this):
````
git submodule update --init --recursive
````
Once you run that command, the IDE should automatically import netcipher and a couple submodules in as separate projects. Than you need to set the netcipher library project as a libary of the browser project however your IDE makes you do that. Once those steps are done, the project should be all set up and ready to go. [Please read this tutorial for more information on git submodules](http://www.vogella.com/tutorials/Git/article.html#submodules)

####License
JumpGo Project
````
Copyright 2015 Josiah Horton

JumpGo Project Family

   This Source Code Form is subject to the terms of the 
   General Open Control License, v. 1.0. If a copy of the GOC 
   was not distributed with this file, You can obtain one at 
   
   https://github.com/JTechMe/GOC-General-Open-Control-Licence-v1.0/
````
Lightning Browser
````
Copyright 2014 Anthony Restaino

Lightning Browser

   This Source Code Form is subject to the terms of the 
   Mozilla Public License, v. 2.0. If a copy of the MPL 
   was not distributed with this file, You can obtain one at 
   
   http://mozilla.org/MPL/2.0/
````
This application is derived from the Lightning Browser source code found at [https://github.com/anthonycr/Lightning-Browser](https://github.com/anthonycr/Lightning-Browser). Changes made to this repo are intended for the JumpGo Browser but can be coppied to the Lightning Browser dev branch at [https://github.com/anthonycr/Lightning-Browser/tree/dev](https://github.com/anthonycr/Lightning-Browser/tree/dev) if requested.

If you have any questions regarding the open-source license, please contact me at [jtech.inc.me@gmail.com](jtech.inc.me@gmail.com)
