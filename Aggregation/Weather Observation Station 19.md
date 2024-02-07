<h2>Solve it on <a href="https://www.hackerrank.com/challenges/weather-observation-station-19/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  select round(sqrt(power(min(lat_n)-max(lat_n),2)+power(min(long_w)-max(long_w),2)),4) from station;
</code>
