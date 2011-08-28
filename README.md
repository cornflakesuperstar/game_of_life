# Game of Life

The Game of Life, also known simply as Life, is a cellular automaton devised by the British 
mathematician John Horton Conway in 1970 - [Wikipedia] [1]

## Project inspiration
Pete Yandell hosted a [code retreat] [2] at Envato on August 27th in 2011 where we practised TDD pairing using the Game of Life as our problem. It was a bit tricky to bang out a solution in 45 minutes. This github project was created to think about it a bit more.

## Running this codebase

    $ git clone git@github.com:cornflakesuperstar/game_of_life.git
    $ cd game_of_life
    $ ./world.rb --simulate sample_worlds/oscillator-blinking.gol

## Codebase thoughts
The performance of this codebase could definitely be optimised a lot. 

It would also be interesting to test with infinity in mind - would the data type usage blow up memory allocation?

This implementations board also doesn't grow. 

  [1]: http://en.wikipedia.org/wiki/Conway's_Game_of_Life "Wikipedia"
  [2]: http://notes.envato.com/developers/code-retreat/   "Envato"  