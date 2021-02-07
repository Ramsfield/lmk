 # LMK
 ## Let Me Know
 If called after a program that may take a significant amount of time, will alert the user when the task is complete

 ### Dependencies
 lmk uses `notify-send` to ping a message to the user. It depends on having an image called "face-smile" that often lives within `/usr/share/icons/gnome/32x32`

 ### Setup
 If there are no dependency issues (a test run can be ran with `./lmk` inside the directory), simply adding `lmk` to the path will allow you to call it from anywhere.
 Simply add it to your path, or make an alias with complete pathing to allow you to call it by running `lengthy_program; lmk`
