# controller-configs

# Steam configs
PS4 Controller with gyro and flickstick as mouse.
Open this link steam://controllerconfig/338170/2654063828 or create the directory ~/.local/share/Steam/steamapps/workshop/content/<your user id>/2654063828 with the [PS4 controller config file](1782857511233637843_legacy.bin) inside.

Single Joycon with gyro and flickstick as mouse. Set up the BetterJoy config first.
Open this link steam://controllerconfig/338170/2654540249 or create the directory ~/.local/share/Steam/steamapps/workshop/content/<your user id>/2654540249 with the [Joycon config file](1782857511235957837_legacy.bin) inside.


# [AntiMicroX](https://github.com/AntiMicroX/antimicrox) configs
Wii Balance Board as mouse: [wbb.gamecontroller.amgp](wbb.gamecontroller.amgp).
You will need [wbb-uinput](../../../wbb-uinput) for it to work

# [BetterJoy](https://github.com/Davidobot/BetterJoy) configs
Single Joycon with gyro as mouse: [BetterJoyForCemu.exe.config](BetterJoyForCemu.exe.config). Replace the original config with this one. This config is for the left joycon. If you use the right joycon change line 90 to `<add key="GyroMouseLeftHanded" value="false"/>`
