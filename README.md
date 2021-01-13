# MMU2-on-any-printer

<p align="left">
  <img src="https://i.ibb.co/ZXKqCYj/IMG-1161.jpg" width="350" title="Water Dragon by Cipis">
</p>

This is a work in progress, all the current 3d files work good enough but are not final, I would recommend waiting a few weeks before attempting a build in order to get the more reliable models and also have access to the documentation and videos about building the MMU Clone and how to set it up in Marlin. Checkout my youtube channel (https://www.youtube.com/channel/UCF2tb5Hu6G_z-tB3_e_9U4A) for more info. This github is currently meant for people that want to take a look at the files or that want to contribute to the project. For now the minimum  board requirements are at least 5 independent motor control(X,Y,Z,Extruder,Idler) make sure to take into account dual Z steppers(can be solved easiely by using a splitter), I was able to do the first multimaterial prints using a bowden style setup so it is confirmed that only 5 stepper motor controls are required but I still highly recommend to get a board with at least one more control since the direct drive setup will most likely be way more reliable and capable, this also gives you an upgrade path with your printer). If you are planning on contributing I recommend using the SKR pro (V1.1 is the one I am using but V1.2 will also work since they are basically the same) if you are simply trying to find a cheap board that should work get something like the skr V1.4 or any board that respects the previously mentioned requirements.

I am currently working on a rotary encoder to work as a filament detector/flow meter and I am polishing the current firmware and the physical model. Once the result is clean enough and works properly I will be making a detailed video about how to install it and everything that you should know if you want to build you own. I will also work on the documentation and start working on different mounting systems for the most popular 3d printers.(If you ever create your own for your specific device make sure to create a pull request so that we can add it to the repo).
 
 If you want to contact me, asks questions, provide ideas or just stay up to date with this project join the discord server: https://discord.gg/Pj8bwTn
 If you want to contact me privatly, you can do so on discord or email me at: pierre.masselot.d@gmail.com



