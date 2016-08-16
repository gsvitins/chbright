___ABOUT___

Python script that changes laptop brightness (tested on Xubuntu using xfce4).
This script allows to change brightness directly by entering number or by increment, thus making it better than default xfce4 keyboard shortcuts that allows interval only of 10. I use it by binding e.g. 'sudo chbright -i -1' to xfce4 keyboaard shortcut to quickly decrease/increase screen brightness by 1 unit. Requires root privileges.

___USAGE___

__usage: chbright [-h] [-i number] [-s number] [-d]__

__-i__ number, --increase numbe _(Increase/decrease current brightness by chosen number.)_

__-s__ number, --set number _(Set brightness to your chosen number.)_

__-d__ --display _(Show current brightness)_
