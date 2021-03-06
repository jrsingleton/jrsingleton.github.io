---
layout: project
type: project
image: images/projectpic2.png
title: Kermit Arcade Game
permalink: projects/arcadegame
# All dates must be YYYY-MM-DD format!
date: 2018-11-27
labels:
  - Java
  - Object Oriented Programming
  - Development
  - Eclipse
summary: My team developed a simple arcade style game.
---

<img class="ui image" src="{{ site.baseurl }}/images/projectpic.png">
<hr>

 For this project, I worked with my partner in programming the different classes required for this game.  I started by programming the basics, such as setting up the images and formatting them correctly, and adding in sound effects. I then programmed the keyboard inputs according to their purpose in the game.  The "W" and "S" keys are used to move the player, and the spacebar is used to shoot.  Next, I added the enemies to the screen using an array of images, they are added to the leftmost edge of the window at random y-values, when the enemies "spawn" they move across the screen at random speeds. 
 
 From there, I created functions to make the program register when the player was hit by the enemy, and vice versa.  Each time the player is hit by the enemy, one heart image is removed from the screen, and each time the enemy is hit an explosion image is shown on the screen at the location of the hit. The game keeps track of your score with a FileWriter and displays it when you lose.

Here is some code that illustrates how we determined if the enemy is hit:

```js
// hits is initially 1 
int hits;

while(Player.laser.getXCenter() > -100 ) {
	hits = 1;
	//moves the laser from the gun to the left of the screen
	Player.laser.moveForward(-70 );
	for(int j = 0; j<handHolder.length; j++) {
	// detects when the laser hits a hand and teleports it back to the left of the screen
		if (Player.laser.getXCenter() <= handHolder[j].getXCenter() &&
		(Player.laser.getYCenter() <= handHolder[j].getYCenter()+handHolder[j].getHeight()/2 && 
		handHolder[j].teleport2();
		hits--;
	}
```
I learned an immense amount about programming during this project. I strengthened my programming skills in Java, and improved my problem solving skills as well. I also gained experience on working with a team to program one project, determining each of our roles and agreeing on the project plans was crucial to produce a quality end result. This project was also very useful in improving my detail orientation, there are many stylistic elements that rely on specific coding syntax that you don't anticipate if you don't have sufficient experience with programming. Experience and practice is the best way to learn, I certainly gained a lot of each!

You can watch a demonstration [here](https://www.youtube.com/watch?v=uDI-i-WEaTo&feature=share)

<hr>
<hr>



