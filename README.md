# Collision/Gravitation Simulator
https://sites.google.com/view/nat-stone-programming-projects/collisiongravitation-simulator

This simulator is capable of modelling rigid collisions and gravitation, with related constants such as little g, big G, friction, restitution, and drag being adjustable and quantities such as momentum and energy being visible in an in-simulation menu. Dynamic balls and immovable rectangular, triangular, circular, and custom walls are supported.

The following is a detailed explanation of every button/control, though most of it is intuitive within the simulator. The below description is clearer when viewed raw.

Positive directions are right and up.
Press "p" to pause the simulation.
Press "u" to jump one frame.
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
  While holding "control", click a value to copy it.
Click to create new objects depending on chosen mode.
  Press "b" for ball mode.
  Press "w" for rectangular wall mode.
  Press "t" for triangular wall mode.
  Press "c" for circular wall mode.
  Press "l" for custom (list) wall mode.
  Press "d" to cancel creation.
  Hold "control" to avoid selecting an existing object or align angles to 15° increments.
  Creation color will constantly and randomly change during creation.
Click objects to select and drag them.
  Press "m" to move selected objects.
  Release "m" to set position and velocity.
  Press "a" to rotate selected objects.
  Release "a" to set angular position and velocity.
  Hold "shift" to align positions and distances to set increments.
  Hold "control" to align angles to set increments.
  Click the object in the menu to center on it.
Click a ball to edit its variables.
  Click "general" to edit general ball variables.
    "color" is the color of the ball.
    "size" is the diameter of the ball.
    "mass" is the mass of the ball.
    "moi" is the coefficient for the ball's moment of inertia (moment of inertia = moi * mass * (size / 2)²).
  Click "position" to edit the ball's position.
    "px" is the horizontal position of the ball.
    "py" is the vertical position of the ball.
    "pa" is the angular position of the ball, with counterclockwise rotation being positive.
  Click "velocity" to edit the ball's velocity.
    "vx" is the horizontal velocity of the ball.
    "vy" is the vertical velocity of the ball.
    "va" is the angular velocity of the ball, with counterclockwise rotation being positive.
  Click "drag" to edit the ball's drag coefficients.
    "drag0" is the coefficient of the constant (v⁰) term of drag.
    "drag1" is the coefficient of the linear (v¹) term of drag.
    "drag2" is the coefficient of the quadratic (v²) term of drag.
  Click "delete" to delete the ball.
Click a wall to edit its variables.
  Click "general" to edit general wall variables.
    "color" is the color of the wall.
    "wRest" is the coefficient of restitution between the wall and balls.
    "wFrict" is the coefficient of friction between the wall and balls.
  Click "position" to edit the wall's position and size.
  Click "delete" to delete the wall.
Click "timing" to edit performance/timing settings.
  "fps" is the maximum frames per second, which is also capped by browser refresh rate (usually 60).
  "upf" is the maximum number of simulation updates per frame.
  Click "pause" to pause the simulation.
  Click "update" to update one frame.
  "time" is the time the simulator has run for (or since last change).
  "end time" is the time at which the simulator will stop, if non-negative.
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
Click "objects" to change creation mode or reset.
  "ball" creates balls.
  "rectangle wall" creates rectangular walls.
  "triangle wall" creates triangular walls.
  "circle wall" creates circular or arc-shaped walls.
  "custom wall" creates custom walls following a path.
  Click "reset" once to remove all balls.
  Click "reset" twice (or when there are no balls) to remove all walls.
Click "defaults" to edit the ball creation defaults.
  "density" controls the mass of the created balls (mass = density * size³).
  "moi" controls the coefficient of the created ball's moment of inertia (moment of inertia = moi * mass * (size / 2)²).
  "w rest" controls the coefficient of restitution between a wall and balls.
  "w frict" controls the coefficient of friction between a wall and balls.
  "drag 0" controls the coefficient of the constant (v⁰) term of drag.
  "drag 1" controls the coefficient of the linear (v¹) term of drag.
  "drag 2" controls the coefficient of the quadratic (v²) term of drag.
  "dist inc" is the increment applied when holding "shift".
  "angle inc" is the increment applied when holding "control".
Click "variables" to edit simulation variables.
  "speed" is the speed of the simulation.
  "height" is the in-simulation height of the screen (the width will automatically adjust).
  "G" is the universal gravitational constant.
  "gx" is the horizontal component of the uniform gravitation force.
  "gy" is the vertical component of the uniform gravitation force.
  "b rest" is the coefficient of restitution between balls.
  "b frict" is the friction coefficient between balls.
  "wind vx" is the horizontal component of wind velocity, which drag is relative to.
  "wind vy" is the vertical component of wind velocity, which drag is relative to.
  "collide" is whether or not balls collide with other balls.
Click "info" to view the simulation information.
  "px" is the total horizontal momentum of balls in the simulation.
  "py" is the total vertical momentum of balls in the simulation.
  "kinetic" is the total translational and rotational kinetic energy of balls in the simulation.
  "energy" is the total energy of the simulation (translational kinetic, rotational kinetic, potential due to uniform gravity (relative to the bottom left of the screen), and potential due to gravity between balls).
