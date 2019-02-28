# Inverted-Pendulum
Simulation of Inverted pendulum with animation on virtual realm 3d tool.

Tune the PID block to play around with the stability of the model.
Pulse is given as an external disturbance to assess the model stability.
Make sure you use the LINEAR dynamics block instead of the non linear dynamics block that has been commented.

This also works with joystick. Make sure you plug a USB joystick that is detectable on windows platform. Uncomment the Joystick block, and connect the output of '5' that is in a triangular block (Basically a gain block) to the input of the system. (remove the '0' constant block that is left of the PID(s) and the summer block and connect it here.) PLEASE DONOT FORGET TO TURN ON THE ANALOG BUTTON ON THE JOYSTICK OR ELSE THE INPUT FROM THE JOYSTICK WILL BE DIGITAL (lowest and highest) PUSHING THE INVERTED PENDULUM BLOCK OFF YOUR SCREEN.

Uncomment the "Real time pacer" block so that the simulation time reduces to the actual real world time.
Make sure all the files are in one folder.
Run the Init_vars.m file to initialise global variables. Only then run the "Inverted_pendulul.slx" file to view the simulink simulation.
Double click the VR sink block (The one with a pink sphere and a blule square) to see the animation.

Enjoy!
