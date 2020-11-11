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
  * Ensure that the computer timers and subsequent programs function on command.
  * 
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Game Start Up. | Game starts up. | √ |			
| 2 | Character begins to scroll. | Character scrolls through the map. | √ |			
| 3 | Character moves up and down. | Character successfully moves up and down. | √ |			
| 4 | Objects begin to spawn. | Objects are spawning from the right side of the screen. | √ |			
| 5 | Character begins shooting at objects. | Objects are being shot at and are disappearing when contact is made by projectile. | √ |			
| 6 | Character moves right when shooting. | Character begins to move to the right side of the screen while shooting. | √ |			
| 7 | Character stops shooting when reaching a certain point on the screen and allows for character location reset. | Character stops shooting while present on a specified point on the map. | √ |			
| 8 | Character begins to move left to a certain point while shooting is absent until safe. | Character has stopped shooting and moved left to specified point. | √ |			
| 9 | Character resumes shooting when location is reset on left. | Character continues to shoot when location on map on the left is touched. | √ |			
| 10 | Character repeats process until object strikes the character. | Test has resumed until computer has failed to keep the character out of harms' way. | √ |			

## Overall Test Status:

The test has been concluded, and the program's automated test has successfully performed and completed all tasks given above. Character has successfully moved up and down, shot objects, reset its location when in danger, and exploded on impact with object. These functions have been performed automatically without any outside help from developers. Testing tool is ready to be utilized by developers for purposes defined at their discretion.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/20 | 11/10/20 | Completed |


