# Welcome to Michael Haggerty's GitHub Page

## Code Review:
*While I did have other artifacts planned, I ultimately changed due to them being unfeasable.*

*However, This can still show my skill at analyzing code.*

**[REVIEW LINK](https://drive.google.com/file/d/1P2oWLjikh-stWaZOzWydvHmxgpiPjsVG/view?usp=drive_link)**

In this class I improved three different programs.

## 1: Fuzzy Farmer 3D
### Collect Fuzzies before time runs out in this 3D platformer.
Download the File **[HERE](https://drive.google.com/file/d/1GKi1U7q7RuK-uhaaUvotmHtQAcQeESDP/view?usp=drive_link)**
### List of improvements over the original version:
- Made the walls inescapable
- Added particle effects
- Added background music
- Added quit buttons to the win and lose screens
- Added detailed destruction
### Narratives _Originally Written 05/24/23_

For my software engineering artifact, I chose “Fuzzy Farmer 3D”, which was made for my “GAM-303” class at SNHU.  This program is a game where the player must climb rocks and dig blocks to collect all the “fuzzies” within a time limit.  The game opens with an instruction screen overlay on the first and only playable level.  If the player collects both red fuzzies and both blue fuzzies, then they win and are taken to a victory screen.  If the time expires, the player is instead taken to a “game over” screen.  I chose Fuzzy Farmer 3D because it has an intricate counting system where the player needs to collect all fuzzies of every type before beating the level.  Said system also works together with a level system to make sure that I originally planned to use the “Coinbased Castle” program from “GAM-305”, but I could not get it working.  While that program was part of a team project, Fuzzy Farmer 3D was created solo (with the help of instructions given during my GAM-303 class).  I also made good use of quick asset swapping in my enhancements that demonstrate a unique way to dig tiles.

Past iterations of this game have had flaws where the player could jump out of bounds, so I replaced the fence with a brick wall that still fits the aesthetic of the game.  I also made certain geometry in the level “crumble” when interacted with by having the object delete itself and be traded with a nearly identical physics object. I also fixed several UI issues.  The first was that the Intro screen was not big enough.  I also added a background behind the timer and fuzzy counts so that players can see the HUD better. For the text and other objects to be centered on the HUD and win/lose screens, it is recommended to play the game as a standalone application.  When playing, the player can also press escape to close the game without having to tab out.

I set out to create a more solid program.  I am most proud of the new destruction system.  Having digging claws that splinter objects is far more realistic than having the objects that just vanish without a trace.  This is one of the “well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value.”  In this case, as with most games, more advanced game mechanics means more desire for the product, which leads to more sales.

When developing the program, I had a lot of trouble implementing the “dig” feature.  I first had to install a new plugin for “apex destruction.”  Next, I repeatedly tried to get the digging feature to work with a single object, but the object would either start destroyed, would not get destroyed, or would have no collision.  I could not find a good fence texture big enough to properly, so I settled on a brick wall that still fits the farm aesthetic.  I learned more than I ever needed to about fracture/destruction physics in Unreal.  I also learned that swapping objects can have many other uses for future projects.

## 2: Top Destinations
### List your favorite destinations to visit.
Download the File **[HERE](https://drive.google.com/file/d/1rMJ3efDqobngNMs93nED3EXpyqUjXrh4/view?usp=drive_link)**
### List of improvements over the original version:
- Added a for loop to obtain user input
- Now allow for users to input images
- Condensed items into arrays
- Added an exit button
### Narratives _Originally Written 06/07/23_

My artifact is a program that lists the top 5 locations to travel to.  It opens in a self-contained widget and allows users to click back and forth between various slides and show a list of locations with some information displayed to accompany them.  In the previous version of this program, said information was hardcoded into the program itself.  In the current version, the information can be edited by the user within a console when starting the program.  The locations also have images to accompany the information as well.

This was originally created to be just a widget, but I modified it to be a proper database via adding a second java class.  This way, functionality can be expanded while keeping the base structure intact.  I also added a title and ending page that do not render images to the user.  I made sure to provide comments that let anyone seeing the code know how the program works.  I believe that I can show true mastery of this program by the time of the final submission by allowing the program to store images as well, and thus becoming able to use different locations.

I believe that I met the requirement to “design and evaluate computing solutions that solve a given problem,” as the program can now be customized to fit the needs of users regardless of their needs.  Because of the customization that I added to my program, anyone using the program can now add entries by simply running the right program, as opposed to looking for the proper line to input code.  In the future I hope to make the program fully customizable, including the editing of categories and images to make sure everyone can use the program to the fullest, regardless of their location preferences.  I was unable to get a page number system that was not manually entered, thus defeating the purpose of said system, but I might be able to add that before the final submission as well.

My original plan was to use the animal database that I made, as it was the best example of a “database” that I had.  Unfortunately, I was unable to get it working because I encountered several errors and I forgot too much about Jupyter Notebook to know what to do.  At first, I originally thought it was going to be nearly impossible to convert a simple widget program to a proper database that can store user input.  I then figured out how to use one program to store input from the user into a database and have it extend the widget program to ensure that the original workings of the program remained intact.  From there, I could use simple if/else loop to add the opening and ending pages.

## 3: Linked List
### Search through, add, and delete bids in a list.
Download the File **[HERE](https://drive.google.com/file/d/1YBdD1nSOSiEKIMvuD10bAvPLY9qT8iHH/view?usp=drive_link)**
### List of improvements over the original version:
- Added a way to search for specific bid
- Added the ability to use any .csv file
- Improved comments
### Narratives

This program is about connecting to a list of bids and allowing the user to perform various actions on them.  The user can add their own bid, load bids from a .csv file, display a list of all bids, delete a bid, or search for a bid by its ID.  Later revisions also added the ability to find a specific bid by entering an ID and the ability to load a database of the user's choice.  This can be seen as either an algorithm or a database program, depending on what you want to focus on.

I was able to make the program more suited to anyone's needs by adding additional functionality.  As with the Top Destinations program, this program went from being an example of what a program can do to giving the user full freedom to find any item in any list.

I was not able to incorporate much feedback into this program, as it was a last-minute replacement for another program that I could not improve further.  I tried to flesh it out as much as possible by converting the program from a simple proof-of-concept to a full fledged program.  

**You can download this full text, screenshots, and more via the .zip and tar.gz files above.**
