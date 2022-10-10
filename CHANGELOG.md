# version 10.2

Added the option to hide any defeated token from the combat tracker, only if defeated tokens are also ignored.

Fixed the Combat round messages so the trash can icon lines up with the trash cans from the regular messages.

Updated actor sounds to show a stop icon when the sound effect is playing.

Fixed the auto scroll top top feature to correctly set the top when displayed on the combat tracker popout.

Fixed issue with PF2E displaying the name of statuses.

Removed a duplicate invisible status icon.

Fixed issue with showing the combat CR.

# version 10.1

Fixed an issue dropping a tile from the tile picker

Added the option to right click the actor sidebar icon to open the last viewed Actor if you're the GM and your character sheet if you're a player.

Fixed issue popping out the combat tracker.

Fixed issue with combat turn

# Version 1.0.58

More v10 support

Adding a timer for darkness transition.

# Version 1.0.57

More v10 support

# Version 1.0.56

Adding v10 support

# Version 1.0.55

Fixed issues with combat bars not showing if the non combat bar is set to never display.

Fixed issue with combat marker when token is scaled

Fixed combat turn notification so it only notifies when the turn actually changes.

Fixed issues with status list being set to columns.

# Version 1.0.54

Added the option to hide combatants in the combat tracker until their turn has happened.

Fixed issue with saving combat bars when it's a prototype token.

Added the option of displaying the Your Turn Is Next, and Your Turn messages in large fint across the screen.

Fixed issue starting a combat if you don't have libWrapper loaded.

# Version 1.0.53

Added a context menu entry to the combat tracker, so you can right-click and target combatants.

Added the Turned status to the list of statuses, in case you want to keep track of undead your party has turned.

Added actor sound API, so each token can play their Actor sound.

Fixed issues with the combat marker if the combatant no longer has a token set.

Added the option to prevent starting a combat if not all combatants have rolled initiative.

Added the option to trigger Actor Sounds using Active Tiles.

# Version 1.0.52

Fixed issue with Monster Blocks and the Actor Sounds button.

Fixed an issue with Actor Sounds not playing on the Forge.

Animated bloodsplats so that they'll fade into view, rather than swap abruptly.

Added the option for different combat animation with hostile tokens.

Added the option to automatically pan to the current token in combat for the GM

Sort of fixed issues with sorting statuses.

Added the tab swap when starting a combat to a setting.

# Version 1.0.51

Fixed issue with bloodsplats always being on.

Fixed issue with bloodsplat text

# Version 1.0.50

Fixed issues with the update images function when using The Forge

Updated the actor sounds to correctly use the global interface volume.  So changing the volume setting will change actor sounds currently playing.

Updated the combat turn sounds to use the global interface volume.

Changed the interface for actor sounds so that it uses a dialog instead of a drop down menu to add extra functionality.

Updated the bloodsplat options so you can continue to show the tokens while also showing the bloodsplat.

Fixed issue with combat marker when switching between effects.

Fixed issue when dropping a Tile onto the canvas from the Tile Picker.

# Version 1.0.49

Fixed issues with the transform context menu and systems other than dnd5e.

# Version 1.0.48

Fixed issue with combat marker not getting the token highlight or token animation properly.

Fixed issue with combat turn throwing an error if the token is null.

Added caching for the animation settings.

Added the option that when pressing tab in the Macro Editor, it will add a tab rather than moving to the next field.

Added colouring of dependant module in the module management so you can easily see which ones are missing and which ones are inactive.

Added the option to click on dependant modules to scroll to that module in the list.

Added the option to transform into the selected actor in the actor directory to the context menu.  So if you have a wildshape druid, instead of relying on drag and drop to transform you can just right click the shape you want to transform into.

# Version 1.0.47

Fixed an issue with combat markers

# Version 1.0.46

Fixed issues created when fixing issues with Item Piles

Added the option to change the treasure chest icon

Added the option to change the treasure chest size.

# Version 1.0.45

Added the option to add sound controls for either NPCs only, or all Actor sheets.

Fixed issues with bloodsplats and ItemPiles

Added chat timer to Monk's Active Tiles.

Fixed issue drawing combat bars when the default was set to Never Show

Added the options for setting individual token combat highlight animations for each token.

Added option to select a combatant on combatant turn

Fixed issue with the start turn shadow, if the token was rotated, or if the token used a bigger image, or if the image was flipped, the shadow will now show the correct image.

Added an Apply button to the Macro editing screen, so you can now edit and save without closing the window.

# Version 1.0.44

Fixed issue with reordering the collapse button, thank you rmasoni for some better css.

Fixed an issue where deleteing a combatant could have an issue if the token associated with the combatant has already been deleted.

Added the option to keep the combat list scrolled to the currently active token.

Fixed an issue where if you delete the M key it would throw an error.

Added Portuguese (Brazilian) translation, thank you eduardopata41

# Version 1.0.43

Fixed an issue with moving a token by selecting it then pressing M at a new location.  Dragging a token while holding M still worked, but the key press wasn't.  Thank you alessiocali.

# Version 1.0.42

Changed the round marker chat message styling so that it works correctly in PF2

Fixed an minor issue where unreachable code was being reported.  Although technically correct... it's code that's never reached anyways.

# Version 1.0.40

Adding v9 support

Fixing some minor issues with actor sounds.  You could play a sound, then remove it and it would still believe you had sounds to play due to caching.

Fixed v9 changes related to bloodsplats and combat bars

Fixed some issues with changing the combat marker for a specific token.

Added the option to have a combat marker for hostile tokens vs friendly tokens.

Fixed issue with combat turn not remembering the last target that was selected.

Changed hotkeys to use the core keybindings

Fixed a core issue where dropping a Tile onto a scene where one edge was putside of the Scene's boundaries will cause it to fail, even if the Tile still exists inside the Scene.

And... added new marker pictures.

# Version 1.0.39

Fixed issue where the Actor sound button disappear due to an update with the system.

Fixed bloodsplats to that they'll check for either Loot sheet or Merchant sheet.

Added option to use an animated webm file for turn markers.

Fixed issue where start of turn shadows weren't being set to the correct position.

Added option to turn tokens invisible after dying.

# Version 1.0.38

Added a setting so that repositioning the collapse button of the sidebar menu isn't always on.  I liked having the collapse/expand button stay in the same general area, but there are a couple of UI stylings that aren't expecting this and put it in a weird location, making it difficult to expand the sidebar once collapsed.

Turn marker has been updated with cleaner graphics.  Thank you Verthiss!

Removed some debugging information and put others behind a debug setting so there's less chatter in the console log.

Added option to remove the combat turn marker after the first move.

Added option to have a custom turn marker image for individual tokens.

Sort of fixed issue where the turn marker would disappear when the token was updated.  It still happens, but only on the first update, and if you havn't changed scenes, and comes back the next time through the combat turn.

Fixed issue with the turn marker pulse animation

Added option to remember the previous target per each token.  So you can clear targets as the turn changes, but when it comes back to that token it will retarget the last thing it had targetted.  Will not retarget a token that is now invisible, or has died/ been defeated.

Added option to use wildcards with round and turn sounds

Fixed issue where showing the start spot was only showing for the player that moved the token.  Now it will show for both the GM and that player.

Added option to sort statuses.  So altering the Token HUD is now independant of sorting the statuses in the HUD.

Added a "Find my Token" button to the Token menu.  Just in case you're not sure where your token is, you can click the button to find it.  Doesn't work for the GM as the GM owns all tokens.

And the combat tracker will now popout for tokens that have been added mid-combat.

# Version 1.0.37

Fixed libWrapper issues with Bloodsplats and Combat bars

Added the volume option back to the settings.  Apparently the sound files were really loud.

Added integration with changeLogs so that people are informed of breaking changes such as moving the drag points to a different module.

Added Italian language, thank you Luisphigor

Updated Spanish language, thank you as always Lozalojo

# Version 1.0.36

Split some of the functionality into separate files to make debugging a little easier.

Fixed compatibility issue with Hidden Initiative.  Hidden Initiative is doing some strange things with getting the Combat Tracker data that locks out other modules from modifying the data.  I did my best to work around it.

Disabled the next turn notification when Hidden Initiative is active.

Added round markers, so a small chat message is added at the start, end, and when a round changes so you can see what happened during what round.

Added 'none' animation so you can display a solid image that doesn't move.

Fixed issue with CR calculations.  It was having a hard time with single creatures.

Added option to change the default bloodsplat colour, and to change the bloodsplat colour for individuals.

Made the layer switching keys a little more generic so that any module that adds a layer can be included.

Added a placeholder for tokens to denote the starting spot of their combat turn.

# Version 1.0.35

Added proper challenge rating lables for Pathfinder.  The calulations were corrected but the terminology was DnD5e rather than Pathfinder.

Updated the code to use different variable names than icon as I thought it might be causing a conflict.  Turns out it wasn't but it's probably more readable anyways.

Changed the Clear Targets setting so that players could also use this.  Default is one for GM and off for Players.

Added styling for the new Tile HUD icons.  They aren't in quite the same format as the old ones so the highlighting was being missed.

Fixed issues with PF2E getting encounter ratings.  There was a change with how to find character levels.

Added combat turn marker animation options, now you can have the animation go counter-clockwise, pulse, fade in, and fade out.  No more boring clockwise rotation.

Fixed issue where deleting a combatant token would prevent it from being added back to the scene.

# Version 1.0.34
Fixing issue with Pathfinder dead status and bloodsplats

Fixed an issue where the layer swap keys were accesible to players

Updated spanish translations, thank you lozalojo

Wrapped the wall points with libWrapper

# Version 1.0.33

Enhanced the option to drag wall points together.  Before it just updated after you moved the wall, now it will drag the points together.

Updated the sounds so that the GM is in charge of what sound is played but players (and GM) and choose what sounds they want to hear.  By default the Next Turn, and Your Turn sounds are turned off for the GM.

Removed the volume setting for the combat sounds.  It should default to the system levels rather than being hidden in a module setting.

Fixed an issue where estimating CR of a combat was listing the players levels as 0

Changed the sound settings so that they're more compact.

Updated the /timer chat command so you can now have it count up or down, set it to track minutes or hours. Have it display flavor text.  And have it display another chat message when the timer runs out.

Removed the disable open combat setting as there are modules out there that can help you set players settings.

Tried to fix issue with defeated not setting the token status to dead.

MERGE CODE: Added option to set autodefeated on negative rather than 0.  Thank you pseudocode.

# Version 1.0.32

Fixing issue with libWrapper integration

# Version 1.0.31
Fixing an issue with PF2 status labels

# Version 1.0.30
Added support for a chat command to set a timer, /timer 5 will show a chat message with a timer that counts down from 5s.

Fixing some small errors

Fixed issue with detecting combatant

Adding libWrapper support

# Version 1.0.29
Added support for version 0.8.x

# Version 1.0.28
Added option for GM to hear the next round sound

Changed the positioning of the status effects to be consistent with Foundry standards.

Fixed an issue with the bloodsplat causing players to receive an error message

Fixed issue with images not scaling properly in the Windows Foundry Client.

Added option to select sounds with wildcards

Fixed an issue where the palette button would duplicate if multiple scene configs were opened up.

Fixed a bloodsplat issue that couldn't find the correct sized font, so the image would be off center.

Fixed issue where the skull overlay would show briefly before the bloodsplat redraws.

If auto defeated is enabled, set the token to the defeated status too, not just the combat defeated status.  This was causing some weird issues when the combat ended and some tokens stopped being bloodsplats.

Fixed issues with Warhammer positioning of expand 

# Version 1.0.27
File name accidentally changed to .svg, restored it back to .png

# Version 1.0.26
Fixing a small error when calculating the CR of an encounter

File optimization, Thank you xdy!

# Version 1.0.25
Fixing issues with the combat resource bars.

Adding option to move the pause icon

Adding option to sort token statues by column rather than row.

# Version 1.0.22
Added option to use different setting for resource bars when the token is in combat.  This will also display a see through version of the bar for hover and controlled option until the token is hovered or controlled.  This should make it easier to set the bars to not be seen during regular movement, but have them show once combat starts.

Added interface with DF Library Hotkeys to show hotkey settings just for Monks Little Details.

# Version 1.0.21
Adding option to auto-defeat players aswell as npc's.

Moved the game paused icon up a bit more so that it's obvious the game is paused.  If it's too low down it can be missed.

Added a fixed maximum width to select boxes in a form.  If the text is too big it'll drop to the next line.  Still unsure if this is too big of a change though, not entirely sure of the consequences.  But I find it interesting that the input fields are a fized width, but the select fields are not.

Whenever the turn changes, remove targets if you are the GM.

# Version 1.0.20
Don't mind me, just trying to find a set of keys that aren't used by other things and don't cause issues with Foundry.

# Version 1.0.19
Fixed issue with quick viewing layers, by using Library: DF Hotkeys.  Awesome module by the way.  It's not a requirement for Monks Little Details as it will check to see if you need to to be installed, but will warn you to install it if you want the feature.

# Version 1.0.17
Fixing styling with the token HUD in Pathfinder.

Changing the location of stacked condition indicator in PF2

Adding the option to briefly switch between layers by holding down a key and pressing Shift+key will change the layer.  This should let you switch briefly to another layer such as the Tiles layer to hide or show a tile before releasing the key and going back tot he token layer.  Current keys are assigned as r=tokens, t-tiles, y-lighting, u-sounds, i-terrain (if you have the Terrain Layer module installed)

# Version 1.0.16
Adding option to not highlight the image in the Token HUD.  If the system uses full colour images, then highlighting it just distorts the image.

Updated the background palette so that it only loads after clicking a button.  Saves on refresh speed.

Added context menu to view scene artwork in a compendium.  Always found it difficult to select a map if I wasn't sure what I was looking at.  This should allow you to see the whole map before importing it.

Automatically set the defeated status to an NPC that's in combat and drops to 0 HP.

Allow the monster sound effect to be stopped if you press the speaker a second time while it's playing.

Fixing issues with PF2E styling of Token HUD items.  The stackable items weren't getting the right styles.

# Version 1.0.15
Altered the combat tracker so that enemies aren't visible to players when setting up the combat.

Updated the dominanat colour palette to get colours from animated maps

Added option to set the animation speed of the combat tracking highlight

Added option for combat highlight size

Added option to change combat highlight image

Fixed issue where combat tracking highlight shows on tokens for a combat that hasn't started yet.

Letting PF2 change the invisible man icon

Got the altered Token HUD working in PF2

# Version 1.0.14
Possibly fixed cross origin issues with getting the palette on images from Forge or S3 bucket.

Fixed issue with the next up notification.  Wasn't getting the correct combat to pull information from.

Added indicator to show which token has the current turn in combat

# Version 1.0.12
Added Japanese translations (Thank you touge)

# Version 1.0.11
Adding option to show bloodsplat when character dies.

# Version 1.0.10
Added Combat Rating for Pathfinder

# Version 1.0.9
Adding retain notify options.  If you're not on the chat sidebar the notification will stay there until you go back to the chat bar.

Also adding debug to try and figure out issues with the round notification.

# Version 1.0.7
Added option to change which key moves tokens

Updated the code that moves the characters to move them as a batch, rather than individually

Added the option to prevent tokens being removed from a combat encounter via the token HUD.  They can still be removed from the Encounter Interface.

# Version 1.0.6
Added support to specify what audio file to play for the next, current, and round events.  Leave it blank to not play a sound.

Scene Navigation changes

Fixed an issue with closing the Combat Tracker after the encounter is finished.

# Version 1.0.5
Fixed the conflicts with Token Scaler.  Little Details doesn't exactly play nice, but will resize where it can.

Fixed an issue with the settings not turning off the HUD changes.

Fixed an issue with the CR estimation not working due to vehicles added to the encounter.

# Version 1.0.4
Fixed some issues with the next turn not working

Added setting to disable the turn based sounds

Added feature to attach sound effects to a creature.

# Version 1.0.3
Fixed some issues with Pathfinder

# Version 1.0.2
Initial release
