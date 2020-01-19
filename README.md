# cap/IO
Photo/Video iphone app that gives full control over camera back to users
no bulshit ads, promotions or social integration, just pure camera with extended manual/auto functions

# Please support me on continuing developing this app and sharing the code:
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=2KK97H75UCY7C&item_name=to+support+free+software+development&currency_code=USD&source=url)

# in AppStore (search for Capio):
  https://itunes.apple.com/us/app/cap-io/id1209620433?mt=8

![Alt text](/capio_ico_ArtWrk150x150.png "app_ico_art")

![Alt text](/capio.png?raw=true "in_app_screen")

```
  sudo gem install cocoapods
  pod init
  pod install --verbose
```
### Current Status:
  2020-01-09
  - a cripling update from swift3 to swift5 is done and app's working state is restored
  - new version 2.0.0 is published

### Current Features List:
  - manually change at any given point following settings:
    -- focus
    -- shutter
    -- iso
    -- temperature
  - record video with sound playing in background from your phone
  - if you have music playing in your headphones -> video recording is not gonna stop it
  - adjust any camera setting while recording video or making photo
  - make photos while recording video
  - easy resolution and FPS switch with format info
  - fastest ever swipe-to-select menu for camera settings
  - handy fast gestures to perform photo (double tap) and video (triple tap)
  - do long exposure photos or slo-mo video by adjusting shutter speed
  - use camera as meter for all camera settings while they are in AutoMode
  - tap to focus and long tap and drag to focus at point
  - lock device recording orientation (landscape/portrait/auto)
  - flash mode toggle
  - grid toggle and quad grid
  - camera timer (3x, 10x)
  - you can do just photos without giving perms to video (audio recording perms)

### TODO release 2.2.0:
  - multi-cameras support
  - fix layout issue on >iPhone1X (need to buy a new phone just  for that, thanks apple)
  
### TODO:
  - save user settings
  - switch back to all auto shortcut button
  - pixel shader implementation -> reflection shader
  - UI\Unit tests (help needed)
  - 3d motion feature point tracking
  - better notifications and UI response feedback
  - torch mode on-off
  - TimeLapse
  - HDR
  - Live
  - settings presets
  - gyroscope/level grid
  - app's fast access from phone's widgets view (if that's even possible?)
  - AppleWatch support (remote photo app control)
  - inApp tutorial (maybe)
