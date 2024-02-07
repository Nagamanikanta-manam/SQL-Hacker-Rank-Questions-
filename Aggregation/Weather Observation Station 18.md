<h2>Solve it on <a href="https://www.hackerrank.com/challenges/weather-observation-station-18/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  select round(abs(min(lat_n)-max(lat_n))+abs(min(long_w)-max(long_w)),4) from station;
</code>
