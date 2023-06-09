# Java Project : CY-Slide
GRANDJEAN Théo ; BOCQ Andrew ; GOSSELIN Julian ; PAQUES Anatole ; JUMEL Paul
## Requierements :

- Make sure you have `JavaFx` library and `JRE System` library installed 
- create a package named "application"
- /!\ Dont forget to change the path of the file "level.txt" in TaquinFX.java at line 53
- Open a terminal in the project folder
- To compile : `javac -d bin -sourcepath src -cp src/application Main.java`
- To run : `java -cp bin application.Main`
## Game - How to play
![Screen Console](style/screenJEU.png)

- There's an empty slot, you can move a block in it by dragging it.
- Simply click on a block and it will take the place of the empty slot.
- The blocks are first shuffled, and the game is won when the initial layout is reached.
- There are several levels, and to access them, you must pass the current level!
- At the beginning, the level is in its final position. To start it, click <img src="style/Reset.png" width="30" height="30"> and select your mix type.
Then solve the riddle!
- If you get stuck, you can always click on the light bulb <img src="style/resolve.png" width="30" height="30">, which will solve the puzzle step by step. There's automatic solving, 
or square by square.
- But be careful!!! The light bulb will not validate the level.
- If the level is finished, the game board will turn green. To restart the level, press the Shuffle <img src="style/Reset.png" width="30" height="30"> button again.
- Black squares are forbidden: you can't go on them.
- You can play with your mouse or keyboard: simply select the square with the arrow keys, then press space or enter.
                    
## Javadoc
To access the Javadoc go to the folder `javadoc/application`
