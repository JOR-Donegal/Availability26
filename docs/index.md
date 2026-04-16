# Introduction

!!! abstract "Availability"

Computing has got a great deal more complex in the 60 years or so that it has been about. In the microprocessor era, we have gone for the original 4004 processor (1971) with 2,300 transistors, to the record holder at time I wrote this module originally (2015), the Intel Xeon Haswell-EP with 5.5 x 10^9 transistors.

At the same time, software also become equally complex. In 1992, Windows NT had 4 million lines of code. Windows 11 has 60-100 million lines of code!

As systems become more complex, it becomes more difficult to ensure they are accurate, without bugs, unknown problems or unexpected consequences. We don’t have a good scientific law for this but there is a body of commentary, relating to the difficulty in making complex systems work. The things we can say with confidence is that the more complex something is:

- The less likely it is to ever work in the first place
- The more hidden flaws are in the system
- The more likely it is to fail catastrophically
- The more likely it is to fail unexpectedly 

In the early days of UNIX, the folks who were writing utilities had a simple philosophy. Every tool has a single purpose only and is as simple as it can be. If there is a better philosophy, I have yet to find it. There is a quote attributed to Einstein but probably apocryphal; “Everything should be made as simple as possible, but no simpler.” 

One of the advantages of object oriented code is that we can encapsulate code and data and that each object can be developed and debugged independently.

When we write large applications, we write them in layers. We have a database layer to deal with the backend database. We have a business logic layer to handle all the programme code. And we have one or more presentation layers for end user devices. Once again, we try to break up the architecture into layers so that one layer can change without effecting all the other code. If we change from Oracle to MS-SQL, we change one layer, everything else remains the same.

The approaches above are typical in enterprise application development.

In these notes we will examine how we cope with complexity (or not!) and look at how we can simply model system uptime, downtime and failure rates. To cover this topic from an engineering perspective, we could spend an entire module; these notes are intended to scratch the surface and allow you do to some basic calculations.