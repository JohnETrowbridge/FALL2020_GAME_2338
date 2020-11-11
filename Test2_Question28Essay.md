# Test Case 

## Test Details

* Test Case ID:
  * #TC001
* Test Case Name:
  * #HNS_G01
* Component: 
  * To ensure that the player can successfully execute and complete the Hide and Seek program.
* Test Case Designer:
  * John Trowbridge
* Creation Date:
  * 11/10/2020
* Modified By:
  * John Trowbridge
* Modified Date:
  * 11/10/20
* Requirements Covered:
  * Player can move up, down, left, or right on the 2D map.
  * 2D Map is designed in a way that blocks players from going through walls or walking on areas not designated for the player.
  * Players are designated for hiding and seeking with 1 player as the seeker.
  * Hiders are given a designated time by the host to hide before seeker is released.
  * Seeker can call a command that eliminates a hider when the hider is found by the seeker.
  * Game must have a timer set at a designated number of minutes and seconds made by the host of the game.
* Test Description/Purpose:
  * Game should be hosted and started successfully.
  * Computer randomly chooses the hiders and 1 seeker.
  * Computer timer begins to count down when all the players have connected and the map has been loaded.
  * Hiders take their designated time to hide.
  * Seeker begins to seek out the players until all hiders are found or the timer runs out.
  * Results will be displayed at the end.
* Pre-Test Conditions:
  * Game needs to start up.
  * Keybind or command for movement of up, down, left, and right must be functional.
  * Level must be designed and implemented into the program.
  * Ensure that when the character comes to an unwalkable area that the character can't walk on the area.
  * Ensure that the computer timers and subsequent programs function as designated.
  * Host can set timers for the computer.
  * Hiders and Seekers are available and designated.
  * Seeker can call when a player is found.
  * Results screen is designed and variables are available and tracked to be displayed.
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Game Start Up. | Game starts up. | √ |			
| 2 | Host selects the timers. | Timers are entered and inputted into the game. | √ |			
| 3 | Hiders and Seekers are designated. | Hiders and Seekers are designated and displayed. | √ |			
| 4 | Map and Characters load onto the screen. | Map has been loaded and the characters are spawned at the starting locations. | √ |			
| 5 | Timer begins to count down for Hiders to hide. | Timer has counted until reaching zero. | √ |			
| 6 | Hiders can move their character around the map-up, down, left, and right. | Controls are no longer halted for the hiders. | √ |	
| 7 | Seeker is released to go find players after Hide Timer ends. | Controls are no longer halted for the seeker. | √ |			
| 8 | Seeker looks for players and executes command when near hiding player. | Command is executed for finding a hider. | √ |			
| 9 | Hider is eliminated. | Hider character is eliminated from instance and is given spectator of seeker while eliminated. | √ |	
| 10 | All hiders are found or timer runs out. | Results are displayed if the game was completed by seeker or the timer ran out. | √ |			

## Overall Test Status:

The test has been concluded, and the program's functional test has been successfully completed. More functions will need to be added in order to have the computer check for any abnormalities such as long or incorrect timer inputs by the host, too many hiders being disconnected from the game, and seeker being disconnected from the game. A simple and basic test has been completed of the game's functions so far and have successfully functioned as programmed. Further tests will follow as more functions are added to the base program.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/20 | 11/10/20 | Completed |


