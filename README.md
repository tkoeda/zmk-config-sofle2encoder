# Sofle Choc 2 encoders. 
*My shops https://keyboard-hoarders.com & https://keyboardhoarders.etsy.com
![IMG_0823](https://github.com/user-attachments/assets/2ea9dfec-71c9-428f-aef8-a898e3273b3d)


## Keymap
![sofle2enc](https://github.com/user-attachments/assets/97862878-3886-4d13-90c4-bc0ee6767be2)


## Bluetooth
![soflebluetooth](https://github.com/user-attachments/assets/6c6c1d46-74e9-4e91-8191-667fd3f0ec6d)

### Power saving
If you would like to maximise battery life, you can disable the built-in OLED
display. This is done by commenting out the display related lines in
`config/sofle.conf`. The repository already ships with these options disabled:

```
# CONFIG_ZMK_DISPLAY is not set
# CONFIG_ZMK_DISPLAY_STATUS_SCREEN_BUILT_IN is not set
# CONFIG_ZMK_LV_FONT_DEFAULT_SMALL_MONTSERRAT_26 is not set
# CONFIG_LV_FONT_DEFAULT_MONTSERRAT_26 is not set
# CONFIG_ZMK_DISPLAY_WORK_QUEUE_DEDICATED is not set
```

Building the firmware with these settings will omit NiceView/OLED support,
reducing power consumption.
