# controller-configs

# Steam configs
PS4 Controller with gyro and flickstick as mouse.
Open this link steam://controllerconfig/338170/2654063828 or create the directory `~/.local/share/Steam/steamapps/workshop/content/<your user id>/2654063828` with the [PS4 controller config file](2654063828/1782857511233637843_legacy.bin) inside on Linux and the same on Windows with this path `<some drive>\Steam\userdata\<your user id>\<game id>`.

Single Joycon with gyro and flickstick as mouse. Set up the BetterJoy config first.
Open this link steam://controllerconfig/338170/2654540249 or create the directory `~/.local/share/Steam/steamapps/workshop/content/<your user id>/2654540249` with the [Joycon config file](2654540249/1782857511235957837_legacy.bin) inside on Linux and the same on Windows with this path `<some drive>\Steam\userdata\<your user id>\<game id>`.


# [AntiMicroX](https://github.com/AntiMicroX/antimicrox) configs
It could be that AntiMicroX crashes when you use loaded configs (might just be for the Balance Board)
  
Wiimote with Motion Plus as mouse: [wbb.gamecontroller.amgp](wbb.gamecontroller.amgp). 

Wii Balance Board as mouse: [wiimotionplus.gamecontroller.amgp](wiimotionplus.gamecontroller.amgp).
You will need [wbb-uinput](../../../wbb-uinput) for it to work

# [BetterJoy](https://github.com/Davidobot/BetterJoy) configs
Single Joycon with gyro as mouse: [BetterJoyForCemu.exe.config](BetterJoyForCemu.exe.config). Replace the original config with this one. This config is for the left joycon. If you use the right joycon change line 90 to `<add key="GyroMouseLeftHanded" value="false"/>`. If you don't use HIDG set line 66 to `<add key="UseHIDG" value="false" />`
