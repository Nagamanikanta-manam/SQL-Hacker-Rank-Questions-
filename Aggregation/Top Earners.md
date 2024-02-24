<h2>Solve on <a href="https://www.hackerrank.com/challenges/earnings-of-employees/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  select (salary*months) as earnings,count(*) from employee group by earnings order by earnings desc limit 1; 
</code>
