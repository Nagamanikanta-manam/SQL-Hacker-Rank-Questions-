<h2>Solve it on <a href="https://www.hackerrank.com/challenges/weather-observation-station-5/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  select city,length(city) from station order by length(city),city limit 1;
  select city,length(city) from station order by length(city) desc,city limit 1;
</code>
