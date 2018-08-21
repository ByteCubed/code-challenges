# The exciting life of seat planning
You work for a wedding planner and are in charge of assigning seating for guests. You are given a list of tables (defined by table name - max capacity). You are also given a list of guest parties, along with the number in that party. Also noted is if a party dislikes one or more other parties. If possible, you should not seat parties at the same table with a party they dislike. If it is not possible to seat all parties at the same table, the program should return an error.

## Example input: 
```
tables: A-8 B-8 C-7 D-7 
```
### Reservations

* Thornton, party of 3 
* Garcia, party of 2 
* Owens, party of 6 dislikes Thornton, Taylor
* Smith, party of 1 dislikes Garcia 
* Taylor, party of 5
* Reese, party of 7

#### Example output: 
```
Table A:  Thornton, party of 3  & Taylor, party of 5
Table B : Smith, party of 1  & Owens, party of 6
Table C : Garcia, party of 2
Table D : Reese, party of 7
```

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
As with all ByteCubed Challenges, we are more concerned about how you went about solving and thinking about the problem than anything else.  We use this as a data point within our interview process and it is meant to help drive the conversation.

####
