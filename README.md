# Fight-and-free-the-self
Three dimensional raycaster of maze-wandering and real-time monster combat. You go through areas, collecting potions, battling monsters, and the main goal is to go to the exit. (And defeat the final bosses in the final area.) Keep health above 0.

Raycasting is basically a technique where rays are fired at several angles relative to the player's perspective and the distance is recorded to generate an image.

For raycasting: Raycaster fires a ray each frame from many "slanted" angles relative to player position Wall height is inversely proportional to distance traveled by the ray from FOV, and renders the Anticlockwise stuff left, Clockwise stuff right (relative to the middle).

for entities some math is used:
vx = ((x * cos(CAM DIR)) - (y * sin(CAM DIR)));
vy = ((x * sin(CAM DIR)) + (y * cos(CAM DIR)));

By the way, the title is a pun: Fight-and-3D-self

Online Playable Link = https://iamdominic2.itch.io/fafts

Downloaded ZIP (HTML version had a technical error) = https://drive.google.com/file/d/1Behw3lnvMsX6lIOfQdMuG1wsRxYLTFAj/view?usp=sharing

Yet again, note that I only documented post-implementation to ensure full accuracy with the final program as I might forget to change things here along the way.

Project ID = 723740037

Block Count = 1518 
