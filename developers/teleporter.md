# Teleporter

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
Los Angeles - San Fransisco
San Fransisco - Oaktown
Los Angeles - Oaktown
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

### Questions
You may use any documentation or forum posts. You may also use any other frameworks or tooling that you choose.  Please leverage Github as your source code repository and send a note to your reviewer/recruiter when you are ready.
