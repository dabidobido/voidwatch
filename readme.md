# Voidwatch Bot for FFXI

The commands are:

        //vw t: trade cells and displacers and start fight
		//vw bc (number): buy number of cobalt cells from nearby Voidwatch Officer
		//vw br (number): buy number of rubicund cells from nearby Voidwatch Officer
		//vw bp (number): buy (number) phase displacers from Ardrick
		//vw setp (number): set number of phase displacers to use
		//vw setc (number): set number of cobalt cells to use
		//vw setr (number): set number of rubicund cells to use
		//vw autosell: toggles whether to auto sell drops or not. Uses //sparky purge.
		//vw autoloop: toggles whether to auto loop or not.
		//vw autows: toggles whether to auto WS or not.
		//vw converttocell: toggles whether to convert pulse to cells or not.
		//vw setws: set the WS name to auto WS.
		//vw settp: set the TP threshold for auto WS.
		//vw warpwhendone: toggle warping when done. Uses a Scroll of Instant Warp.
		//vw refreshtrusts: toggles whether to resummon trusts after battle.
		//vw trustset (name): sets the name of the trust set. Uses Trusts addon to summon trusts.
		//vw scdelay (number): sets the skillchain delay when a sc_opener is in the party.
		//vw altdelay (0-5): sets a delay so that each character is attempting to open the chest at different times.
            //vw stop: stops all parsing of incoming packets.
    
    When loaded on a character a settings file will be created for that specific character.
    when setting the 'altdelay' be sure to use a unique number (between 0 and 5, inclusive) for each character.


As of now the delay only affects opening the chest.  If multiple characters are attempting to buy cells from the Voidwatch npc
at the same time you will still get conflicts.

# Version history
1.0.4:
- Only party leader should trade cells+displacers

1.0.3:
- Fix help text and readme

1.0.2:
- Fix buying cells

1.0.1:
- Fix buy cells spam

1.0.0:
- Merged with multibox friendly changes by Snads
- Made compatible with new cell purchase flow implemented in Aug 2022 update.