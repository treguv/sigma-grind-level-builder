# Sigma Grind Level Builder

  ## Project Description:
This is the level building tool designed to speed up the level building process for Sigma Grind. It allows you to use image parsing to convert a .png file into code that Sigma Grind can understand and use to build a level for you to enjoy. With this tool the fun and creativity is endless!


  ### How Does It Work?:
https://www.youtube.com/watch?v=cjMHRbpUyd4

 ## Installation Instructions:
 1) Pull the repository from GitHub.
 2) ```npm i``` to install all needed packages for node.


  ## Usage Instructions:
 1) Using an image editing program of your choice, draw the level using the colors provided in the Color Coding Key.
 2) Save the file as a ```.png``` file.
 3) Open ```parser.js``` and replace line 41 ```IMAGE_NAME``` with the name of your file (Assuming it is in the root directory)
 4) If you plan to...

 a) Add your own level, replace ```LEVEL_FUNCTION_NAME``` with the name you want to give to your level.
 
 b) Replace the third level, do not change it.

 5) run ```node ./parser.js``` in the terminal. This will generate the level code.
 6) Copy the code from ```level.txt```, and open the main sigma grind project.
 7) If you want to simply replace the third level, open ```levels/levelOne.js``` and replace the ```loadTestLevel``` function with the code you copied from level.txt.
 8) If you want to add more levels to the game, please look through ```SceneManager.js``` and see how the level system is implemented. 
## Credits
   ### Sigma Grind Github page:

  [GitHub Repository](https://github.com/apotafiy/sigma-grind)
### Check Out My Github
   [Vlad Tregubov](https://github.com/treguv)