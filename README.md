# Flipper Debug Devboard
This dev board features solderable jumpers and one of those IDC connectors, so that it can be directly connected to one of those 20$ logic analyzers. 

## How to make
Download the [Gerber file](https://github.com/vguttmann/flipper-debug-devbaord/raw/master/flipper-debug-devboard.zip), and upload it to a manufacturing service of your choice. The tolerances were designed with JLCPCB in mind, but other services will probably work, too.
Buy 90° pin headers. Pay attention that the plastic spacers are in the same orientation they are in as in the renders! Otherwise, the pins will be too short to fully seat in the Flipper's sockets!

After you've received the boards and soldered the headers and IDC connector, you're ready to use it. To bridge a pin from the Flipper to the logic analyzer, simply solder a bridge on the pin and line you want to have bridged.
If there are signals you're getting from somewhere else you also want to have on the logic analyzer, the logic analyzer lines are also broken out on the right of the board. The line numbers are given in the rectangle above.

![flipper-debug-devboard-front](https://github.com/vguttmann/flipper-debug-devbaord/assets/61903989/ecd8584a-9037-4b0a-b214-c5ee372c5932) 

![flipper-debug-devboard-back](https://github.com/vguttmann/flipper-debug-devbaord/assets/61903989/4caa14be-983c-41d3-94ab-3f98e3afdaf3)


