<h2>Solve on <a href="https://www.hackerrank.com/challenges/weather-observation-station-11/problem?isFullScreen=true">Hacker Rank</a></h2>
<h3>Solution:</h3>
<code>
  SELECT DISTINCT city 
FROM station 
WHERE LOWER(SUBSTRING(city, 1, 1)) NOT IN ('a', 'e', 'i', 'o', 'u') 
OR LOWER(SUBSTRING(city, -1)) NOT IN ('a', 'e', 'i', 'o', 'u');
</code>
