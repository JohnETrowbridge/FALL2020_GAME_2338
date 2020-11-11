# Test Case 

## Test Details

* Test Case ID:
  * #TC001
* Test Case Name:
  * #SSFS_G01
* Component: 
  * Automating testing for side scrolling flying shooting game.
* Test Case Designer:
  * John Trowbridge
* Creation Date:
  * 11/10/2020
* Modified By:
  * John Trowbridge
* Modified Date:
  * 11/10/20
* Requirements Covered:
  * Player can move up and down and can shoot objects.
  * As player shoots objects, player will move further to the right where objects spawn onto screen.
  * Automated testing program should be able to replicate these movements and watch for objects without outside help.
* Test Description/Purpose:
  * Computer should start the game immediately.
  * Automated movement of up and down while avoiding objects.
  * Automated shooting of objects while moving up and down and avoiding objects that are missed.
  * Automated stopping of shooting to reset position when computer reaches certain point on the screen.
* Pre-Test Conditions:
  * Game needs to start up.
  * Keybind or command for movement of up and down must be functional.
  * Keybind or command for shooting must be functional.
  * Ensure that when the character shoots that it moves towards the direction of object's spawn.
  * Ensure that objects spawn randomly by computer.
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


