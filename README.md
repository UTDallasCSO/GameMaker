# Game Maker

http://gamemakertutorials.com/

### Learning objectives of the workshop
* Basics of the GameMaker software
* Algorithmic approach that characterizes writing computer programs
* The perception behind incremental program enhancement
* The objective behind event-based computer programming
* Develop an understanding of object-oriented programming
* If you want a head start on learning Java or C++, you can learn to use the GameMaker scripting language

### What is GameMaker?
* GameMaker is a software produced by YoYo games, in order to make people experience the thrill of making a computer do what they ask it to do, under the guise of producing a game
* GameMaker creates an event-driven, object-oriented simulation with a visual drag-and-drop interface
* GameMaker program executables can be run on a standalone computer, mobile device or from within a web page (after loading a plug-in)
* The “Lite” Edition can be downloaded for free! There is also a “Pro Edition” that costs $20

### Where can I get GameMaker?
* Go to http://www.yoyogames.com/legacy for Mac and http://game-maker.en.uptodown.com/windows for Windows
* As discussed earlier, The “Lite” Edition can be downloaded for free!  There is also a “Pro Edition” that costs $20.

<br /> <br />

### Getting started
* Double-click on the GameMaker icon on your desktop
    ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/1_zpsuhtopgnn.png)


* We can also start the program from start menu or search options on windows 8.
    
    Now, click here 

    ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/2_zpsr0giewrf.png)

### The First Screen ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/3_zpsgcttlhma.png)

![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/4_zpsebeatbpw.png)
    
    
### Resources ###
* All the things that we can add to the game are called resources.
* On the GameMaker software we can get them from any of the below areas:

    ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/5_zps5tgtghkg.png)

### Resources by definitions ###
* _Sprites:_ Images that are used to show the objects 
* _Objects:_ The things in the game 
* _Rooms:_ The scenes (levels) in which the objects live 
* _Backgrounds:_ The images used as background for the rooms 
* _Instances:_ One particular occurrence of an object 
* _Sounds:_ These can be used in games, either as background music or as effects 
* _Scripts:_ Small pieces of code  that can be used to extend the possibilities of your game
* 
### How do I build a game in GameMaker? ###
* Describe the game you are trying to create  What is it supposed to do? What is it supposed to look like?
* Define the sprites
* BDefine the sounds
* Define the objects themselves, but not (yet) their events and actions
* Go back and define each object’s events and actions
* Define the room
* Put the object instances in the room


> **Note:** It is suggestible to define the objects first and their events and actions later because some of those actions will need to be asked for in terms of objects (that might not have been created yet).

### What next? ###
Now that we are acquainted  with the basic terminology required for working on the GameMaker software, let’s stretch ourselves to know more about various resources and their  functionalities.


![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/6_zpsovjqh6tp.png)

### Sprites ###

* Sprite = picture
    - It can’t do anything but look good
* Visual representation of game objects
* Any common drawing format (gif, jpeg, tiff, png, pnt, cut, etc.)
* Single image
* Sprite things beyond where we go today..
    - Multiple image
        * Animated: explosions, walking
        * Rotated
 
### Adding Sprites ###
* Click “Pacman” on the menu bar 
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/7_zps566b4v4i.png)

* Select Create Sprite from the Resources Menu
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/8_zpslpmv8upy.png)

### Sprite Properties ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/9_zpsfzyr32vp.png)

### Sprite Properties: Starter Recommendations ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/10_zpsvgg2lhh0.png)

### Extra: Edit Sprite ###

* Can use any paint or graphics program
* Transform functions
* Mirror, Flip, Rotate, Scale, Stretch, etc.
* Images functions
* Cycle, Colorize, Shift Hue, Crop, etc.
* Animation functions
* Expand canvas, shift image for center of rotation
* Counter-clockwise Rotation
* Number of Images = 360 / degrees of rotation
* Initial image must face RIGHT
* Advantage of Game Maker Registered Version 

### Quick Review ###

* Sprite = picture
    - Pacman shortcut
    - Load a picture
    - Name spr_thename
    - Now onto objects
* Object = Something on the screen
* Room = The screen
 
### Object = Three main parts ###

1. A sprite.  This is the image it will have on the screen.
2. Events that make the object react.
    - An object is created
    - A key is pressed
    - A collision with another object
    - A click of the mouse
    - ...
3. Actions related to the events.  
    - How the object moves when a key is pressed, 
    - or it runs into a wall, 
    - or when a mouse is clicked or…..

### How do I create an Object? ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/11_zpsynj0kx9y.png)

### Tying a sprite to the object ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/12_zpsgsyxhqh6.png)

### Events and Actions ###
* Now that the object has an associated sprite we need to give it some personality with an associated behavior.
* The next section will describe how to have the object react.
* It takes two pieces
    1. Picking events to react to
    2. Defining the actions they will take when the event occurs.

### Events ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/13_zpsoquzgpkf.png)

### Event Selector ### ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/14_zpsyhccvjrs.png)

Here is the Event Selector menu that lists possible events.  Included are a few brief descriptions:

* _Create_: Defines what the object will do when it is created. Example: Have it moving in a direction.
* _Destroy_: What happens when the object is destroyed.  
* _Step_: What happens during each step of the game.  Steps happen several times a second so often this event includes some random action. Like having a 1 in 100 chance of an enemy appearing.
* _Collision_:  This is used to define how the object will react when hitting other objects.  For example.  Stopping when it hits a wall, getting points when it collides with a treasure, making a noise when it collides with a bell,…
* _Mouse_: Reacting to Mouse clicks (Left, right, middle, wheel, …)
* _Other_: Several events.  Will often use the ‘Boundary’ event to destroy objects when they leave the boundary of the game.
* _Keyboard_: Reacting to when a key is pressed and as long as it is being held down it will continue to do the actions associated with the key being pressed. (Think machine gun)
* _Key Press_: This event occurs when a key is pressed, but only one time (Think of a rifle)
* _Key Release_: This event occurs when the key is released. (Rifle)

### Review ###
* Sprite= Picture
* Room = The Screen
* Object = Something on the screen
* Basic parts of an object
    - Associated Sprite
    - Events the object will respond to 
    - Actions the object will take when the associated events occur.
* Next we will look at a few of the actions available
 
### Event overview ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/15_zpsvcaagsft.png)
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/16_zpsp3xshs42.png)
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/17_zpstazhefjv.png)
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/18_zpsgy0luirp.png)
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/19_zpscwq5d7sf.png)
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/20_zpslckgtgph.png)

### Too many events? ###
We’ll take a little closer look at the move events then look at an example of having he rock controlled by the keyboard. (Example- Rock demonstration)

### Actions: Move ###

 ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/15_zpsvcaagsft.png)
 
 Move Fixed : Give it a direction and speed for moving. (This is the action we will use for the rock) 
 Move Free: Give it direction and speed.
 Move Towards: Pick object, and speed.
 Speed Horizontal: Sets the horizontal speed.
 Speed Vertical: Sets the vertical speed.
 Set Gravity:
 Reverse Horizontal: Good for when you run into a boundary
 Reverse Vertical
 Set Friction
 
> **Note:** All “Move” actions are defined in the description from left to right beginning from the top. 
 
### Actions: Jump ###
 
 ![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/15_zpsvcaagsft.png)
 
* Jump to Position: Give an (x, y) coordinate
* Jump to Start
* Jump to Random
* Align to Grid
* Wrap Screen: Allows you drive run off of one side of the screen only to reappear on the other side of the screen
* Move to Contact
* Bounce

> **Note:** All “Jump” actions are defined in the description from left to right beginning from the top. 

### Example: Rock, Hit Key, Move ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/21_zps4ysc3ox7.png)

### Keyboard Event ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/22_zpsz43sqbh0.png)

### Pick Action ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/23_zpsnogokvzt.png)

### Pick the Direction ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/24_zpskzfsxv11.png)

### Review & Check ###
* Sprite = Picture
* Room = Screen
* Object = Something on the screen
* Parts of an Object
    - Associated Sprite
    - Events to respond to
    - Actions associated with the Events
* Your turn: Create an event and associated action for having the object move right when the right arrow is pressed

### Background ###

These are usually large images that are used as backgrounds (or foregrounds) for the rooms in which the game takes place, but they can also be large images composed of many smaller ones called tiles which you can then place individually in your room to create complex visual designs for levels with far less processing overhead than you would get with objects and sprites.

![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/25_zpskrnvsich.png)

### Rooms ###
* Now we have a Rock sprite
* We have created a Rock object using this sprite.
* We have created two events (Left arrow hit, Right arrow)
* We have associated two actions to the events (Move left and move right)
* Now it’s time to make a Room.

### Adding a Room ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/26_zpsg9i8cryb.png)

### Adding Objects to the Room ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/27_zpslsa81ysd.png)

### Review ###
* Sprite = Picture
* Object = Something on the screen
    * Associated sprite
    * Events to respond to
    * Actions associated with the events
* Background = Background for the room
* Room = Screen
* We now have enough for a basic, although not terribly riveting, game.
* We have a rock that will move left and right based on keys that are pressed.

### Running the Game ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/28_zpscfkd3uzd.png)

### Game ###
![] (http://i1305.photobucket.com/albums/s555/csk12utdsk12/GameMaker/29_zpseglbz77o.png)

### Game-1 ###
* Create a brick sprite, brick object and use the brick objects to make walls.
* Create collision events so that when the rock hits the wall object it stops horizontal direction
* Create a maze
* Add events and actions needed for the Rock to be able to go through the maze.
* Test the rock going through the maze
* Pushes
    * Add features to the game
        * Find other images for sprites. GIFs, Pac man, ..
        * Monsters
        * Secret walls
        * Battles
        * Treasures
