libnotify
=========

The libnotify library provides a convenient API for presenting notifications to the user.
Notifications can be simple message or they can allow the user to respond.
Notifications made with libnotify will use the appropriate interface in the environment the application is running in.
In GNOME 3, notifications are displayed at the bottom of the screen and then put into the messaging tray.


## Usage ##

Compile with `notify.d` and link against `libnotify` and `libgmodule`.