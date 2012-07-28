libnotify
=========

[libnotify](http://developer.gnome.org/libnotify/) is a library that sends desktop notifications to a notification daemon, 
as defined in the Desktop Notifications spec.
These notifications can be used to inform the user about an event
or display some form of information without getting in the user's way.

The [libnotify](http://developer.gnome.org/libnotify/) library provides a convenient API for presenting notifications to the user.
Notifications can be simple message or they can allow the user to respond.
Notifications made with libnotify will use the appropriate interface in the environment the application is running in.
In GNOME 3, notifications are displayed at the bottom of the screen and then put into the messaging tray.


## Usage ##

Compile with `notify.d` and link against `libnotify` and `libgmodule`.