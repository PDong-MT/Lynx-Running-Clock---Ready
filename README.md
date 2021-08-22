# Lynx-Running-Clock---Ready
 
This is a basic installer for the Electron packaged controller for the DIY scoreboard project.

This requires no coding knowledge to operate.

The program runs on the same computer as FinishLynx, and uses the included "DIY - 2 Board" lss file which needs to be placed in your Lynx folder. (c:/Lynx, by default)

Lynx scoreboard settings:
Network (UDP)
Port: 5479
IP Address: 127.0.0.1
Running Time: Normal

This code outputs to a Raspberry Pi running at 192.168.0.171

If you're looking for control over these settings, I suggest checking the DIY scoreboard repo.

This project uses Henner Zeller's great Pixel-Pusher library to send data to the clock.  It requires a Raspberry Pi with ethernet (3B+) and an Adafruit RGB Matrix Hat to output to boards.  You may need to play with your board settings through the RGB library examples to figure things out, as all panels are different.
