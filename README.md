# Starmap
A live starmap which uses extensive javascript and jquery to present up to date information to the user in visual form.  Data comes from a Google spreadsheet (viewable here: https://docs.google.com/spreadsheets/d/1JPbD3smWLr85-83vazj2wizhfd_1rOJssnST5oqQjVE ).

Feel free to click about.  I have set the various ships to where they should all be going somewhere at various speeds.

All ships actually move, and the starmap will occasionally check the spreadsheet again for any updates.  The speed of travel is scaled 1:1 on the warp scale chart found in the Star Trek Encyclopedia.  Time period is based on Star Trek Online.  Stardate is calculated based on 1000 stardates to a Year and that Voyager episode with First Contact Day as the epoch, assuming Janeway's Captain's Log is pretty close to April 5th.

Kind of slow for the updating to be immediately obvious, so I have set a few ships to rather high warp factors.  Trouble is then they actually arrive at their destination fairly promptly and their location is effectively rendered in real time.

Tips:
* Clicking on a ship will bring up details about that ship.
* If ships are stacked, double-clicking (or multi-clicking) will attempt to cycle through all the ships at that point.
* Clicking most sets of (x,y) coordinates on the HUD will try to center the map view on those coordinates as closely as possible.
* Clicking on the speed value will change the unit between Warp Factor and a value of C.
* Clicking on the ETA value will change it between the Gregorian date, Stardate, and the countdown to arrival.
