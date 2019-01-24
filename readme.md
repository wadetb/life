# Conway's Game of Life

I created this simple interactive activity and accompanying worksheet for the 2017 Day of Code at Dora L. Small school in South Portland, ME. 

For a description of Conway's Game of Life and cellular automata in general, see https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life.

A direct link to the activity is here: https://rawgit.com/wadetb/life/master/life.html

The optional worksheet is here: https://rawgit.com/wadetb/life/master/Game%20of%20Life%20Sheet.pdf

## Preview

![Sample](sample.jpg)

## Instructions

* Clear the board and leave it paused while students gather around the monitor.
* Explain the 3 rules. Relate them to underpopulation and overpopulation of other kinds of communities.
* Demonstrate each rule in turn, by drawing a simple pattern with the mouse and advancing the simulation one step. Students predict the outcome before advancing.
* Use the "sprinkle life" button to scatter live cells randomly around the board. Students make predictions about how many will survive. Keep sprinkling life until the students vote to stop.
* Run the simulation full speed and watch it animate. Ask if the outcome matches their predictions.
* Have students design their own patterns using the worksheets and predict the outcomes.
* Let students use the computer in small groups testing the patterns they created, and experimenting with the example patterns. Motivated students can try to create a working "Gosper's glider gun".

## Discussions

* Discuss the meaning of the words "cell" and "automaton". Relate automaton to automatic.
* Discuss the complexity of the rule set, compared with other games the students may know of, such as board games.
* Examine why clicking on an open space in the board, while the simulation is running, has no apparent effect. How is pausing the simulation useful?
* After the state settles, examine various stable structures that form.
  * Try to determine why each one is stable.
  * Experiment with clicking on different parts of stable structures while the simulation is running (killing or activating one cell) and see how this affects the "community". Example: Any one corner of a square can be killed and it will be "healed".
* After the state settles, examine a 3-row to 3-column oscillator. Have students help you through one oscillation. Discuss the meaning of "to oscillate". 
  * Challenge students to come up with another oscillator. Note- the examples section has several.
* Ask students whether they believe the simulation will always stabilize, or if it might go on changing forever. Pause, clear the board, and create a single glider.
* Talk to students about building complicated machines with simple structures. Show them how working computers have been built on the game of life (and its 3 simple rules), for example: https://www.youtube.com/watch?v=My8AsV7bA94

## Code

The activity is written in simple HTML and JavaScript. Advanced students might like to try changing the color of the dots, or altering the rules. 

How does it change if some of the rules are disabled? The website <a href="conwaylife.com">conwaylife.com</a> lists a number of rule variations; challenge the students to implement one of them.
