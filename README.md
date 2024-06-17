# mazeIt
A maze game designed and developed as a college project

Introduction
I am a game developer working in a company that developers computer games and I have been asked to develop a game for an audience between the ages of 7 and 12 years. In the game the player is suppose in a maze to collect key and avoid being touches by the enemies. The player has three lives and will lose a live if they are touched by the enemy, the keys collected by the player adds to their scores which will help the player progress to the next level. However, the player has to collect all the keys within a time limit and will lose a live if they are not able to collect all the keys within the time limit. 
Demographic Information
Audience
The intended of audience of the game are children between the ages of 8 and 12 old, however the audience of the game is not gender specific because it can be played anyone provided the person likes arcade maze games.  
Purpose
The purpose of developing this game is to enable me satisfies the clients of the company and to gain experience throughout the development process. Being a junior developer in the games industry and stilling skill developing my skills and creativity in how games are developed working on a project like this essential to me because I will gain skills.
Client’s requirement
The game is expected tom meet the following requirements. The game should be developed to be PEGI 7 that is, it should be appealing to appealing to children between the ages of 8 and 12 years of age. The game should also have a character that can be navigated around the area to collect items in the form of key and avoiding hazards like monsters and asteroids moving around the screen area of the game. Also, collecting the keys should add points to their scores and lose lives when they are hit by the hazards, but the players have limited lives of three so if players lose all lives the game is over for that session.
Game genre
The genre of the game I am developing for the client is an arcade game which is based on a maze where the character move around the maze avoiding the hazards which are the monster and asteroid and also moving around the maze either in the vertical or horizontal movement. The game can only be played on the computer using the keyboard using the arrow keys to control the movement of the character. The character cannot shoot or destroy any thing in most games. 
Visual style
The visual style of the game is such that, the view of the game is from the above whereas the characters are below from the view of the person playing the game. The objects in the game are a combination of space object and bricks. The main character and the asteroid in the game are from the space game object and the bricks and monster are from the maze game world. Visually the game looks like a maze. 
Character perspective
The characters in the game are view from the top. That is the game has an elevated view from the player’s perspective.
Initial game design
The game is based on a maze where the player must collect keys whiles avoiding being touched by the monster and the asteroids when moving about in the maze. The keys collected by the player add to their scores which is recorded and accumulated as more keys are collected. Also, the player must complete the tasked of collecting the keys in under two minutes if not they shall lose in that session. When the player is touched by the monsters and asteroids they lose a live, however, the player has a limited live of three. If the player loses all three live the session comes to an end. When all the keys are collected within the time allocated for the task the player will then be able to move next level by opening the locks that prevents the player from getting to the food. The next level of the game operates in a similar way except that level is more difficult than the previous one.
Assets table
Asset used
Source
Purpose
Size
Type
Sprite – bricks 
Game maker sprite images 
Used to mark-out the maze 
3.12 KB

Sprite – burger 
Game maker sprite images
the price after completing the task of collecting the require number of keys 
3.58 KB

Sprite -ghost 
Game maker sprite images
The hazard(enemies) 
3.18 KB

Sprite - key
Game maker images
Collectible 
3.94 KB

Sprite – rocker  
Game maker sprite images
Player 
3.03 KB

Sprite – meteorite 
Game maker sprite images
Hazard
3.40 KB

Sprite - gates 
Game maker sprite images
Restrict the player from getting the burger unless all keys are collected 
3.20 KB


Flowchart

 Pseudocode 
Movement:
playerSpeed = 3;
MOVELEFT = keyboard_check(ord('A'));
MOVERIGHT = keyboard_check(ord('D'));
MOVEUP = keyboard_check(ord('W'));
MOVEDOWN = keyboard check(ord('S'));
If (MOVELEFT )
{
x -= playerSpeed;
}
if (MOVERIGHT)
{
x += playerSpeed;
}
If (MOVEUP )
{
y -= playerSpeed;
}
If (MOVEDOWN )
{
y += playerSpeed;
}
Score object
global.gamescore +=1;
Score object
global.gamescore = 0;
draw text(x,40,"Sales = " + string(global.gamescore));

Data Dictionary
Name 
Data type 
Data length 
Scope 
Purpose
Lives 
Integer
3 to 0 
Global
Shows the remaining live of the player
Score object 
Integer 
0 point  to 10 points
 Global
Show the number of points collect by the player from picking keys 
Timer object 
Float 
2 min to 0 sec
Global 
Shows the remaining time left for the player to complete the game. 



Development Choices
Platform
The platform I decide to develop the game for is the personal computer running on Microsoft windows operating system because the IDE I am going to use to develop the game can run on the operating system. Any other computer the run on the MAC operating system can’t run the game.  
Programming language
The programming language used in developing the game is the Game Maker Language which is the proprietary language for Game Maker studio. Creating games in this language is simple to understand even for beginners because it comes with its own software game maker studio. 
API and computer game development kits
Computer game development kits or software used in developing the game is the Game maker studio which comes with its own language, the Game maker language. Creating a game with game maker studio is quite simple because of the how flexible the Game maker language is, game maker itself has a feature known as ‘drag and drop’. This enable you to add methods or attributes to the object in the game without having to spend much typing plenty lines of codes. The software also gives the facility to write your lines of codes to suit you need. The software on relies on object oriented and event driven programming paradigms when making a game. Event driven programming is used to create the graphical interface of the game and object-oriented programming is also used to add attributes and methods such as movement, scores and live to the objects which are the characters in the game.  
Computer game development kits
The game is developed for a windows computer and any other device that is able to execute .exe files. This is because the game maker studio IDE can only export the game files in .exe file format.
Resources
Hardware
The hardware resources I used to develop the game are monitor, keyboard, mouse, speaker, system unit. The monitor served as the display for me to see what I was working on. The speaker to hear the sound I added to games, I needed to how it sounded when it is added to the game. The keyboard was used to write the code is used in the game development. Mouse for point and selecting the feature of the software is used in developing the game. And the system unit contains the processing unit I used to process the game. 
The game use need to play the game is the keyboard, mouse, monitor and speak. 
Software
I used game maker studio 8.0 in developing the game. Game maker studio allows you to create game for different genres, it also studio has a feature known as ‘drag and drop’ which makes it possible for new game developers like me be able to add actions or method(characteristic and attributes) to the objects of the game without having to write plenty lines of code. 
Constraints on the game development
Time
At the start of the process of creating the game it was timing consuming because I was still trying to familiarise myself with the software I was using, but once I got to know my way around how the software works I can able to work within the time allocated for each task. 
Game Maker’s IDE
Although Game maker is simple to use and helpful to novice and experienced developers, it has its own constraints like any other software out there. Some of the constraints for companies and developers it can only be installed on a window operating system, meaning developers who have different operating systems cannot use the software. Another with gamer maker is the ability to translate or transfer from it to different platforms is limited mainly of the ‘drag and drop’ features. 
Legal and ethical consideration
Copyright law
Copyright law is meant to help protect the intellectual works of authors be it media or art contents. This means that you can’t claim someone work as your own work without having to giving credit to them even if it is for educational purposes. Because 
Ethical consideration
 When was a product is being created there are usually several ethical issues that must be considered during the development process based on the user requirement. And because the game is being developed for audience between the ages of 8 years and 12 years, it is ethical for it not to contain violence and anyone damaging information which might have an adverse effect on the behaviour of the players. 
Consumer rights Act 2015
This act makes it obligatory for the maker or manufacturer of a product to refund or repair their products which they have sold to their customers when the products develops a fault or have a problems with it. This act is only limited to paid products but also free product. Therefore in order not to violate the act I shall fix anyone faults developed by the game if a client request it or if I distributed it for free. 
Licence fees
Before you distribute a game on a platform whether it is a paid or free game you need to pay a licence fee to the platform in the view that your game will not in any way tarnish the reputation of the company operating the platform. And because my game is for educational purpose I won’t be publishing it on any platform meaning the wont be a need for me to pay any licences fees. 
Royalties 
Royalties are the payment made to a commercial game engine when you make and publish a game using that engine. Royalties are paid when the game is not free to play. Because I won’t be publishing the on any game engine, there will not be the need to pay any royalties.
Digital Right Management
Digital right management are the right regarding how digital products are shared and used. I won’t be using the digital right management because I don’t intend to share or distribute the game on any platform.


Project plan
Gantt chart
Task
Expected completion
Actual completion
Comment 
Demographic 
11/02/2020
11/02/2020

Game genre 
12/02/2020
12/02/2020

Initial game design 
12/02/2020
13/02/2020

Design review and feedback 
13/02/2020
13/02/2020

Revised game design
14/02/2020
14/02/2020

Asset table 
14/02/2020
14/02/2020

Flowcharts
15/02/2020
15/02/2020

Pseudocode
15/02/2020
15/02/2020

Data dictionary 
16/02/2020
16/02/2020

Development choice 
17/02/2020
17/02/2020

Resources 
18/02/2020
18/02/2020

Constraints 
19/02/2020
19/02/2020

Legal and ethical consideration 
20/02/2020
20/02/2020

Test plans/ table



Project plan 



Game development 




Test plans
Test No.
Purpose 
Input(Data)
Expected Result
Achieved Result 
Correction Action/Comment 
1.
Character Movement 
Right key, left key, up key, down key
Character movement in correspondence of the key pressed 


2.
Does score increase?
Collecting keys
The score increases by one


3.
Does timer decreases?
When the game start 
Timer decreases 


4.
Lives  bar
Collision with monster and rocks
The live bar decreases by one 



Playability Testing 
Test No.
Purpose 
Input(Data)
Expected Result 
Achieved Result
Correction Action/Comment
1
Game over
After losing all lives 
The game end s


2
Does the player go to the next level after collecting all keys?
Reach out to the doors leading to the next level
The player is supposed to progress to level two


3
Difficulty
Are you able to achieve victory on each level?
Difficult should increase as each level increases. 


4
Able to reach the end of level 2 with the allocated time limit
Play through the game to see if the player can reach the end of before the time runs out
Should be able to be able to finish with the time allotted if played with care.


5
Balance of hazards and rewards
Collision with monsters and keys
The hazards should be distributed on the screen evenly




Compatibility Testing 
Test No.
Purpose 
Input(Data)
Expected Result 
Achieved Result
Correction Action/Comment
1
Does the game loads properly 
Reload the on existing level.
the game should reload without restarting the whole game


2
Does game save properly?
Try saving the game on the current level
The game should continue from the point where you saved it.


3
System controllers 

Every input should do what it was intended for.


4
Platform functionality?

The game should work smoothly 



Stability Testing 
Test No.
Purpose 
Input(Data)
Expected Result 
Achieved Result
Correction Action/Comment
1
Does the game work without braking 
Moving the player around the maze
The player is able to move around in the maze without breaking 


2
Frame rate 
  
There shouldn’t be glitches when the characters move. 








 

