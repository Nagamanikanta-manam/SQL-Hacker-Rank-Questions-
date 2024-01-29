<a href="https://www.hackerrank.com/challenges/weather-observation-station-11/problem?isFullScreen=true">Hacker rank link</a>
<h2>Answer:</h2>
<code>
  select distinct city from station where substr(city,1,1) not in ('A','E','I','O','U') or substr(city,-1) not in ('a','e','i','o','u');  
</code>
