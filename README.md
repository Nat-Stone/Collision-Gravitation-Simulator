# Collision/Gravitation Simulator
https://sites.google.com/view/nat-stone-programming-projects/collisiongravitation-simulator

This simulator is capable of modelling rigid collisions, springs, and gravitation, with related constants such as little g, big G, restitution, static and kinetic friction, and drag being adjustable and quantities such as momentum and energy being visible in an in-simulation menu. Dynamic balls, springs, and immovable rectangular, triangular, circular, and custom walls are supported. Test your knowledge with the slope demo presets; which balls will reach the bottom first?

The following is a detailed explanation of every button/control, though most of it is intuitive within the simulator. The below description is clearer when viewed raw.

Positive directions are right and up.
Press "p" to pause the simulation.
Press "u" to jump one frame.
Press "r" to reset.
  Press "r" once to remove all balls.
  Press "r" twice (or when there are no balls) to remove all walls.
Click arrows, "+", "-", "<", and ">" to change the simulation viewport or speed.
  Click arrows to move the veiwport.
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
  Press "k" for spring mode.
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
    "movable" is whether the ball can be moved by interactions with other objects.
    "rotatable" is whether the ball can be moved by interactions with other objects. Unrotatable balls function as boxes.
  Click "position" to edit the ball's position.
    "px" is the horizontal position of the ball, relative to the closest point on dist inc lattice to the left of the screen.
    "py" is the vertical position of the ball, relative to the closest point on dist inc lattice to the bottom of the screen.
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
Click a spring to edit its variables.
  Click "general" to edit general spring variables.
    "color" is the color of the spring.
    "length" is the length of the spring.
    "x̄" is the equilibrium length of the spring.
    "k" is the spring constant of the spring.
    "size" is the width of the spring.
    "coils" is the number of coils (1 way) of the spring.
    "thick" is the coil thickness of the spring.
  Click "object 1" to edit the spring's first object.
    Click "select" to enable object selection.
  Click "object 2" to edit the spring's second object.
    Click "select" to enable object selection.
  Click "delete" to delete the spring.
Click a wall to edit its variables.
  Click "general" to edit general wall variables.
    "color" is the color of the wall.
    "w rest" is the coefficient of restitution between the wall and balls.
    "w μₛ" is the coefficient of static friction between the wall and balls.
    "w μₖ" is the coefficient of kinetic friction between the wall and balls.
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
  Click a preset to apply it.
  While holding "shift", click a preset to edit its title.
  While editing a preset and holding "control", press "backspace" to delete it.
  While holding "control", click a preset to copy it.
  Click "save" to save the current simulation state as a preset.
  While holding "control", click "save" to paste a copied preset.
  Click "demos" to see demo presets.
    Click "general" to see general demos.
      "empty" is empty with no gravity.
      "small" is empty with downward gravity.
      "large" is empty with gravity between balls.
      "box" has box walls.
      "orbit" has to balls with the masses and distances of the Earth orbiting the Sun.
    Click "collision labs" to view collision-related demos.
      "random" creates two random balls that collide at the center of the screen.
      "Newton's cradle" contains 3 1d systems that model Newton's cradle.
    Click "slope labs" to view slope-related demos.
      "mass (g=2r)" contains two balls (the green ball's mass is twice the red ball's mass) rolling down equivalent slopes.
      "radius (g=2r)" contains two balls (the green ball's radius is twice the red ball's radius) rolling down equivalent slopes.
      "disk (r) vs ring (g)" contains a red disk (moi=0.5) and a green ring (moi=1) that roll down equivalent slopes.
      "smooth vs rough" contains a red ball that slides (μ=0) and a green ball that rolls (μ>0) down equivalent slopes.
      "roll vs slide" contains a red ball that rolls (rotatable) and a green ball that slides (unrotatable) down equivalent slopes.
      "height for loop" contains 7 balls that roll down a slope, but only some complete the full loop.
    Click "spring labs" to view spring-related demos.
      "mass (g=4r)" contains two balls on equivalent springs, where the green ball's mass if four times that of the red ball.
      "mass (g=4r)" contains two equivalent balls on springs, where the green springs's spring constant if four times that of the red spring.
      "number (g=2r)" contains two equivalent balls on equivalent springs, but the green ball is attached to two springs instead of one.
    Click "orbit labs" to view orbit-related demos.
      "mass (g=2r)" contains two balls (the green ball's mass is twice the red ball's mass) orbiting a star.
      "distance (g=2r)" contains two balls (the green ball's distance is twice the red ball's distance) orbiting a star. 
Click "objects" to change creation mode or reset.
  "ball" creates balls.
  "spring" creates springs.
  "rectangle wall" creates rectangular walls.
  "triangle wall" creates triangular walls.
  "circle wall" creates circular or arc-shaped walls.
  "custom wall" creates custom walls following a path.
  Click "reset" once to remove all balls.
  Click "reset" twice (or when there are no balls) to remove all walls.
Click "defaults" to edit object creation defaults.
  Click "increments" to edit increment defaults.
    "distInc" is the distance that holding "shift" aligns to.
    "angleInc" is the distance that holding "control" aligns to.
  Click "balls" to edit ball-related defaults.
    "density" controls the mass of the created balls (mass = density * size³).
    "moi" controls the coefficient of the created ball's moment of inertia (moment of inertia = moi * mass * (size / 2)²).
    "drag 0" controls the coefficient of the constant (v⁰) term of drag.
    "drag 1" controls the coefficient of the linear (v¹) term of drag.
    "drag 2" controls the coefficient of the quadratic (v²) term of drag.
    "movable" controls whether balls can be rotated by interactions with other objects.
    "rotatable" controls whether balls can be moved by interactions with other objects.
  Click "springs" to edit spring-related defaults.
    "k coef" controls the spring constant of springs (k = kCoef * size³ / x̄).
    "coils/s" controls the number of coils (1 way) per width of springs (coils = floor(coils/s * size)).
    "thick/s" controls coil thickness to width ratio of springs (thickness = thick/s * size).
  Click "walls" to edti wall-related defaults.
    "rest" controls the coefficient of restitution between a wall and balls.
    "μₛ" controls the coefficient of static friction between a wall and balls.
    "μₖ" controls the coefficient of kinetic friction between a wall and balls.
Click "variables" to edit simulation variables.
  Click "general" to edit general settings.
    "speed" is the speed of the simulation.
    "height" is the in-simulation height of the screen (the width will automatically adjust).
  Click "gravity" to edit gravity-related constants.
    "G" is the universal gravitational constant.
    "gx" is the horizontal component of the uniform gravitation force.
    "gy" is the vertical component of the uniform gravitation force.
  Click "ball" to edit ball-related constants.
    "collide" is whether or not balls collide with other balls.
    "rest" is the coefficient of restitution between balls.
    "μₛ" is the coefficient of static friction between balls.
    "μₖ" is the coefficient of kinetic friction between balls.
    "wind vx" is the horizontal component of wind velocity, which drag is relative to.
    "wind vy" is the vertical component of wind velocity, which drag is relative to.
Click "info" to view the simulation information.
  "mom x" is the total horizontal momentum of balls in the simulation.
  "mom y" is the total vertical momentum of balls in the simulation.
  "kinetic" is the total translational and rotational kinetic energy of balls in the simulation.
  "energy" is the total energy of the simulation (translational kinetic, rotational kinetic, potential due to uniform gravity (relative to the closest point on the dist inc lattice to the bottom left of the screen), and potential due to gravity between balls).
