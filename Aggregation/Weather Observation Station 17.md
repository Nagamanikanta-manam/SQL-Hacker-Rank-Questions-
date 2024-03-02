<h2>Solve it on <a href="https://www.hackerrank.com/challenges/weather-observation-station-17/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution(MySQL):</h3>
<code>
  select round(long_w,4) from station where lat_n>38.7780 order by lat_n limit  1; 
</code>
