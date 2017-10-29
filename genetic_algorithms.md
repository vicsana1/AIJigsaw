# Search & Optimization problems

Imagine that we manage the truck for a transportation company whose distribution center is in city A. As part of our activities, tomorrow we have to deliver goods to cities B, C, D, E, F, and G, and the go back to our distribution center. As you can observe on the image below,  the roads between the different cities have different lengths and traffic conditions, resulting in different travel times between pairs of cities. What route would you follow to deliver the goods and then go back to your distribution center?

<p align="center">
  <img src="https://github.com/vicsana1/AIJigsaw/raw/master/tsp.png">
</p>

For the figure above, there are many possible routes that visit each city at least once and end up in the distribution centre in city A. It seems also clear that different routes result in different travel times. For instance, starting from A, and then travelling to B, C, D, E, F, G, and A again would take 26 minutes. A route from A to G, then to F, E, C, D, B, and A again would take 30 minutes.

The problem faced by the business consists of finding the route that takes the lesser time, and it is common in many logistic companies. We say that, in this problem, a route is a solution. There will be many possible solutions: as many as routes. In fact, for the small problem depicted in the figure above, there are more than 5,000 different routes or solutions.

Very often, computers have to **solve problems that have an almost infinite number of possible solutions**. However, **not all of the solutions are equally good**. Thus, we would like the computer to **find the best possible solution**. These types of problem are called **search & optimization problems**. Watch the video below to understand more about what is an optimization problem.

<a href="https://www.youtube.com/watch?v=Q2dewZweAtU"><img align="center" src="https://img.youtube.com/vi/Q2dewZweAtU/0.jpg" alt="Optimization video"></a>

# Optimization algorithms
As mentioned in the video, optimization algorithms are used to solve optimization problems: problems with potentially many solutions and different quality. 

A **naive or brute force** algorithm is the simplest solution to an optimization problem. It simply **generates all of the possible solutions and it keeps the best one in the end**. Obviously, this **guarantees getting the best solution** to the problem, as we generate all of them! This algorithm is **only applicable to small problems** like the one in the figure above. However, the same problem with 50 cities would result in 304 x 10^60 different solutions! The number of solutions is simply too large and it would take ages or decades for a computer to generate all the solutions. This is unfeasible in most applications.

An **exact algorithm or method** still **guarantees getting the best solution** to a problem, but very often **it does not need to generate all possible solutions**. Some traditional tricks employed by these algorithms to avoid exploring all of the solutions include:
- Generating promising solutions first (i.e., those that may potentially lead to better solutions) and keep their quality
- Do not generate solutions whose quality will never improve the quality of the solutions that we have explored so far.

A **heuristic algorithm** normally needs to **generate less solutions than exact algorithms** at the cost of **not being able to guarantee finding the best solution**. Still, **solutions found by a heuristic algorithm tend to be close in quality to the best possible solution**. Often, heuristic algorithms speed up the optimization process by making assumptions on the optimization problem.

An optimization algorithm can also be anytime or non-anytime. We say that an optimization algorithm is **anytime** when it can **provide with a solution at any point in time** of the computation/calculation. It does not matter if we request for a solution after 10 minutes, 30 seconds, or 1 second, it will provide with a solution. Typically, the more that we wait for requesting a solution the higher quality that it has. On the other hand, **non-anytime** algorithms **only provide with a solution by the end of the algorithm's computation**. There are no intermediate solutions.

# Genetic algorithms
Genetic algorithms are **anytime and heuristic** algorithms that can be applied to multiple optimization problems. The ideas behind the steps in a genetic algorithm are **inspired by the theory of evolution**. Initially, a genetic algorithm generates a pool or **population** of random solutions to the problem that needs to be solved. As you can imagine, most of these solutions will have a low quality as they have been generated in a random way and, thus, they will be far from the best possible solution.

The **best solutions from our current population are selected**. Only these solutions undergo mating and mutation operations, inspired by a **survival of the fittest** strategy:
- Pairs of best solutions become parents and they are combined to create a new solution or child. The idea is that the child solution will inherit parts from both parents. The assumption taken is that, if both parents have good quality, a child solution that combines parts of both parents will also have a good or an even better quality. This operation is called **crossover**.
- The best solutions are mutated by introducing small changes in parts of their solutions. The assumption is that, if the original solution had good quality, a small variation in part of that solution should result in a similar or even better quality. This operation is called **mutation**.
The new solutions are introduced in the population, with the hope that they will have improved their parents. This process of selection, and crossover and mutation operations continues for many generations. As we apply this process, solutions in the population tend to have a higher quality, as we applied a **survival of the fittest** strategy.

