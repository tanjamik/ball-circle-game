# Circle the Ball!

A simple browser game: a happy ball bounces around the screen, and you score points by moving your mouse in circles around it. Each full loop = 1 point.

## Play

Just open `index.html` in any browser, or play it online once GitHub Pages is enabled.

## How it works

- The ball bounces with physics (gravity + wall collisions).
- The game tracks the angle of your mouse around the ball and accumulates rotation.
- Every full 360° loop bursts particles and scores a point.
- Best score is saved in `localStorage`.

Works on desktop (mouse) and touch devices (finger drag).
