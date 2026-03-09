# Fight-and-free-the-self
Three dimensional raycaster of maze-wandering and real-time monster combat

Online Playable Link = https://iamdominic2.itch.io/fafts

Downloaded ZIP (HTML version had a technical error) = https://drive.google.com/file/d/1Behw3lnvMsX6lIOfQdMuG1wsRxYLTFAj/view?usp=sharing

Basically, the camera works like this  (for entities) with TRIG (yay)
vx = ((x * cos(CAM DIR)) - (y * sin(CAM DIR)));
vy = ((x * sin(CAM DIR)) + (y * cos(CAM DIR)));
