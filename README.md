# Ecslent
[The Evolutionary Computing Systems Lab](https://ecsl.cse.unr.edu/)'s ENTity game engine provides a basis for building and using Real-Time Strategy games for academic research and especially for evolutionary computing research in RTS game AI. The game engine's clean architecture enables graphics to run in a separate thread, and if necessary, to run without graphics. This is not great for an actual game but excellent for evolutionary computing research where you may need multiple copies of the game running. The default environment is an ocean world with surface ships, no collision checking, and simple 2D RTS physics. We provide rudimentary support for 3D physics. With graphics enabled, AWSD RTS camera movement, single and group mouse selection (left mouse), and an RTS move command (mouse right click) implemented using potential fields for smooth, collision free movement allow some user interaction.

Ecslent uses 
  1. [Ogre](https://www.ogre3d.org) for graphics and for ogre's vector math and quaternion libraries. 
  2. [Boost](http://www.boost.org/) libraries for dealing with time and with thread synchronization.
  
  We used [Eclipse](https://www.eclipse.org/) for developing Ecslent.

More information on Ecslent's architecture can be found from [my game engine architecture course](https://www.cse.unr.edu/~sushil/class/381/) at [UNR](https://www.unr.edu).

Ecslent is pronounced excellent:-)
