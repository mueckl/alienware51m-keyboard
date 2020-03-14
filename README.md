# alienware51m-keyboard
Alienware 51m / keyboard special keys

make special keys accessable under Ubuntu 
(tested on Version 19.10)

## Installation

1) copy file <pre>cp alienware_51m_keyboard.hwdb /etc/udev/hwdb.d/</pre>
2) rewrite hwdb <pre>systemd-hwdb update</pre>
3) reload hwdb <pre>udevadm trigger</pre>

## Usage

now the 19 keys can be used for hotkey-settings in ubuntu 

* X - Cycle Group (blue->red->yellow)
* Blue 1-5
* Red  1-5
* Yellow 1-5
* A-D



## The approach

the approach was adopted from [Linux keymapping with udev hwdb](https://yulistic.gitlab.io/2017/12/linux-keymapping-with-udev-hwdb/)
