# CodingCalculus - Summary of Work Fall 2024
This repository will contain the classwork and class contributions that I have done for Coding Calculus Seminar, CSPB 4830 in Fall 2024. This includes:

- Class work and Assignments
- Online Discussions

This document has an initial highlights section, an then is ordered week-by-week. At the end of this ReadMe, I will also write a brief self-reflection on my performance in the class so far. 

## Overall Highlights/Favorites:
This section will be a discussion of the contributions I thought were most interesting or felt the best about

 - __Week 1 Reading Math Activity Response__: I felt like this initial response was a great precursor to the course - seeing how the context of a math problem changed my response and approach to solving it was really interesting. It was a good reminder to consider the bigger picture when approaching a seemingly difficult problem. I feel like a lot of the assignments in this course were very big-picture, and applied calculus concepts to the rather than focusing just on the calculus itself.
   
 - __Week 2 SIRPlot Variations__: This was a very time consuming activity - but I'm glad I did it! It was a good way to look at different systems of equations, and I got a lot of practice with graphing in this context that I was able to use in many later assignments. I wanted to highlight this assignment because I think that it shows good progress in how my code for graphing and modeling improved over time

 - __Mini-Project 1__: I was especially proud of the work that I did on the last part of this assignment, where I implemented a model of Newton's Law of Cooling that accounted for the amount of sugar dissolved in a beverage. Although I originally thought that this  would be a straightforward addition to the original Cooling equations, it was a little more involved! I ended up having to adjust the parameters of my equation a lot - I did some basic research to see how fast sugar might dissolve in a liquid and how the temperature would affect that, and how much sugar is a normal amount to add to tea initially (I add a lot haha).  I relied heavily on the visualizations that I generated to check whether my model was using parameters that fell within the realm of the plausible!
   
 - __Newton's Method Infinite Loop__ :While working on a homework problem requiring the 



## Week 1: Calculus in Context
This week, we started working with SIRPlot, a code that models the spread of a disease over time by modeling susceptible, infected, and recovered populations over time. This was a good introduction to using calculus in coding - having largely only done calculus by hand, modeling the changes in these populations over time in Python was a good review of some basic concepts and how to implement them in Python. 

So that everything is in the same place, I have added the PDF write up in this repository.

## Week 2: Euler's Method
In week 2, we explored Euler's Method. This homework was fairly straightforward, but walked through how changing certain constants in the SIR algorithm or SIRPLOT functions could change how a disease spread. This homework is listed as "Week 2" in the repo. 

This assignment did take a while to complete, but we looked at a lot of different kinds of models, and it was a very thorough investigation of how changing the individual population functions for S, I and R populations changed the spread of the disease as a whole. For me, changing variables and generating visualizations is a really effective way to learn how concepts work in general, so I appreciated the attention to that this week.

For my own future reference: The Euler method describes the process of taking the derivative of a function at evenly spaced x-values to generate an estimation to the true curve of the derivative of said function.

## Week 3: Derivatives
This week was a good introduction to the definition of the derivative!. This assignment is listed in the repo as "Week 3".

The equations presented this week are used for finding the derivative at a point given the original function. This was different from Euler's method, as we aren't necessarily calculating the change between two points, but calculating what the derivative/slope of the line was at each point.

## Week 4: Derivatives as Functions
This week built on the previous week to use the point-derivative across a range of values to estimate the derivative as a function. This assignment is in the repo as "Week 4". 
In this assignment, the material touched on the concepts of limits in the definition of a derivative without diving into them too much (limits are something that make sense conceptually but I struggle with how they are represented in most math, and working with them in equations).I thought it was interesting to see how more intervals led to a smoother graph, as it did when using Euler's method above. 

## Week 5-6: Modeling and Differential Equations
During these two weeks, we looked at more growth functions, and completed a mini-project that used these differential equations to model real-world phenomena. This assignment is in the repo as Mini-Project1.

For my project, I went through the worked examples of modeling hare-lynx populations using the May model and modeling fermentation and yeast-to-sugar ratios using differential equations. I thought the fermentation exercises were especially interesting, as they added a third population that limited the growth of another. For the final part of this project, I decided to investigate Newtons Cooling, and generated a model for how the law would change if the amount of sugar stirred into a hot beverage varied. Overall, this was a good way to experience working with a lot of different models, and practicing graphing.


## Week 7: Accumulation Function
I  was excited to start getting into integrals! In this week, we returned to the disease models (Ebola this time) to investigate the accumulation - the total sum of f(x) over all of x. The assignment for this week is in the Repo as Week 7

I liked the initial drawing activities - it was interesting getting to draw out by hand what the accumulation function or average function across the bar charts might be. The activity where we matched the normal curves to their accumulation functions was especially interesting, and a great introduction to what the anti-derivative of that kind of function would look like. I did have to re-count the bars in the first part of the assignment many times. 

## Week 8: Differentiation Rules
We got to review differentiation rules! I really appreciated this review of the product, quotient, and chain rules for differentiation. I rarely solve derivatives by hand anymore, so this felt like great practice. I don't know why all of the a's in the pdf are missing though :(

This assignment is listed in the repo as "HW7". 

The most interesting part of this assignment was trying to create a numeric derivative solver - I was not able to implement one successfully as a part of this assignment, but it was very eye-opening in terms of how many things really go into consideration when solving for a derivative. 

## Week 9: Newton's Method
This was a fun method I had never seen before! The assignment is listed in the repo as "NewtonActivities". 

I thought that this was a really interesting way to find the roots of a function, and a fun coding exercise. I know I discussed this more above, but I really would like to dive deeper into the math and possibly work through a proof for this method.


## Week 10: Riemann Sums
This week was all about learning the Riemann sum method for approximating the area under the curve. I thought this was a great review of the concepts, and having the examples about negative areas where x or y was negative was a good reminder to pay attention to the value of the coordinates. This assignment is in the repo as a jupyter notebook "Week 10 Riemann".

I really enjoyed doing the coding for this assignment, it was very satisfying to generate clean graphs that were customizable to the part of the assignment I was on and what method of riemann sum I was using (left, right, center). Again touching on the concept of limits by reducing the interval size and increasing the number of intervals. I hadn't used the trapezoidal estimation instead of the rectangular one before, so it was interesting to learn about that!


## Week 11: The Integral and the Fundamental Theorem of Calculus
This was a nice, simple assignment that illustrated some of the basic concepts of the FTC. I like the activities that are done by-hand, and the matching exercise was a good way to gain intuition about what an anti-derivative is compared to the original function, and what the integral looks like when written out. Good practice with different formats of equations. This assignment is listed in the Repo as "FTC"

