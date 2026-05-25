# Physics-Simulator
This physics simulator is capable of simulating rigid collisions and gravitation, with related constants such as little g, big G, friction, and restitution being adjustable and quantities such as momentum and energy being visible in an in-simulation menu. Dynamic balls and immovable rectangular, circular, and custom walls are supported.

The default system is the Earth orbitting our Sun, with the actual values for G, the masses, and the distances.
Positive directions are right and down.
Press "r" to reset.
  Press "r" once to remove all balls.
  Press "r" twice (or when there are no balls) to remove all walls.
Click arrows, "+", "-", "<", and ">" to change the simulation viewport or speed.
  Click arrows to move the veiwpoint.
  Click "-" to zoom out.
  Click "+" to zoom in.
  Click "<" to slow down the simulation.
  Click ">" to speed up the simulation (high speeds will increase simulation error).
Click menu items to change their value.
  Enter numbers and ".", toggle "-", and press "e" (for scientific notation) to enter values.
  Press backspace to delete.
  Press enter to confirm.
  Press escape to cancel.
Click to create new objects depending on chosen mode.
  Press "b" for ball mode.
  Press "w" for rectangular wall mode.
  Press "t" for triangular wall mode.
  Press "c" for circular wall mode.
  Press "l" for custom (list) wall mode.
  Press "d" to cancel creation.
  Hold "control" to avoid selecting an existing object or align angles to 15° increments.
  Creation color will constantly, randomly change during creation.
Click objects to select and drag them.
  Press "m" to move selected objects.
  Release "m" to transfer position and velocity.
  Press "a" to rotate selected objects.
  Release "a" to transfer angular position and velocity.
  Hold "shift" to align positions and distances to set increments.
  Hold "control" to align angles to set increments.
  Click the object in the menu to center on it.
Click balls to edit their states.
  "mass" is the mass of the ball.
  "size" is the diameter of the ball.
  "moi" is the coefficient for the ball's moment of inertia (moment of inertia = moi * mass * (size / 2)²).
  "vx" is the horizontal velocity of the ball.
  "vy" is the vertical velocity of the ball.
  "va" is the angular velocity of the ball, with counterclockwise rotation being positive.
Click "settings" to edit performance settings.
  "fps" is the maximum frames per second, which is also capped by browser refresh rate (usually 60).
  "upf" is the maximum number of simulation updates per frame.
Click "presets" to select simulation presets.
  Click "save" to save the current simulation state as a preset.
  "empty" is empty with no gravity.
  "small" is empty with downward gravity.
  "large" is empty with gravity between balls.
  "box" has box walls.
  "orbit" has to balls with the masses and distances of the Earth orbitting the Sun.
  Click a preset to apply it.
  While holding "shift", click a preset to edit its title.
  While holding "control", press "backspace" to delete a preset while editting it.
Click "variables" to edit simulation settings.
  "speed" is the speed of the simulation.
  "height" is the in-simulation height of the screen (the width will automatically adjust).
  "G" is the universal gravitational constant.
  "gx" and "gy" are the vector components of the uniform gravitation force.
  "wFrict" is the friction coefficient between balls and walls.
  "wRest" is the coefficient of restitution between balls and walls.
  "bfrict" is the friction coefficient between balls.
  "brest" is the coefficient of restitution between balls.
  "collide" is whether or not balls collide with other balls.
  "drag0" is the coefficient of the constant term of drag.
  "drag1" is the coefficient of the linear term of drag.
  "drag2" is the coefficient of the quadratic term of drag.
Click "defaults" to edit the ball creation defaults.
  "density" controls the mass of the created balls (mass = density * size³).
  "moi" controls the coefficient of the created ball's moment of inertia (moment of inertia = moi * mass * (size / 2)²).
  "distInc" is the increment applied when holding "shift".
  "angInc" is the increment applied when holding "control".
Click "info" to view the simulation information.
  "px" is the total horizontal momentum of balls in the simulation.
  "py" is the total vertical momentum of balls in the simulation.
  "kinetic" is the total translational and rotational kinetic energy of balls in the simulation.
  "energy" is the total energy of the simulation (translational kinetic, rotational kinetic, potential due to uniform gravity (relative to the bottom left of the screen), and potential due to gravity between balls).
