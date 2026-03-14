# Dynamic Systems: State-Space Representation and MATLAB Simulink Project
**System Modeling, Mathematical Representation, Simulation using Simulink**\
(A.I. is used for organizing the report)
Theory not provided(many good explanations can be found online), only demonstration of the method. However, for inquiries of any kind, feel free to reach out on my email(on my profile).
All projects and portfolios are solely my own with no outside contributions to the making.

## I.	Why the project is useful

This Project is An Introduction to Control Systems
This project is an "intro" because it teaches you the three pillars of control:
1.	Modeling (The Physics): Writing the equations of motion for the components.
2.	Representation (The Math): Organizing those equations into the matrix format. The A matrix represents the system's internal "personality" (how it moves on its own), while the B matrix represents how your inputs (like a motor torque) change that behavior.
3.	Simulation (The Testing): Using the Integrator blocks in Simulink to see if your system oscillates, crashes, or stays stable.

## II.	What the project does

At the end, we’ll have what is called in control systems as an “Open Loop” or “Feedforward loop, meaning the system just reacts to an input and doesn’t react back to the output to fix any errors or deviation from the desired goal.
The next logical step from here is adding a feedback loop. Which takes those output signals, compare them to a desired goal, and use a controller (like PID) to fix the error.

This method transforms raw mechanical differential equations of motion into a State-Space Representation—a standardized mathematical format, it decreases the order of the equations but in return add an equation. Easily represent Complex systems as simple matrices(the back bone of most simulations for any type of systems, crucial for high performance), turning it into linear algebra—a trick used often for ease of calculations and simple representation. It then uses Simulink to visualize how those equations respond to inputs over time.

In reality, you rarely have one simple input and one output. State-space allows you to track many "states" (positions, velocities, angles) simultaneously. It is the industry standard for modeling complex systems where simple transfer functions fall short.

## III.	Get started with the project

I’ll use a simple system to demonstrate the method. However, the method is the same and just as simple for more complex systems.

Here is some useful references:






