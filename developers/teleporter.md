

## Introduction:
You have discovered the secrets of teleportation and have several teleportation routes up and running. Each route allows instantaneous travel from one city to another. All routes are two way: if you can teleport from city A to city B, you can also teleport from city B to city A. You want to create a system to make it easier for you to answer specific queries about your network. You should assume anyone using your network wants to travel only by teleportation.

## Description
Input to the program will be a list of teleportation routes, followed by a list of queries.

### Example input:
```
Fortuna - Hemingway
Fortuna - Atlantis
Hemingway - Chesterfield
Chesterfield - Springton
Los Amigos - Paristown
Paristown - Oaktown
Los Amigos - Oaktown
Summerton - Springton
Summerton - Hemingway
cities from Summerton in 1 jumps
cities from Summerton in 2 jumps
can I teleport from Springton to Atlantis
can I teleport from Oaktown to Atlantis
loop possible from Oaktown
loop possible from Fortuna
```

### Example output:
```
cities from Summerton in 1 jumps: Springton, Hemingway
cities from Summerton in 2 jumps: Springton, Hemingway, Chesterfield, Fortuna
can I teleport from Springton to Atlantis: yes
can I teleport from Oaktown to Atlantis: no
loop possible from Oaktown: yes
loop possible from Fortuna: no
```
### Questions to answer:

* What cities can I reach from city X with a maximum of N jumps?
* Can someone get from city X to city Y?
* Starting in city X, is it possible to travel in a loop (leave the city on one route and return on another, without traveling along the same route twice)?

### How to Submit:

Please feel free to sen us a link to a Github repository that will contain your solution.  We are fairly flexible for what language you write this in so feel free to include a response in any of the following languages or what ever language you are most comfortable in:
* Java
* JavaScript
* Go
* Kotlin
* Scala
* Python
* .NET (C# or VB.NET)

When thinking abut how to structure your solution think about how you would typically would work with teams and the common concerns that you may have when sharing code with others.

### Questions

#### How am I evaluated?
* As with all ByteCubed Challenges, we are more concerned about how you went about solving and thinking about the problem than anything else.  We use this as a data point within our interview process and it is meant to help drive the conversation.

####
