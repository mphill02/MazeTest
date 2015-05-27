# MazeTest
This is an implementation of a maze we use to teach students how to write an algorithm for navigating a maze.

Using SmartMazeTest
You can use the SmartMazeTest class to help you visualize the behavior of your navigation algorithm. The SmartMazeTest class has all of the code you need to be able to validate your algorithm. Here is what you need to know:
* Load your maze using the getSampleMaze method. If you have a blank proceedToNextCell method you will get a visual display of your Maze.
* Put your correct path in the loadIdealMovePath method
* Put your navigation algorithm in the proceedToNextCell method.
* You need to have the implementation of the Cell.

There are three key variables that you need to understand:
currentCell - reference to the Cell object where you are currently located
currentCellKey - String reference to where you are currently located. It is in the form “x,y”
maze - reference to a HashMap that stores Cell objects with key of type String in the form "x,y"

The coordinate system starts with 1 for both the x and y axes.

Modify your run configurations to pass the starting point of your Maze.

If you are not on the ideal path you will get a dialog message letting you know.
If you run out of path to validate you will get a dialong message letting you know.


