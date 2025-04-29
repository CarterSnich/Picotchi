# Picotchi

Fork of Tamaguino

Forked from [niubit's code](https://github.com/niubit/piconsole/tree/master/soft/Tamaguino), but the [original code](https://github.com/alojzjakob/Tamaguino) was from [Alojz Jakob](https://jakobdesign.com/).

I already have a DIY console but I have no games for it yet. I wanna test it, and I found Jakob's game.

The following are the modifications I made:

- Switched from SPI to I2C.
- Up/Down buttons are used for navigation; A button for opening the menu and selecting items, B button for going back.
- Menu navigation does not wrap around — reaching the end stops at the last item.
- Removed the ability to pause during gameplay.
- Moved graphics to a separate header file.
