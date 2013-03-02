[Screenshot]: http://dl.dropbox.com/u/45530199/Programs/RuinsOfRevenge/RuinsOfRevenge.png

# Ruins of Revenge

![RuinsOfRevenge][Screenshot]

(Click for better quality)

## What is this?

This is a game written in Java, using a graphics and game library "LibGDX", Riven's 
and MatthiasM's "Continuation and Green Threads" library, and LibGDX's port of Box2D.
It is supposed to be a RPG with Physical elements.

## How to clone and run

This is pretty simple with eclipse:
(If you have egit) clone this repository using File -> Import then search for "Projects from Git".
If that option is not available for you, then it's likely that either your egit plugin is outdated
or you don't even have it installed.

To run this game, you now need to create a new Run Configuration (Run -> Run Configurations... then
right click on "Java Application" -> New...) and choose a name (for example "RuinsOfRevenge"). Don't
forget to set the project and main class (org.matheusdev.ror.RuinsOfRevenge).
Now go to the "Arguments" Tab and add this to the "VM-arguments": -javaagent:lib/continuations-agent.jar

Thats it!

You can now run the RuinsOfRevenge run configuration! :)