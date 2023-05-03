Download Link: https://assignmentchef.com/product/solved-cs2261-homework3-game
<br>
<strong>Purpose:</strong> To build a more complex game in Mode 3 to further your understanding of: structs, arrays, and pooling. <strong> </strong>

<strong>Instructions </strong>

In this homework, you will be making a more complex game in Mode 3.<strong> This must be something different than what you implemented for HW02 or any of the labs. </strong>Examples of games you can use for inspiration are at the bottom of this PDF.

<strong> </strong>

The design of this game must be more complex than “catching/dodging falling boxes” or basic “pong”. We are leaving this one more open ended so that you can push yourself creatively and see what fun game you can come up with! You are free to choose one of the examples we provide, but you are also free to create your own original game (if you choose this option, <em>please</em>​<em> speak with a TA firs</em>​t so that we can ensure it is on the expected difficulty level).

<strong> </strong>




<strong>Requirements: </strong>




Your <em>game</em>​ ​ must use the following:

<ul>

 <li>At least <strong>one struct</strong>​</li>

 <li>At least<strong> one array</strong>​</li>

 <li><strong>Object pooling </strong></li>

 <li>A <strong>state machine </strong>​ including at least the following states:​

  <ul>

   <li>Start</li>

  </ul></li>

</ul>

○    Pause

○    Game

○    Win (and/or lose)

■    It is okay if your game is a survival based game, and therefore only has a lose state

○ You must be able to <strong>navigate</strong>​<strong> between the states</strong> in some way (e.g. pressing button START while on the Start state takes you to the Game state, beating the game while on the Game state takes you to the Win state, etc.)

<ul>

 <li>At least<strong> four moving objects</strong>​</li>

 <li>At least <strong>four buttons</strong>​ used for input​</li>

 <li><strong>Collision that matters </strong>(​ e. <em>something</em>​ must happen whenever two different objects hit each other)</li>

 <li>A<strong>txt</strong>​ file​

  <ul>

   <li>An instruction manual (of sorts) that tells a player how to play your game Only a <strong>minimal amount of flicker</strong>​</li>

  </ul></li>

</ul>

<strong> </strong>

Your <em>code</em>​ ​ must have the following:

<ul>

 <li>At least <strong>three .c</strong>​ files (this time more than just main.c and myLib.c)​</li>

 <li>At least <strong>two .h</strong>​ files​</li>

 <li>Good organization (see tips below)</li>

 <li>Meaningful comments</li>

</ul>

<strong> </strong>

<strong> </strong>

<strong>Examples of games at the complexity level we expect:</strong>

<ul>

 <li>Tanks</li>

 <li>Simple flash games (e.g. <a href="https://thesimplearcade.com/">https://thesimplearcade.com</a>​ <a href="https://thesimplearcade.com/">/</a><a href="https://thesimplearcade.com/">)</a><u>​</u></li>

 <li>Simple Neopets games (<a href="http://neopets.com/games/">http://neopets.com/games</a><u>​ </u><a href="http://neopets.com/games/">/</a><a href="http://neopets.com/games/">)</a><u>​</u></li>

 <li>Old Atari games, like Asteroids (<a href="http://freeasteroids.org/">http://freeasteroids.org</a><u>​ </u><a href="http://freeasteroids.org/">/</a><a href="http://freeasteroids.org/">)</a><u>​</u></li>

</ul>

<strong> </strong>




<strong>Tips </strong>

<ul>

 <li><strong>Start early</strong>. Never underestimate how long it takes to make a game!​</li>

 <li>When splitting code between multiple files, put code that will be useful in multiple games in myLib.c, and code specific to this game in main.c or other files. Those other files should be specific to a concept (response to collision, a specific state of the state machine, etc.).</li>

 <li>Organize your code into functions specific to what that code does. <strong>Your</strong>​<strong> main method should not be very long at all!</strong></li>

 <li>Having update() and draw() functions that you either call directly in main() or call in another function that is called in main() is helpful.</li>

 <li>Make sure the order of calling your functions takes into account waiting for vBlank at the correct times to minimize flicker.</li>

 <li>Build upon the myLib.c and myLib.h files from previous assignments.</li>

 <li>Feel free to reference the Recitations files on Canvas to review concepts.</li>

 <li>Feel free to reach out to the TAs if you have any questions!</li>

</ul>