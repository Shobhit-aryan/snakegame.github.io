## Basic snake game
The background board is created using Canvas.
Data Structure used:-  
            Here I have used array for creating snake. 
            For snake motion, pop the last cell and add it in front.
            Change the cordinates of cell according to key pressed for changing the direction.
            Food object is created and generated randomly on the board using random function.
            Whenever the cordinates of food object and first cell matches the snake size is increased by adding one cell to the last.
            And increased the score by 5 points.
            Whenever the first cell of snake encounters the boundary co-ordinates, the game stops and an alert message pop up displaying game-over.
