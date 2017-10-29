# Search & Optimization problems

Imagine that we manage the truck for a transportation company whose distribution center is in city A. As part of our activities, tomorrow we have to deliver goods to cities B, C, D, E, F, and G, and the go back to our distribution center. As you can observe on the image below,  the roads between the different cities have different lengths and traffic conditions, resulting in different travel times between pairs of cities. What route would you follow to deliver the goods and then go back to your distribution center?

![Travelling Salesman Problem](https://github.com/vicsana1/AIJigsaw/raw/master/tsp.png)

For the figure above, there are many possible routes that visit each city at least once and end up in the distribution centre in city A. It seems also clear that different routes result in different travel times. For instance, starting from A, and then travelling to B, C, D, E, F, G, and A again would take 26 minutes. A route from A to G, then to F, E, C, D, B, and A again would take 30 minutes.

The problem faced by the business consists of finding the route that takes the lesser time, and it is common in many logistic companies. We say that, in this problem, a route is a solution. There will be many possible solutions: as many as routes. In fact, for the small problem depicted in the figure above, there are more than 5,000 different routes or solutions.

Very often, computers have to **solve problems that have an almost infinite number of possible solutions**. However, **not all of the solutions are equally good**. Thus, we would like the computer to **find the best possible solution**. These types of problem are called **search & optimization problems**. Watch the video below to understand more about what is an optimization problem.

<a href="https://www.youtube.com/watch?v=Q2dewZweAtU"><img align="center" src="https://img.youtube.com/vi/Q2dewZweAtU/0.jpg" alt="Optimization video"></a>

 However, the same problem with 50 cities would result in 304 x 10^60 different solutions! 

