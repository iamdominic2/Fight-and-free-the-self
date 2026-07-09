# Fight-and-free-the-self

The title is a pun: Fight-and-3D-self!

**Link (HTML) = https://iamdominic2.github.io/Fight-and-free-the-self/**

Three-dimensional raycaster of maze-wandering and real-time monster combat. You go through areas, collecting potions, battling monsters, and the main goal is to go to the exit. (And defeat the final bosses in the final area.) Keep health above 0.

Definition: Raycasting is the methodological basis for 3D CAD/CAM solid modeling and image rendering. It is essentially the same as ray tracing for computer graphics, where virtual light rays are "cast" or "traced" on their path from the focal point of a camera through each pixel in the camera sensor to determine what is visible along the ray in the 3D scene.

Raycaster fires a ray each frame from many "slanted" angles relative to the player's position. Wall height is inversely proportional to the distance traveled by the ray from FOV, and renders the Anticlockwise stuff left, Clockwise stuff right (relative to the middle).

For entities, some math is used:
vx = ((x * cos(CAM DIR)) - (y * sin(CAM DIR)));
vy = ((x * sin(CAM DIR)) + (y * cos(CAM DIR)));

It was originally a 2022 Scratch project, but I updated the minimap and showed the enemies, and then compiled it to HTML because Scratch was laggy, which was annoying. It's great now!
