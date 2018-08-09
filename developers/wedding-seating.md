##The exciting life of seat planning

You work for a wedding planner and are in charge of assigning seating for guests. You are given a list of tables (defined by table name - max capacity). You are also given a list of guest parties, along with the number in that party. Also noted is if a party dislikes one or more other parties. If possible, you should not seat parties at the same table with a party they dislike. If it is not possible to seat all parties at the same table, the program should return an error.

Example input: tables: A-8 B-8 C-7 D-7 

Thornton, party of 3 
Garcia, party of 2 
Owens, party of 6 dislikes Thornton, 
Taylor Smith, party of 1 dislikes Garcia 
Taylor, party of 5 Reese, party of 7

Example output: 
Table A Thornton, party of 3  Taylor, party of 5
Table B Smith, party of 1 Owens, party of 6
Table C Garcia, party of 2
Table D Reese, party of 7
