# Homework 9
**Attention:** This homework is not mandatory. It is a suggestion in order to familiarize yourself with the concept of von Neumann stability analysis. We do not expect you hand in something.

The diffusion equation

<p align="center">
<img src="stuffy_stuff/f1.png" width="150">
</p>

is the prime example for a parabolic PDE. The advection equation

<p align="center">
<img src="stuffy_stuff/f3.png" width="130">
</p>

on the other side is the most simple hyperbolic PDE. For the hyperbolic PDE we found in the von Neumann stability analysis, that the forward time centered space (FTCS) discretization lead to an unconditionally unstable algorithm.

Carry out a von Neumann analysis of the FTCS discretization of the diffusion equation above. In that respect approximate the temporal derivative by a forward difference (just like for the advection equation) and replace the second spatial derivative by the second order accurate finite difference
<p align="center">
<img src="stuffy_stuff/f2.png" width="300">
</p>

Show that the algorithm is stable for
<p align="center">
<img src="stuffy_stuff/f4.png" width="90">
</p>
