My homework for the Game Design and Implementation class in BJTU (2016)


Objects
* PLATEFORMS	####
* CHARACTER	&
* KEY		K
* DOOR		D

Rules
* The KEY and the DOOR are generated at the beginning of the LEVEL, at a random position. 
* The CHARACTER is generated at the beginning of the game, positioned at the very bottom.
* The KEY, the DOOR and the CHARACTER are as tall as large and have the same size (let say ‘1 unit’)
* PLATEFORMS are generated at a random position. They are as tall as the CHARACTER is, and from 2 to 5 times larger : 1 unit tall, 2-5 units large.
* The SCREEN contains 10 units large, and 14 units tall.
* The PLATEFORMS move from right to left then change direction when hitting a side of the screen.
* The player can move the CHARACTER to the left or the right by pressing 's' or 'd' key (respectively).
* The CHARACTER can't go through PLATEFORMS but he can stay on them. If so, the CHARACTER will move as the PLATEFORM moves (in addition to its own moves).
* The gravity makes the CHARACTER going down with a regular speed, 1 unit by 1, until he reaches a PLATEFORM.
* The player may make the CHARACTER jump by hitting 'spacebar'. That means the CHARACTER will go up for 5 units (1 by 1), ignoring gravity during this time.
* The CHARACTER must collect the KEY, unique one by LEVEL, by reaching it.
* The CHARACTER must go to the DOOR WITH the KEY to finish the LEVEL.
* You loose if the CHARACTER doesn’t reach the door within 30seconds.
* The PLATEFORMS are moving faster according to the LEVEL (+1LEVEL after reaching the DOOR).
