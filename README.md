Hello! My name is Ria and this is my coding portfolio! I decided to put some of my favorite projects I've worked on over the years here for everyone to see. 
Just an FYI, I've never used GitHub/worked with it, so I'm still figuring things out.

My first project is a 3D rocket simulation that simulates the trajectory of a rocket launch. I first define basic constants and parameters for the rocket 
and Earth, then I implement functions to calculate air density, gravity, and rocket mass over time. The heart of my simulation is the "rocket_dynamics" function,
which computes the forces acting on the rocket (like thrust, drag, gravity, and the Coriolis effect) and determine its acceleration. Using these dynamics, my code 
solves the equations of motion with "solve_ivp", then processes and visualizes the results with four plots showing the 3D trajectory, altitude, velocity, and 
acceleration over time. Finally, my code prints the maximum altitude reached and the ground distance traveled by the rocket. This is probably my most complex project yet,
but I had so much fun learnning more about rockets and learning/applying tricky calculus topics into my code. 
