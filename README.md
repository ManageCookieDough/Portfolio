Hello! My name is Ria and this is my coding portfolio! I decided to put some of my favorite projects I've worked on over the years here for everyone to see. 
Just an FYI, I've never used GitHub/worked with it, so I'm still figuring things out.

My first project is a 3D rocket simulation that simulates the trajectory of a rocket launch. I first define basic constants and parameters for the rocket 
and Earth, then I implement functions to calculate air density, gravity, and rocket mass over time. The heart of my simulation is the "rocket_dynamics" function,
which computes the forces acting on the rocket (like thrust, drag, gravity, and the Coriolis effect) and determine its acceleration. Using these dynamics, my code 
solves the equations of motion with "solve_ivp", then processes and visualizes the results with four plots showing the 3D trajectory, altitude, velocity, and 
acceleration over time. Finally, my code prints the maximum altitude reached and the ground distance traveled by the rocket. This is probably my most complex and difficult 
project yet, but I had so much fun learnning more about rockets and learning/applying tricky calculus topics I knew nothing about into my code. 

The second project I'll be showing you is a simuation of the membrane potential dynamics of a group of five neurons over a specified time period. I initialize parameters like membrane 
time constant, resistance, and threshold potential, and generate random input currents for each neuron during a defined time window. The simulation loop updates each neuron's membrane 
potential based on the input current and checks if the potential reaches a threshold, indicating a spike. If a spike occurs, the membrane potential is reset, and the spike is recorded. 
I visualize both the membrane potentials and spike trains of the neurons using Matplotlib plots. This was a fun project because I learned  more about the brain, which fascinates me.
