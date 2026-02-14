## Classical Atom

A simple simulator of a classical atom. The simulator operates on two threads using a lockless design, the physics thread operates with no limits, depending on how complex the atom it can operate anywhere between 300 fps and well over a million for very simple atoms. On the other hand the render thread is locked to the refresh rate of the monitor ensuring not to waste resources.

Only coulomb forces and the strong nuclear force are simulated, using the Yukawa Potential and a large inverse distance portion to simulate the strong force, are supported.

The simulator allows you to enter the number of protons, neutrons and electrons to simulate, and allows for easy restarting of the simulation.

Although many electrons can be added to the system, when more then one are added they will quickly be ejected due to the system being purely classical.

Move around the viewport using WASD click and drag the mouse to look in different directions.