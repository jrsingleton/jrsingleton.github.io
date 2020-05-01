---
layout: essay
type: essay
title: Design Patterns and Chernobyl
# All dates must be YYYY-MM-DD format!
date: 2020-04-30
labels:
  - Software Engineering
  - Design Patterns
  - Energy
---

<hr>
## Nuclear Power

The quest to generate electricity most effectively has lasted centuries. 
It took many methods before the arrival of nuclear fission.
The [nuclear fission](https://www.britannica.com/science/nuclear-fission) reaction is advantageous in the way that it creates such a huge quantity of electricity.
One disadvantage to the creation of enormous electricity? If the chain reaction is uncontrolled… a nuclear bomb is created.
So, the reaction must be controlled to generate power.
In a nuclear reactor, the nuclear fission reaction is contained in a reactor core, which heats water, and in turn, 
creates steam to spin metal turbines. But, this boiling water must be cooled down to continue the cycle. 
There is an exact protocol to follow to solve every problem that arises.

<hr>
## Modern Problems Require Modern Solutions

Something similar can be said about software engineering, but if I messed up something in my code I wouldn't cause the
[Chernobyl disaster](https://en.wikipedia.org/wiki/Chernobyl_disaster) (I hope). Design patterns are what I would call the protocols or strategies to follow when programming.
You don’t need to use these patterns if you don't want to, but our software engineering elders discovered them to help us 
solve common problems and save time. If you were working with a team and you informed them of which design pattern you would
use to solve a problem, they would know what the solution would likely look like, as well as the pros and cons of that 
approach. If you encounter a problem enough times, likely, you will even create your own design patterns. 
The [Factory pattern](https://www.geeksforgeeks.org/design-patterns-set-2-factory-method/) is one I have used rather often. Rather than reciting and defining the same code over and over again,
you simply pass the type of a method from the client to the factory method to create.
<hr>

## The Singleton Pattern

It would be despicable of me to not mention my namesake, the [Singleton pattern](https://www.geeksforgeeks.org/singleton-design-pattern/).
It may be considered an anti-pattern... and it may make code difficult to debug... and if you change it,
it could disrupt your whole application. But sometimes it's good to have code that cannot be cloned, 
one example of this is logging.
<hr>

