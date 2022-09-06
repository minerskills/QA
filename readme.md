# Short introduction to myself

Hey, I'm Mika and I've worked in QA as a volunteer for a little over 2 years. In this time I have reported ~70 tickets for [Fleetyard Studios](https://mantis.starshipsimulator.co.uk/view_all_bug_page.php), and ~200 for Messy Desk Interactive (tracker not public). This does not count interactions (comments, updating status, ...), since those difficult to track both on mantis and GitLab. I expect there to be over 1000 interactions for Fleetyard and Messy Desk combined, not counting any ticket changes that happened because of changes to the ticket process, where I was often the person to update the whole bug tracker to adhere to these changes for Fleetyard.

Fleetyard Studios and Messy Desk Interactive have very different styles of reporting. Messy Desk required a title, expected behaviour, current behaviour, picture of the map and the version number. 
Fleetyard on the other hand makes use of ingame reporting which captures info such as location and rotation of the player character, and hardware/software info. This eliminates the need for a picture of the map and version number. To streamline the process for normal players and staff, it was decided that expected behaviour wasn't needed either. 
To keep the examples of bugs I have reported below in the same style, I'll convert the Messy Desk Formatting over to the Fleetyard formatting. 

## Example 1

### Possible to regain full access to character movement in certain Menus

#### Current Behaviour
The player list opens. Once you release TAB you have full control over your movements which should not happen while you are in any menu.

#### Reproduction Steps
1. Launch the game at a random location
2. Open the menu
3. Click "Quit game"
4. Select one of the two options
5. Press TAB twice

Project: The Orville - Interactive Fan Experience 
## Example 2

### Dead Engineers can still repair panels

#### Current Behaviour
After killing an engineer he was still able to finish the repair of the panel I destroyed.

#### Reproduction Steps
1. Destroy any panel
2. Wait for any engineer to start repairing that panel
3. Kill the engineer while they are repairing the panel. 
4. Watch the panel pop into existence

Project: Starship Simulator
