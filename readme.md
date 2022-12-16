# Short introduction to myself

As one of the QA Leads at Fleetyard Studios, I have played a key role in ensuring the quality and playability of our games. In my 2.5 years with the project, I have identified and reported over 80 issues, and have had over 1000 interactions with our bug tracking system. In addition to my work on Fleetyard's projects, I have also contributed to the testing efforts of Messy Desk Interactive as a QA Tester, where I identified and reported around 200 issues.

Some specific examples of my work as a QA Lead include:


- Developing and implementing a new process for tracking and prioritizing issues in our bug tracker. This process helped to improve the efficiency of our testing efforts and allowed us to more effectively address the most critical issues.
- Leading the testing efforts for the first ever demo and playtest of Starship Simulator, in preparation for the projects Kickstarter.

Overall, my track record as a QA Lead demonstrates my ability to identify and report on issues, work effectively with development teams, and develop and implement effective processes for testing and tracking issues."

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
