The project is a game that allows the user to solve Sudoku puzzles.Sudoku is one of the most popular puzzle games of all time.The aim of the project is to recreate the experience of solving Sudoku puzzles that people used to do in newspapers.The game consists of a 9x9 grid of boxes that can be filled with digits from 1 to 9.The game has a reset button, an exit button and a check button.The game grid consists of 9 rows and 9 columns, which are buttons that can be clicked to fill the digit in the box.It will be a combination of a 9x9 matrix of buttons.

![Screenshot (27)](https://github.com/shivanikowkuri/Suduko/assets/147936662/d337b9b2-0078-4dab-9bbf-6a71513fb4bc)

The project focuses on technologies used: Java(logic, including OOP concepts), Java Swing and Jframe(GUI).
Java Swing is a part of JFC(java foundation class) and is responsible for creating lightweight GUI applications.Frames are top-level containers provided by Java Swing which provide a playground for designing components.JFrames are also known as base windows on which other components such as menu bars, panels, labels, text fields, buttons, etc. rely.Almost every Java Swing application starts with the JFrame window.


The project will be created using Java with Maven for building and designing the UI for a Sudoku solver .As said above The main Jframe form will be used for designing.To design the sudoku jframe we use panel which acts as grid for each grid and we use buttons which will be added to the grid after further adjustments.9 buttons are present in every grid, with each button named according to row and column.Each button have its own functionalities.
The buttons for selection, reset, exit, and check moves are present.A 2D array string is created to store the solver values of Sudoku.The turn variable will store the value of the selection button that is pressed which indicates with a background colour of blue.The value of the turn variable will be set in the clicked grid with background colour set to white.

![Screenshot (17)](https://github.com/shivanikowkuri/Suduko/assets/147936662/4d464a8a-c000-459a-805b-a3353a18ee94)

There are few predefined buttons which are highlighted with a skyblue colour in the backgroud.They remain constant in the jframe.If one want to change its value a warning message will be dispayed.

![Screenshot (19)](https://github.com/shivanikowkuri/Suduko/assets/147936662/e4f2145c-a712-4081-ac23-089e34ad917f)

As mentioned above,the check button is used to check whether the value set in the each button is correct or not .If it is not correct ,it highlights the button with red background else remain same.The checking of correct value in the button is done with the help of 2D array Solver values. 

![Screenshot (21)](https://github.com/shivanikowkuri/Suduko/assets/147936662/60cb7e3e-fe6c-4f24-975a-96428b761581)

Upon clicking the reset button, a warning box will be displayed using JOptionPane. If Yes is clicked, the program will reset by replacing the prefilled grids with a blank text.
The function 'reset game' is called upon clicking the reset button. The 'buttons' array stores the names of the 81 buttons, while the 'predefined buttons' array stores the names of the buttons that are predefined.Nested for loops are used to iterate over the 9 grids and their 9 buttons. A boolean flag variable is used to identify whether the value of a specific grid is predefined or not.If a grid is not predefined, its value will be set to blank upon clicking the reset button.

![Screenshot (22)](https://github.com/shivanikowkuri/Suduko/assets/147936662/d72a7d41-8cf9-48df-a8f4-534d46dbbbb3)

Upon clicking the exit button, a warning method will be displayed with two options: Yes or No. If Yes is clicked, the program will stop the execution and the JFrame window will be closed.

![Screenshot (24)](https://github.com/shivanikowkuri/Suduko/assets/147936662/5185646e-a39d-43c5-b267-8e844b5b6dd8)


Sudoku-The game that piques everyone's interest.

Thankyou!



