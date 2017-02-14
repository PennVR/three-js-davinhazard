# Davin Hazard Threejs

#Techniques

My terrain is generated through implementing Perlin Noise. I used a high resolution image of a galaxy to create the texture map on the terrain. I liked the variation in color it created, although I would have liked to spend more time improving the mapping, as the dimensions were a little off. This created a slightly blurred effect. For the fireworks I created a class called Firework that when created, sets off a single sphere with a y velocity. After a set lifespan, the single sphere disappears and "explodes" into rings of multiple spheres, with radially outward velocities from the initial sphere. I would like to go back in and adjust the physics of the fireworks to add more variation - perhaps randomizing the initial y-velocity and the time of explosion. 

#VR Mode

Currently experiencing bugs with VR mode and getting it to work properly. I had some trouble toggling between VR and regular mode, and currently have it only working in web (non-VR). 

#Other difficulties 

I spent a disproportionate amount of time trying to configure the VR settings. I was surprised to encounter so much difficulty with this, as I followed multiple examples with no luck. I wish that I could have spent more time fine-tuning the visuals and fireworks effects. 

It would have been nice to have a basic code skeleton or more explicit instructions, at least for setting up the VR. 
