# Connect_3_Game
A connect 3 game which keeps track of red versus yellow pieces to connect in a 3-way, tic-tac-toe style format. Designed and developed using Android Studio

Video link: https://youtu.be/thFOAKH7HQI

This folder contains a project I worked on called Connect3. This was one of the first games I designed, and implemented in Android Studio. In its simplest form its a hybrid between tic-tac-toe and connect 4. The complexity comes in when i sought out an implementation that works. 

Some of the biggest challenges in making this application came with the design. Without any application design experience I needed a fluid way to provide functionality so that the game was at least enjoyable. That came with the decision to transition the connect 3 pieces from the top of the screen, into the layout using tags and a gridLayout. 

Some other aspects of the game that needed consideration was how I would determine when there is a winner. The implementation already keeps track of the winningPositons, gameState, and activePlayer. But initially there was no way for me to stop the game once we had a winner. I was able to introduce another variable, gameActive, which acted as a switch. I was only able to add pieces to the grid as long as the game was active, and once a winning position was met, the variable was set to false, not allowing the player to add pieces. 

The most fun part of the application was designing the “Play Again” feature. That is truly what made this application playable. The best part about a game is the ability to replay it, so adding the feature to reset the board made this project feel complete. What you may find is that the play again functionality now exists in many of the games I make.

