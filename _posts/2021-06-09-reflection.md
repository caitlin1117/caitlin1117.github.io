---
layout: post
title: Reflection on project
---


### Overall, what did you achieve in your project? 
I created a Python package that solves some basic PDEs and creates visualizations of the solution. The PDEs include 1d advection equation, 1d and 2d heat equation, 1d and 2d wave equation, and inviscid Burgers equation. The numerical solutions are solved using finite difference methods.  All of the solutions can be visualized by animation. 

### What are two aspects of your project that you are especially proud of? 
I am very happy with the animation I created of the solution to the 2d wave equation. I learned about how to implement homogenous Neumann condition which is more difficult to implement than Dirichlet boundary condition. Also, I am happy with the result of the solution visualization to the 2d heat equation. The method I learned about is the alternating-direction implicit method which involves creating two matrices. 

### What are two things you would suggest doing to further improve your project?
One thing I would like to improve on is to make this package a tutorial style package. For example I can make additional Jupyter notebooks on how these equations are derived or how they can be solved analytically.
Another aspect is that I would like to look more into the derivation of the convergence condition for each method. When I implemented the different methods, I only looked up the convergence condition and directly used the result without looking into how it is derived. 

### How does what you achieved compare to what you set out to do in your proposal? 
Overall, I achieved most of the things I planned. In the proposal, I mentioned that I wanted to use different methods to solve and visualize each equation. When I started doing the project, I realized some of the methods I mentioned will not give a very accurate solution. For example, when solving the transport equation, I first implemented the Lax-Friedrichs scheme, the scheme is stable but also suffers from a considerable dissipation. Then I implemented the Lax-Wendroff scheme which does not suffers from a considerable dissipation. So, in the end I only used Lax-Wendroff scheme to solve the equation. I also mentioned I wanted to solve the KdV equation and this is the part I didn’t get to finish. In addition to what I planed in the proposal, I implemented solving the 2d wave and heat equation.

### What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc? 
In the process of creating this project, I looked up many references on solving PDEs using finite difference method. This is definitely the thing I learned most about when creating the project. I also learned about some plotting techniques using Python. For example, creating animation, and plotting 3d surfaces. I also learned about how to create my own Python package and publish it to Pypi. 

### How will your experience completing this project will help you in your future studies or career?
Solving differential equations numerically is very important in many areas in applied math. For example, I am very interested in learning about physics based modeling in computer graphics. When modeling some systems, it usually involves solving differential equations. In the past, I have used Euler’s method and Verlet integration to solve the spring mass system when modeling cloth. Currently, I plan on learning more about physics based modeling so I need to have the knowledge in solving PDEs numerically. I plan to take a course in finite difference method for PDEs next quarter. I believe that my experience completing this project will help me prepare for taking the course and for future studies in applied math. 