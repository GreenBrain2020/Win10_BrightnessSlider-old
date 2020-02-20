# Win10_BrightnessSlider
this app puts a Monitor Brightness icon to on Taskbar Tray. So you can access it with 1 click.
targeting laptops. 

* **supported os**:  win7 , win8 , win10 
* **requirements**: 
  * .net4 framework.  (win7 may need to install)
  * for ddci monitors, ([make sure  ddci is enabled on monitor menu](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/enable%20ddc-ci.jpg?raw=true)
)

* **Note For Developers**: code version is  first working version (maybe 1.01). but **executable is always up to date**

* **Note For VirusAlert**: 
   * dont open issues about virus total trojan alert etc. if you dont trust dont use it.   
   * old code published here is free to play.
   * uptodate code is my private intellectual property. coding effort made without any money, wont be put here.
   
**Download Link**   [All Versions](https://github.com/blackholeearth/Win10_BrightnessSlider/releases)


#### ChangeLog

 
v1.04 [most stable]
* added: author page to  menu item  that shows version no.
* trying to fix: fallback doesnt handle management not supported exception.
* added: seperately change brightness of multiple monitors.
* added: supports setting Brighness on ddc/ci Monitors(at startup, it may show -1,  )
* fixed: slider showing itself on second screen onhide 
* fixed: popup stays under taskbar, if taskbar is autoHiding  
* fixed: slider wasn't positioning itself according to taskbar position (Top Or Bottom Or Left Or Right of Screen)

