<h2>Solve it on <a href="https://www.hackerrank.com/challenges/population-density-difference/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  select ceil(avg(salary)-avg(replace(salary,'0',''))) from employees;
</code>
