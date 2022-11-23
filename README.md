# Game-Dev
Coin Chaser

Game link - https://birendra-khimding.github.io/Game-Dev/

The name of the game is Coin Chaser. The idea behind the game came though one of the popular mobile game called, Temple Run. It is a 3D endless running game. The player controls a character who runs endlessly through obstacles to collect coins and get the highest score possible. 

<img src="https://user-images.githubusercontent.com/118632127/203461039-e7ad50d1-5b4b-496a-ac31-a7b13920d2e5.png" alt="cplusplus" width="700" height="200"/>


* Background

<img src="https://user-images.githubusercontent.com/118632127/203461207-978d5790-d214-48b9-a7c5-6eedc1a61eee.png" alt="cplusplus" width="700" height="200"/>
The background is a landscape of a mountain downloaded from the assets store named Low Poly Road Pack. 


* Foreground
<img src="https://user-images.githubusercontent.com/118632127/203461427-9964613b-8dca-45f7-b26b-84429cfb27ca.png" alt="cplusplus" width="700" height="200"/>
The foreground is composed of two 3D cube objects. One 3D cube object works as a road, which is the base for the character to run and to hold all the obstacles, coins and power ups. The other 3D cube object is used as a line divider for the road.

This object also works as a means to creating an effect of the player moving by adding a script and making it move toward -z axis. 
<img src="https://user-images.githubusercontent.com/118632127/203461943-fa525843-b390-4ba5-8030-19948bc60c37.png" alt="cplusplus" width="800" height="200"/>


* Player

<img src="https://user-images.githubusercontent.com/118632127/203462032-475c859c-4d13-41de-8571-ccbb293c370b.png" alt="cplusplus" width="800" height="200"/>
The player character used in this game is downloaded from the assets store named, Character Pack: Free Sample. The running and jumping animation are included in the sample pack.By making the Main Camera child of the Player object, it follows the player character and its movement. The character control inputs are that it can move left, right and jump. The player is stopped if it reaches certain position in x axis, so the player does not fall over the road. 

<img src="https://user-images.githubusercontent.com/118632127/203462173-fa460b70-b2b4-41b3-8440-f3e19d98320c.png" alt="cplusplus" width="800" height="500"/>


* Obstacles-Coins-Powerups
For obstacles-coins-powerups, some are downloaded from the assets store, and some are made using 3D objects and stored as prefabs. 
<img src="https://user-images.githubusercontent.com/118632127/203462365-2569a41b-99b9-4f63-a574-4d652b213900.png" alt="cplusplus" width="800" height="200"/>
To make the objects spawn throughout the game Instantiate and InvokeRepeating methods are used. 
<img src="https://user-images.githubusercontent.com/118632127/203462473-10af824c-c449-4574-ad25-504dad565d86.png" alt="cplusplus" width="800" height="200"/>

To make the spawning object not to overlap each other, certain conditions were given to objects when they spawned. 
<img src="https://user-images.githubusercontent.com/118632127/203462686-7f464f73-b442-44a8-a8f9-dab3cac8ce05.png" alt="cplusplus" width="800" height="500"/>
<img src="https://user-images.githubusercontent.com/118632127/203462827-5906ec75-ea9b-48b6-9b4a-ce4ce4f04409.png" alt="cplusplus" width="800" height="500"/>

* Power-ups
When the player gets the powerup, it last for 10 seconds and the player will be able to destroy the obstacle upon collision with the obstacles.
<img src="https://user-images.githubusercontent.com/118632127/203462942-8b244183-5a08-405c-b638-e4921f14cb9a.png" alt="cplusplus" width="800" height="500"/>

* Coin 
The coin logic is that when the player collides with the coin, the coin objects get destroyed and the TextMeshPro variable gets updated. Every coin is 10 points.
<img src="https://user-images.githubusercontent.com/118632127/203463037-84075cdd-7323-47b4-bf4b-7ffcad73d0fd.png" alt="cplusplus" width="800" height="500"/>

* Game Logic
The game logic is simple and straightforward, if the player collides with the obstacle with out the power up, the game ends. 
<img src="https://user-images.githubusercontent.com/118632127/203463112-a0fcde8f-740f-4c4a-9f17-80d9e9aec87a.png" alt="cplusplus" width="800" height="500"/>







 



