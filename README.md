Random_Pacman

       In the <body> section, there are two buttons: "Add PacMan" and "Start Game." 
       The JavaScript functions create() and move() are defined in the <script> section. 
       These functions control the behavior of PacMan images.
       The create() function generates a new PacMan image element with random initial positions and velocities. 
       It appends the image to the HTML body and stores information about the PacMan 
       (position, velocity, direction) in various arrays.
       The move() function animates the movement of PacMan images. 
       It updates the positions of the PacMan images based on their velocities and changes their source image to create a 
       "chomping" effect. The setTimeout() function is used to repeatedly call the move() function with a delay of 100 milliseconds, creating animation.
