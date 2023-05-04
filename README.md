Download Link: https://assignmentchef.com/product/solved-cs4300-project-4-ghostbusters
<br>
In this project, you will design Pacman agents that use sensors to locate and eat invisible ghosts. You’ll advance from locating single, stationary ghosts to hunting packs of multiple moving ghosts with ruthless efficiency.

As in previous projects, this project includes an autograder for you to grade your answers on your machine. This can be run with the command:

<h1>python autograder.py</h1>

The code for this project consists of several Python files, some of which you will need to read and understand in order to complete the assignment, and some of which you can ignore. Download search.zip from here http://ai.berkeley.edu/tracking.html which will contain all the code and supporting files.

<h1>1            Files to edit</h1>

For this project you will need to edit the following files

<ul>

 <li><strong>py: </strong>Agents for playing the Ghostbusters variant of Pacman.</li>

 <li><strong>py: </strong>Code for tracking ghosts over time using their sounds.</li>

</ul>

<h1>2            Ghostbusters and Bayes Nets</h1>

Your primary task in this project is to implement inference to track the ghosts. For the keyboard based game above, a crude form of inference was implemented for you by default: all squares in which a ghost could possibly be are shaded by the color of the ghost. Naturally, we want a better estimate of the ghost’s position. Fortunately, Bayes’ Nets provide us with powerful tools for making the most of the information we have. Throughout the rest of this project, you will implement algorithms for performing both exact and approximate inference using Bayes’ Nets.

For all the problem titles described below, please refer to the link http://ai.berkeley. edu/tracking.html for the problem description and what is expected of each problem. As always autograder has different test cases against which you can run your program to check the correctness. Please ensure your code is readable and use comments in your code to make it more clear for the person reading your code.

You will be graded on your code implementation for the following questions:

<ol>

 <li>Exact Inference Observation (12 pts)</li>

 <li>Exact Inference with Time Elapse (12 pts)</li>

 <li>Exact Inference Full Test (12 pts)</li>

 <li>Approximate Inference Observation (12 pts)</li>

 <li>Approximate Inference with Time Elapse (16 pts)</li>

 <li>Joint Particle Filter Observation (16 pts)</li>

 <li>Joint Particle Filter with Time Elapse (16 pts)</li>

</ol>

<h1>3            Self Analysis</h1>

<ol>

 <li>What was the hardest part of the assignment for you?</li>

 <li>What was the easiest part of the assignment for you?</li>

 <li>What problem(s) helped further your understanding of the course material?</li>

 <li>Did you feel any problems were tedious and not helpful to your understanding ofthe material?</li>

 <li>What other feedback do you have about this homework?</li>

</ol>

<h1>4            Evaluation</h1>

Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes within the code, or you will wreak havoc on the autograder. If your code passes all the test cases in the autograder you would receive full points for the implementation.

However even if your code does not necessarily pass all the test cases, we would evaluate your code and then award you partial points accordingly. In such cases it would be even more beneficial if you could give a short description of what you tried and where you had failed and that would help us in giving you better points.