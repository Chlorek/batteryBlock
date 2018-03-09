# batteryBlock
As simple as possible bash script for querying multiple batteries status in Lenovo Thinkpad devices (possibly other hardware as well, but that's what I tested).

It's made specifically for use as i3blocks script, but I can see that being used in different ways (like Xfce genmon etc.).
To change order of batteries (or add more batteries) change numbers in for loop. By default it is "1 0" as my Thinkpad t440s has removable battery as BAT1 and built-in one as BAT0.

## Dependencies
None. It does not even use ACPI.
