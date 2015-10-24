Keyboard Shortcuts + Interface Adjust:
	Interface Adjust:  Adjusts the character selection GUI so that it does not overlap with the character interface.

	Keyboard Shortcuts:
This adds 11 shortcuts to the game: "z","x","c","v","b","n","m",",",".","/","l"

z raises levy directly from any county you have control over
z also toggles siege interface while selecting a province or army in an enemy province.
z also sends units to the left side of an army or ship balancing screen, each press sends the bottom listed unit left.  press and hold for rapid rebalancing
z will 'cancel' or 'go to' on event windows (such as disband troops, or after a siege/battle has completed)
z will go to the previous holding in demesne

x dismisses the currently selected levy (army or ship), *capital* "x" will dismiss ALL selected levies or ships

c raises ships directly from any county you have control over
c assaults holdings when you have an army/county is selected that allows for assaulting
c Confirms diplomacy interactions, and will 'ok' event windows (such as disband troops)

v embarks the currently selected levy into a ship that is IN port in that province
v also selects all armies inside boats if a ship is selected
v also will close one army at a time while having multiple armies selected.  The two previously mentioned shortcuts take priorty.  This shortcut is ideal for raiding with multiple armies as a viking.  (v selects armies, right click all onto a county, press v, right click onto another county, repeat.)
v will create a new vassal from the holding screen of minor owned baronies

b merges selected levies or ships, so long as they are in the same zone or province (naturally.)  If you have a single army/shipgroup the "b" key will open the new unit interface (ship/army rebalancing)
b also sends units to the right side of an army or ship balancing screen, each press sends the bottom listed unit right.  press and hold for rapid rebalancing
b will go to the next holding in demesne
b is also back button for the main interfaces

n selects the trade port screen on coastal provinces

m selects the normal holdings screen 

l toggles looter status for pagan armies

, opens the ledger, and closes the ledger

. opens the find characters interface, and also closes it

/ opens the find title interface

################################################################################
To manually alter keybindings, download notepad++ from www.ninite.com and install
use notepad++ to 'search in files', select the mod folder as the directory
search for: Shortcut = "
(leave the quotations open)
this will pull up all the shortcuts listed in the mod files.
doubleclick on the bottom of the screen through each of the results until you see the "guiButtonType =	{" that looks like what you want.
you can alter or remove any of the options that say "shortcut = "x"" to your liking
There is some trial and error to this if you are not experienced with the layout of the game files.  Just play with it, you'll figure it out.
################################################################################



Changelog:
6-19-2013
Overhaul changes.  Discovered that keybound event decisions cause the engine to fire the wrong event options.  Removed 1-2-3-4, and consolidated keybinds to z x c v b.  Attempting for a 'qwerty' style using available bottom row.  Lots of multi-use buttons, but no incompatibility issues.  Play with it for a few minutes and it will feel natural, sorry for the big shift.
Added instructions to manually edit keybinds.

6-9-2013
added z key to confirm decisions on the diplomatic screen.  Only works if the "Send" button is activatable.  Use caution unless you are certain of what you want to do.
added "," ledger keybind.  toggleable.  When buildings screen is selected this keybind will not function.  (Overridden by "previous holding in demense" button.)
added "." find character keybind.  toggleable.  When buildings screen is selected this keybind will not function.  (Overridden by "next holding in demense" button.)
added "/" find title keybind.  

6-4-2013
added z key and b key army rebalancing.  while selecting the 'balance ships' or 'balance army' screen, z will send the bottom most visible unit on the right side to the left, and b will send the bottom most visible unit to the right.

6-3-2013
Added v key: close one army at a time while having multiple armies selected. This shortcut is ideal for raiding with multiple armies as a viking.  (v selects armies, right click all onto a county, press v, right click onto another county, repeat.)

5-29-2013
Added "z" to toggle siege interface while selecting a province or army in an enemy province.  In situations of a hostile siege in your land, the Toggle Siege interface overrides the raise levy shortcut, requiring a manual click.  Since the times where you would WANT to raise an army with 0 morale against a hostile siege is very rare, this additional shortcut actually helps prevent mistakes from being made.  
Added "v" to select all armies in boats if a single ship stack is selected.  If multiple ship stacks are selected, "v" will select all of the last listed armies.
Added "c" to toggle looter status while an army is selected.  This shortcut only works when you have a single army selected.  Does not work when you have an army currently raiding a county (Siege interface), but CAN disable looting while you are at sea or travelling from one county to another.  Be careful you don't accidentally disable your looter status, requiring a trip home to re-enable.

These keybinds should not conflict with any of the existing keybinds (except those mentioned here) since they function on seperate screens.
