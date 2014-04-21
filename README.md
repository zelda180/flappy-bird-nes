# Flappy Bird NES

This project is an attempt to create a clone of Flappy Bird for the Nintendo
Entertainment System.  The project can be run through a NES emulator, such
as [FCEUX](http://www.fceux.com).

![Flappy Bird NES Screenshots](assets/screenshots.png "Flappy Bird NES Screenshots")

## Project Details

### Assembler

The assembler being used is the somewhat controversial `nesasm` assembler
(I have version 2.51).

### Progress

The project so far:

- There is:
    - a start screen
    - background scrolling
    - an animated bird
    - gravity
    - ability to flap - press 'A'
    - a game over state - currently only triggered when the bird wipes out by
      ploughing into the ground
- There is not:
    - any pipes to avoid
    - sound

## Notes

- This project was created as a personal learning excercise
- The code is well commented, but I would advise against using it as a learning
tool for NES development - I don't really know what I'm doing when it comes to
NES development (or assembly for that matter), so there will be few (if any)
occurences of best practices being used in the code.
- With the above in mind, a great resource for learning NES development is the
popular [Nerdy Nights tutorials](http://nintendoage.com/forum/messageview.cfm?catid=22&threadid=7155)