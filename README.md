# Round-MACOSX
This project is a multiplayer, top-down, shooting, comptetitive, cooperative computer game called Round.

### Development
Round is in development for its 8th version. For more details on recent updates and development of the game, visit the link
given under the __Source__ header near the end of this document.

### Notes
Within this directory is the downloadable client application for the game for computers running the mac operating system, 
but it will not run unless its server is also running at the ip address and port to which it will attempt to connect.

Currently, the server is not running regularly, so the game is not playable yet.

To see versions of this game made compatible for computers with windows operating systems, see the links given under the 
__Other OS__ header at the end of this document.

----

# Installation
To install this application (which is not suggested at the moment, given it shouldn't do much), follow these suggested steps in their given order:
  1. Download the .zip file of the project
    1. Navigate to the green _Clone or download_ button
    2. Press it
    3. Select _Download ZIP_ from the drop-down menu
  2. Find the project on your computer
    1. It's a folder called _Round-MACOSX-master_
  3. Open the project folder
  4. Allow the app to run
    1. I'm not an identified mac developer, so if you try to open the app right away, your computer will think it's a bad idea
    2. Open _System Preferences_ on your computer
    3. Navigate to and open _Security and Privacy_
    4. Under the _General_ menu, change the preferences entitled _Permit applications downloaded from:_ to _Anywhere_
    5. It's going to recommend that you not do that, and it's true that it's not recommendable to allow any application to run, so if you think Round is malware, don't install it
  5. Open _Round_Client_ in the project folder
    1. Your computer will give you one last warning before allowing you to proceed.
  6. Restore your original security preferences
    1. You won't have to change your security preferences again to allow Round to work in the future, and it's not recommendable to leave these preferences set to allow apps to run from anywhere for too long
  7. Enjoy playing Round

If you notice anything inaccurate or confusing in the above installation instructions, please let me know so I can fix them.

----
  
# Gameplay
There are instructions that I wrote that can be read within the game, but they don't go into much detail and are somewhat incomplete
in an attempt to make them concise, so here are more exhaustive instructions.

### Goal
Increase your score

### Controls
__Movement:__ W,A,S,D keys or arrow keys

__Attack:__ Left-click

__Special:__ Right-click

### Home Menu
When you first open the game, a home menu is shown. There are 4 buttons:

__Info Button:__ General background information about the game

__Help Button:__ In-game instructions. You can scroll through them or use the up/down buttons on the right side of the screen to read.

__Team Button:__ A list of teams, each with its appropriate icon, owner, and code. If no one owns a team, you may request to own it by navigating here after creating an account and clicking the icon. To request a new team, scroll down to the bottom and use the + button.

__Play Button:__ Continue to sign-in

### Sign-in Menu
This is the area where you select your _combat package_ (the buttons along the top), adjust game settings, create an account, and sign in to play the game.

__Combat Package:__ A version of play. Each package has its own speed, attack weapon, and special ability.

__Game Settings:__ There are small circular buttons on the left. The upper is to alter how stuff is displayed in-game. The lower is to change options between creating an account and signing in. If you don't have an account yet, it should be set to _NEW FILE_.

__Create Account:__ Switch to _NEW FILE_ and type in a username. If you include numbers, players won't be able to see those numbers, so they can act as a password so others don't sign in as you. Then click the play button on the right.

__Sign In:__ Switch to _LOAD FILE_ and type in your username, including numbers. If you have signed in before on that computer, the game should offer an auto-completion your username. To accept the completion, press ENTER/RETURN. When finished, click the play button on the right and you should be taken to the game field.

### Teams
I've described this game as cooperative as well as competitive because there is the option of creating and joining teams.

__Create a Team:__ Write your username in the Sign-in Menu and then navigate to the Home Menu and then click the Team Button (it has a shield picture on it). Choose a team you like by clicking its icon (if it's unowned), or request a new team by using the + button at the bottom (scroll down). If you make a team request, I'll try to create the team. If I do, it will show up the the Teams Menu and you will own it.

__Join a Team:__ To be part of a team, you have to indicate its code in the Sign-in Menu, which you can get from a player who owns the team by asking them in the chat (e.g. _Hi, can I join your team?-OwnersName_). 

__Team Code:__ Just append underscore + TEAMCODE to the end of your username when signing in to use it (if your username is _Bob McSomeone123_ and your team code is _popcorn_, sign in with: _Bob McSomeone123_popcorn_) 

### Chat
After you have signed and are playing, move the mouse to the lower-right corner and press the button to chat, or just use the ENTER/RETURN key to toggle the chat menu. Type a message 
and press ENTER to send it. 

By default, the message is sent to everyone. If you are on a team, it is sent to those on your team. 

To send a message to an individual player, append "-ReceiverName" to the end of your message (e.g. _Hi, Player One. It's Player Two speaking.-Player One_).

### Stats
To see your health and remaining ammunitions in-game, move your mouse to the upper-left corner.

### Enemies
There are artificial enemies that the server creates as well as players in the field. The enemies drop a coin 60% of the times they
die, and are shown without names.

### Quit
To exit the game without signing out, move your mouse to the upper-right corner and click the stop button.

### Change Username
To change your username in-game, move your mouse to the lower-left corner and click the rename button (looks like a pencil). Just type your new name and hit ENTER/RETURN.

----

# Source
The source code to this project (written in Processing), as well as more detailed development information, is available 
at this repository: [ogallagher/Round-Source](https://github.com/ogallagher/Round-Source)

----

# Other OS
If you have a computer running a windows operating system, check out the following repositories:
- For Windows-32 OS: [ogallagher/Round-WIN32](https://github.com/ogallagher/Round-WIN32)
- For Windows-64 OS: [ogallagher/Round-WIN64](https://github.com/ogallagher/Round-WIN64)

----
