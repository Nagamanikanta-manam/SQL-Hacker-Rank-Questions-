Query the Name of any student in STUDENTS who scored higher than Marks. Order your output by the last three characters of each name. 
If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by 
ascending ID.
Input Format

|Column|Type|
-------|-----
|ID    |Integer |
|Name|String|
|Marks|Integer|

The STUDENTS table is described as follows: The Name column only contains uppercase (A-Z) and lowercase (a-z) letters.

Solve it on <a href="https://www.hackerrank.com/challenges/more-than-75-marks/problem?isFullScreen=true">Hacker Rank</a>
<h2>Answer:</h2>
<code>
  select name from students where marks>75 order by substr(name,-3),id; 
</code>
