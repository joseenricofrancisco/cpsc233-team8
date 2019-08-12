
# Battleship

- CPSC233 T02-TEAM8
- Project Name: **Battleship**
- Project Description：
  User loads into the game, which displays 10*10 buttons on the game board. There are three ships which are randomly located on the game board. User and AI randomly press the buttons on the game board one by one, and user will press first at the beginning of this game. If user or AI presses the right buttons which the ships locate on them, the buttons will show an “X”, this means user or AI has already hit the ship for once. If user or AI presses the wrong buttons which there are not ships that locate on them, then the buttons will show an “O”, this means user or AI has not hit the ship. When all ships have been already damaged, the game will be closed. If user has damaged more ships than AI, then user will win, otherwise AI will win. 

***
There are two version now: text-version and GUI.

Text-version and GUI-version are compressed as "Final.zip" in this git.



## Technologies:
- Java 8 or 9
- JUnit 4
- Eclipse IDE (version 4.12 was used for this project)

## How to start text-version:
    
    1. Download the file "Final.zip" in https://github.com/joseenricofrancisco/team-8-battleship

    2. Unzip the file and locate the folder you unzipped in your command terminal.

	3. Locate your position into "src" folder in your command terminal.

    4. Use command "java battleship.gui.GUIStarter" to run the game.

## How to start GUI-version:
    
    1. Download the file "Final.zip" in https://github.com/joseenricofrancisco/team-8-battleship

    2. Unzip the file and locate the folder you unzipped in your command terminal.

	3. Locate your position into "src" folder in your command terminal.

    4. Use command "java battleship.gui.GUIStarter" to run the game.

## How to run JUnit test:

#### Board JUnit test
In "Source" folder, there is a folder named "Testfile". From there access te file "BoardJUnit".


The folder contains 4 files:
- BoardTest.java
- Board.java
- hamcrest-core-1.3.jar
- junit-4.12.jar

1. Download the files in https://github.com/joseenricofrancisco/team-8-battleship/tree/master/Source/Testfile/BoardJUnit

2. Locate your position into "Testfile" folder in your command terminal.

3. Copy and paste this command into your terminal and hit enter to compile.

   javac -cp .:junit-4.12.jar:hamcrest-core-1.3.jar *.java

4. Copy and paste this command into your terminal and hit enter to run tests.

   java -cp .:junit-4.12.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore BoardTest

***
#### Ship JUnit test
To run the JUnit test (in Eclipse) for the Ship class, please follow https://github.com/joseenricofrancisco/team-8-battleship/tree/master/Source/Testfile/ShipJUnit for detailed instructions.
    
## Addtional resoures
- Here's a sample Battleship board.
![Battleship board](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Battleship_game_board.svg/1280px-Battleship_game_board.svg.png)

